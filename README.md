# Distributed Rate Limiter

A scalable **API rate limiting system** for protecting backend services under heavy traffic.  
Implements multiple algorithms and supports distributed environments using Redis.

## ✨ Features
- **Algorithms Supported**
  - Fixed Window Counter
  - Sliding Window Log
  - Sliding Window Counter
  - Token Bucket  

- **Distributed Support**
  - Redis-based shared state for multi-instance deployments  
  - Lua scripting for atomic operations  

- **API Gateway Integration**
  - Works as a Spring Boot starter for easy integration  
  - Configurable per-user / per-IP / per-endpoint  

## 🛠 Tech Stack
- Java 25 (LTS), Spring Boot 3  
- Redis (with Lua scripts)  
- Docker, Testcontainers  
- JUnit 5, k6 for load testing  

## 📚 What I Learned
- Trade-offs between **rate limiting algorithms**  
- Implementing **atomic operations in Redis** with Lua  
- Designing for **fairness, scalability, and low latency**  
- Building reusable infrastructure as a library/starter  
