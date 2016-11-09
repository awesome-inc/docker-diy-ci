# DIY CI (Docker)

Poor man's Continuous Integration platform using Docker.

Right now, this comprises

- [Gitblit](http://gitblit.com/) 
- [Jenkins](https://jenkins.io/) 

## Setup

1. Install [docker](http://docker.io).
2. Install [docker-compose](http://docs.docker.com/compose/install/).
3. Clone this repository

## Usage

Start your stack using *docker-compose*:

    docker-compose up

Alternatively use [Vagrant](https://www.vagrantup.com/)

    vagrant up

Browse to Gitblit [http://localhost:8080](http://localhost:8080) and Jenkins [http://localhost:8081](http://localhost:8081)