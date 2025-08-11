# Kubernetes Local Cluster with Minikube on EC2

Set up a local Kubernetes cluster using Minikube on an Ubuntu EC2 instance and deploy a sample NGINX application. The service is exposed via port-forwarding for external access.

## Tools Used
- Minikube
- kubectl
- Docker (Minikube built-in)
- NGINX Docker image

## Steps Performed

1. **Installed Minikube and kubectl** on Ubuntu 24.04 EC2 instance.
2. **Started Minikube** using Docker as the driver:
   minikube start --driver=docker
3. Created a Kubernetes Deployment using NGINX
4. Exposed the deployment as a service
5. Tested application access.
