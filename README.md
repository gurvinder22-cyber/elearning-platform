A full-stack E-Learning Platform built with React, Node.js, Express, and MongoDB Atlas, featuring authentication, course management, enrollments, and an admin panel.
🛠 Tech Stack
Frontend

React (Vite)

React Router

Axios

Tailwind CSS

JWT Authentication

Backend

Node.js

Express.js

MongoDB Atlas

Mongoose

JWT (Authentication)

bcrypt (Password hashing)

Deployment

Frontend → Vercel

Backend → Render

Database → MongoDB Atlas

Version Control → GitHub

✨ Features
👤 User

Signup & Login

Browse courses

View course details

Enroll in courses

Track progress

User dashboard

🛠 Admin

Admin login

Create courses

Edit courses

Delete courses

View enrollments

🔐 Security

Passwords encrypted using bcrypt

JWT authentication

Role-based access (User / Admin)

Environment variables for secrets

📁 Project Structure
elearning-platform/
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   ├── server.js
│   ├── package.json
│   └── .env.example
│
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   ├── components/
│   │   ├── services/
│   │   └── App.jsx
│   ├── package.json
│   └── .env.example
│
└── README.md

⚙️ Environment Variables
Backend .env
MONGO_URI=your_mongodb_atlas_connection_string
JWT_SECRET=your_secret_key

Frontend .env
VITE_API_URL=https://your-render-backend-url

🧪 Run Locally
Backend
cd backend
npm install
npm start

Frontend
cd frontend
npm install
npm run dev

🌍 Deployment Guide
MongoDB Atlas

Create a free cluster at https://mongodb.com/atlas
Backend – Render

Create Web Service

Connect GitHub repo

Root Directory: backend

Start Command:

node server.js


Add environment variables:

MONGO_URI
JWT_SECRET

Frontend – Vercel

Import GitHub repo

Root Directory: frontend

Add env variable:

VITE_API_URL = https://your-render-backend-url


Deploy

📸 Screenshots (Add)

Landing Page

Course List

Login / Signup

Dashboard

Admin Panel

📚 What I Learned

Building REST APIs

JWT authentication

Role-based access

Full-stack deployment

MongoDB schema design

React routing & state management

👨‍💻 Author

Gurvinder Singh Ranjan
B.Tech CSE
Internship Project – Full Stack Development
Copy the connection string

Paste it into Render as MONGO_URI
