# Skyglow Backend Assignment

This is a basic backend server built with Node.js and Express. It handles user registration, login, and limited user data retrieval.

## Getting Started

1. Clone this repository.
2. Install dependencies: `npm install`
3. Create a `.env` file in the project root directory and define the following variables:
    * DB (MongoDB connection string)
    * PORT (server port number) 
4. Run the server: `node server.js`

## API Endpoints

* **POST /register**: Registers a new user.
* **POST /login**: Logins a user and returns a JWT token.
* **GET /users**: Retrieves a list of users (limited data for unauthorized users).

**Note:** To access the `/users` endpoint with full user data, authorization is required

## Deployment

* **Render Deployment**:https://skyglow-backend-assignment.onrender.com/ 
