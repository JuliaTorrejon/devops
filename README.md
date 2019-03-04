# Docker and Docker-Compose

Docker compose configuration which launches a Mediawiki instance using MariaDB as a database. 

## Docker Compose Overview

Compose is a tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to configure your application’s services. Then, with a single command, you create and start all the services from your configuration.

## Docker Compose Environments

Compose works in all environments: production, staging, development, testing, as well as CI workflows. 

## Docker Compose Three-Step Process

1. Define your app’s environment with a `Dockerfile` so it can be reproduced anywhere.

2. Define the services that make up your app in `docker-compose.yml` so they can be run together in an isolated environment.

3. Run `docker-compose` up and Compose starts and runs your entire app.

## Docker Compose Commands for Managing the Whole Lifecycle of an Application

- Start, stop, and rebuild services
- View the status of running services
- Stream the log output of running services
- Run a one-off command on a service

## Docker Compose Steps

### Step 1: Set Up



## Docker Glossary


**Container**: A container is a runtime instance of a docker image.

A Docker container consists of

- A Docker image
- An execution environment
- A standard set of instructions
---
**Compose**: Compose is a tool for defining and running complex applications with Docker. With Compose, you define a multi-container application in a single file, then spin your application up in a single command which does everything that needs to be done to get it running.

---
**Dockerfile**: A Dockerfile is a text document that contains all the commands you would normally execute manually in order to build a Docker image. Docker can build images automatically by reading the instructions from a Dockerfile.

---
**Image**: Docker images are the basis of containers. An Image is an ordered collection of root filesystem changes and the corresponding execution parameters for use within a container runtime. An image typically contains a union of layered filesystems stacked on top of each other. An image does not have state and it never changes.

---
**Volume**: A volume is a specially-designated directory within one or more containers that bypasses the Union File System. Volumes are designed to persist data, independent of the container’s life cycle. Docker therefore never automatically delete volumes when you remove a container, nor will it “garbage collect” volumes that are no longer referenced by a container. Also known as: data volume

There are three types of volumes: host, anonymous, and named:

A host volume lives on the Docker host’s filesystem and can be accessed from within the container.

A named volume is a volume which Docker manages where on disk the volume is created, but it is given a name.

An anonymous volume is similar to a named volume, however, it can be difficult, to refer to the same volume over time when it is an anonymous volumes. Docker handle where the files are stored.
