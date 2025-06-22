# DESCRIPTION
We deployed a custom Apache web application in Kubernetes using the image patthechosen/my-apache-container:v1 through a Deployment resource with five replicas. To make the service accessible externally, we created a Kubernetes LoadBalancer Service on port 80. This setup ensures high availability and enables web access to all Apache pods running inside the EKS cluster.


