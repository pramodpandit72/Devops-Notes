# Services

## Overview
routes traffic inside cluster

provides load balancing and service discovery within or outside the cluster.

## Types
- ClusterIP - Used for communication inside the cluster
- NodePort
- LoadBalancer - Creates an external load balancer (cloud providers), Used for public access

## Interview questions with answers
- Q: Why do we need services?
	A: Pods change IPs; services provide stable access.
- Q: What is the difference between ClusterIP and NodePort?
	A: ClusterIP is internal only; NodePort exposes a port on each node.
