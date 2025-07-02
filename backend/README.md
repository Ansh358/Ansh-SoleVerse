# SoleVerse Backend

## Overview
This is the backend server for the SoleVerse e-commerce platform. It provides RESTful APIs for product management, cart operations, and user interactions.

## Tech Stack
- Node.js
- Express.js
- MongoDB with Mongoose
- CORS for cross-origin resource sharing

## Project Structure
```
├── models/          # Database models
├── routes/          # API routes
├── server.js        # Main server file
├── package.json     # Dependencies and scripts
└── .env            # Environment variables
```

## Environment Variables
Create a `.env` file in the backend directory with these variables:
```env
PORT=5000
VITE_BACKEND_URL=http://localhost:5000
MONGODB_URI=mongodb://localhost:27017/soleverse
NODE_ENV=development
FRONTEND_URL=http://localhost:5175
```

## API Endpoints

### Customer Routes
- `GET /api/customers` - Get all customers
- `POST /api/customers` - Create a new customer
- `GET /api/customers/:id` - Get customer by ID
- `PUT /api/customers/:id` - Update customer
- `DELETE /api/customers/:id` - Delete customer

## Setup Instructions

1. Install dependencies:
```bash
npm install
```

2. Start MongoDB:
Ensure MongoDB is running locally at `mongodb://localhost:27017`

3. Start the server:
```bash
# Development mode with nodemon
npm run dev

# Production mode
npm start
```
4. Inside the website:
```
   Firstly Signup and Login then only you can purchase any product
```
## Development
- Uses nodemon for automatic server restart during development
- Environment variables for configuration
- CORS enabled for frontend communication

## Error Handling
- Proper error handling middleware
- Validation for request data
- Appropriate HTTP status codes

## Security
- Environment variables for sensitive data
- CORS configuration for secure communication
- Input validation and sanitization
