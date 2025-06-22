# DESCRIPTION
This repository contents scripts that allow to  deploy a custom Apache application using a Docker image (patthechosen/my-apache-container:v1) and scaled it with a Kubernetes Deployment running 5 replicas inside an Amazon EKS cluster. After verifying pod health and service functionality from within the cluster, we exposed the application to the internet via a LoadBalancer Service on port 80. This setup was provisioned and managed through kubectl on an EC2 instance connected to the EKS control plane.

