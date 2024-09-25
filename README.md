# Java and Microservices Mentorship Curriculum

## Duration: 3 Months
### Schedule: 3 Days per week, 1 hour per day

---

## Month 1: Core Java Fundamentals & Spring Boot Basics

### Week 1: Core Java Fundamentals
- **Day 1**: Advanced OOP Concepts
  - **Topics**: Advanced OOP – inheritance, polymorphism, encapsulation, and abstraction.
  - **Practice**: Design a small banking system with multiple account types using OOP principles.
- **Day 2**: Collections Framework & Streams
  - **Topics**: Java collections (List, Set, Map) and Streams API.
  - **Practice**: Implement a simple user transaction system using collections and streams.
- **Day 3**: Exception Handling & File I/O
  - **Topics**: Custom exception handling, Java I/O (reading and writing files).
  - **Practice**: Build a transaction logging system that handles and logs exceptions to files.

### Week 2: Multithreading & Concurrency, JDBC
- **Day 4**: Multithreading & Concurrency
  - **Topics**: Threads, Executors, synchronization, CompletableFuture.
  - **Practice**: Simulate concurrent banking transactions and ensure thread-safe operations.
- **Day 5**: JDBC & Database Interaction
  - **Topics**: JDBC, SQL operations (CRUD), database transactions.
  - **Practice**: Implement account balance updates with transaction management.
- **Day 6**: Java 8-17 Features & Review

### Week 3: Spring Boot Introduction & Lombok
- **Day 1**: Overview of Spring Framework and Spring Boot
  - **Topics**: Dependency Injection (DI), Inversion of Control (IoC).
  - **Practice**: Set up a Spring Boot project with basic configuration.
- **Day 2**: Spring Boot project setup and Spring Initializr
  - **Practice**: Create a RESTful API for user registration and account management.
- **Day 3**: Lombok for reducing boilerplate code in Spring Boot
  - **Practice**: Refactor the existing codebase using Lombok annotations (`@Data`, `@Builder`).

### Week 4: Spring Boot Basics & Security Introduction
- **Day 1**: Spring Boot RESTful services – building secure APIs
  - **Practice**: Build an API to retrieve user balances and secure the endpoint using basic authentication.
- **Day 2**: Dependency Injection & Spring Beans lifecycle
  - **Practice**: Explore different scopes (`@Singleton`, `@Prototype`) in a real application.
- **Day 3**: Spring Security Fundamentals
  - **Topics**: Authentication and Authorization in Spring Security.
  - **Practice**: Secure API endpoints for account management with roles and permissions.

---

## Month 2: Microservices Architecture & Advanced Topics

### Week 1: Data Access with Spring Data JPA & Testing
- **Day 1**: Introduction to Spring Data JPA
  - **Practice**: Design entity classes for users, accounts, and transactions.
- **Day 2**: CRUD operations with Spring Data JPA and PostgreSQL
  - **Practice**: Build a service for account and transaction management using PostgreSQL.
- **Day 3**: Testing with H2 Database
  - **Practice**: Write unit and integration tests using H2 to simulate a database.

### Week 2: Microservices Architecture Fundamentals
- **Day 1**: Microservices Principles – Decoupling and Scalability
  - **Practice**: Decompose the banking application into services (e.g., User, Account, Transaction).
- **Day 2**: Communication in Microservices – REST and Messaging
  - **Practice**: Set up inter-service communication between the Account and Transaction services.
- **Day 3**: Designing Microservices with CQRS
  - **Topics**: CQRS (Command Query Responsibility Segregation) for separating read and write operations.
  - **Practice**: Implement CQRS in the transaction service to handle complex queries.

### Week 3: Service Discovery, Config Management, & Security Integration
- **Day 1**: Service Discovery with Netflix Eureka
  - **Practice**: Implement Eureka for dynamic service discovery in the banking system.
- **Day 2**: Spring Cloud Config for Centralized Configuration Management
  - **Practice**: Set up Spring Cloud Config to manage configurations across different environments.
- **Day 3**: Implementing Security with Keycloak
  - **Topics**: OAuth2, OpenID Connect, and Keycloak.
  - **Practice**: Secure microservices with Keycloak and enforce role-based access control (RBAC).

### Week 4: API Gateway & Advanced Microservices Topics
- **Day 1**: API Gateway with Spring Cloud Gateway
  - **Practice**: Create an API Gateway for routing all microservice requests in the banking app.
- **Day 2**: Load balancing with Spring Cloud LoadBalancer
  - **Practice**: Distribute requests among multiple instances of microservices using LoadBalancer.
- **Day 3**: Circuit Breakers and Resilience Patterns with Resilience4J
  - **Practice**: Implement circuit breakers to handle service failures and improve resilience in microservices.

---

## Month 3: Hands-On Real Project – Digital Banking Application

### Week 1: Project Setup & Core Features Development
- **Day 1**: Define project requirements and architecture for the digital banking system
  - **Topics**: Define microservices for Users, Accounts, and Transactions.
- **Day 2**: Set up microservices with Spring Boot, PostgreSQL, and Docker
  - **Practice**: Dockerize individual microservices and run them with Docker Compose.
- **Day 3**: Implement user registration, login, and account creation features
  - **Practice**: Use Spring Data JPA to persist user and account data.

### Week 2: Microservice Communication, Security, and Gateway
- **Day 1**: Build additional microservices for payments and transactions
  - **Practice**: Integrate Feign clients for microservice communication.
- **Day 2**: API Gateway and centralized security with Keycloak
  - **Practice**: Secure the API Gateway using OAuth2 and Keycloak authentication.
- **Day 3**: Service Communication with Feign and Message Queues
  - **Practice**: Implement inter-service communication with Feign clients and message queues for event-driven architecture.

### Week 3: Advanced Features, Testing & CQRS
- **Day 1**: Implement CQRS in the Transactions service
  - **Practice**: Separate the command and query layers in the transaction service for complex data operations.
- **Day 2**: Notifications, reporting, and roles management
  - **Practice**: Add notification features for transactions and reports for account summaries.
- **Day 3**: Testing & Quality Assurance
  - **Practice**: Write unit tests, and integration tests, and perform performance testing for microservices.

### Week 4: Deployment & Final Review
- **Day 1**: Dockerize the Application for cloud deployment
  - **Practice**: Build Docker images for all microservices and set up Kubernetes/Docker Compose for deployment.
- **Day 2**: Deploying Spring Cloud Config and Keycloak in Production
  - **Practice**: Use Spring Cloud Config to manage configuration across all microservices and secure them with Keycloak in a cloud environment.
- **Day 3**: Final Review & Presentation
  - **Practice**: Review the complete banking application, fix any issues, and present the final project.

---
