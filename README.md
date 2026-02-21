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
```
 docker-compose up -d
```
 Verify if ollama run successfully?
 
 - http://localhost:11434/
 Below text should be appeared in browser
```
ollama is running
```
 
  Enter into the container
  ```
 docker exec -it ollama /bin/sh (mac/linux)
 docker exec -it ollama bash (windows)
```

  Now run the below command, it will pull the model and execute it
  ```
  ollama run qwen2.5:3b
  ollama run qwen3-embedding:4b
  ```
