# Services

## Overview
Services expose pods in a stable way.

## Types
- ClusterIP
- NodePort
- LoadBalancer

## Interview questions with answers
- Q: Why do we need services?
	A: Pods change IPs; services provide stable access.
- Q: What is the difference between ClusterIP and NodePort?
	A: ClusterIP is internal only; NodePort exposes a port on each node.
