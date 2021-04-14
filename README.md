# POS
A cross-platform point of sale system using electron and the MERN stack.

# Development Setup

### Running the Frontend and Backend together

Install the required dependencies in the root project directory.

```
yarn install
```

### The Frontend

Install the required dependencies for the frontend, in the frontend directory.

```
cd frontend && yarn install
```

### The Backend

Install the required dependencies for the backend, in the backend directory.

```
cd backend && yarn install
```

### The Database

This project uses MongoDB, a NoSQL, document-oriented database program. You are required to install
MongoDB Community Edition (v4.4) from https://www.mongodb.com/ for this software to work.

### Running the POS Program

To run the program, simply run ```npm start``` from the root project directory. This will concurrently launch both the backend and frontend.
Alternatively, you can choose to run the backend in its own process ```cd backend && npm run dev```, and the frontend in its own process ```cd frontend && npm start```.
