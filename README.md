# Spring Boot User Management API

A backend REST API built using Spring Boot and PostgreSQL hosted on Aiven.
This project demonstrates authentication, user management, and secure API design using Spring Security

##  Features

- Spring Security Login Authentication  
- Custom Login Success Message  
- REST API Architecture  
- PostgreSQL Database Integration using Aiven Cloud  
- Clean Controller → Service → Repository Structure  
- Maven Build System  

##  Tech Stack

Backend:
- Java 17
- Spring Boot 3
- Spring Security
- Spring Data JPA
- Maven

Database:
- PostgreSQL hosted on Aiven Cloud

Tools:
- Postman for API Testing
- Git & GitHub for Version Control

##  Project Structure

src/main/java/com/Sai/usermanagement

- config → Security Configuration
- controller → REST Controllers
- service → Business Logic
- repository → Database Layer
- dto → Data Transfer Objects
- entity → Database Entities


##  Authentication

Spring Security is configured with login authentication.
On successful login, user receives a success message.

Example Endpoint:

POST /login

##  Database

The project uses PostgreSQL hosted on Aiven Cloud.

Configuration is stored in application.properties using secure credentials.


##  How to Run Project

1. Clone repo
2. Open in IntelliJ or VS Code
3. Configure Aiven PostgreSQL credentials
4. Run:

mvn spring-boot:run

Server runs on:
http://localhost:8080

##  Future Improvements

- User Registration API
- JWT Authentication
- Role Based Authorization
- Docker Deployment
- Unit Testing
- Swagger API Documentation


##  Author

Sai Bachhav  
Spring Boot Learner | Backend Developer in Progress
