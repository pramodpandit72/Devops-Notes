# Project: Dockerized App

## Goal
Containerize a simple app and run it locally.

## Steps
1) Create a basic app (any language).
2) Write a Dockerfile.
3) Build the image.
4) Run the container.

## Important commands
- `docker build -t myapp .` use: build the app image
- `docker run -p 8080:8080 myapp` use: run the container

## Interview questions with answers
- Q: What files are required to dockerize an app?
	A: A `Dockerfile` and the app source code.
- Q: How do you pass environment variables to a container?
	A: Use `-e KEY=value` or a compose file.
