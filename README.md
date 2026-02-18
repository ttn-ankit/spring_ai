# Setup Instructions for Spring AI

## Docker Prerequisites
 Before you start, ensure you have Docker and Docker Compose installed on your machine. You can download them from the following links:
- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Clone the repo
 Clone the repository with below url:
- https://github.com/ttn-ankit/spring_ai

## Start Docker
 This project already have the docker-compose.yml file which will pull the ollama image and run the container for you, use below command
- docker-compose up -d

  Enter into the container
- docker exec -it /bin/sh (mac/linux)
- docker exec -it bash
