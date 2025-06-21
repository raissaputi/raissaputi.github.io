---
title: "Heymart"
excerpt: "Heymart is a modular e-commerce system with microservice architecture, built using Java Spring Boot"
collection: portfolio
---

Heymart is a scalable, modular e-commerce platform developed as the final project for the Advanced Programming course. The application simulates real-world supermarket operations with multiple domains, each managed by a dedicated microservice.

The backend system is split into three core services:
- **Authentication Service** for user login, registration, and secure access control
- **Store Service** for managing products and shopping cart operations
- **Order Service** for handling transactions, coupons, and balance management

Each service follows clean architecture and applies various design principles and patterns to ensure maintainability and robustness.

### Key Highlights:
- **Design Patterns**:
  - *Builder Pattern* (used in authentication)
  - *Factory Pattern* (used in coupon management)
  - *Strategy Pattern* (applied in balance management logic)

- **SOLID Principles**: The system is structured around Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, and Dependency Inversion principles.

- **Testing & Quality**:
  - 211 unit tests with full TDD workflow
  - Static code analysis via SonarCloud
  - Secure coding practices including validation and authorization layers

- **Architecture**:
  - RESTful API with DTO layers
  - Asynchronous AJAX operations for data fetching and updates
  - High-level networking abstraction and CI/CD pipelines for all services

- **Deployment**:
  - Deployed via *Big Bang Deployment* strategy
  - Each service is containerized and deployed to Google Cloud Platform
  - Monitoring is integrated to track service health and performance

The project demonstrates how enterprise-level practices can be applied to a student project using Java Spring Boot and modern CI/CD workflows.

**GitHub Repositories**:
- [Authentication Service](https://github.com/AdPro-B14/heymart-auth)
- [Store Service](https://github.com/AdPro-B14/heymart-store)
- [Order Service](https://github.com/AdPro-B14/heymart-order)

More about this project:  
[Read the report](https://drive.google.com/file/d/1QiRNE01jfqMKPlMvdTAFLobxFM78ZD3t/view?usp=sharing)
