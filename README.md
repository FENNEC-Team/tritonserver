# Server with detection and identification models

## Repository structure

- __nn__ - package with models
- __inference_triton__ - package for serving with [Nvidia Triton Inference Server](https://developer.nvidia.com/nvidia-triton-inference-server)

## Start

Firstly you need to install docker and docker-compose(latest version)

```bash
cd inference_triton/docker
DOCKER_BUILDKIT=1 docker-compose -f prod.yml up --build
