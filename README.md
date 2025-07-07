# MERN Authentication Starter

A starter MERN stack application featuring user authentication and a Single Page Application (SPA) workflow using **Vite** as the frontend build tool. This project is based on the MERN Stack From Scratch | eCommerce course, tailored for quick setup and easy customization.

---

## Features

### Backend (API)
- Built with **Express.js** and **MongoDB** (using Mongoose ODM)
- User routes for:
  - Registration
  - Authentication (login)
  - Logout (clears JWT cookie)
  - Get user profile (protected route)
  - Update user profile (protected route)
- JWT authentication with tokens stored in **HTTP-only cookies** for enhanced security
- Middleware for:
  - Protecting routes by verifying JWT tokens
  - Custom error handling (404 and other errors)
- Password hashing with **bcrypt** to securely store user passwords

### Frontend
- Built with **React.js** using **Vite** for fast bundling and development
- State management with **Redux Toolkit**
- UI styled with **React Bootstrap**
- Navigation handled by **React Router v6** with protected routes
- User flows to:
  - Register new accounts
  - Login/logout
  - View and update user profile
- Notifications powered by **React Toastify** for feedback messages

---

## Tech Stack

| Layer       | Technology          |
|-------------|---------------------|
| Frontend    | React, Redux Toolkit, React Router, React Bootstrap, React Toastify, Vite |
| Backend     | Node.js, Express.js, MongoDB, Mongoose, bcrypt, JSON Web Token (JWT)       |
| Tools       | Vite, Postman (for API testing), npm                                       |
