# Spring Boot Microservices Project

This repository contains a sample Spring Boot microservices project consisting of three microservices: User Microservices, Hotel Microservices, and Rating Microservices. The project is designed to demonstrate the development of microservices using Spring Boot and Docker for containerization.

## Table of Contents

- [Project Overview](#project-overview)
- [Microservices](#microservices)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Running the Microservices](#running-the-microservices)
- [Dockerization](#dockerization)
  - [Building Docker Images](#building-docker-images)
  - [Running Docker Containers](#running-docker-containers)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project is a simple example of a microservices-based architecture. Each microservice focuses on a specific domain:

- **User Microservices**: Manages user information.
- **Hotel Microservices**: Handles hotel-related data.
- **Rating Microservices**: Manages hotel ratings and reviews.

These microservices communicate with each other over RESTful APIs to provide a comprehensive hotel booking and rating system.

## Microservices

Each microservice is organized within its own directory with its source code, configuration files, and documentation. The main directories are:

- `user-microservice/`: User Microservices.
- `hotel-microservice/`: Hotel Microservices.
- `rating-microservice/`: Rating Microservices.

Inside each microservice directory, you will find more specific details about that particular service.

## Getting Started

### Prerequisites

Before you can run the microservices, ensure you have the following prerequisites installed:

- [Java Development Kit (JDK)](https://adoptium.net/) 11 or later.
- [Maven](https://maven.apache.org/) for building the Spring Boot projects.
- [Docker](https://www.docker.com/) for containerization.

### Running the Microservices

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/spring-boot-microservices.git
