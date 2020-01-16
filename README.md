# Docker Setup to setup an ELK stack to log all running docker containers

To start up the docker containers run:

~~~
docker-compose up -d --build
~~~

# Dependencies: Docker

You have to have docker and docker-compose installed to run the containers.
There is a convenience ansible setup in this repository to install docker on 
your machine: https://git.ph1.uni-koeln.de/docker/prepare_for_docker.git. 

Please run:

~~~
git clone https://git.ph1.uni-koeln.de/docker/prepare_for_docker.git
cd prepare_for_docker
./prepare_for_docker.sh
~~~

And enter your sudo password when asked for.

