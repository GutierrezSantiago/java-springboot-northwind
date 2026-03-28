# Northwind REST API

A RESTful API built with Java Spring Boot modeling a product distribution system. Covers the full order flow across customers, employees, products, suppliers, and shippers. Designed with clean separation of concerns, DTO-based request/response handling, and custom exception management, with unit tests written in JUnit.

---

## Architecture

Follows a **Layered Architecture** (N-Tier):

```
Controller → Service → Repository → Database
```

- **DTOs** separate API contracts from JPA entities (distinct create/update request objects)
- **Layered services** with interface + implementation split
- **Custom exceptions** for consistent error handling

---

## Tech Stack

- Java + Spring Boot
- Spring Data JPA
- Lombok
- JUnit
