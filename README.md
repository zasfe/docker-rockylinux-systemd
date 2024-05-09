Docker Rocky Linux Systemd
==========================

This Dockerfile can build containers capable to use systemd.

[![build status badge](https://img.shields.io/github/actions/workflow/status/zasfe/docker-rockylinux-systemd/build-push-action.yml?branch=main&label=GitHub%20CI)](https://github.com/zasfe/docker-rockylinux-systemd/actions?query=workflow%3A%22GitHub+CI%22+branch%3Amain) 
![Docker Automated build](https://img.shields.io/docker/automated/zasfe/rockylinux?label=Docker%20Automated%20build)
![Docker Cloud Automated build](https://img.shields.io/docker/cloud/automated/zasfe/rockylinux?label=Docker%20Cloud%20Automated%20build)
![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/zasfe/rockylinux?label=Docker%20Cloud%20Build%20Status)

[![Docker Image Version (tag)](https://img.shields.io/docker/v/zasfe/centos/main)](https://hub.docker.com/r/zasfe/rockylinux)
[![Docker Stars](https://img.shields.io/docker/stars/zasfe/centos.svg)](https://hub.docker.com/r/zasfe/rockylinux) 
[![Docker Pulls](https://img.shields.io/docker/pulls/zasfe/centos.svg)](https://hub.docker.com/r/zasfe/rockylinux) 
[![Docker Image Size (tag)](https://img.shields.io/docker/image-size/zasfe/rockylinux/main?label=Docker%20Image%20Size)](https://hub.docker.com/r/zasfe/rockylinux) 


Branches
--------

This repository has multiple branches that relate to RockyLinux versions.

|Branch |Rocky Linux Version|Docker image tag|
|-------|-------------------|----------------|
|7      |7                  |7               |
|8      |8                  |8               |
|master |9                  |latest          |

Pull strategy
-------------

The different branches are **not** merged, they live as individual branches.

Manually starting
-----------------

```
docker run \
  --tty \
  --privileged \
  --volume /sys/fs/cgroup:/sys/fs/cgroup:ro \
  robertdebock/rockylinux
```
