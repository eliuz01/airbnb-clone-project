# airbnb-clone-project
Airbnb Clone - Backend
Overview
This project implements the backend of an Airbnb-like platform, designed to manage users, property listings, bookings, payments, and reviews. It provides a scalable, secure, and well-documented RESTful and GraphQL API for seamless interaction with frontend clients.

Objectives
Build a reliable backend that mimics the core functionalities of Airbnb.

Ensure scalability, maintainability, and security across all components.

Provide comprehensive API documentation for easy integration and testing.

Key Features
User Management: Register, authenticate, and manage user profiles.

Property Management: Create, update, and retrieve property listings.

Booking System: Reserve properties, manage booking lifecycle, and handle availability.

Payment Processing: Process and track transactions.

Review System: Enable users to leave reviews and ratings for listed properties.

Performance Optimization: Includes database indexing and caching for faster response times.

Tech Stack
Backend: Django, Django REST Framework

Database: PostgreSQL

APIs: REST (OpenAPI), GraphQL

Task Queue: Celery with Redis

Deployment: Docker, CI/CD pipelines

API Endpoints
👤 Users
GET /users/ - List users

POST /users/ - Create user

GET /users/{id}/ - Retrieve user

PUT /users/{id}/ - Update user

DELETE /users/{id}/ - Delete user

🏡 Properties
GET /properties/ - List properties

POST /properties/ - Create property

GET /properties/{id}/ - Retrieve property

PUT /properties/{id}/ - Update property

DELETE /properties/{id}/ - Delete property

📅 Bookings
GET /bookings/ - List bookings

POST /bookings/ - Create booking

GET /bookings/{id}/ - Retrieve booking

PUT /bookings/{id}/ - Update booking

DELETE /bookings/{id}/ - Delete booking

💳 Payments
POST /payments/ - Process payment

⭐ Reviews
GET /reviews/ - List reviews

POST /reviews/ - Create review

GET /reviews/{id}/ - Retrieve review

PUT /reviews/{id}/ - Update review

DELETE /reviews/{id}/ - Delete review