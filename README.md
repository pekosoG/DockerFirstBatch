# Docker Fundamentals 
## [Dev.f GDL](https://www.devf.mx/guadalajara) - Cinta Negra - Batch 1
=================


Docker Images are build based on a file content, filled with instructions to tell docker what to download
what to install and how to install.

Using [Docker Repos](https://hub.docker.com) to store and download official images

Dockerfile
--------

This file contains the instructions to build the base image

```
FROM <image-name>:<image-tag>   -> FROM indicates the base image and the tag used by docker, downloaded from the repo

```