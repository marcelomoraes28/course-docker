# Docker Project
Course "Docker: Essential Developer Tool" from Udemy.

This project has for objective simulate a scalable architecture to send emails.

## Architecture

### Containers
* db - postgres:9.6
* frontend - nginx:1.13
* app - python:3.6
* queue - redis:3.2
* worker - custom image 

## How can a use?
* Start docker in daemon mode: docker-compose up -d
* Access in your browser: localhost
* Write a message and send

To follow the logs of messages you can use: docker-compose logs -f -t
