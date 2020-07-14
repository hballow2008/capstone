# Project 5 - Cloud DevOps Engineer Capstone Project

>  I applied all skills and knowledge which was developed throughout the Cloud DevOps Nanodegree program.

## Project Tasks:

* Working in AWS
* Using Jenkins to implement CI/CD
* Building pipelines
* Working with CloudFormation to deploy clusters
* Building Kubernetes clusters
* Building Docker containers in pipelines

## About Project: 

> I created a CI/CD pipeline for a basic website that deploys to a cluster in AWS EKS which is Blue/Green Deployment.

## Project Requirement:

> To be able to use this CI/CD pipeline you will need to install:

* Jenkins
* Blue Ocean Plugin in Jenkins
* Pipeline-AWS Plugin in Jenkins
* Docker
* Pip
* AWS Cli
* Eksctl
* Kubectl

## The files included are:

* Create-clusters-pipeline : CloudFormation Script of Cluster Pipeline
* Deploy-containers-pipeline : Deployment Script of Containers Pipeline
* Jenkinsfile : for Creating Pipeline
* Dockerfile : for building image 
* green-controller.json : Create a replication controller of green pod
* green-service.json : Create a green service
* blue-controller.json : Create a replication controller of blue pod
* blue-service.json : Create a blue service
* index.html : Web file.