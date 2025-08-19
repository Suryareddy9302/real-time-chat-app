# Real-Time Chat Application

This is a full-stack, real-time chat application built with Spring Boot and React. It uses WebSockets for instant message delivery.

## Features
-   Real-time messaging between multiple clients.
-   "User joined" and "User left" notifications.
-   Simple, clean user interface.

## Tech Stack
-   **Backend:** Java, Spring Boot, Spring WebSocket (with STOMP)
-   **Frontend:** React, JavaScript, CSS, @stomp/stompjs
-   **Build Tool:** Maven

## How to Run Locally

### Prerequisites
-   Java 17 or later
-   Node.js and npm
-   Maven

### 1. Run the Backend
```bash
# Navigate to the backend folder
cd chatapp

# Run the Spring Boot application
./mvnw spring-boot:run
```
The backend server will start on `http://localhost:8080`.

### 2. Run the Frontend
```bash
# In a new terminal, navigate to the frontend folder
cd chat-frontend

# Install dependencies
npm install

# Start the React development server
npm start
```
The application will be available at `http://localhost:3000`.
