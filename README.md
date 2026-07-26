# Chat Live 💬

Chat Live is a real-time messaging application that lets users sign up, log in securely, and exchange messages instantly. Built with a Socket.io-powered backend for live message delivery and a React frontend for a responsive chat experience.

---
## 🚀 Tech Stack

**Frontend:**
- React.js
- Socket.io-client

**Backend:**
- Node.js + Express.js
- Socket.io (real-time, bidirectional communication)
- MongoDB + Mongoose
- bcrypt (password hashing)
- JWT-based authentication
- CORS, dotenv

---
## ✨ Features

- Real-time messaging with instant delivery via Socket.io (no polling/refresh needed)
- Secure user authentication with hashed passwords (bcrypt)
- User-to-user chat with persistent message history stored in MongoDB
- RESTful API for user and conversation management
- Clean, responsive chat UI

---
## ⚡ Installation & Setup

1) **Clone the repository**
   ```
   git clone https://github.com/abhiiishekj-max/Chat-App.git
   cd Chat-App
   ```

2) **Setup Backend**
   ```
   cd server
   npm install
   ```
   Create a `.env` file in the `server` folder with:
   ```
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   ```
   Run the backend:
   ```
   npm start
   ```

3) **Setup Frontend**
   ```
   cd ../client
   npm install
   ```
   Create a `.env` file in the frontend folder with:
   ```
   REACT_APP_BACKEND_URL=http://localhost:5000
   ```
   Run the frontend:
   ```
   npm start
   ```

4) Open `http://localhost:3000` in your browser. The app connects to the backend over a Socket.io connection for real-time updates.

---
