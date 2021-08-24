# Codeflix RabbitMQ

## What is Codeflix?

Codeflix is a streaming platform similar to Netflix. It is built with different microservices developed with Node.js, Python, Golang and Laravel.

## What's in this repository

The message broker used by Codeflix is RabbitMQ. This repository has a Docker Compose file responsible to provision a RabbitMQ Server and its Management Console.

# Running the project

Docker makes it very easy to set up RabbitMQ. You'll simply need to run the code below:
```
docker-compose up
```

## Ports

RabbitMQ will run in two different ports, since the Docker Compose file spins up the server and also the management console:

- Server: 127.0.0.1:<b>5672</b>
- Console: 127.0.0.1:<b>15672</b>
