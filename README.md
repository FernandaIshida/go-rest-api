# Go REST API - Product Management

![Go](https://img.shields.io/badge/Go-1.22-blue)
![REST API](https://img.shields.io/badge/REST-API-green)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue)
![Docker](https://img.shields.io/badge/Docker-Containerized-blue)
![GORM](https://img.shields.io/badge/GORM-ORM-orange)
![Middleware](https://img.shields.io/badge/Middleware-Implemented-purple)
![React](https://img.shields.io/badge/Frontend-React-blue)
![Status](https://img.shields.io/badge/status-in%20progress-yellow)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

---

### About

This project is a REST API built with Go for learning backend fundamentals such as routing, JSON handling, database integration, and middleware concepts.

The goal is to build a clean and scalable backend service from scratch, focusing on understanding how HTTP servers work and how APIs are structured in real-world systems.

---

### Features (in progress)

* HTTP server in Go
* JSON request and response handling
* RESTful routing
* Product CRUD (Create, Read, Update, Delete)
* Resource-based endpoints
* Database integration (planned)
* Middleware implementation (planned)

---

### Learning Goals

This project is being developed as part of a backend learning journey focused on:

* Understanding how web servers work in Go
* Building RESTful APIs from scratch
* Working with JSON in HTTP communication
* Structuring backend applications properly
* Introducing database persistence concepts
* Learning middleware patterns for request lifecycle control

---

### API Design (initial idea)

GET    /products
GET    /products/{id}
POST   /products
PUT    /products/{id}
DELETE /products/{id}

---

### Tech Stack (in progress)

Go (Golang)
net/http
JSON encoding/decoding
PostgreSQL (planned)
GORM (planned)
Docker (planned)
Middleware (planned)

---

## Running the project

```bash
git clone <repository-url>
cd project-name
go run main.go
```

## License

This project is licensed under the MIT License.

## Dev Journey

This project is part of a [Dev Journey](https://github.com/FernandaIshida/dev-journey/blob/main/README.md) focused on exploring backend development across multiple technologies and architectural approaches:

* Go (standard library) – understanding HTTP servers, routing, and core backend concepts
* Go (REST APIs evolution) – building structured APIs and learning backend best practices
* PostgreSQL – relational data modeling and persistence (planned)
* GORM – ORM-based database interaction (planned)
* Docker – containerization and environment consistency (planned)
* Middleware patterns – request lifecycle and cross-cutting concerns (planned)

This project represents an early-stage backend system, focused on clarity, fundamentals, and progressive learning toward production-grade API design.
