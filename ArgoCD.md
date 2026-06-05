# kubectl config get-contexts

# kubectl config use-context docker-desktop

# kubectl get nodes

# declarative insfracture

# GitOps

# Push vs Pull Deployment

## commands - 
1. tree -F
   
2.   D:\Devops\Devops-Notes\gitops-capstone> @"
>> apiVersion: v1
>> kind: Service
>> metadata:
>>   name: nginx-service
>> spec:
>>   selector:
>>     app: nginx-app
>>   ports:
>>   - port: 80
>>     targetPort: 80
>>   type: ClusterIP
>> "@ | Set-Content apps/base/service.yaml

3.  Get-Content apps\base\deployment.yaml
4.  kind create cluster --name gitops
5.  

no one can directly change or touch our cluster directly -> using gitops

# Get-ComputerInfo -Property HyperVisorPresent, HyperVRequirementVirtualizationFirmwareEnabled

# Git is the single source of truth for what our insfrastructure should look like

# YAML file in git reop is the bluprint and kubernetes cluster is house and argocd read the bluprint and make it

Artitect -> YAML file

# Three pilars of GitOps - 
1. Declaritive Configuration - we describe the end state like no. of replicas
2. Git as an Audit trail - All configs are stored in Git.
3. Automated Sync (Continuous Reconciliation) - Self healing property(with the help of argocd)

# Pull Based - argocd runs inside kubernetes and pulls from git 
-> argocd inside cluster pulls and applies changes from git repo, cluster credientials never leaves the cluster

# Push Based - use ci/cd secrets, needs cluster credentials, it is traditional CI/CD pipeline this is external as we uses third party like github-action or jenkins for that we need cluster credintials(kubernetes credentials are stored outside the cluster) 