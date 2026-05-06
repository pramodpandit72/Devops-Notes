# Docker Networking

## Overview
Containers communicate using networks.

## Key ideas
- Default bridge network
- User-defined networks allow container name resolution

## Important commands
- `docker network ls` use: list networks
- `docker network create mynet` use: create a network
- `docker network inspect mynet` use: inspect a network

## Interview questions with answers
- Q: How do containers talk to each other?
	A: They use Docker networks and service names.
- Q: What is the bridge network?
	A: The default local network for containers on a host.
