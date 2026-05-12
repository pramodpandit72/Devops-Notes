## A Namespace is a logical partition inside a Kubernetes cluster used to organize, isolate, and manage resources.

Namespaces exist to organize, isolate, and control resources inside one shared Kubernetes cluster

Kubernetes already gives some: -
default -> where your apps go (by default)
kube-system	-> system components
kube-public	-> public resources
kube-node-lease	-> node heartbeat

# Why we use Namespaces -
* Avoid naming conflicts
  eg - dev/api-service, prod/api-service
* Separate environments
  eg - namespace: dev
       namespace: staging
       namespace: prod 

* Access control - 
You can control:
Who can deploy
Who can view logs
Who can delete resources