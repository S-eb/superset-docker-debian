# superset-docker-debian

## How to deploy apache superset on docker

![logo](https://avatars3.githubusercontent.com/u/42724554?s=200&v=4)

Apache Superset is a fantastic tool for data viz. You should really try it if you haven't yet.
The official documentation [here](https://superset.apache.org/) is great but really describes only two main path of deploying: 
using a docker compose or from scratch in development mode.
In my case I was looking:

1. to deploy on kubernetes so the compose path was not ideal;
2. to deploy in production mode.

The short tutorial below will show you how to deploy Apache Superset 0.37.2 using docker.

### Configuration

In this tutorial, I will show
- a deployement of Apache Superset version 0.37.2;
- using Docker Desktop (without docker compose) based on a debian image;
- using redis for cache;
- connecting to postgres for the superset database;
- and running one celery instance.

### Deploying postgres

### Deploying redis

### Setting up a Docker network

### Building the Superset docker image

### Deploying


