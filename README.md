# ✨ Full Stack Real-Time Chat App ✨

A polished real-time chat application with a sleek UI and full MERN+Socket.io stack.

---

## 🚀 Highlights

- **Tech Stack**: MongoDB, Express.js, React, Node.js (MERN), plus Socket.io for real-time messaging, TailwindCSS & DaisyUI for styling
- **Authentication**: Secure user sign-up/login with JSON Web Tokens (JWT)
- **Messaging**: Supports text and image messages, powered by Socket.io
- **User Presence**: See who’s online in real time
- **State Management**: Global app state handled via Zustand
- **Media Upload**: Integrates with Cloudinary for image storage
- **Error Handling**: Robust validation and user-friendly error flows on both frontend & backend
- **JWT Authorization**: Backend endpoints secured with access tokens
- **Free Deployment Included**: Deployment to services like Render🌟

---

## 🛠️ Features

- JWT-based authentication & authorization  
- Real-time bidirectional messaging  
- Media (image) upload & storage via Cloudinary  
- Online/offline user status detection  
- Centralized state management with Zustand  
- Graceful error handling  
- Easy deployment instructions

---

## 🔧 Setup Instructions

cd backend
npm install
Front-end:

bash
Copy
Edit
cd ../frontend
npm install
Create .env file in backend/ (and optionally in frontend/ if needed):

env
Copy
Edit
MONGODB_URI=<your MongoDB connection URI>
PORT=5001
JWT_SECRET=<your secret string>
CLOUDINARY_CLOUD_NAME=<cloud name>
CLOUDINARY_API_KEY=<api key>
CLOUDINARY_API_SECRET=<api secret>
NODE_ENV=development
Run locally:

bash
1. **Clone the repo**
   ```bash
   git clone https://github.com/Shashank2985/fullstack-realtime-chat-app.git

cd ../backend
npm run build         # builds backend (if configured)
npm start             # starts backend server

cd ../frontend
npm run build         # builds frontend for production
npm start             # starts React app
Production deployment:

Follow platform-specific guides (Heroku, Vercel, Render)

Ensure all .env values are set in your hosting environment

📦 Project Structure
csharp
Copy
Edit
fullstack-chat-app/
├── backend/            # Node.js API server
│   ├── controllers     # Route logic
│   ├── models          # Mongoose schemas
│   ├── routes          # API routes
│   └── utils           # Helpers: JWT, Cloudinary, error handling
│
├── frontend/           # React client
│   ├── components      # UI pieces (chat window, auth forms, etc.)
│   ├── pages           # Views (login, chat room)
│   └── store           # Zustand slices & state management
│
├── .gitignore
├── LICENSE             # MIT
└── README.md           # This file


🎯 Why This App?
Learning Resource: Demonstrates full-stack integration with real-time features

Modern Tech: Built with up-to-date tools & best practices

Customizable & Extendable: Great base for adding features like:

Group chats

Push notifications

Read receipts

Video/audio chatting
