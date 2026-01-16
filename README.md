# Airbnb_Clone
A robust, enterprise-grade backend system for a Hotel Management/Airbnb-style application. This project handles the complete lifecycle of property listings, user reservations, and secure authentication using modern Java standards.

🚀 Core Features
1. User Authentication & Security
JWT-Based Authentication: Implemented a stateless security layer using Spring Security and JSON Web Tokens (JWT).

Role-Based Access Control (RBAC): Distinct permissions for Hosts (can list/manage properties) and Guests (can view/book stays).

Secure Password Storage: Utilizing BCryptPasswordEncoder for industry-standard password hashing.

2. Property & Booking Management
Property Lifecycle: Full CRUD operations for property listings (Name, Location, Price, Description).

Booking System: Logic to handle reservations, preventing double-bookings and managing stay dates.

Dynamic Search: Advanced filtering by location, price range, and property name using Spring Data JPA Derived Queries.

3. Technical Excellence
Global Exception Handling: Centralized error management using @ControllerAdvice for clean, consistent API responses.

DTO Pattern: Used Data Transfer Objects to decouple the database layer from the API layer, improving security and performance.

Transaction Management: Ensured ACID compliance during the booking process using the @Transactional annotation.
