# JeJoy – Multi-Application Production-Ready Food Delivery Platform

JeJoy is a multi-application, production-ready food delivery ecosystem built using Java (Spring Boot), React, and MySQL.

The platform supports:

- Customer Android Application
- Delivery Partner Android Application
- Restaurant Owner Android Application
- Admin & Customer Web Dashboard

The system is powered by a scalable REST API backend and deployed on AWS Lightsail with Nginx reverse proxy and SSL configuration.

---

## 🚀 Key Features

- JWT-based secure authentication
- Role-based access control (Customer, Restaurant Owner, Delivery Partner, Admin)
- Multi-role order workflow management
- RESTful API architecture
- API Versioning Ready (v1 / v2)
- Cloud deployment on AWS Lightsail
- Nginx reverse proxy with SSL termination
- Linux server configuration & production hosting

---

## 🧠 Architecture Overview

The production architecture follows a layered and modular design:

- Client Layer (Web + Multiple Android Apps)
- JWT Authentication Layer
- Nginx Reverse Proxy (Traffic handling + SSL termination)
- Spring Boot REST API
  - Controller Layer
  - Service Layer (Business Logic)
  - Security Layer (Spring Security + JWT)
- MySQL Relational Database
- AWS Lightsail (Ubuntu Production Server)

---

## 📊 Performance Testing

Load tested using Apache JMeter.

- Concurrent Users: 900
- Ramp-up Time: 100 seconds
- Error Rate: 0%
- Average Response Time: ~80–100ms
- Stable throughput under high traffic

---

## 📸 Load Testing Report

![JMeter Load Test](jmeter_load_testing.jpeg)

---

## 🏗 Production Architecture Diagram

![Architecture Diagram](architecture-diagram.png)

---

## 🛠 Tech Stack

### Backend
- Java
- Spring Boot
- Spring Security
- Hibernate / JPA

### Frontend
- React
- Vite

### Database
- MySQL

### Cloud & Infrastructure
- AWS Lightsail (Ubuntu Server)
- Nginx Reverse Proxy
- SSL Configuration
- Linux Server Management

### Performance Testing
- Apache JMeter

---

## 🧠 Scalability & System Design Highlights

- Stateless JWT Authentication
- Modular Service Layer Architecture
- API Versioning Support
- Reverse Proxy Architecture
- Designed for Horizontal Scaling
- Production-Optimized Deployment

---

## 🌍 Deployment

Production environment hosted on AWS Lightsail (Ubuntu).  
Configured with Nginx reverse proxy, SSL termination, and firewall security.

---

## 📌 Note

Production source code is private due to security and business considerations.

This repository showcases:

- System Architecture
- Performance Validation
- Deployment Strategy
- Scalability Design
- Technical Capabilities

---

## 👨‍💻 Author

Srinu R  
Full Stack Developer  
Andhra Pradesh, India
