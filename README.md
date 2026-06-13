# Fitness Microservices Platform

A scalable fitness tracking application built using Spring Boot Microservices architecture.

## Features

* User Registration and Login
* JWT Authentication
* Workout Management
* Nutrition Tracking
* Goal Tracking
* Progress Analytics
* API Gateway
* Service Discovery

## Tech Stack

### Backend

* Java 17
* Spring Boot
* Spring Security
* Spring Cloud
* MySQL

### Frontend

* React.js

### DevOps

* Docker
* GitHub Actions

## Microservices

### User Service

Handles authentication and profile management.

### Workout Service

Manages workouts and exercise history.

### Nutrition Service

Tracks calorie intake and meal plans.

### Analytics Service

Generates fitness progress reports.

## Architecture
                    ┌─────────────────┐
                    │   React Frontend│
                    └────────┬────────┘
                             │
                             ▼
                  ┌───────────────────┐
                  │   API Gateway     │
                  │ Spring Cloud      │
                  └────────┬──────────┘
                           │
         ┌─────────────────┼─────────────────┐
         │                 │                 │
         ▼                 ▼                 ▼

 ┌─────────────┐   ┌─────────────┐   ┌─────────────┐
 │ User Service│   │Workout Serv.│   │NutritionSvc │
 └──────┬──────┘   └──────┬──────┘   └──────┬──────┘
        │                 │                 │
        ▼                 ▼                 ▼
 ┌─────────────┐   ┌─────────────┐   ┌─────────────┐
 │ User DB     │   │ Workout DB  │   │ NutritionDB │
 │ MySQL       │   │ MySQL       │   │ MySQL       │
 └─────────────┘   └─────────────┘   └─────────────┘

                           │
                           ▼

                  ┌──────────────────┐
                  │ Analytics Service │
                  └─────────┬────────┘
                            │
                            ▼
                     Analytics DB


## Future Enhancements

* AI Workout Recommendations
* Wearable Device Integration
* Social Fitness Challenges


