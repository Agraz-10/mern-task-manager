# MERN Task Manager

A full-stack task management application built with MongoDB, Express, React, and Node.js.

---

## Features

- User authentication (JWT)
- CRUD operations for tasks
- Mark tasks as complete/incomplete
- RESTful API

---

## Tech Stack

- Frontend: React  
- Backend: Node.js, Express  
- Database: MongoDB  
- Auth: JWT  

---

## Installation

```bash
git clone https://github.com/your-username/mern-task-manager.git
cd mern-task-manager

## Backend
cd backend
npm install
npm start

## Frontend
cd frontend
npm install
npm start

---

## Environmental Variables
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000

---

## API
POST /api/auth/signup
POST /api/auth/login
GET /api/tasks
POST /api/tasks
PUT /api/tasks/:id
DELETE /api/tasks/:id

---

## License
MIT