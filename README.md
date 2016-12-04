# Docker-Tools

<a href="https://binfalse.de/2016/12/03/handy-docker-tools/"><img src="https://binfalse.de/assets/media/pics/2016/docker-toolbox.png"  title="Docker Tools" width="200px"></a>

This is a suite of tools that will come in handy if you're working with Docker.
The suite contains:

* `dclean` can be used to get rid of old, exited Docker containers and dangling images.
* `denter` will give you quick access into a shell of any running container.
* `dip` shows the IP addresses of running containers.
* `dkill` helps you killing all running containers with a single command.
* `dupdate` will update all images that you've downloaded from any registry.

As you see, all tools agree on the leading `d` ;-)

You'll find [better documentation on the Docker-Tools in my blog](https://binfalse.de/2016/12/03/handy-docker-tools/).

## Installation

To install the tools just clone this repository and add the executables to your `$PATH` environment.

If you're running a Debian-based system, you may instead [use my apt-repository to install the Docker-Tools]().
In that case you just need to run

    aptitude install bf-docker-tools

and you'll always stay up-to-date with bug fixes and new features :)
