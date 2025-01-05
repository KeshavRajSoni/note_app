
# Notes App

A simple notes application with **React frontend**, **Node.js backend**, and **MongoDB database**.

## Features
- Create, Read, Update, and Delete (CRUD) notes.
- Search functionality to filter notes by title.
- Responsive design.

## Setup Instructions

### Backend
1. Navigate to the `backend` folder:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file with the following content:
   ```
   MONGO_URI=<your-mongodb-connection-string>
   ```
   Replace `<your-mongodb-connection-string>` with your MongoDB connection string.
4. Start the server:
   ```bash
   npm start
   ```

### Frontend
1. Navigate to the `frontend` folder:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the app:
   ```bash
   npm start
   ```

## Tech Stack
- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
