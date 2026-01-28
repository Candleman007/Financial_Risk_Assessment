# Low Level Design (LLD)

## 1. Application Structure
The application follows Flask best practices with a modular folder structure.

---

## 2. Module-Level Design

### 2.1 Authentication Module
- Handles user registration and login
- Uses encrypted passwords
- Maintains user sessions

### 2.2 Risk Assessment Module
- Accepts financial inputs
- Applies rule-based risk logic
- Calls ML prediction service

### 2.3 Analytics Module
- Aggregates risk data
- Prepares data for chart visualization

### 2.4 Reporting Module
- Generates user-specific risk reports

---

## 3. File-Level Responsibilities

- routes/: Handles HTTP routing
- services/: Contains business logic
- models/: Defines database schema
- templates/: UI pages
- static/: CSS and JavaScript files

---

## 4. Error Handling
- Invalid input validation
- Graceful API error responses
- Logged exceptions
