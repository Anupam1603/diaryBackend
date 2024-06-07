# Introduction
- myDiary is a backend service designed for writing, storing, and managing personal notes. It includes robust authentication mechanisms to ensure your notes are secure and private.

## Features
- Create, Read, Update, and Delete Notes: Full CRUD functionality for managing notes.
- User Authentication: Secure user registration and login.
- Secure Storage: Notes are stored securely with user-specific access.
- Token-Based Authentication: Uses JWT for maintaining sessions.
## Technologies Used
- Node.js: Runtime environment.
- Express: Web framework for Node.js.
- MongoDB: Database for storing notes and user information.
- Mongoose: ODM for MongoDB.
- JWT (JSON Web Tokens): For authentication.
- bcrypt: For password hashing.
## Installation
### Prerequisites
- Node.js (v14 or later)
- MongoDB

### Steps
 - Clone the repository

```
git clone https://github.com/your-username/myDiary.git
cd myDiary

```
- Install Dependencies
```
npm Install
```
- Set up environment variables:
 Create a .env file in the root directory and add the following:
 ```
 PORT=3000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```
## Configuration
- The application can be configured using environment variables. The primary configurations include:

- PORT: The port on which the server will run.
- MONGODB_URI: The URI for connecting to the MongoDB database.
- JWT_SECRET: The secret key for signing JWT tokens.
