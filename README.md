# BankMicroserviceApp
Overview
This repository contains a Spring Boot microservices application designed to showcase various microservices in action, with each service serving a specific purpose:

Account Service: This microservice manages user accounts, including user registration, login, and account information retrieval.

API Gateway: The API Gateway acts as the entry point for external clients to interact with the microservices. It handles request routing, load balancing, and authentication.

Config Server: The Config Server stores and distributes configuration properties to all other microservices, allowing for centralized configuration management.

Customer Service: This microservice is responsible for managing customer information, including creating, updating, and retrieving customer details.

Service Registry: The Service Registry is used for service discovery and registration, enabling microservices to locate and communicate with each other dynamically.

Prerequisites
Before you begin, ensure you have met the following requirements:

Java Development Kit (JDK) installed (Java version 17 or higher).
Maven installed.
Git installed.
Getting Started
To get started with this project, follow these steps:

Clone the repository to your local machine:

shell
Copy code
git clone https://github.com/your-username/your-repo.git
Change into the project directory:

shell
Copy code
cd your-repo
Build the project using Maven:

shell
Copy code
mvn clean install
Running the Microservices
To run the microservices, follow these steps:

Start the Config Server:

shell
Copy code
cd config-server
mvn spring-boot:run
Start the Service Registry:

shell
Copy code
cd service-registry
mvn spring-boot:run
Start the Account Service, API Gateway, and Customer Service in separate terminal windows using the same command structure:

shell
Copy code
cd account-service
mvn spring-boot:run
shell
Copy code
cd api-gateway
mvn spring-boot:run
shell
Copy code
cd customer-service
mvn spring-boot:run
