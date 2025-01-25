# Lab 13 - Security in Java Web Applications

Student Name: Sadettin Celik
Student ID: 40312

This project aims to create a simple user management system using Spring Boot.

## Technologies Used

- Spring Boot
- Spring Security
- SQLite database
- Flyway

## Setup

1. Download the project
2. Copy `.env.example` to `.env`
3. Run with `./mvnw spring-boot:run`

## API Usage

### User Operations
- Register: `/api/auth/register`
- Login: `/api/auth/login`
- View profile: `/api/auth/profile`

### Admin Operations
- List users: `/api/admin/users`
- Activate/deactivate user: `/api/admin/users/{id}/activate` or `/deactivate`

## Admin Account
- Email: admin@example.com
- Password: admin123
