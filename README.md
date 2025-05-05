# Recipe Sharing Full Stack App (MERN Stack)
The Recipe Sharing Platform is a full-stack web application that enables users to create, browse, and interact with recipes. 
Users can register and authenticate securely, upload their recipes, and explore a vast collection shared by the community. 
The platform also allows users to rate recipes, leave comments, and bookmark their favorites.
 Designed to be fully responsive, the application ensures a seamless experience across various devices.

# MERN Recipe App

## Table of Contents
- [Screenshots](#screenshots)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Folder Structure](#folder-structure)
- [Technologies Used](#technologies-used)

![image](https://github.com/user-attachments/assets/d6cb725f-06e3-4fa1-9e13-b9c57459b101)


![image](https://github.com/user-attachments/assets/d16293c6-17a7-448b-8f59-fe5b1f9a3fbe)

![image](https://github.com/user-attachments/assets/55f71bfb-9803-4095-86ff-23f0ad92f41d)

## Features
- **User Authentication**: Secure user authentication and registration system.
- **Recipe Management**: Create, edit, and delete your recipes.
- **Recipe Discovery**: Browse and search for recipes shared by other users.
- **Comments and Ratings**: Leave comments and rate recipes.
- **Favorite Recipes**: Save your favorite recipes for easy access.
- **Responsive Design**: Works seamlessly on both desktop and mobile devices.

## Prerequisites
Make sure you have the following installed:
- Node.js (v14 or higher)
- MongoDB (local or remote)
- Git
- A text editor or IDE (e.g., Visual Studio Code)

Getting Started

Clone the repository:
git clone https://github.com/Rohith-Manjunath/MERN-Recipe-App.git

Navigate to the project directory:
cd Mern-Recipe-App

Navigate to the client directory:
cd client
cd my-app

Install client dependencies:
npm install

Return to the root directory:
cd ../..

Navigate to the server folder:
cd server

Create a .env file and add the following environment variables:
PORT=2000
MONGODB_URI=mongodb://localhost/recipe-app
SECRET=your-secret-key

(Replace "your-secret-key" with a secure key for JWT token generation.)

Start the backend development server:
node index.js

Folder Structure
The project uses a standard MERN stack structure:

MERN-Recipe-App/
├── client/ → Contains the React frontend
│ └── my-app/ → React application
├── server/ → Contains the Express backend
│ ├── Schema/ → MongoDB schemas and models
│ ├── routes/ → API routes
│ ├── controllers/ → Business logic and DB operations
│ ├── middlewares/ → Middleware (e.g., authentication)
│ └── db/ → Database configuration files

Technologies Used

Frontend:

React

Backend:

Node.js

Express.js

MongoDB (using Mongoose)

JSON Web Tokens (JWT) for authentication

bcrypt for secure password hashing
