# docker-uv
This repository contains all sources necessary to build a openthinclient docker image frome the  ucs-appbox base image.

A stable version is not yet released.

## Installation Instruction

### Build the Image by hand (first way)
* clone this repo
* cd docker-uv 
* docker build -t docker-uv .

### download from Docker hub (second way)
* docker pull jenerpeon/docker-uv

### launch a container
* docker run -it --name otc --net=host docker-uv 

And you are done! 

* visit http://localhost:8080 to start the manager console

But...
there are some requirements to fullfill before managing and booting your devices with the openthinclient solution.
Further Information is provided here
* https://wiki.openthinclient.org/confluence/dashboard.action
* http://openthinclient.org/de/dokumentation-openthinclient/

### About the Software
openthinclient is a Free Open Source thinclient Solution consisting of a Linux based operating system along with a comprehensive Java based management GUI and server component. It is intended for environments where a medium to large number of thinclients must be supported and managed efficiently. Offering flexibility unheard of in the world of proprietary thinclient Solutions, openthinclient empowers developers and integrators to create advanced thin client solutions… for free.
