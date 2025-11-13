# Express Chat App

This is a full-stack real-time chat application built with the PERN stack (PostgreSQL, Express, React, Node.js).

## Technologies Used

### Backend

- Node.js
- Express
- PostgreSQL
- Prisma
- Socket.io
- TypeScript
- JWT for authentication
- bcryptjs for password hashing
- cookie-parser for cookie management

### Frontend

- React
- Vite
- TypeScript
- Tailwind CSS
- DaisyUI
- Zustand for state management
- React Router for routing
- socket.io-client for real-time communication

## How to Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Matviidev/ExressReactChat
   cd ExressReactChat
   ```

2. **Install dependencies for both backend and frontend:**

   ```bash
   npm install
   ```

3. **Set up your environment variables:**

   - Create a `.env` file in the `backend` directory.
   - Add the following environment variables:
     ```
     DATABASE_URL="postgresql://your_db_user:your_db_password@localhost:5432/your_db_name"
     JWT_SECRET="your_jwt_secret"
     NODE_ENV="development"
     PORT=5000
     ```

4. **Run the application:**
   - **Development:**
     ```bash
     npm run dev
     ```
   - **Production:**
     ```bash
     npm run build
     npm start
     ```

## Live Demo

A live demo of the application is available at [https://exressreactchat.onrender.com/](https://exressreactchat.onrender.com/).
