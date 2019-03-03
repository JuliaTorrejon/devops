# Docker and Docker-Compose

Docker compose configuration which launches a Mediawiki instance using MariaDB as a database. 

## Docker Compose Overview

Compose is a tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to configure your application’s services. Then, with a single command, you create and start all the services from your configuration.

## Docker Compose Environments

Compose works in all environments: production, staging, development, testing, as well as CI workflows. 

## Docker Compose Three-Space Process

1. Define your app’s environment with a Dockerfile so it can be reproduced anywhere.

2. Define the services that make up your app in docker-compose.yml so they can be run together in an isolated environment.

3. Run docker-compose up and Compose starts and runs your entire app.
