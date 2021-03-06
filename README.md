
[![bkocis](https://circleci.com/gh/bkocis/CloudDevOps-ND-Microservices-AWS.svg?style=svg)](https://app.circleci.com/pipelines/github/bkocis/CloudDevOps-ND-Microservices-AWS)

# Description

This porject contain files for deploying a machine leaning app on AWS using docker. The project is focused in the steps of building and linting the infrastructure of the app. 

# Steps

Initialize a cloud9 environment with an Ubuntu 18.04 AMI

Modify the EC2 instance volume (at least 25GB)

Make a python env.



## github repo of the project
https://github.com/udacity/DevOps_Microservices

## install hadolint
https://github.com/hadolint/hadolint/

Install "haskel" first then "stack".

#### Haskel: 
`sudo apt-get install haskell-platform`

#### stack:
`curl -sSL https://get.haskellstack.org/ | sh`

#### hadolint
`git clone https://github.com/hadolint/hadolint
cd hadolint
stack install`

#### CircleCI

`sudo curl -fLSs https://raw.githubusercontent.com/CircleCI-Public/circleci-cli/master/install.sh | sudo bash`


#### kubernetes


#### minikube onm linux machine

https://computingforgeeks.com/how-to-install-minikube-on-ubuntu-debian-linux/

`wget https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64`
`chmod +x minikube-linux-amd64`
`sudo mv minikube-linux-amd64 /usr/local/bin/minikube`