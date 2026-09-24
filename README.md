MERN Chat Application

A full-stack, real-time messaging application built using the **MERN** stack (**MongoDB**, **Express.js**, **React**, **Node.js**) and **Socket.io**. Designed and developed by **Ayush Kumar**, this platform enables seamless **one-on-one messaging**, **group chats**, and **instant notifications** for offline or inactive users.

### 🔗 Live Demo
[Click here to view the live app](https://mern-chat-app-bg6g.onrender.com)
🔑 Key Features
🔐 Secure Authentication: JWT (JSON Web Tokens) user authentication with password hashing (bcrypt.js).

💬 One-on-One Messaging: Instant private conversations between individual users.

👥 Group Chats: Create, manage, and rename group channels with multiple members.

⚡ Real-Time Messaging: Low-latency message delivery powered by Socket.IO.

🔔 Unread Notifications: Real-time badges and alerts when receiving messages outside the active chat.

🗂 RESTful Backend API: Built using Express and MongoDB with Mongoose for data persistence.

🛠 Tech Stack
Frontend
Framework: React.js

HTTP Client: Axios

Real-time Engine: Socket.IO Client

Styling & UI: Modern CSS / Chakra UI (or custom styling)

Backend
Runtime: Node.js

Framework: Express.js

Database: MongoDB (via Mongoose ODM)

Real-time Engine: Socket.IO

Security: JSON Web Tokens (JWT) & Bcrypt.js

📂 Project Structure
Plaintext
Mern-Chat-Application/
├── backend/
│   ├── config/          # Database connection setup
│   ├── controllers/     # Route business logic (User, Chat, Message)
│   ├── middleware/      # Auth & Error handling middlewares
│   ├── models/          # Mongoose database schemas
│   ├── routes/          # Express API endpoints
│   ├── server.js        # Server entry point & Socket.IO config
│   └── .env             # Environment variables
├── frontend/
│   ├── src/
│   │   ├── components/  # Modular UI components & modals
│   │   ├── Context/     # React Context for Chat & Auth state
│   │   ├── Pages/       # ChatPage & HomePage views
│   │   └── App.js       # Main application entry
│   └── package.json
└── README.md
🚀 Getting Started
Prerequisites
Node.js (v16.x or higher)

MongoDB (Local installation or MongoDB Atlas Connection String)

Git

Installation & Setup
Clone the Repository:

Bash
git clone [https://github.com/Ayush6204/Mern-Chat-Application.git](https://github.com/Ayush6204/Mern-Chat-Application.git)
cd Mern-Chat-Application
Configure Backend Environment:
Create a .env file inside the backend directory:

Code snippet
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
NODE_ENV=development
Install Dependencies:

Bash
# Install backend packages
cd backend
npm install

# Install frontend packages
cd ../frontend
npm install
🏃 Running the Application
Start the Backend Server:

Bash
cd backend
npm start
# or for development mode:
npm run dev
The backend server runs on http://localhost:5000

Start the Frontend Client:

Bash
cd frontend
npm start
The React application runs on http://localhost:3000

📸 Screenshots
Chat Interface & One-on-One Messaging
Group Chat Management & Search
User Profile & Settings
👤 Author & Contact
Developed with ❤️ by Ayush Kumar

GitHub: @Ayush6204

Repository: Mern-Chat-Application
