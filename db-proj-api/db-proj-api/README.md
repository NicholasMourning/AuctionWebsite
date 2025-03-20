<h1>Database-Centric REST API Setup Guide</h1>
This repository provides examples for the initial setup of a database-centric REST API required for your course project. The examples are fully automated for easy deployment in third-party environments using either Docker or Maven (depending on your chosen project).

Note: This guide does not replace the official assignment description. Please review the assignment for complete details.

Overview of the Contents
PostgreSQL:
A ready-to-run PostgreSQL database in a Docker container (with or without Docker Compose).

The app/ directory is mounted for live development.
Java:
A Java/Spark web application template with Docker container configuration. It can be run using Docker Compose with PostgreSQL or in your favorite IDE.

Postman:
A collection of Postman requests exported to help test the API.

Requirements
Before running the project, ensure that you have the following installed:

Docker
Docker Compose
Maven (required only for the Java option)
Demo: Python REST API
To start the Python demo, run the following script:

sh docker-compose-python-psql.sh

This script uses Docker Compose and the configuration defined in docker-compose-python-psql.yml to launch both the server and the PostgreSQL database. The app directory is mounted into the container, so any changes you make are reflected immediately without the need to rebuild or restart.

Access the API: http://localhost:8080
Demo: Java REST API
To run the Java demo, execute the following script:

sh docker-compose-java-psql.sh

This demo uses Spring Boot, a widely adopted framework for building REST APIs and microservices. Spring Boot makes it simple to create stand-alone, production-grade applications that “just run.” Deployment is easily automated with Maven or Docker.

Access the API: http://localhost:8080
