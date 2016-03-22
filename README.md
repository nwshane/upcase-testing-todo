## Background

This dockerized setup of Rails was built with [this tutorial](https://docs.docker.com/compose/rails/).

## Setup

* Install [Docker Toolbox](https://www.docker.com/)
* `docker-compose build`
* `docker-compose run web rake db:create`
* `docker-compose up`

The application should now be viewable at `http://{docker_machine_ip_address}:3000/`. You can determine docker_machine_ip_address by running `docker-machine ip`.
