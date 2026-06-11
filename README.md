QuizSphere is a Microservices-based Quiz Management System developed using Spring Boot. 

The application consists of four independent services: Gateway Service, Question Service, Quiz Service, and Service Registry.

The Service Registry enables service discovery, while the Gateway Service acts as a single entry point for client requests. 

The Quiz Service communicates synchronously with the Question Service to fetch and manage quiz questions. 

This architecture demonstrates service discovery, API gateway routing, inter-service communication, and scalable microservices design.

This project showcases core microservices concepts, including service discovery, API gateway routing, and inter-service communication, while demonstrating the design of 

scalable and maintainable distributed systems.

Technology Stack

Java 21

Spring Boot 4.0

Spring Cloud

OpenFeign Client

Netflix Eureka Server

Spring Cloud Gateway

Spring Boot Actuator

WebFlux

Maven


Key Features

Microservices Architecture
Service Discovery and Registration using Netflix Eureka
Centralized API Routing through Spring Cloud Gateway
Synchronous Inter-Service Communication using OpenFeign
Health Monitoring and Metrics using Spring Boot Actuator
Reactive Gateway Implementation with WebFlux
Scalable and Maintainable Distributed System Design
Author Shree Kalyankar.
