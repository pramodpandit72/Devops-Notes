# Docker Compose

## Overview
Compose runs multi-container apps with one command.

## Example
```yaml
services:
  web:
    build: .
    ports:
      - "8080:80"
```

## Important commands
- `docker compose up -d` use: start services in the background
- `docker compose down` use: stop and remove services

## Interview questions with answers
- Q: When should you use Docker Compose?
  A: For local multi-container development or testing.
- Q: What is a service in Compose?
  A: A container definition in the compose file.
