[![Build Status](https://travis-ci.com/marcelobbfonseca/animal-shelters.svg?branch=master)](https://travis-ci.com/marcelobbfonseca/animal-shelters) [![codecov](https://codecov.io/gh/marcelobbfonseca/animal-shelters/branch/master/graph/badge.svg)](https://codecov.io/gh/marcelobbfonseca/animal-shelters) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) [![Greenkeeper badge](https://badges.greenkeeper.io/marcelobbfonseca/animal-shelters.svg)](https://greenkeeper.io/) [![Percentage of issues still open](http://isitmaintained.com/badge/open/marcelobbfonseca/animal-shelters.svg)](http://isitmaintained.com/project/marcelobbfonseca/animal-shelters "Percentage of issues still open") [![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/marcelobbfonseca/animal-shelters.svg)](http://isitmaintained.com/project/marcelobbfonseca/animal-shelters "Average time to resolve an issue")

# Backend example project

Laravel API example project using laradock and Vue

## Running project with docker

Clone project and build the project containers specifing nginx and postgres containers.
```
    cd laradock/
    docker-compose up -d nginx postgres
```
The command above should take a while. They will start atomatically and you`ll find the Application to be running in ```localhost```. No need to specify port.
    Just type ```localhost``` in your browser.

## Docker commands
    docker-compose up -d nginx postgres # Run docker containers
    docker-compose exec workspace bash  # Run workspace command line
    exit

## Laravel commands in workspace
```php
    php artisan tinker # Run laravel console
    vendor/bin/phpunit # Run tests
```
