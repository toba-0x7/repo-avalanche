## Continuous Deployment & Integration using Github, Jenkins, Sonarqube, Docker, Kubernetes. (In Progress)

## Prerequisites:
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

## Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL

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
- Setup Jenkins, Sonarqube, Dockerhub, Minikube, Helm
- Configure Dockerfile, pom.xml, Helm charts, kubernetes yaml files and Jenkins file
- Test pipeline
- Confirm deployment
- Clean up


