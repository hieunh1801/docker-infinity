# Docker Trainning Basic

## Get Started, Part 1: Orientation and setup

### Docker concepts

- What is Container?
- What is image?

### Command Line to start, stop an image

| Command                                         | Description                                   |
|-------------------------------------------------|-----------------------------------------------|
| __docker ps__                                   | show current container running                |
| __docker info__                                 |                                               |
| __docker image ls__                             | show all images was dowloaded in your machine |
| __docker container ls [-all]__ or __docker ps__ | show container is running [all container]     |
| __docker run -p 4000:80 friendlyhello__         | running image __friendlyhello__ on port 4000  |
| __docker run -d -p 4000:80 friendlyhello__      | __running__ image in background               |
| __docker container stop 1fa4ab2cf395__          | Stop container with id =  1fa4ab2cf395        |

## Log in with your Docker ID

