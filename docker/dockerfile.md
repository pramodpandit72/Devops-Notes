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

## Interview questions
- What is the difference between `CMD` and `ENTRYPOINT`?
- Why use a slim base image?
