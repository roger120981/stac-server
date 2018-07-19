# sat-api 

[![CircleCI](https://circleci.com/gh/sat-utils/sat-api.svg?style=svg)](https://circleci.com/gh/sat-utils/sat-api)

Sat-api is a STAC compliant web API for searching and serving satellite imagery metadata. Development Seed runs an instance of it for Landsat and Sentinel imagery hosted on AWS. You can access this instance at https://sat-api.developmentseed.org.

An older version of sat-api can be found on the [legacy branch ](https://github.com/sat-utils/sat-api/tree/legacy) and is deployed at https://api.developmentseed.org/satellites.

This repo includes a number of npm packages that are used to create and populate an instance of sat-api. For the full list of packages go to:
https://www.npmjs.com/org/sat-utils

## Documentation

Access the documenation [here](docs) or on [gitbook(https://sat-utils.gitbook.io/sat-api/).

## Development

### Local Installation

    $ yarn
    $ yarn bootstrap
    $ yarn build

    # to continually watch and build source files
    $ yarn watch

### Run Docs locally

    $ yarn docs-serve

## About

[sat-api](http://github.com/sat-utils/sat-api.git) was made by [Development Seed](http://developmentseed.org).
