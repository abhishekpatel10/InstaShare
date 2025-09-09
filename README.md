# MERN Project: "InstaShare" - A Full Stack Social Media App



This is the official code repository for the "InstaShare" project, a full-stack MERN (MongoDB, Express, React, Node.js) application. It's a simple social media app that allows users to post interesting events that happened in their lives.

This project was built following the comprehensive video tutorial series on YouTube.


## 📋 Table of Contents
* [Project Overview](#-project-overview)
* [Features](#-features)
* [Tech Stack](#-tech-stack)
* [Getting Started](#-getting-started)
    * [Prerequisites](#prerequisites)
    * [Installation & Setup](#installation--setup)
* [Project Structure](#-project-structure)
* [Contributing](#-contributing)
* [License](#-license)

## 📌 Project Overview

"Memories" is a full-stack social media application built to demonstrate the power and workflow of the MERN stack. Users can create, update, like, and delete their own "memories," creating a dynamic and interactive timeline of events. This repository provides the complete source code, allowing you to build, run, and extend the application on your own machine.

By following the tutorial and exploring this codebase, you will gain a strong, practical understanding of how to connect a React frontend with a Node.js & Express backend and interact with a MongoDB database.


## ✨ Features

*   **Create, Read, Update, and Delete (CRUD) Posts**: Full implementation of CRUD operations for memories.
*   **Image Uploads**: Users can upload images to accompany their posts.
*   **Liking Posts**: Interactive feature to like and unlike posts.
*   **RESTful API**: A well-structured backend API built with Node.js and Express.
*   **Responsive Frontend**: A modern and responsive user interface built with React and Material-UI.

## 💻 Tech Stack

The project is built using the MERN stack and other modern technologies:

**Frontend:**
*   **React.js**: A JavaScript library for building user interfaces.
*   **Redux**: For predictable state management.
*   **Material-UI**: For a rich library of UI components.
*   **Axios**: For making API requests to the backend.
*   **React Router**: For client-side routing.

**Backend:**
*   **Node.js**: A JavaScript runtime for the server.
*   **Express.js**: A web application framework for Node.js.
*   **MongoDB**: A NoSQL database to store application data.
*   **Mongoose**: An Object Data Modeling (ODM) library for MongoDB and Node.js.
*   **CORS**: For enabling Cross-Origin Resource Sharing.

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You must have the following software installed on your machine:
*   [Node.js](https://nodejs.org/en/) (v14 or higher is recommended)
*   [npm](https://www.npmjs.com/) (Node Package Manager), which comes with Node.js
*   **MongoDB**: You need a running MongoDB database. You can either:
    *   Install it locally on your machine.
    *   Use a cloud service like [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) for a free cloud database.

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/abhishekpatel10/InstaShare.git
    cd YOUR_REPOSITORY_NAME
    ```

2.  **Set up the Backend Server:**
    *   Navigate to the `server` directory:
        ```bash
        cd server
        ```
    *   Install the dependencies:
        ```bash
        npm install
        ```
    *   Create a `.env` file in the `server` directory and add your MongoDB connection string.
        ```
        CONNECTION_URL="your_mongodb_connection_string"
        PORT=5000
        ```
    *   Start the server:
        ```bash
        npm start
        ```
    The server will be running on `http://localhost:5000`.

3.  **Set up the Frontend Client:**
    *   Open a **new terminal window** and navigate to the `client` directory from the root project folder:
        ```bash
        cd client
        ```
    *   Install the dependencies:
        ```bash
        npm install
        ```
    *   Start the client application:
        ```bash
        npm start
        ```
    The React application will open automatically in your browser at `http://localhost:3000`.

You should now have the full-stack application running!

## 📁 Project Structure

The project is organized into two main folders: `client` for the React frontend and `server` for the Node.js backend.

```bash
/
├── client/         # React Frontend
│   ├── public/
│   └── src/
│       ├── actions/
│       ├── api/
│       ├── components/
│       ├── constants/
│       ├── reducers/
│       ├── App.js
│       └── index.js
│
└── server/         # Node.js & Express Backend
    ├── controllers/
    ├── models/
    ├── routes/
    ├── index.js
    └── .env


## 🙌 Contributing

Contributions are welcome! If you have any ideas, suggestions, or find any bugs, please open an issue or submit a pull request.

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
