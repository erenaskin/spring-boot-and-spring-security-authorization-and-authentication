# Spring Boot & Spring Security JWT Authentication and Authorization

This project demonstrates how to build a secure authentication and authorization system using **Spring Boot**, **Spring Security**, and **JWT (JSON Web Tokens)**.  
It covers token-based login, protected endpoints, role-based access control, and best practices for secure API design.

## 🔐 Features

- User authentication with **JWT**
- Spring Security configuration
- Role-based access control (e.g. USER / ADMIN)
- Token generation and validation
- Refresh tokens (optional)
- Secure password hashing with BCrypt
- Exception handling for unauthorized access
- Stateless session management

## 🛠️ Tech Stack

- Java 17+ / Java 21+
- Spring Boot
- Spring Security
- JWT (JJWT or Java JWT library)
- Maven / Gradle
- PostgreSQL / H2 (your choice)
- Lombok

## 📁 Project Structure

```text
src/
├── config/                 # Spring Security configuration
├── controller/             # Auth and protected endpoints
├── dto/                    # Login and register request/response DTOs
├── entity/                 # JPA entities (User, Role)
├── repository/             # Spring Data JPA interfaces
├── service/                # Business logic (auth, token generation)
├── util/                   # JWT utilities
