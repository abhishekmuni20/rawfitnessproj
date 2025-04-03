# Raw Fitness - MERN Stack Application

A full-stack gym management website built with MongoDB, Express.js, React.js, and Node.js for Raw Fitness.

## Features

- User authentication (register/login)
- Membership management
- Class scheduling
- Trainer profiles
- Responsive design
- Modern UI with Material-UI

## Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd raw-fitness
```

2. Install backend dependencies:
```bash
npm install
```

3. Install frontend dependencies:
```bash
cd client
npm install
```

4. Create a `.env` file in the root directory with the following variables:
```
PORT=5000
MONGODB_URI=mongodb://localhost:27017/raw-fitness
JWT_SECRET=your-super-secret-key-here
NODE_ENV=development
```

5. Start the development server:
```bash
# From the root directory
npm run dev:full
```

This will start both the backend and frontend servers concurrently.

## Project Structure

```
raw-fitness/
├── client/                 # React frontend
│   ├── public/
│   └── src/
│       ├── components/     # Reusable components
│       ├── pages/         # Page components
│       └── App.js         # Main App component
├── models/                # MongoDB models
├── routes/               # API routes
├── server.js            # Express server
└── package.json         # Backend dependencies
```

## API Endpoints

- POST /api/auth/register - Register a new user
- POST /api/auth/login - Login user
- GET /api/memberships - Get all membership plans
- GET /api/classes - Get all classes
- GET /api/trainers - Get all trainers

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is licensed under the MIT License. 