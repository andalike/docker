## Installing Docker
    1  sudo apt-get remove docker docker-engine docker.io
    2  sudo apt-get update
    3  sudo apt-get install     apt-transport-https     ca-certificates     curl     software-properties-common
    4  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
    5  sudo apt-key fingerprint 0EBFCD88
    6  sudo add-apt-repository    "deb [arch=amd64] https://download.docker.com/linux/ubuntu \ $(lsb_release -cs) \ stable"
    7  sudo apt-get update
    8  sudo apt-get install docker-ce
    9  sudo docker run hello-world

## List Docker CLI commands
docker
docker container --help

## Display Docker version and info
docker --version
docker version
docker info

## Execute Docker image
docker run hello-world

## List Docker images
docker image ls

## List Docker containers (running, all, all in quiet mode)
docker container ls
docker container ls --all
docker container ls -aq
