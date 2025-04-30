# 💬 Real-time Chat Application

A full-stack real-time chat application built with the MERN stack (MongoDB, Express.js, React, Node.js), featuring real-time communication using Socket.io. This app includes user authentication, private/group chat, responsive UI with TailwindCSS + DaisyUI, Zustand for global state, and JWT for secure auth.

---

## 📌 Project Setup Instructions

### 🛠 Prerequisites

- Node.js (v16+ recommended)
- MongoDB (local or MongoDB Atlas)
- Git

---

### ⚙️ Installation Steps

#### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/realtime-chat-app.git
cd realtime-chat-app
```
2. Set up Backend
```bash
cd backend
npm install
```
Create a .env file inside /server and add:
env
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
CLIENT_URL=http://localhost:5173
To run the backend:

```bash
npm run dev
```
3. Set up Frontend
```bash
cd ../frontend
npm install
npm run dev
```
Visit the app at: http://localhost:5173

🧩 Dependencies
Frontend
React
TailwindCSS + DaisyUI
Socket.io-client
Zustand
Axios
React Router DOM

Backend
Express
Mongoose
Socket.io
bcryptjs
jsonwebtoken
dotenv
cors

![Screenshot 2025-04-23 134501](https://github.com/user-attachments/assets/de5b0dfd-95b7-4f54-a066-6eb30ed202ac)


🧪 Features
✅ User Authentication (Signup/Login)

✅ Real-time Messaging via Socket.io

✅ One-to-One Chat

✅ Group Chat Support

✅ Online/Offline Status

✅ Zustand State Management

✅ Light/Dark Mode (DaisyUI)

✅ Responsive Design (Mobile-Friendly)
