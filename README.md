### hello-world-k8s

This is a small application created to demonstrate the Terraform provisioned Kuberenetes cluster on AWS.

You could use this repo to build and deploy this pipe line in Gitlabs.

## Environment Variables

Please add the below environment variables in GitLab project

DOCKER_USER - Docker user ID
DOCKER_PASSWORD - docker login password

Kubernetes specific details:

SERVER - server API details of Kubernetes cluster

CERTIFICATE_AUTHORITY_DATA - You could get it from the Kubernetes cluster

TOKEN - Token for the gitlab user

