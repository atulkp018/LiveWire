
# Realtime Full-Stack Chat Application

This project is a fully functional real-time chat application built using the MERN stack, integrated with Socket.io for seamless communication. The app features authentication, online user status, and efficient global state management, making it a scalable and user-friendly chat solution.

## 🚀 Features

- **Tech Stack**: MERN (MongoDB, Express.js, React.js, Node.js) + Socket.io + TailwindCSS + Daisy UI
- **Authentication & Authorization**: Secured with JWT for user authentication
- **Real-time Messaging**: Powered by Socket.io for instant message delivery
- **Online Status Tracking**: Users can see who is online in real time
- **Global State Management**: Zustand is used for efficient state management across the app
- **Error Handling**: Comprehensive error handling on both the client and server sides
- **Cloudinary Integration**: Handles media uploads for profile pictures and shared files
- **Optimized Deployment**: Easily deployable with free hosting solutions

## 🛠️ Getting Started

### 1️⃣ Clone the repository
```shell
git clone https://github.com/yourusername/repo-name.git
cd repo-name
```

### 2️⃣ Install dependencies
```shell
npm install
```

### 3️⃣ Setup environment variables
Create a `.env` file in the root directory and add the following configuration:
```ini
MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

NODE_ENV=development
```

### 4️⃣ Build the app
```shell
npm run build
```

### 5️⃣ Start the server
```shell
npm start
```

## 📌 Additional Notes
- The frontend is built using React and styled with TailwindCSS and Daisy UI.
- WebSockets (via Socket.io) enable real-time communication between users.
- MongoDB stores user data and messages securely.
- Zustand efficiently manages the application's global state.
- The application is structured to support easy scalability and future feature expansion.

Feel free to fork, modify, and enhance this project as needed! 🚀
```
