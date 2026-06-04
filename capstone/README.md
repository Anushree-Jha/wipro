# PlayStore Management System - Microservices Project

## Project Overview

PlayStore Management System is a Spring Boot Microservices-based application that allows users to explore, download, and review applications while enabling owners to publish and manage their apps.

The project demonstrates the implementation of Microservices Architecture using Spring Boot, Eureka Server, API Gateway, Spring Security, JWT Authentication, and REST API communication.

---

## Features

### User Module

* User Registration
* User Login
* JWT Authentication
* View Applications
* Download Applications
* Submit Reviews
* View Notifications
* Manage Profile

### Owner Module

* Owner Registration
* Owner Login
* Add New Applications
* View Download Statistics
* Manage Application Visibility
* Delete Applications

### Application Module

* Add Applications
* Search Applications
* Filter by Genre
* Filter by Rating
* Track Downloads

### Review Module

* Add Reviews
* View Reviews
* Rating System

### Notification Module

* Generate Notifications
* View Notifications

---

## Microservices Used

1. User Service
2. Owner Service
3. App Service
4. Review Service
5. Notification Service
6. Eureka Server
7. API Gateway

---

## Technologies Used

* Java
* Spring Boot
* Spring Security
* JWT Authentication
* Spring Data JPA
* Hibernate
* Eureka Server
* API Gateway
* REST APIs
* H2 Database
* HTML
* CSS
* JavaScript

---

## Architecture

Frontend (HTML/CSS/JavaScript)

↓

API Gateway

↓

Microservices

* User Service
* Owner Service
* App Service
* Review Service
* Notification Service

↓

Individual Databases

---

## Microservice Communication

Services communicate through REST APIs using:

* RestTemplate
* RestClient

Example:

* App Service → Notification Service
* Review Service → Notification Service

---

## Security

* Spring Security
* JWT Token Generation
* JWT Validation
* Protected APIs
* Authentication and Authorization

---

## Exception Handling

Global Exception Handling is implemented using:

* @RestControllerAdvice
* @ExceptionHandler

Custom Exceptions:

* UserNotFoundException
* AppNotFoundException

---

#Key Concepts Demonstrated

* Microservices Architecture
* Service Discovery
* API Gateway Routing
* JWT Authentication
* Spring Security
* REST API Development
* CRUD Operations
* Exception Handling
* Frontend-Backend Integration

---

 Developed As

Capstone Project for learning Spring Boot Microservices and Full Stack Development.

Thank you to Wipro and Great Learning the mentors for providing guidance, support, and valuable learning throughout the program.
