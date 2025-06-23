# 💬 MERN Stack Real-Time Chat Application

A full-stack real-time chat application built with the **MERN Stack** (MongoDB, Express, React, Node.js), powered by **Socket.IO** for live messaging and **Cloudinary** for image uploads and media storage.
---

## ✨ Features

### ✅ Core Features:
- Real-time messaging with **Socket.IO**
- One-to-one chats
- User authentication (Register/Login)
- Online/offline user status indicators
- Image sharing in chat (via **Cloudinary**)
- Chat history with persistent messages
- Mobile-responsive design

### 🔐 Authentication:
- Secure user login & registration
- **JWT-based authentication**
- Password hashing with **Bcrypt**

### 📸 Media Support:
- Upload and share images in chat using **Cloudinary**
- Profile picture uploads and updates

## Tech Stack

### 🖥️ Frontend:
- **React.js** with **React Router**
- **Axios** for API requests
- **Tailwind CSS** or **CSS Modules** for styling
- **Socket.IO Client** for real-time events

### ⚙️ Backend:
- **Node.js** with **Express.js**
- **MongoDB** with **Mongoose**
- **Socket.IO** for real-time communication
- **JWT** for authentication
- **Cloudinary** for image uploads
- **Bcrypt** for password security
- **dotenv**, **Cors**, etc.

## Setup Instructions

### Prerequisites:

- Node.js and npm installed
- MongoDB installed or a cloud MongoDB database (MongoDB Atlas)

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/abhishekrajsingh25/QuickChat-Chat-App.git
   cd QuickChat-Chat-App
   ```

2. **Install Backend Dependencies**
   ```bash
   cd server
   npm install
   ```

3. **Install Frontend Dependencies**
   ```bash
   cd ../client
   npm install
   ```
   
4. **Environment Variables Setup**
   Create a .env file in the root directory of the backend with the following:
   ```bash
   MONGODB_URI = your_mongo_database_uri
   JWT_SECRET = your_jwt_secret_key
   CLOUDINARY_NAME=  your_cloudinary_cloud_name
   CLOUDINARY_API_KEY = your_cloudinary_api_key
   CLOUDINARY_SECRET_KEY = your_cloudinary_api_secret
   ```

5. **Environment Variables Setup**
   Create a .env file in the root directory of the frontend with the following:
   ```bash
   VITE_BACKEND_URL = "http://localhost:5000"
   ```
   
### Running the Application

1. **Start the Backend Server**
   ```bash
   cd backend
   npm run dev
   ```
   The backend server should now be running on `http://localhost:5000`.

2. **Start the Frontend**
   ```bash
   cd ../frontend
   npm run dev
   ```
   The frontend should now be running on `http://localhost:5173`.

## Deployment

- The frontend can be deployed using Vercel.
- The backend can be deployed using Vercel.
- MongoDB can be hosted on MongoDB Atlas.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Submit a pull request.

---

Feel free to contribute, suggest features, or open issues.

---

Thank you for visiting. I hope you find my work interesting and valuable! To see the Website. 
- For Frontend, Click <a href="https://quickchat-chatapp-abhishek.vercel.app/" >Here</a>.
