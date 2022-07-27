### Circle CI Status
[![CircleCI](https://dl.circleci.com/status-badge/img/gh/tech-lady/udaservice/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/tech-lady/udaservice/tree/main)

### Project Summary

 This project deploys a containerized machine learning microservice using Docker with kubernetes.
 It has a funtionality for offering predictions about housing prices through API calls.

### Project Completed Tasks

###### The following tasks were completed in this project:

* Testing project code with linting
* A complete Dockerfile to containerize this application
* Containerized application deployed using Docker and with prediction values in output text files
* Improved the log statements in the source code for this application
* Configured Kubernetes and created a Kubernetes cluster
* Deployed a container using Kubernetes and make a prediction
* Uploaded a complete Github repo with CircleCI status badge

You can find a detailed [project rubric, here](https://review.udacity.com/#!/rubrics/2576/view).

**The final implementation of the project will showcase your abilities to operationalize production microservices.**

---

## Setup the Environment

* Create a virtualenv with Python 3.7 and activate it. Refer to this link for help on specifying the Python version in the virtualenv. 
```bash
python3 -m pip install --user virtualenv
# You should have Python 3.7 available in your host. 
# Check the Python path using `which python3`
# Use a command similar to this one:
python3 -m virtualenv --python=<path-to-Python3.7> .devops
source .devops/bin/activate
```
* Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Upload docker image: `./upload_docker.sh`
4. Run in Kubernetes:  `./run_kubernetes.sh`
5. Make a prediction: `./make_prediction.sh`

### Kubernetes Steps

* Setup and Configure Docker locally
* Setup and Configure Kubernetes locally
* Create Flask app in Container
* Run via kubectl
