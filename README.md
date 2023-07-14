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
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
```
mysql -u <user_name> -p accounts < accountsdb.sql
```
## Objectives
- Setup Jenkins, Sonarqube, Dockerhub, Minikube, Helm
- Configure Dockerfile, pom.xml, Helm charts, kubernetes yaml files and Jenkins file
- Test pipeline
- Confirm deployment
- Clean up


