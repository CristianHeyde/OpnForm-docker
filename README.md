# OpnForm Docker

This repository contains Docker configurations and build scripts for the OpnForm project.

## Repository Structure

- `api/`: Contains the Dockerfile and related files for the API service.
- `client/`: Contains the Dockerfile and related files for the client service.
- `web/`: Contains the Dockerfile and related files for the web service.
- `docker-build.sh`: Shell script to build Docker images for the different services.

## Prerequisites

- Docker
- Docker Buildx
- Git

## Building Docker Images

To build the Docker images, you can use the provided `docker-build.sh` script. This script will build the images for the API, client, and web services.

### Usage

1. Clone the repository:
    ```sh
    git clone https://github.com/your-org/OpnForm-docker.git
    cd OpnForm-docker
    ```

2. Set the `OPNFORM_VERSION` environment variable (optional, defaults to `v1.5`):
    ```sh
    export OPNFORM_VERSION=main
    ```

3. Run the build script:
    ```sh
    ./docker-build.sh
    ```

## Environment Variables

- `OPNFORM_VERSION`: The version of the OpnForm repository to clone (default: `v1.5`).

## License

This project is licensed under the MIT License. See the LICENSE file for details.# OpnForm Docker

This repository contains Docker configurations and build scripts for the OpnForm project.

## Repository Structure

- `api/`: Contains the Dockerfile and related files for the API service.
- `client/`: Contains the Dockerfile and related files for the client service.
- `web/`: Contains the Dockerfile and related files for the web service.
- `docker-build.sh`: Shell script to build Docker images for the different services.

## Prerequisites

- Docker
- Docker Buildx
- Git

## Building Docker Images

To build the Docker images, you can use the provided `docker-build.sh` script. This script will build the images for the API, client, and web services.

### Usage

1. Clone the repository:
    ```sh
    git clone https://github.com/your-org/OpnForm-docker.git
    cd OpnForm-docker
    ```

2. Set the `OPNFORM_VERSION` environment variable (optional, defaults to `v1.5`):
    ```sh
    export OPNFORM_VERSION=main
    ```

3. Run the build script:
    ```sh
    ./docker-build.sh
    ```

## Environment Variables

- `OPNFORM_VERSION`: The version of the OpnForm repository to clone (default: `v1.5`).

## License

This project is licensed under the MIT License. See the LICENSE file for details.