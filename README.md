## Continuous Deployment & Integration using Github, Jenkins, Sonarqube, Docker, Kubernetes. (In Progress)

## Prerequisites:
- Chocolatey
- Vagrant
- Virtualbox
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
- Install Chocolatey, Vagrant, Virtualbox
- Setup Jenkins, Sonarqube, Dockerhub, Minikube, Helm
- Configure Dockerfile, pom.xml, Helm charts, kubernetes yaml files and Jenkins file
- Test pipeline
- Confirm deployment
- Clean up

## Install Chocolatey
https://chocolatey.org/install
## Install Vagrant
https://community.chocolatey.org/packages/vagrant
To install Vagrant (Install), run the following command from the command line or from PowerShell:
```choco install vagrant```
## Install Virtualbox
https://community.chocolatey.org/packages/virtualbox
To install Virtualbox (Install), run the following command from the command line or from PowerShell:
```choco install virtualbox```
## Jenkins Setup
Jenkins is set up on an ubuntu 22 VM through vagrant
https://app.vagrantup.com/bento/boxes/ubuntu-22.04
Choose a suitable working directory and run the following:
```vagrant init bento/ubuntu-22.04```
Do neccessary configurations to the vagrantfile and then run
```vagrant up```





