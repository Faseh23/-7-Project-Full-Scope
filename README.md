# -7-Project-Full-Scope
ParkWheelz - Parking Management System
Project Overview
ParkWheelz is a modern, user-friendly parking management system designed to simplify the process of booking, tracking, and managing parking spaces. Built using React 19 and Vite for lightning-fast performance, the project features a clean, responsive UI styled with Tailwind CSS and seamless navigation handled by React Router. The backend is powered by Node.js and json-server, with JWT authentication for secure access.
Setup Guide
Prerequisites
Make sure you have the following installed on your system:
• Node.js (v18 or later)
• npm (v9 or later) or yarn
Client Setup
Run the following commands:
cd parkwheelz-client
npm install
npm run dev
This will start the React frontend on http://localhost:5173
Server Setup
Run the following commands:
cd parkwheelz-server
npm install
npm run dev
This will start the backend server on http://localhost:3001
Environment Variables
Create a .env file inside the parkwheelz-client directory and add the following line:
VITE_API_BASE_URL=http://localhost:3001
Access Points
• Frontend (Client) → http://localhost:5173
• Backend (Server) → http://localhost:3001
Tech Stack
Layer	Technologies Used
Frontend
Backend	React 19, Vite, Tailwind CSS, Axios, React Router
Node.js, json-server, JWT Authentication
Project Structure
parkwheelz/
├── parkwheelz-client/     # React frontend
└── parkwheelz-server/     # Node.js backend
Development Commands
Client: npm run dev (port 5173)
Server: npm run dev (port 3001)
