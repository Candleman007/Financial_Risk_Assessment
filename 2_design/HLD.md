# High Level Design (HLD)

## 1. Introduction
This document describes the high-level architecture of the Financial Risk Assessment System. It explains the major components, their responsibilities, and interactions.

---

## 2. System Architecture Overview
The system follows a layered architecture consisting of:

- Presentation Layer (Frontend)
- Application Layer (Flask Backend)
- Business Logic Layer (Services)
- Data Layer (SQL Database)
- Analytics Layer (ML Model)

---

## 3. Component Description

### 3.1 Frontend Layer
- Implemented using HTML, CSS, and JavaScript
- Served via Flask templates and static files
- Responsible for user interaction and visualization

### 3.2 Backend Layer
- Implemented using Flask
- Handles HTTP requests and responses
- Performs authentication and validation

### 3.3 Business Logic Layer
- Contains risk calculation logic
- Integrates ML-based risk prediction
- Isolated from routing logic

### 3.4 Data Layer
- SQL database for persistent storage
- Stores user details and risk records

### 3.5 Monitoring Layer
- Logs user actions and system errors
- Supports maintenance and debugging

---

## 4. Deployment Overview
The application is container-ready and can be deployed locally or on any cloud platform using Docker.
