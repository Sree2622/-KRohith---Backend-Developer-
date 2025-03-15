# Backend Developer Assignment

## Tech Stack
- **Node.js** – Backend runtime
- **Express.js** – Fast, minimalist backend framework
- **MongoDB** – NoSQL database for storing user data
- **JWT (JSON Web Token)** – Secure user authentication
- **TypeScript** (Optional) – For type safety

## Features
- User Authentication (Signup/Login with JWT)
- MongoDB schema for users
- CRUD API implementation for a sample resource

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/backend-assignment.git
   cd backend-assignment
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Create a **.env** file in the root directory and add the following:
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   ```

4. Start the server:
   ```sh
   npm start
   ```

## API Endpoints

### Authentication
- **POST /signup** – Register a new user
- **POST /login** – Authenticate user and return JWT

### CRUD Operations (Example: Tasks)
- **POST /tasks** – Create a new task (Protected)
- **GET /tasks** – Fetch all tasks (Protected)
- **GET /tasks/:id** – Fetch a specific task (Protected)
- **PUT /tasks/:id** – Update a task (Protected)
- **DELETE /tasks/:id** – Delete a task (Protected)


```

