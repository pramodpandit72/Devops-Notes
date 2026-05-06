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
- `docker compose up -d` start services
- `docker compose down` stop services

## Interview questions
- When should you use Docker Compose?
- What is a service in Compose?
