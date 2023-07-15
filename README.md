## Continuous Deployment & Integration using Github, Jenkins, Sonarqube, Docker, Kubernetes. (In Progress)

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
- Setup Jenkins, Sonarqube, Dockerhub, Minikube, Helm
- Configure Dockerfile, pom.xml, Helm charts, kubernetes yaml files and Jenkins file
- Test pipeline
- Confirm deployment
- Clean up

## Install Ubuntu 22 VM
https://github.com/toba-0x7/notebook/blob/main/os-linux/setup.md
## Jenkins Setup






