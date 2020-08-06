# Ubuntu16 Ansible Test Image

<a href="https://github.com/MonolithProjects/docker-systemd-ubuntu16/actions"><img src="https://github.com/MonolithProjects/docker-systemd-ubuntu16/workflows/Dockerfile%20test/badge.svg?branch=master"/></a>
<a href="https://hub.docker.com/repository/docker/monolithprojects/systemd-ubuntu16"><img src="https://img.shields.io/microbadger/layers/monolithprojects/systemd-ubuntu16"/></a>
<a href="https://hub.docker.com/repository/docker/monolithprojects/systemd-ubuntu16"><img src="https://img.shields.io/docker/pulls/monolithprojects/systemd-ubuntu16"/></a>
<a href="https://hub.docker.com/repository/docker/monolithprojects/systemd-ubuntu16"><img src="https://img.shields.io/docker/cloud/automated/monolithprojects/systemd-ubuntu16?maxAge=2592000"/></a>

Docker image with ubuntu16 and enabled systemd. Image contains also `ansible` user (UID/GID 1000) with NOPASSWD:ALL sudo rights.  
This docker image is ment to be used for development purpose. I do not recomend to use it in production.

## Tags

- `latest`  
- `<monthly build timestamp>` for the list of the tags see the [Docker Hub](https://hub.docker.com/repository/docker/monolithprojects/systemd-ubuntu16/tags?page=1)


## How-to

  1. Run command `docker pull monolithprojects/systemd-ubuntu16:latest`  
  2. Run a container from the image: `docker run --detach --privileged --volume=/sys/fs/cgroup:/sys/fs/cgroup:ro monolithprojects/systemd-ubuntu16:latest`  

## License

MIT
