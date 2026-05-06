# Deployments

## Overview
Deployments manage pod replicas and rolling updates.

## Key ideas
- Desired state
- Rolling update and rollback

## Important commands
- `kubectl get deploy` use: list deployments
- `kubectl rollout status deploy/name` use: check rollout status
- `kubectl rollout undo deploy/name` use: roll back a deployment

## Interview questions with answers
- Q: What is a rolling update?
	A: Updating pods gradually to avoid downtime.
- Q: How do you roll back a deployment?
	A: Use `kubectl rollout undo deploy/name`.
