# Udagram App refactored into Microservices - Project 3

## Github Repo

<https://github.com/adityasanil/Udagram-microservices>

The _udacity-c3-deployment_ folder, contains docker files and k8s deployment, services files.\
The _udacity-c3-frontend_ contains simple Ionic client web application.\
The _udacity-c3-restapi-feed_ contains a nodejs microservice for feed management.\
The _udacity-c3-restapi-user_ contains a nodejs microservice for user management.\

## Setup

### Installing Node and Npm

This project depends on Nodejs and Node Package Manager, download from [here](https://nodejs.com/en/download).

### Installing Ionic Cli

The Ionic Cli is required to serve and build the frontend, dowload it from [here](https://ionicframework.com/docs/intro/cli)

## Installing Docker, Minikube and Kubectl

To install Docker visit this [link](https://docs.docker.com/docker-for-mac/install/)\
Install `Homebrew` if you don't have it, [link](https://brew.sh/)\
Install minikube using `brew install minikube`\
Install kubectl using `brew insall kubectl`

## Docker Hub Repo

Frontend: <https://hub.docker.com/repository/docker/adityasanil/udacity-frontend>\
Backend-User: <https://hub.docker.com/repository/docker/adityasanil/udacity-restapi-user>\
Backend-Feed: <https://hub.docker.com/repository/docker/adityasanil/udacity-restapi-feed>\
Webserver: <https://hub.docker.com/repository/docker/adityasanil/reverseproxy>\
