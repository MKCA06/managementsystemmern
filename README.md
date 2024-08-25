# Project Management System

[![Deployment](https://img.shields.io/badge/Deployed%20on-Vercel-brightgreen)](https://management-system-rjpu.vercel.app/)
[![Node.js](https://img.shields.io/badge/Node.js-v20.16.0-green)](https://nodejs.org/)
[![React](https://img.shields.io/badge/React-v18.0.0-blue)](https://reactjs.org/)
[![Express](https://img.shields.io/badge/Express-v4.17.1-lightgrey)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-v5.0.5-brightgreen)](https://www.mongodb.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)

## Overview

**Project Management System** is a full-stack web application designed to streamline project management for teams and organizations. The system allows users to manage projects, tasks, and team members efficiently, with role-based access control for admins, project managers, and users.

### Live Demo
Explore the live application: [https://management-system-rjpu.vercel.app/](https://management-system-rjpu.vercel.app/)

## Features

- **User Authentication**: Secure registration and login functionality with JWT-based authentication.
- **Role-Based Access Control**: Different access levels for Admin, Project Manager, and User.
- **Admin Dashboard**: Manage users and projects, with the ability to delete or update records.
- **Project Management**: Create, update, delete, and view projects.
- **Task Management**: Add, edit, delete tasks, and use drag-and-drop to update their status.
- **Search & Filter**: Powerful search and filtering capabilities for projects and tasks.
- **Responsive Design**: Fully responsive UI, optimized for all devices.
- **Real-Time Notifications**: Instant updates for project and task changes.

## Tech Stack

- **Frontend**: React.js, Tailwind CSS, React DnD
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose)
- **Authentication**: JWT (JSON Web Tokens)
- **Deployment**: Vercel

## Installation & Setup

### Prerequisites

- **Node.js** (v20.16.0 or later)
- **MongoDB** (local or cloud instance)

### Local Development

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/project-management-system.git
   cd project-management-system

   
Install dependencies:

npm install
cd client
npm install
cd ..

Environment Variables:
Create a .env file in the root directory and add the following:

NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret


Run the application:
npm run dev

