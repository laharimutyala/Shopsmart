# ShopSmart

A full-stack e-commerce application built with React.js and Node.js.

## Features

- User Authentication (Login/Register)
- Admin Dashboard
- Product Management
- Shopping Cart
- Order Management
- Responsive Design

## Tech Stack

### Frontend
- React.js
- React Router
- Styled Components
- Bootstrap
- Axios

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication

## Setup Instructions

### Backend Setup
1. Navigate to the Backend directory:
```bash
cd Backend
npm install
```

2. Create a `.env` file with:
```
MONGODB_URI=your_mongodb_connection_string
PORT=5000
```

3. Start the backend server:
```bash
npm start
```

### Frontend Setup
1. Navigate to the Frontend directory:
```bash
cd Frontend
npm install
```

2. Start the frontend development server:
```bash
npm start
```

## Environment Variables
Make sure to set up the following environment variables in your `.env` file:

- `MONGODB_URI`: Your MongoDB connection string
- `PORT`: Backend server port (default: 5000)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
ISC 