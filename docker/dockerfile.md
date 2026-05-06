# Dockerfile

## Overview
A Dockerfile describes how to build an image.

## Common instructions
- `FROM` base image
- `WORKDIR` set working directory
- `COPY` copy files
- `RUN` run commands during build
- `CMD` default command

## Example
```dockerfile
FROM python:3.11-slim
WORKDIR /app
COPY . .
RUN pip install -r requirements.txt
CMD ["python", "app.py"]
```

## Interview questions with answers
- Q: What is the difference between `CMD` and `ENTRYPOINT`?
	A: `CMD` sets defaults; `ENTRYPOINT` defines the main command.
- Q: Why use a slim base image?
	A: Smaller images are faster to pull and have fewer vulnerabilities.
