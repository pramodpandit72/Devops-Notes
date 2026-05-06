# Docker Basics

## Overview
Docker packages apps into containers for easy deployment.

## Key ideas
- Images are templates
- Containers are running images

## Important commands
- `docker build -t app .` use: build an image
- `docker run -p 8080:80 app` use: run a container
- `docker ps` use: list running containers
- `docker images` use: list images
- `docker logs <id>` use: view logs

## Interview questions with answers
- Q: What is the difference between an image and a container?
	A: An image is a template; a container is a running instance.
- Q: Why use containers?
	A: They make apps portable and consistent across environments.
