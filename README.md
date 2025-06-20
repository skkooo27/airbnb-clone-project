# airbnb-clone-project.
 Project Overview
This project is a backend-focused clone of Airbnb, designed to simulate the architecture and core functionalities of a real-world booking platform. It emphasizes backend systems, database modeling, API development, and DevOps practices.

 Project Goals
Develop a robust backend for a property rental service.

Implement secure APIs and database schemas.

Integrate CI/CD pipelines for deployment automation.

Simulate a full-stack collaboration environment.

 Tech Stack
Django: Web framework for handling API logic and routing.

MySQL: Relational database for storing user, booking, and property data.

GraphQL: API query language for optimized data fetching.

Docker: Containerization for consistent development and deployment.

GitHub Actions: CI/CD pipeline for automated testing and deployment.

Team Roles
Role	Responsibilities
Backend Developer	Develops and maintains APIs, handles business logic, integrates database operations.

Database Administrator (DBA)	Designs, implements, and manages the relational schema and ensures data integrity.

DevOps Engineer	Sets up Docker containers, GitHub Actions, and deployment pipelines.

QA Engineer	Manages testing, ensures code meets quality standards before deployment.

Project Manager	Oversees project milestones, team coordination, and documentation.

Technology Stack
Technology	Purpose
Django	Backend framework for routing, models, and RESTful API logic.

MySQL	Stores structured relational data like users, bookings, and properties.

GraphQL	Allows efficient and flexible data querying between frontend and backend.

Docker	Ensures consistency across environments via containers.

GitHub Actions	Automates tests, builds, and deployments using workflows.

🗂 Database Design
Key Entities and Fields
Users

id, name, email, password_hash, role

Properties

id, title, description, location, user_id

Bookings

id, user_id, property_id, start_date, end_date

Reviews

id, user_id, property_id, rating, comment

Payments

id, booking_id, amount, payment_method, status
