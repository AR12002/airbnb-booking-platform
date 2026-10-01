# Airbnb Booking Platform

A Spring Boot backend for an Airbnb-style hotel booking platform.

## Tech Stack

- Java
- Spring Boot
- Spring Security
- JWT Authentication
- Spring Data JPA / Hibernate
- PostgreSQL
- Stripe
- Maven
- Lombok
- ModelMapper
- OpenAPI / Swagger

## Features

- User registration and login
- JWT-based authentication
- Role-based authorization
- Hotel management
- Room management
- Hotel search and browsing
- Room inventory management
- Hotel booking
- Booking management
- Dynamic pricing strategies
- Stripe payment integration
- Webhook handling
- Global exception handling
- REST APIs

## Running Locally

1. Install Java and PostgreSQL.
2. Create a PostgreSQL database named `airBnb`.
3. Configure the database and optional Stripe credentials using environment variables.
4. Run the application with:

```bash
./mvnw spring-boot:run
```

On Windows:

```bash
mvnw.cmd spring-boot:run
```

## Environment Variables

See `.env.example` for the variables used by the application.

Never commit real passwords, JWT secrets, Stripe keys, or webhook secrets to GitHub.

## API Base URL

```text
http://localhost:8080/api/v1
```

## Project Structure

```text
src/main/java/.../airBnbApp/
├── advice
├── config
├── controller
├── dto
├── entity
├── exception
├── repository
├── security
├── service
├── strategy
└── util
```
