# Cloud DevOps Application Deployment Platform
## Prerequisites
* Docker installed on the system
* Kubernetes cluster set up
## Setup Steps
1. Clone the repository
2. Build the Docker image using `docker build -t cloud-devops .`
3. Deploy the application to the Kubernetes cluster using `kubectl apply -f deployment.yaml`
## Configuration
* Update the `config.json` file with the database and server settings
* Use Ansible to automate the deployment process