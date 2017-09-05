Docker image for PhpMetrics
===========================

## Usage

To launch the phpMetrics into the container, run:

    docker run --rm --user $(id -u):$(id -g) --volume $(pwd):/data/www nicodocker91/phpmetrics <options> ${ROOT_FOLDER}

## Volumes

The only volume available to mount is `/data`.

The entrypoint is `/data/www`.

## Options

Run the following command to read all options available:

    docker run --rm nicodocker91/phpmetrics --help

