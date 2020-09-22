
# Operationalize Machine Learning Microservice API.

[![<ORG_NAME>](https://circleci.com/gh/maxgherman/udacity-microservices.svg?style=svg)](https://circleci.com/gh/maxgherman/udacity-microservices)

Deploying an elastic and fault-tolerant Machine Learning inference API using Kubernetes. Configure this
microservice to be highly available by using Kubernetes best practices. Validate the design by load testing the service and verifying the application architecture performs as designed.

### Project Tasks

Project goal is to operationalize working machine learning microservice using [kubernetes](https://kubernetes.io/), which is an open-source system for automating the management of containerized applications.

### Project Steps

* Test the project code using linting
* Complete a Dockerfile to containerize the application
* Deploy  containerized application using Docker and make a prediction
* Improve the log statements in the source code for this application
* Configure Kubernetes and create a Kubernetes cluster (minikube)
* Deploy a container using Kubernetes and make a prediction
* Upload a complete Github repo with CircleCI to indicate that the code has been tested

---

## Setup the Environment

* Create a virtualenv and activate it

```sh
python3 -m venv ~/.devops
source ~/.devops/bin/activate
```

* Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`
4. Make predictions: `./make_prediction.sh`

### Docker

1. Publish docker image: `./upload_docker.sh`

### Kubernetes Steps

* Setup and Configure Docker locally
* Setup and Configure Kubernetes locally
* Create Flask app in Container
* Run via kubectl
