<h1 align="center"> Eureka service </h1> <br>

<p align="center">
  Eureka Server is an application that holds the information about all client-service applications. Every Micro service will register into the
  Eureka server and Eureka server knows all the client applications running on each port and IP address. Eureka Server is also known as Discovery
  Server
</p>


## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Quick Start](#quick-start)
- [Acknowledgements](#acknowledgements)




## Introduction

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/e91606af4a364076a7058c5ea1c006a8)](https://www.codacy.com/app/joneubank/microservice-template-java?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=overture-stack/microservice-template-java&amp;utm_campaign=Badge_Grade)
[![CircleCI](https://circleci.com/gh/overture-stack/microservice-template-java/tree/master.svg?style=shield)](https://circleci.com/gh/overture-stack/microservice-template-java/tree/master)

## Features
This service based on Spring Boot 2.7.4 and java 17. 
Use eureka server.


## Requirements
The application can be run locally or in a docker container, the requirements for each setup are listed below.


### Local
* [Java 8 SDK](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
* [Maven](https://maven.apache.org/download.cgi)

### Docker
* [Docker](https://www.docker.com/get-docker)


## Quick Start

### Run Local
```bash
$ mvn spring-boot:run
```

Application will run by default on port `9084`
Configure the port by changing `server.port` in __application.properties__


### Run Docker

First build the image:
```bash
$ docker-compose build
```

When ready, run it:
```bash
$ docker-compose up
```

## Acknowledgements
Acknowledgements for Yevhenii Khudolii for interesting trainig project and support =)
