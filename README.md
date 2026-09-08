# Node.js Authentication API (MongoDB)

A secure and well-structured RESTful Authentication API built with **Node.js**, **TypeScript**, **Express**, and **MongoDB**.  
This project demonstrates modern backend practices including JWT authentication, password hashing, input validation, and protected routes.

## Features

- User Registration
- User Login with JWT
- Password Hashing using bcrypt
- Protected Routes
- Input Validation
- Centralized Error Handling
- Environment-based Configuration
- Clean and scalable project structure

## Tech Stack

- **Runtime:** Node.js
- **Language:** TypeScript
- **Framework:** Express.js
- **Database:** MongoDB + Mongoose
- **Authentication:** JWT + bcrypt
- **Validation:** Zod
- **Security:** Helmet, CORS, express-rate-limit
- **Package Manager:** npm

## API Endpoints

| Method | Endpoint              | Description                     | Access     |
|--------|-----------------------|---------------------------------|------------|
| POST   | `/api/auth/register`  | Register a new user             | Public     |
| POST   | `/api/auth/login`     | Login and get JWT token         | Public     |
| GET    | `/api/auth/me`        | Get current authenticated user  | Protected  |
| GET    | `/health`             | Health check                    | Public     |

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- MongoDB (local or MongoDB Atlas)
- npm

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/your-username/node-auth-api.git
cd node-auth-api
