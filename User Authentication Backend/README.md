# JWT Authentication Backend

A backend authentication API built using Node.js, Express.js, MongoDB Atlas, Mongoose, JWT, and bcrypt.

## Features

* User Registration (Signup)
* User Login (Signin)
* Password Hashing using bcrypt
* JWT Token Generation
* Protected Routes using JWT Middleware
* User Profile API
* Logout Functionality
* MongoDB Atlas Integration
* Cookie-based Authentication

## Tech Stack

* Node.js
* Express.js
* MongoDB Atlas
* Mongoose
* JSON Web Token (JWT)
* bcrypt
* cookie-parser
* dotenv
* cors

## Installation

1. Clone the repository

```bash
git clone <repository-url>
```

2. Install dependencies

```bash
npm install
```

3. Create a `.env` file

```env
PORT=5001
MONGODB_URL=your_mongodb_connection_string
SECRET=your_jwt_secret
CLIENT_URL=http://localhost:3000
```

4. Start the server

```bash
npm run start
```

## API Routes

### Signup

```http
POST /api/auth/signup
```

### Signin

```http
POST /api/auth/signin
```

### Get User

```http
GET /api/auth/user
```

### Logout

```http
GET /api/auth/logout
```

## Project Structure

```text
backend
├── config
│   └── databaseConfig.js
├── controller
│   └── authController.js
├── middleware
│   └── jwtAuth.js
├── model
│   └── userSchema.js
├── router
│   └── authRoute.js
├── app.js
├── index.js
└── .env
```

## Author

Ravi Kumar
B.Tech (Information Technology)
AKTU University
