# PX4 Containers

Contains Dockerfiles for Docker containers to build and test PX4, with and without ROS and ROS2.

License: according to [LICENSE](https://github.com/PX4/Firmware/blob/master/LICENSE) in the root directory of the PX4 Firmware repository.

[![Build Status](https://github.com/PX4/PX4-containers/actions/workflows/docker_builds.yml/badge.svg)](https://github.com/PX4/PX4-containers/actions/workflows/docker_builds.yml)


## Container Hierarchy

- [px4io/px4-dev-base-archlinux](https://hub.docker.com/r/px4io/px4-dev-base-archlinux) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-base-archlinux.svg)](http://microbadger.com/images/px4io/px4-dev-base-archlinux) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-base-archlinux.svg)](https://hub.docker.com/r/px4io/px4-dev-base-archlinux)
- [px4io/px4-dev-base-bionic](https://hub.docker.com/r/px4io/px4-dev-base-bionic) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-base-bionic.svg)](http://microbadger.com/images/px4io/px4-dev-base-bionic) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-base-bionic.svg)](https://hub.docker.com/r/px4io/px4-dev-base-bionic)
    - [px4io/px4-dev-clang](https://hub.docker.com/r/px4io/px4-dev-clang) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-clang.svg)](http://microbadger.com/images/px4io/px4-dev-clang) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-clang.svg)](https://hub.docker.com/r/px4io/px4-dev-clang)
    - [px4io/px4-dev-nuttx-bionic](https://hub.docker.com/r/px4io/px4-dev-nuttx-bionic) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-nuttx-bionic.svg)](http://microbadger.com/images/px4io/px4-dev-nuttx-bionic) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-nuttx-bionic.svg)](https://hub.docker.com/r/px4io/px4-dev-nuttx-bionic)
    - [px4io/px4-dev-nuttx-clang](https://hub.docker.com/r/px4io/px4-dev-nuttx-clang) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-nuttx-clang.svg)](http://microbadger.com/images/px4io/px4-dev-nuttx-clang) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-nuttx-clang.svg)](https://hub.docker.com/r/px4io/px4-dev-nuttx-clang)
    - [px4io/px4-dev-raspi](https://hub.docker.com/r/px4io/px4-dev-raspi) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-raspi.svg)](http://microbadger.com/images/px4io/px4-dev-raspi) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-raspi.svg)](https://hub.docker.com/r/px4io/px4-dev-raspi)
    - [px4io/px4-dev-simulation-bionic](https://hub.docker.com/r/px4io/px4-dev-simulation-bionic) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-simulation-bionic.svg)](http://microbadger.com/images/px4io/px4-dev-simulation-bionic) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-simulation-bionic.svg)](https://hub.docker.com/r/px4io/px4-dev-simulation-bionic)
        - [px4io/px4-dev-ros-melodic](https://hub.docker.com/r/px4io/px4-dev-ros-melodic) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-ros-melodic.svg)](http://microbadger.com/images/px4io/px4-dev-ros-melodic) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-ros-melodic.svg)](https://hub.docker.com/r/px4io/px4-dev-ros-melodic)
            - [px4io/px4-dev-ros2-dashing](https://hub.docker.com/r/px4io/px4-dev-ros2-dashing) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-ros2-dashing.svg)](http://microbadger.com/images/px4io/px4-dev-ros2-dashing) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-ros2-dashing.svg)](https://hub.docker.com/r/px4io/px4-dev-ros2-dashing)
            - [px4io/px4-dev-ros2-eloquent](https://hub.docker.com/r/px4io/px4-dev-ros2-eloquent) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-ros2-eloquent.svg)](http://microbadger.com/images/px4io/px4-dev-ros2-eloquent) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-ros2-eloquent.svg)](https://hub.docker.com/r/px4io/px4-dev-ros2-eloquent)
- [px4io/px4-dev-base-focal](https://hub.docker.com/r/px4io/px4-dev-base-focal) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-base-focal.svg)](http://microbadger.com/images/px4io/px4-dev-base-focal) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-base-focal.svg)](https://hub.docker.com/r/px4io/px4-dev-base-focal)
    - [px4io/px4-dev-nuttx-focal](https://hub.docker.com/r/px4io/px4-dev-nuttx-focal) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-nuttx-focal.svg)](http://microbadger.com/images/px4io/px4-dev-nuttx-focal) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-nuttx-focal.svg)](https://hub.docker.com/r/px4io/px4-dev-nuttx-focal)
    - [px4io/px4-dev-simulation-focal](https://hub.docker.com/r/px4io/px4-dev-simulation-focal) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-simulation-focal.svg)](http://microbadger.com/images/px4io/px4-dev-simulation-focal) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-simulation-focal.svg)](https://hub.docker.com/r/px4io/px4-dev-simulation-focal)
        - [px4io/px4-dev-ros-noetic](https://hub.docker.com/r/px4io/px4-dev-ros-noetic) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-ros-noetic.svg)](http://microbadger.com/images/px4io/px4-dev-ros-noetic) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-ros-noetic.svg)](https://hub.docker.com/r/px4io/px4-dev-ros-noetic)
            - [px4io/px4-dev-ros2-foxy](https://hub.docker.com/r/px4io/px4-dev-ros2-foxy) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-ros2-foxy.svg)](http://microbadger.com/images/px4io/px4-dev-ros2-foxy) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-ros2-foxy.svg)](https://hub.docker.com/r/px4io/px4-dev-ros2-foxy)
    - [px4io/px4-dev-ros2-rolling](https://hub.docker.com/r/px4io/px4-dev-ros2-rolling) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-ros2-rolling.svg)](http://microbadger.com/images/px4io/px4-dev-ros2-rolling) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-ros2-rolling.svg)](https://hub.docker.com/r/px4io/px4-dev-ros2-rolling)
    - [px4io/px4-dev-ros2-galactic](https://hub.docker.com/r/px4io/px4-dev-ros2-galactic) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-ros2-galactic.svg)](http://microbadger.com/images/px4io/px4-dev-ros2-galactic) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-ros2-galactic.svg)](https://hub.docker.com/r/px4io/px4-dev-ros2-galactic)
- [px4io/px4-dev-base-jammy](https://hub.docker.com/r/px4io/px4-dev-base-jammy) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-base-jammy.svg)](http://microbadger.com/images/px4io/px4-dev-base-jammy) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-base-jammy.svg)](https://hub.docker.com/r/px4io/px4-dev-base-jammy)
    - [px4io/px4-dev-nuttx-jammy](https://hub.docker.com/r/px4io/px4-dev-nuttx-jammy) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-nuttx-jammy.svg)](http://microbadger.com/images/px4io/px4-dev-nuttx-jammy) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-nuttx-jammy.svg)](https://hub.docker.com/r/px4io/px4-dev-nuttx-jammy)
- [px4io/px4-dev-base-noble](https://hub.docker.com/r/px4io/px4-dev-base-noble) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-base-noble.svg)](http://microbadger.com/images/px4io/px4-dev-base-noble) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-base-noble.svg)](https://hub.docker.com/r/px4io/px4-dev-base-noble)
    - [px4io/px4-dev-nuttx-noble](https://hub.docker.com/r/px4io/px4-dev-nuttx-noble) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-nuttx-noble.svg)](http://microbadger.com/images/px4io/px4-dev-nuttx-noble) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-nuttx-noble.svg)](https://hub.docker.com/r/px4io/px4-dev-nuttx-noble)
- [px4io/px4-dev-armhf](https://hub.docker.com/r/px4io/px4-dev-armhf) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-armhf.svg)](http://microbadger.com/images/px4io/px4-dev-armhf) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-armhf.svg)](https://hub.docker.com/r/px4io/px4-dev-armhf)
- [px4io/px4-dev-aarch64](https://hub.docker.com/r/px4io/px4-dev-aarch64) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-aarch64.svg)](http://microbadger.com/images/px4io/px4-dev-aarch64) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-aarch64.svg)](https://hub.docker.com/r/px4io/px4-dev-aarch64)
- [px4io/px4-dev-base-sign](https://hub.docker.com/r/px4io/px4-dev-base-sign) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-base-sign.svg)](http://microbadger.com/images/px4io/px4-dev-base-sign) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-base-sign.svg)](https://hub.docker.com/r/px4io/px4-dev-base-sign)
    - [px4io/px4-dev-simulation-sign](https://hub.docker.com/r/px4io/px4-dev-simulation-sign) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-simulation-sign.svg)](http://microbadger.com/images/px4io/px4-dev-simulation-sign) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-simulation-sign.svg)](https://hub.docker.com/r/px4io/px4-dev-simulation-sign)

- [px4io/px4-docs](https://hub.docker.com/r/px4io/px4-docs) [![](https://images.microbadger.com/badges/image/px4io/px4-docs.svg)](http://microbadger.com/images/px4io/px4-docs) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-docs.svg)](https://hub.docker.com/r/px4io/px4-docs)


## Running

If you like to run the container and use the Firmware source from outside of the container, use the following command and specify the appropriate volume mapping.

```
docker run -it --rm \
    -v <local_src>:/home/user/Firmware:rw \
    -v /tmp/.X11-unix:/tmp/.X11-unix:ro \
    -e DISPLAY=${DISPLAY} \
    -e LOCAL_USER_ID="$(id -u)" \
    --name=container_name px4io/px4-dev-simulation-sign /bin/bash
```

Or use [docker_run.sh](https://github.com/PX4/Firmware/blob/master/Tools/docker_run.sh).

### Running Sign Scheme
Allow graphical access to the container
```sh
xhost +local:docker  
```

To run the Sign Scheme environment inside a PX4 container, use the following command:
```sh
docker run -it --privileged --user root \
    -v ./PX4-Autopilot:/home/docker_user/PX4-Autopilot:rw \
    -v ./sign_scheme:/home/docker_user/sign_scheme:rw \
    --network host \
    --name px4-sign \
    px4io/px4-dev-simulation-sign:latest bash

```

After starting the container, execute the following steps:

```sh
cd sign_scheme/
./compile.sh

cd /home/docker_user
mkdir log
mkdir key
cd /home/docker_user/key
openssl genpkey -algorithm RSA -out private_key.pem -pkeyopt rsa_keygen_bits:2048
openssl rsa -in private_key.pem -pubout -out public_key.pem


cd /home/docker_user/PX4-Autopilot
git config --global --add safe.directory /home/docker_user/PX4-Autopilot
git submodule update --init --recursive


HEADLESS=1 make px4_sitl jmavsim
```

## Building

```
cd docker
docker build -t px4io/px4-dev-simulation-sign -f Dockerfile_simulation-sign .
```

or:

```
cd docker
make px4-dev-simulation-sign
```