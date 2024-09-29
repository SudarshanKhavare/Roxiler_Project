# Roxiler Company Project

## Overview

This project is a RESTful API built with Node.js, Express, and MongoDB. It serves as the backend for the Roxiler Company application, providing various endpoints to manage and interact with the application data.

## Features

- RESTful API architecture
- MongoDB for data storage
- Environment variables using dotenv
- CORS support for cross-origin requests

## Technologies Used

- Node.js
- Express.js
- MongoDB (Mongoose)
- Cors
- dotenv

## Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v12 or later)
- [MongoDB](https://www.mongodb.com/) (or MongoDB Atlas for cloud hosting)

-Navigate to the project directory:
    cd roxiler-main/server

-Install the required packages:
    npm install

-Create a .env file in the root of the server directory and add your MongoDB connection string:
    MONGODB_URI=<your-mongodb-connection-string>
    PORT=8080


#Running the Server
Start the server using Nodemon:
    npx nodemon server.js

#The server will be running on http://localhost:8080. You should see the message:
    Server is running on port 8080


Frontend Technologies
- React
- Ant Design Components
- Chart.js
- Moment
- Axios

Backend Technologies
- Express
- Node
- Mongoose
- MongoDB
- Axios
