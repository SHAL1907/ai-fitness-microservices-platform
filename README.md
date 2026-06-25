# AI Fitness Microservices Platform

A production-inspired full-stack fitness management platform built using Java Spring Boot Microservices architecture. The application enables users to track fitness activities, receive AI-powered recommendations, and securely access services through OAuth2 authentication.

## Features

- User Registration & Login
- Secure Authentication using Keycloak
- API Gateway
- Service Discovery with Eureka
- Centralized Configuration Server
- RabbitMQ Asynchronous Communication
- AI-powered Fitness Recommendations using Gemini API
- Activity Tracking
- Responsive React Frontend
- RESTful APIs
- MySQL Database

---

## Architecture

```
React Frontend
        │
        ▼
   API Gateway
        │
 ┌──────┼─────────┐
 ▼      ▼         ▼
User  Activity   AI
Service Service Service
        │
    RabbitMQ
        │
        ▼
   Gemini API

Eureka Server
Config Server
```

---

## Tech Stack

### Backend
- Java 21
- Spring Boot
- Spring Security
- Spring Cloud
- Spring Data JPA
- Hibernate

### Frontend
- React
- Redux
- Axios

### Cloud & DevOps
- Docker
- RabbitMQ
- Keycloak
- Eureka
- Config Server

### AI
- Gemini API

### Database
- MySQL

---

## Microservices

- User Service
- Activity Service
- AI Recommendation Service
- API Gateway
- Eureka Discovery Server
- Config Server

---

## Screenshots

(Add screenshots here)

---

## Future Enhancements

- Workout Planner
- Nutrition Recommendation
- Progress Dashboard
- BMI Calculator
- AI Chat Assistant
- Email Notifications
- Docker Compose Deployment
- Kubernetes Deployment

---

## Author

Shalini Rani

GitHub:
https://github.com/SHAL1907
