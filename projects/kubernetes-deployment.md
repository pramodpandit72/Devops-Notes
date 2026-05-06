# Project: Kubernetes Deployment

## Goal
Deploy a containerized app to Kubernetes.

## Steps
1) Create a deployment YAML.
2) Create a service YAML.
3) Apply the manifests.
4) Verify pods and service.

## Important commands
- `kubectl apply -f deployment.yaml` use: create or update a deployment
- `kubectl apply -f service.yaml` use: create or update a service
- `kubectl get pods` use: list pods
- `kubectl get svc` use: list services

## Interview questions with answers
- Q: What does `kubectl apply` do?
	A: It creates or updates resources from a manifest.
- Q: How do you expose a service?
	A: Create a Service or Ingress depending on the need.
