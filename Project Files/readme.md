# Project Executable files
# 🏠 HouseHunt

A full-stack MERN application designed to simplify the home renting and listing process. HouseHunt connects buyers, renters, sellers, and real estate professionals through a streamlined platform built with modern web technologies.

---

## 📂 Folder Overview

This project is divided into two main directories:

### 🔹 `/frontend`
Contains the client-side application built with **React** and **Vite**. This is the user interface of HouseHunt, allowing users to browse listings, apply filters, and interact with the platform.

Key features:
- Modern UI built with React
- Bootstrap for styling
- Routing using React Router
- API integration using Axios
- State management using hooks

### 🔹 `/backend`
Contains the server-side logic built with **Express.js** and **MongoDB**. It handles authentication, database operations, route handling, and more.

Key features:
- RESTful APIs for listings, users, etc.
- JWT-based authentication
- MongoDB with Mongoose for database management
- Middleware support for validation, auth, error handling

---

## 🚀 How to Run the Project

## ⚙️ Project Setup Instructions

Follow the steps below to run both backend and frontend locally:

1. Clone the Repository

git clone https://github.com/your-username/househunt.git
cd househunt

2. Setup the Backend

cd backend
npm install

Create a .env file inside the backend/ directory and add the following:

PORT=5000
MONGO_URI=your-mongodb-uri
JWT_SECRET=your-secret

Then run the backend server:

npm start

3. Setup the Frontend

cd ../frontend
npm install

Create a .env file inside the frontend/ directory and add the following:

VITE_API_URL=http://localhost:5000/api

Then run the frontend development server:

npm run dev
