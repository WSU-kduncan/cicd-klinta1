# Project 6

## Project Overview

Created a new repository containing a website that displays a recipe for chacolate chip cookes. Makes a Dockerfile to create a container enviroment to run the website in and documents the process.

## Dockerize

- installed the docker and dependancies on debian(sudo apt install docker && apt install python3).

- built the containter (docker build -t cookie-cont .)

- ran the container (docker run -d -p 80:80 cookies-cont)

- opened browser and copied https://localhost:8080/

## GitHub actions and Dockerhub

- went to hub.docker.com and created and account and verified my email

- logged into dockerhub in the CLI (docker login)

- stored GitHub secrets (DockerHub username and password) to authenticate through DockerHub (set to 'DOCKER_USERNAME' and 'DOCKER_PASSWORD' respectively)