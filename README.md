# Online-Library 
This is a Basic Online Library   that performs the basic SCRUD fucntions with a professional UI/UX     made using the MERN Stack     
# Library Management System

A full-stack library management application built with React (frontend) and Node.js/Express (backend).

## Local Development

### Prerequisites
- Node.js (v14 or higher)
- MongoDB

### Installation

1. Clone the repository
2. Install backend dependencies:
   ```bash
   cd backend
   npm install
   ```
3. Install frontend dependencies:
   ```bash
   cd frontend
   npm install
   ```

### Running the Application

1. Start the backend server:
   ```bash
   cd backend
   npm run dev
   ```
   The backend will run on `http://localhost:5005`

2. Start the frontend development server:
   ```bash
   cd frontend
   npm run dev
   ```
   The frontend will run on `http://localhost:3030`

### Access the Application

Open your browser and navigate to: **http://localhost:3030**

## Features

- User authentication and registration
- Book management (add, edit, delete books)
- User management
- Borrowing history tracking
- Real-time updates with Socket.io

## Tech Stack

- **Frontend:** React, TypeScript, Vite, Material-UI
- **Backend:** Node.js, Express.js, MongoDB, Socket.io
- **Authentication:** JWT tokens

