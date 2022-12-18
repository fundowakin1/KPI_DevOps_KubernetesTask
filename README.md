# KPI_DevOps_DockerTask

## Simple node.js app that runs on port 80

### Build Docker image

`docker build -t fundowakin/devopsdockerlab . `

### Run docker image with options:

`docker run -p 80:80 --cpus=2 -m="100m" -d fundowakin/devopsdockerlab`

- -d - run container in the detached mode

- -p - maps ports in container to Docker host port (in our case it maps port 80 on container to 80 on Docker host)

- -m - the maximum amount of memory the container can use

- --cpus - specify how much of the available CPU resources a container can use

### Link to the Dockerhub: https://hub.docker.com/repository/docker/fundowakin/devopsdockerlab
