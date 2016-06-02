# Microservice application with continuous integration

**What is this repository?**
This is an open source project to build a continuous integration pipeline for building, testing and deploying a microservices application in a continuous integration environment.

**Notes**
This section describes some design principles and decisions.
 - Less is more
    _"This is actually easy as it has just started ;)"_
 - **Docker** it is used to package the application artifacts and its dependencies.
 - This project assumes you are defining your **infrastructure as code** using docker-compose. 
 - By now we assume you use **jhipster** to generate microservices application.
    _"The jhipster microservice application has to be packaged as docker containers and use docker-compose for CI environment deployment."_
 - It uses **Gitlab** as code repository, CI and docker registry.

**Notes for the future**
 - Mode code repositories will be added in future releases.
 - It has to be microservice application technology stack agnostic. 
    _"As far the technology stack supports using docker to package the application and it is generated using yeoman scaffolding, so you can have a working microservices application with a CI pipeline in minutes."_

**Quick Start**
TBD