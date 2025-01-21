## Invigilation Management System

The **Invigilation Management System** serves as a centralized repository for securely storing and tracking invigilation records of teaching staff in an educational institution. Authorized users can efficiently access and search the database for specific staff members' invigilation schedules and assignments. This digital solution eliminates manual paperwork, saving time and promoting transparency.

## Features
- **Centralized Record Management**: Store all invigilation records in a secure, easily accessible database.
- **Search Functionality**: Quickly search for specific staff members and view their invigilation schedules.
- **Role-Based Access**: Ensure only authorized users can access or modify records.
- **Security**: Enhanced security using **JWT Web Tokens** for authentication and secure data access.
- **Efficiency**: Eliminate manual paperwork and streamline administrative processes.

## Technologies Used
### Frontend
- **React.js**: For building an interactive and user-friendly interface.
- **CSS**: For styling and ensuring responsive design.

### Backend
- **Node.js**: For creating a robust server-side application.
- **Express.js**: For building RESTful APIs to handle data requests and responses.

### Database
- **MongoDB**: For securely storing invigilation records and user data.

### Authentication
- **JWT (JSON Web Tokens)**: For secure user authentication and session management.

## How to Use
### Prerequisites
- Node.js installed on your system
- MongoDB server running
- A modern web browser for accessing the frontend

### Installation
```bash
# Clone the repository
git clone <repository-url>
cd teacher-invigilation-tracking-system

# Install dependencies for the backend and frontend
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install

# Set up environment variables
# Create a .env file in the backend directory
# Add the following variables:
PORT=5000
MONGO_URI=<Your MongoDB Connection String>
JWT_SECRET=<Your Secret Key>

# Start the development servers
# Start backend server
cd backend
npm start

# Start frontend server
cd ../frontend
npm start
```

### Usage
1. Open your browser and navigate to `http://localhost:3000`.
2. Log in with your authorized credentials.
3. Use the dashboard to:
   - Add or update invigilation records.
   - Search for specific teaching staff and view their schedules.





