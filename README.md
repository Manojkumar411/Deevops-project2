
OBJECTIVE:-

The primary objective of this project is to establish a robust CI/CD pipeline that
automates the process of building, testing, and deploying applications by integrating Git,
Jenkins, Maven, SonarQube, Docker Hub, ArgoCD and Kubernetes (EKS) , the project aims
to achieve the following goals:
1. Continuous Integration (CI):
Automate the process of code integration, ensuring that new code changes are
seamlessly merged with the existing codebase.
Perform automated code quality checks and static analysis using SonarQube.
2. Continuous Deployment (CD):
Automate the deployment of applications to a Kubernetes cluster.
Utilize Docker for creating and managing containerized applications, facilitating
consistent deployment environments across different stages (development, testing,
and production).
Implement a streamlined workflow for updating deployment configurations and
pushing them to a Git repository for version control.

SUMMARY:
This end-to-end Jenkins pipeline will automate the entire CI/CD process for a Java
application, from code checkout to production deployment, using popular devops tools like
Git, Jenkins, Maven, SonarQube, Docker Hub, ArgoCD and Kubernetes
This project covers setting up a CI/CD pipeline using.
Installing and configuring Jenkins on a Linux server.
 Setting up Docker, configuring Jenkins to use Docker, and handling permissions.
Configuring AWS CLI, installing kubectl and eksctl.
 Creating an EKS cluster with eksctl.
 Installing necessary Jenkins plugins and setting up credentials.
 Creating a Jenkins pipeline to:
 Checkout code from GitHub.
 Perform a SonarQube scan.
 Build the project using Maven.
 Build Docker Image using Docker file and push Docker images to Docker Hub.


Update deployment configurations and push them to a Git repository.
Deploy the application to Kubernetes using ArgoCD.
Pre-requisites
1. Java application code hosted on a Git repository

2. Server Requirements:
 A Linux server for Jenkins , Docker, Sonarqube setup with an instance type
“t2.large” and a EKS Cluster to deploy container application.

3. Software Requirements:
Jenkins
Docker
Maven
SonarQube
Kubernetes CLI (kubectl) , eksctl for managing EKS clusters
EKS Kubernetes cluster
Argo CD
