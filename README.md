# Monitoring App

Python web app hosted on K8s that tracks hardware resource utilizations

## Getting Started

### Prerequisites

1. AWS account
2. AWS CLI configured
3. Python
4. Docker and Kubectl

### Steps
1. Build the Docker image for our Python app
2. Create an AWS ECR repository
3. Push the image to the repository
4. Create an AWS EKS cluster and a node group
5. Define and deploy the service and deployment

### Notes

* Build the image with Dockerfile
* Create the repository with ecr.py
* Define and deploy the service and deployment with eks.py
