# MERN Chat App

This is a demo chat application built using the MERN stack (MongoDB, Express.js, React, Node.js). It utilizes Socket.IO for real-time chat functionality and Zustand for managing frontend state.

## Features

- Real-time messaging using Socket.IO
- Zustand for state management in React
- JWT authentication for user sessions

## Prerequisites

Before running the application locally, make sure you have the following installed:

- Node.js
- MongoDB (Make sure you have a MongoDB URI ready)

## Installation

1. Clone the repository:
 ```bash
 git clone https://github.com/yourusername/mern-chat-app.git
 cd mern-chat-app
```

2. Install dependencies for both frontend and backend:
 ```bash
 # Install backend dependencies
  cd backend
  npm install
  
  # Install frontend dependencies
  cd ../frontend
  npm install
  ```
3. Create an .env file in the backend directory and add the following environment variables:
  ```plaintext
  PORT=5000
  MONGO_DB_URI=<your_mongo_uri>
  JWT_SECRET=<your_secret_key>
  NODE_ENV=development
  ```
  Replace <your_mongo_uri> with your actual MongoDB URI and <your_secret_key> with your JWT secret key.

## Usage
1. Start the backend server:
   ```bash
   # From the root of the project
    cd backend
    npm start
   ```
2. Start the frontend development server:
   ```bash
   # From the root of the project
    cd frontend
    npm start
   ```
3. Open your browser and go to `http://localhost:5173` to view the application.
