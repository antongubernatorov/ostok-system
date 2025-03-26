# Ostock - Microservice Backend

## Overview

The application is a microservices-based asset management system designed to help companies track and manage their licenses and organizational data efficiently. 
It follows cloud-native architecture principles, leveraging Spring Cloud, Kubernetes, and AWS for scalability, security, and resilience. Key features include:

## Technologies Used

- OAuth2/JWT-based authentication for secure access control.
- Centralized configuration management via Spring Cloud Config.
- Service discovery using Eureka for dynamic scaling.
- API Gateway for routing, security, and policy enforcement.
- License & Organization Services for core business logic.
- PostgreSQL for relational data storage.
- Kafka for asynchronous event-driven communication.
- Redis for distributed caching to improve performance.
- ELK Stack (Elasticsearch, Logstash, Kibana) for centralized logging and monitoring.
- Zipkin for distributed tracing to debug latency issues.
