# Task Manager API

## Description
This is a simple task manager API built with Node.js, Express, MongoDB and Mongoose. The API uses JSON Web Tokens (JWT) for authentication and authorization.

## Prerequisites
`Node.js`
`Express`
`MongoDB`
`Mongoose`
`JSON Web Tokens (JWT)`
`bcryptjs`
`express-validator`
`Postman for API testing`

## Installing
Clone the repository and navigate to the project directory

Run npm install to install all the required dependencies.

Create a .env file in the root directory and add the following environment variables:

PORT: The port on which the API will run.

JWT_SECRET: The secret used to sign JSON Web Tokens.

MONGO_URI: The MongoDB URI to connect to the database.

Run npm start to start the API.

## API Endpoints
**POST /users:** To create a new user.

**POST /users/login:** To log in a user.

**POST /tasks:** To create a new task.

**GET /tasks:** To retrieve all tasks created by the user.

**GET /tasks/:id:** To retrieve a specific task.

**PATCH /tasks/:id:** To update a specific task.

**DELETE /tasks/:id:** To delete a specific task.

Testing
Use Postman to test the API endpoints.
