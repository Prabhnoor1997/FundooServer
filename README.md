# Backend Server for Note Keeping Application

This is the backend server for a note-keeping application. It provides the necessary APIs to create, read, update, and delete notes.

## Features

- RESTful API endpoints for CRUD operations on notes.
- MongoDB for data storage.
- Authentication and authorization using JSON Web Tokens (JWT).
- Error handling and validation.
- Middleware for logging and request parsing.

## Technologies Used

- Express.js: Fast, unopinionated, minimalist web framework for Node.js.
- MongoDB: A popular NoSQL database for flexible and scalable data storage.
- JSON Web Tokens (JWT): For secure authentication and authorization.
- Mongoose: An elegant MongoDB object modeling for Node.js.
- Body-parser: Middleware for parsing incoming request bodies.
- Morgan: HTTP request logger middleware.
- Bcrypt: Library for hashing passwords.
- 
## Getting Started

Follow these instructions to get the project up and running on your local machine.

### Prerequisites

- Node.js and npm must be installed on your machine.
- MongoDB database should be set up.

### Installation

1. Clone the repository:

2. Navigate to the project directory:

2. Navigate to the project directory:

3. Install the dependencies:

4. Set up environment variables:
- Create a `.env` file in the root directory.
- Add the required environment variables, such as the MongoDB connection URL, JWT secret, etc.

5. Start the server:

6. 6. The server should now be running on `http://localhost:3000`.

### API Documentation

The API documentation and available endpoints are described in the [API.md](./API.md) file.

