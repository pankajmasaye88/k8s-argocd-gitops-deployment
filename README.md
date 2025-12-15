K8s Kind Voting App (Python, Redis, .NET, Postgres,Node.js)  

A front-end web app in Python which lets you vote between two options  
A Redis which collects new votes  
A .NET worker which consumes votes and stores them in…  
A Postgres database backed by a Docker volume  
A Node.js web app which shows the results of the voting in real time  

Deployment Overview :  
Launch an EC2 instance  
Install docker and Kind  
Create a Kubernetes cluster with 1 control plane and 2 worker nodes using Kind.  
Install kubectl and check nodes.  
Install and configure Argo CD.  
Create new app in Argo CD. Attach Github repo. (https://github.com/LondheShubham153/k8s-kind-voting-app).  
Using k8s specifications files clusted will be setup for app.  
Set up the Kubernetes dashboard.  
Modify EC2 instance security groups port for network connection.  
  
