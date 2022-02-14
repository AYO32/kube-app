# kube-app
# kube-app

This project is a step to step procedure of deploying a java app or web app on kubernetes cluster that has been containerized.

### REQUIREMENTS: They requirement could be that you need:
- High availability
- Fault tolerance
- Easily scalable
- Platform independent
- portable and flexible

### TECHNOLOGIES:
- Kubernetes cluster
- Containerized java application services
- Kops

### STEPS:
- Kubernetes cluster
- Containerized apps
- Create EBS volume for DB pod
- LABEL node with zone names
- Kubernetes definition files for : Deployment, service, secret and volume.

First of all you have to setup kubernetes cluster using kops and other prerequisites like s3 bucket, IAM user for AWS CLI, Route 53 hosted zone
