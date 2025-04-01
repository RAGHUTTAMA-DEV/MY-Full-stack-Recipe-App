# MERN Recipe App

A full-stack web application built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js) that allows users to manage recipes, register/login, and perform CRUD operations on recipes. The app also includes features like user authentication, recipe liking, and password recovery.

---

## Features

- **User Authentication**: Secure login and registration using JWT (JSON Web Tokens).
- **Recipe Management**: Add, view, edit, and delete recipes.
- **Private Routes**: Protect certain routes to ensure only authenticated users can access them.
- **Like Recipes**: Users can like and save their favorite recipes.
- **Password Recovery**: Forgot password functionality for users.
- **Responsive Design**: Fully responsive UI built with React.

---

## Tech Stack

### Frontend:
- **React.js**: For building the user interface.
- **React Router**: For routing and navigation.
- **CSS**: For styling the application.

### Backend:
- **Node.js**: For server-side logic.
- **Express.js**: For building RESTful APIs.
- **Mongoose**: For interacting with MongoDB.

### Database:
- **MongoDB**: A NoSQL database for storing user and recipe data.

---

## Installation and Setup

Follow these steps to set up the project locally:

### Prerequisites:
- [Node.js](https://nodejs.org/) installed on your system.
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) account or a local MongoDB instance.
- [Git](https://git-scm.com/) installed.

### Steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/MERN-Recipe-App.git
   cd MERN-Recipe-App


2.Set Up the Backend:

cd server
npm install

3.Set Up the Frontend:
cd ../client/my-app
npm install

Environment Variables:REpalce the dotnev file with your own creadentialls

MERN-Recipe-App/
├── client/
│   ├── my-app/
│   │   ├── src/
│   │   │   ├── components/       # React components
│   │   │   ├── App.js           # Main React app file
│   │   │   ├── index.js         # React entry point
│   │   └── public/
│   └── package.json
├── server/
│   ├── db/
│   │   ├── config.js            # MongoDB connection setup
│   ├── controllers/             # API controllers
│   ├── routes/                  # API routes
│   ├── Middleware/              # Middleware (e.g., JWT verification)
│   ├── index.js                 # Express server entry point
│   └── package.json
├── .env                         # Environment variables
└── README.md
