# wikitolearn-shared-services

## Synopsis
This repository contains WikiToLearn shared services like Keycloak or Apache Kafka.
Since they are _shared dependencies_ among other architecture services they have to be run once in a development environment.
Consiquently, they cannot be specified into `docker-compose.yml` file of their consumers.

## Development
We use Docker to speed-up development and setup the environment without any dependency issues.

### Minimum requirements
* Docker Engine 17.09.0+

### How to run
It is advisable to run using the `docker-compose.yml` file provided.

Run instructions:

* Build all docker containers with: `docker-compose build`
* Run all docker containers with: `docker-compose up`

## Versioning
We use [SemVer](http://semver.org/) for versioning.

## License
This project is licensed under the AGPLv3+. See the [LICENSE.md](LICENSE.md) file for details.
