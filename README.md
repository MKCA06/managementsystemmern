Project Management System

Overview
Project Management System is a full-stack web application designed to streamline project management for teams and organizations. The system allows users to manage projects, tasks, and team members efficiently, with role-based access control for admins, project managers, and users.

Live Demo
Explore the live application: https://management-system-rjpu.vercel.app/

Features
User Authentication: Secure registration and login functionality with JWT-based authentication.
Role-Based Access Control: Different access levels for Admin, Project Manager, and User.
Admin Dashboard: Manage users and projects, with the ability to delete or update records.
Project Management: Create, update, delete, and view projects.
Task Management: Add, edit, delete tasks, and use drag-and-drop to update their status.
Search & Filter: Powerful search and filtering capabilities for projects and tasks.
Responsive Design: Fully responsive UI, optimized for all devices.
Live Notifications: Real-time notifications for project updates and task assignments.
Tech Stack
Frontend: React.js, Tailwind CSS, React DnD
Backend: Node.js, Express.js
Database: MongoDB (Mongoose)
Authentication: JWT (JSON Web Tokens)
Deployment: Vercel
Installation & Setup
Prerequisites
Node.js (v20.16.0 or later)
MongoDB (local or cloud instance)
Local Development
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/project-management-system.git
cd project-management-system
Install dependencies:

bash
Copy code
npm install
cd client
npm install
cd ..
Environment Variables:

Create a .env file in the root directory and add the following:

bash
Copy code
NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
Run the application:

bash
Copy code
npm run dev
This will start both the backend and frontend servers concurrently.

Access the application:

Open your browser and navigate to http://localhost:3000 for the frontend, and http://localhost:5000/api for the backend API.

Deployment
The application is deployed on Vercel. To deploy your own version:

Fork the repository and clone it to your local machine.
Push to your GitHub repository.
Connect the repository to Vercel.
Set up environment variables on Vercel similar to your local .env file.
Deploy your application.
Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch: git checkout -b feature-branch-name
Commit your changes: git commit -m 'Add some feature'
Push to the branch: git push origin feature-branch-name
Submit a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
For any inquiries or issues, please contact the project maintainer:

Name: Your Name
Email: your.email@example.com
GitHub: your-username
