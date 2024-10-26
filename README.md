# CrimsonSky - Config Server Microservice

---

## Live Link / Demo Link: 🔗
Access the flight service at **[localhost:8888](http://localhost:8888)**

## Table of Contents: 📑

- [About The Service](#about-the-service-)
- [Technologies](#technologies-%EF%B8%8F)
- [Setup](#setup-)
- [Approach](#approach-)
- [Status](#status-)
- [License](#license-%EF%B8%8F)

## About the Service: 📚
The **Config Server** is a core part of the CrimsonSky flight booking system. It stores and handles the configurations for all the microservices. The service is built with **Spring Cloud** and uses **Spring Cloud Config Server** to store and share the configuration will all the microservices.

## Technologies: ☕️

- Java
- Spring Boot
- Spring Cloud
- Spring Cloud Config Server

## Setup: 💻

- **Install Java 21 :**
    - Download and install **[Java 21](https://www.oracle.com/in/java/technologies/downloads/#java21)**
    - Set up the **JAVA_HOME** environment variable.


- **Install Maven:**
    - Download and install **[Maven](https://maven.apache.org/download.cgi)**
    - Add the **bin** directory to the **PATH** environment variable.

**Available Scripts:**

In the project directory, you can run:

- #### `mvn install`
  Installs all necessary dependencies.

- #### `mvn spring-boot:run`
  Runs the flight service.\
  Open [http://localhost:8888](http://localhost:8888) to access it.

# Approach: 🚶
This service is part of the **CrimsonSky** microservices ecosystem, focusing on managing and providing configurations with **Spring Cloud Config Server** for centralized configuration management.

# Status: 📶
Service under development 🛠️

# License: ©️
MIT License (**[Check Here](LICENSE)**)