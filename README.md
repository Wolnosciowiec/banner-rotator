Banner Rotator
==============

[![Docker Build Status](https://img.shields.io/docker/build/wolnosciowiec/banner-rotator.svg)](https://hub.docker.com/r/wolnosciowiec/banner-rotator)
[![MicroBadger Layers](https://img.shields.io/microbadger/layers/wolnosciowiec/banner-rotator.svg)](https://github.com/Wolnosciowiec/banner-rotator)


Banner rotating service. Outputs a list of banners in HTML and JSON formats, has an API documentation.

###### Made for the Anarchist movement

#### Quick start

1. Install required: PHP 7.2, GNU Make, php-sqlite
2. Clone the repository
3. Do the setup: `make build setup_database_first_time`
4. Start the application: `make start_dev`

#### Endpoints documentation

Use `/public/doc` endpoint to access the documentation.
Also, there is an exported list of routes for Postman in `postman.json`
 