# SBCL Dockerfile

This repository contains **Dockerfile** of [SBCL](http://www.sbcl.org/) for Docker's automated
build published to the [Docker Hub](https://hub.docker.com/r/andron94/dockerfile-sbcl/).

## Base Docker Image

+ [alpine:3.7](https://hub.docker.com/_/alpine/)

## Installation

1.  Install [Docker](https://docs.docker.com/engine/installation/).
2.  Download automated build from public Docker Hub Registry:
    ```sh
    docker pull andron94/dockerfile-sbcl:[TAG]
    ```

## Usage

### Run `SBCL` session

```sh
docker run --rm -it andron94/dockerfile-sbcl:[TAG]
```

### Run `shell` session

```sh
docker run --rm -it --entrypoint /bin/sh andron94/dockerfile-sbcl:[TAG]
```
