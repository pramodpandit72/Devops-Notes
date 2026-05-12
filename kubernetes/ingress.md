# Ingress

## Overview
Ingress manages external access to services.
A single entry point that routes to many services.

In short (refined version of your line)
Ingress is a Kubernetes resource that defines rules to route external HTTP/HTTPS traffic from a single entry point (domain/IP) to multiple internal services based on paths or hostnames.

## Key ideas
- Requires an Ingress Controller
- Supports host and path routing

## Interview questions with answers
- Q: What is an Ingress Controller?
	A: The component that implements Ingress rules.
- Q: When would you use Ingress over a LoadBalancer?
	A: When you want host/path routing and fewer load balancers.
