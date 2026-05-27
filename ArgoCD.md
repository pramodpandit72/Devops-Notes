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