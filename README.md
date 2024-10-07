# MERN Stack Authentication App

## Summary
This project is a full-featured MERN (MongoDB, Express, React, Node.js) stack application with a focus on authentication. It includes a React Single Page Application (SPA) frontend and a robust API backend. The project demonstrates how to create and manage state using Redux Toolkit, secure user authentication with JWT tokens, and deploy the app for production.

## Features
- User Authentication (Register, Login, Logout)
- Redux Toolkit for state management
- Full-featured API using Express
- JWT token-based authentication
- React Bootstrap for UI components
- Secure and protected routes with middleware

## Challenges and How I Overcame Them

- **Asynchronous Operations:** Initially, handling asynchronous code in Node.js was challenging. I learned to effectively use `async/await` to manage non-blocking code and implement error-handling strategies that made the code more efficient and reliable.

- **State Management Complexity:** Managing state with Redux Toolkit across various components of the application was difficult at first. But once I understood how to set up the slices and integrate them, it streamlined the data flow and reduced the boilerplate code, making it easier to maintain.

- **Frontend and Backend Synchronization:** Ensuring seamless communication between the frontend and backend, particularly with issues like token expiration and session handling, was one of the toughest parts. Through debugging and testing, I managed to implement a secure way of handling user authentication and session persistence.

## Installation

### Install Dependencies (frontend & backend)
To install the required dependencies for both the backend and frontend, use the following commands:
```bash
npm install
cd frontend
npm install
```
## Run and Build 

### Frontend and backend 
npm run dev

### Frontend only 
npm run server

