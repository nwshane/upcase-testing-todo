## Background

This dockerized setup of Rails was built with [this tutorial](https://docs.docker.com/compose/rails/).

## Setup

* Install [docker, docker-machine and docker-compose](https://www.docker.com/) (packaged together in Docker Toolbox on Mac and Windows)
* `docker-compose build`
* `docker-compose run web rake db:create`
* `docker-compose up`

The application should now be viewable at `http://{docker_machine_ip_address}:3000/`, where `docker_machine_ip_address` is the output of the command `docker-machine ip`.
