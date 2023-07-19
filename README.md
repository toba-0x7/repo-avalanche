# Continuous Deployment & Integration using Github, Jenkins, Sonarqube, Docker, Kubernetes. (In Progress)

## Prerequisites:
- Ubuntu 22 VM
- Kubectl
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

## Database
MSQL DB Installation Steps for Linux ubuntu:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Locate the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file hence import to mysql db server
```
mysql -u <user_name> -p accounts < accountsdb.sql
```
## Objectives
- Install Ubuntu 22 VM
- Setup Jenkins, Sonarqube, Docker, Minikube, Helm
- Configure Dockerfile, pom.xml, Helm charts, kubernetes yaml files and Jenkins file
- Test pipeline
- Confirm deployment
- Clean up

## Install Ubuntu 22 VM
https://github.com/toba-0x7/notebook/blob/main/os-linux/setup.md
## Jenkins Setup
https://github.com/toba-0x7/notebook/blob/main/ci-cd-jenkins/jenkins-setup.md
## Sonarqube Setup
https://docs.sonarsource.com/sonarqube/latest/setup-and-upgrade/install-the-server/#:~:text=search_path%20to%20mySonarQubeSchema-,Installing%20SonarQube%20from%20the%20ZIP%20file,account%20for%20SonarQube%20if%20necessary.
## Docker
https://github.com/toba-0x7/notebook/blob/main/containerization-docker/setup.md
## Minikube
https://github.com/toba-0x7/notebook/blob/main/container-orchestration-k8s/minikube.md
## Helm
https://community.chocolatey.org/packages/kubernetes-helm
```
choco install kubernetes-helm
```
## Add files
Add Dockerfile, pom.xml, Helm charts, K8s yml files and Jenkins file to working directory
## Pipeline & Deployment
- Run build in Jenkins
- Confirm deployment
```
kubectl get all -n <namespace>
```








