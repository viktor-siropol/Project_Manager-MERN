# Project Manager – Full‑Stack MERN Application

A **production‑ready full‑stack Project Management application** built with the **MERN stack** (MongoDB, Express, React, Node.js).  
The system allows users to manage **workspaces, projects, and tasks** with secure authentication and a scalable REST API.

This repository represents a **portfolio‑grade application**, designed with clean architecture, environment separation, and real‑world backend practices.

---

## ✨ Key Features

- 🔐 Secure authentication using JWT (access & refresh tokens)
- 🏢 Workspace‑based organization
- 📁 Project and task management (full CRUD)
- 🌐 RESTful API built with Express & MongoDB
- 🧩 Modular backend architecture (routes, controllers, middleware)
- 🔒 Environment‑based configuration (`.env`)
- 🚀 Ready for local development and cloud deployment

---

## 🛠️ Tech Stack

### Frontend
- React (Vite)
- Axios
- Modern ES6+ JavaScript

### Backend
- Node.js
- Express.js
- MongoDB & Mongoose
- JWT Authentication
- CORS & custom middleware

---

## 📂 Project Structure

```
backend/
 ├── controllers/     # Request handlers
 ├── routes/          # API routes
 ├── models/          # Database schemas
 ├── middleware/      # Auth & validation middleware
 ├── libs/            # Utilities (email, validation, helpers)
 └── index.js         # App entry point

frontend/
 ├── app/
 └──public/

```

---



## ▶️ Getting Started (Local Development)

### 1️⃣ Clone the repository
```bash
git clone https://github.com/viktor-siropol/Project_Manager-MERN.git
cd project-manager
```

### 2️⃣ Install dependencies
```bash
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install
```

### 3️⃣ Run the application
```bash
# Backend
cd backend
npm run dev

# Frontend
cd ../frontend
npm run dev
```

### 4️⃣ Access the application
- Frontend: `http://localhost:5173`
- Backend API: `http://localhost:5000/api-pr-manager`

---

## 🔗 API Overview

Base API URL:
```
/api-pr-manager
```

Main endpoints:
- `/auth` – authentication & authorization
- `/workspaces` – workspace management
- `/projects` – project operations
- `/tasks` – task management
- `/users` – user management

---

## 📌 Notes for Recruiters

This project demonstrates:
- Full‑stack MERN development
- REST API design and architecture
- Secure authentication & middleware usage
- Environment configuration best practices
- Scalable and maintainable backend structure

It was built as a **portfolio project** to reflect real‑world development patterns rather than a simple tutorial implementation.



