### Docker in Docker Image

Based off of latest version here - https://github.com/docker-library/docker

Latest image can be pulled using `docker pull docker:latest`


>**NOTE** Docker in Docker requires you to run as priveledged

Run cmd: `docker run --privileged -d docker:dind`