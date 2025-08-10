# SoleVerse - Sneaker E-commerce Platform

**#Neetlify - Link**

amazing-centaur-cd0415.netlify.app

## Prerequisites

- Node.js (v14 or higher)
- MongoDB (v4.4 or higher)
- Git

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Ansh358/SoleVerse-Fynd.git
cd SoleVerse
```

2. Install dependencies for both frontend and backend:
```bash
# Install root dependencies
npm install

# Install backend dependencies
cd backend
npm install
cd ..
```

3. Set up environment variables:

Create a `.env` file in the backend directory with the following content:
```env
PORT=5000
VITE_BACKEND_URL=http://localhost:5000
MONGODB_URI=mongodb://localhost:27017/soleverse
NODE_ENV=development
FRONTEND_URL=http://localhost:5175
```

4. Start MongoDB:
- Make sure MongoDB is installed and running on your system
- The default connection URL should be: `mongodb://localhost:27017/soleverse`

## Running the Application

1. From the root directory, run both frontend and backend concurrently:
```bash
npm run dev
```

This will start:
- Frontend at: http://localhost:5175
- Backend at: http://localhost:5000

2. Alternatively, you can run them separately:

For frontend only:
```bash
npm run start:frontend
```

For backend only:
```bash
npm run start:backend
```
## Inside the website:
- IMP
- IMP
- IMP
- Firstly SignUp and Login then only you can purchase any product
- Else error will be showing up
- IMP
- IMP
- IMP

## Features

- Browse sneaker collection
- View product details
- Add items to cart
- Checkout process
- Responsive design

## Tech Stack

### Frontend
- React.js
- Vite
- React Router
- Axios
- FontAwesome Icons
- PayPal Integration

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- CORS

## Development

- ESLint is configured for code linting
- Nodemon for backend development
- Concurrently for running multiple scripts

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).
