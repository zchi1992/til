## Download docker image by running below
`docker pull [image]`

## Docker starter gui 
[docker starter guide](https://docs.docker.com/get-started/02_our_app/)

## Container volumes and mounting
Volumes provide the ability to connect specific filesystem paths of the container back to the host machine

`docker volume create ` creates a new volume that containers can consume and store

https://docs.docker.com/engine/reference/commandline/run/#mount

## Bind mounts
https://docs.docker.com/get-started/06_bind_mounts/

## Docker common command
`docker run` vs `docker start`\
`docker run` create and run a new container from an image while `docker start` restarts a stopped container.

`Ctrl + D` stops interactive container session.

A sample command to run a container with bind mount

```
docker run -i -d --name HPCA --mount type=bind,source="$(pwd)",target=/home/cs6290 jsachs123/cs6290
```

`docker run --name [Name] [Container]` assigns a name to the container

`docker run -dp`runs the container in the background `-d` and creats a port mapping between the host and the container `-p`

`docker stop [ID]` stops container and `docker rm [ID]` removes the container`

`docker ps -a` lists all containers. `docker ps` only shows running containers

`docker cp` copies files/folders between a container and the local filesystem.

`docker build -t` name and optially a tag in the name::tag format
