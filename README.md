# Basic-Commands-on-Docker
Docker Basics commands
Steps by steps For Beginners
Note:If you are on windows you can use below docker commands. 
For linux user you have to use sudo command at the begining.

============================
#Docker Basics

1.docker version
2.docker -v
3.docker info
4.docker --help
5.docker login
============================

#Docker Images

1.docker images
2.docker Pull <Image-name>
3.docker rmi
============================

#Docker container
1.docker ps
2.docker run -it -d <image-name> : This will let the docker to run as a daemon.
3.docker start
4.docker stop <container-id>
5.docker exec -it <container-id> bash:This will let us to get inside container.
6.docker commit <container-id> <image-name>
7.docker rm -f $(docker ps -a -q): to remove all the container. "user sudo if you are on linux".
==========================
Docker System
1.docker stats
2.docker system df
3.docker system prune
