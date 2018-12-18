# NPP
Docker Compose configuration to run PHP 7.2 with Nginx, PHP-FPM, PostgreSQL and Composer.

## Overview

This Docker Compose configuration lets you run easily PHP 7.2 with Nginx, PHP-FPM and PostgreSQL.
* nginx (Nginx)
* php (PHP 7.2 with PHP-FPM, composer)
* db (PostgreSQL)

## Install prerequisites

For now the project has been tested on Linux only but should run fine on Docker for Windows and Docker for Mac.

You will need:

* [Docker CE](https://docs.docker.com/engine/installation/)
* [Docker Compose](https://docs.docker.com/compose/install)
* Git (optional)

## How to use it

### Starting Docker Compose

Checkout the repository or download the sources.

Simply run `docker-compose up` and you are done.

Nginx will be available on `localhost:80` and PostgreSQL on `localhost:5432`.