MERN Real-Time Chat Application

🚀 Project Overview

This is a Real-Time Chat Application built using the MERN stack (MongoDB, Express, React, Node.js). It allows users to sign up, log in, and chat in real time with other users. The project includes JWT authentication, Zustand for state management, and Tailwind CSS for styling.

🌟 Features

User Authentication (Sign Up & Login)

Real-Time Messaging

Profile Management

Secure Routes (Protected using JWT & Middleware)

Zustand for Global State Management

Tailwind CSS for UI Styling

Backend API with Express.js & MongoDB

📂 Project Structure

root/
│── backend/               # Node.js & Express Backend
│   ├── models/            # Mongoose Models
│   ├── routes/            # API Routes
│   ├── controllers/       # Route Handlers
│   ├── middleware/        # Authentication Middleware
│   ├── config/            # Configuration Files
│   ├── server.js          # Main Backend Server
│
│── frontend/              # React Frontend
│   ├── src/
│   │   ├── components/    # Reusable UI Components
│   │   ├── pages/         # Different Pages (Login, Home, etc.)
│   │   ├── store/         # Zustand State Management
│   │   ├── App.jsx        # Main App Component
│   │   ├── main.jsx       # React Entry File
│   │   ├── index.css      # Global Styles
│
│── .env                   # Environment Variables
│── package.json           # Dependencies & Scripts
│── README.md              # Project Documentation

⚙️ Setup Instructions

1️⃣ Clone the Repository

git clone https://github.com/ashwajit120603/fullstack-chat-app.git
cd fullstack-chat-app


2️⃣ Backend Setup

cd backend
npm install   # Install dependencies

Create a .env file in backend/ and add:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=5001

Start the Backend Server

npm run dev  # Starts the backend on http://localhost:5001

3️⃣ Frontend Setup

cd frontend
npm install   # Install dependencies

Start the Frontend

npm run dev  # Starts the frontend on http://localhost:5173

🔗 API Endpoints

Authentication Routes

Method

Endpoint

Description

POST

/auth/signup

User Signup

POST

/auth/login

User Login

GET

/auth/check

Check if user is logged in

User Routes

Method

Endpoint

Description

GET

/users

Get all users except logged-in user

GET

/users/:id

Get a specific user

PUT

/users/:id

Update user profile

🛠️ Technologies Used

Frontend: React, React Router, Zustand, Tailwind CSS

Backend: Node.js, Express.js, MongoDB, Mongoose

Authentication: JWT (JSON Web Tokens)

HTTP Requests: Axios

📝 Future Enhancements

WebSockets for real-time messaging

Group chats feature

Dark Mode support

Notifications for new messages


💬 Contact

For any queries, reach out at: ashwajitsurwade945@gmail.com
