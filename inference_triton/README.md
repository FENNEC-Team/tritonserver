# Nvidia Triton based inference

[Nvidia Triton Inference Server](https://developer.nvidia.com/nvidia-triton-inference-server).

# Start

1. Start Triton Inference Server

	Firstly you need to install docker and docker-compose(latest version)

	```bash
	cd docker
	DOCKER_BUILDKIT=1 docker-compose -f prod.yml up --build
	```

2. Install and activate virtual environment

    ```bash
    poetry install --with=dev
    poetry shell
    ```

3. Run tests

    ```bash
    pytest ./tests -vv --disable-warnings
    ```
