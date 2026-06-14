# Jean Station – Scalable E-Commerce Backend Application

## Overview

Jean Station is a scalable E-Commerce backend application developed using Java, Spring Boot, and MySQL. The application follows Microservices architecture principles and provides secure REST APIs for managing products, users, carts, and orders.

This project was designed to simulate real-world enterprise backend systems with modular architecture, clean coding practices, and optimized API performance.

---

## Features

* User Registration & Login
* Product Catalog Management
* Shopping Cart Functionality
* Order Management
* RESTful API Development
* Database Integration with MySQL
* Exception Handling & Validation
* Docker-Based Deployment

---
## Project Structure

```bash
src/main/java
├── controller
├── service
├── repository
├── entity
├── dto
├── exception
└── config
```

## Architecture Flow

Client Request → REST API → Controller Layer → Service Layer → Repository Layer → MySQL Database

## Technologies Used

* Java 17
* Spring Boot
* Microservices
* Hibernate & JPA
* MySQL
* REST APIs
* Docker
* Maven
* Git
* Postman

---

## Responsibilities

* Developed scalable REST APIs using Spring Boot
* Designed backend architecture using Microservices concepts
* Implemented database operations using Hibernate/JPA
* Optimized SQL queries and backend performance
* Integrated MySQL database for order and product management
* Worked on exception handling and API validation
* Performed API testing using Postman

---

## Future Enhancements

* JWT Authentication
* Kafka Integration
* AWS Deployment
* API Gateway
* Kubernetes Support

---

## Sample API Endpoints

| Method | Endpoint           | Description        |
| ------ | ------------------ | ------------------ |
| GET    | /api/products      | Get all products   |
| GET    | /api/products/{id} | Get product by ID  |
| POST   | /api/products      | Create new product |
| PUT    | /api/products/{id} | Update product     |
| DELETE | /api/products/{id} | Delete product     |
| POST   | /api/orders        | Create order       |
| GET    | /api/orders        | Fetch orders       |



## Author

Shirisha Eslavath
Java Backend Developer
