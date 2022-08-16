# Docker-Aug2022

### Instructions for Docker Installation on Ubuntu 18.04

Check Ubuntu version
```lsb_release -a
```

Update all Libraries (First time)
>sudo apt-get update

Install Docker
>sudo apt-get install docker.io

Add current user to docker group
>sudo usermod -aG docker $USER

Logout & log back in or run the following command to activate changes to the docker group
>newgrp docker

Check if docker is up & running
>docker version

Check status of docker daemon
>sudo systemctl status docker
Type ‘q’ to get out of terminal

In case docker daemon is not started, start it using command
>sudo systemctl start docker
