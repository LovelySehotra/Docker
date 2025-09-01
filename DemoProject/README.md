# User Management Project

## Overview
This is a simple full-stack project where users can be created and listed.

## Backend
- Built with Node.js, Express, and MongoDB.
- Uses Mongoose for MongoDB connection and schema definition.
- Provides two API routes:
  - POST /api/users → Create a user (name, email).
  - GET /api/users → Get all users.

### Setup and Run Backend
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Make sure MongoDB is running locally on default port 27017.
4. Start the backend server:
   ```bash
   npm start
   ```

## Frontend
- Built with HTML, CSS, and plain JavaScript.
- Uses Axios to call backend APIs.
- Form to add a user (name + email).
- Displays the list of created users in a table.

### Setup and Run Frontend
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Open `index.html` in a web browser (no build step required).

## Notes
- Backend server runs on port 3000 by default.
- Frontend expects backend API at `http://localhost:3000/api/users`.

