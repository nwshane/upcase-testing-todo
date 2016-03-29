## Todos app for learning test-driven development

This Todos app is used as an example in the Test-Driven Rails course on Upcase. Setup is described in [this video](https://upcase.com/videos/setting-up-the-app-and-initial-test).

## Setup with Docker

* Install [docker, docker-machine and docker-compose](https://www.docker.com/) (packaged together in Docker Toolbox on Mac and Windows)
* `docker-compose build`
* `docker-compose up`
* `docker-compose run web rake db:create`

The application should now be viewable at `http://{docker_machine_ip_address}:3000/`, where `docker_machine_ip_address` is the output of the command `docker-machine ip`.
