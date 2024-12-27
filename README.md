
**PRAKASH V**  
**Company**: CODETECH IT SOLUTIONS  
**Id**: CT08ECB  
**Domain**: Full Stack Web Development  
**Duration**: Dec 17th 2024 to Jan 17th, 2025


# Real-Time Chat Application
This repository contains a real-time chat application with features such as user authentication, chat rooms, private messaging, and real-time communication using React for the frontend and Node.js with Socket.io for the backend.

---

## Features

### User Authentication
- Secure login and registration with hashed passwords.
- JWT-based authentication for maintaining user sessions.

### Real-Time Messaging
- Powered by Socket.io for low-latency communication.
- Instant updates across clients.

### Chat Rooms
- Public and private chat rooms.
- Create and join rooms with dynamic room-based segregation.

### Private Messaging
- Direct one-on-one conversations with other users.
- Real-time notifications for new messages.

### Persistent Chat History
- Messages stored in a database (e.g., MongoDB).
- History retrieval for both chat rooms and private chats.

### Online User Tracking
- Live updates of online users.
- Dynamic user availability status.

---

## Tech Stack

### Frontend
- **React** for building the user interface.
- **Tailwind CSS** for responsive design and styling.
- **Zustand** for state management.

### Backend
- **Node.js** with **Express.js** for APIs and server logic.
- **Socket.io** for WebSocket-based real-time features.
- **MongoDB** as the database solution.

### Additional Libraries
- **React Router** for routing.
- **Toastify** for user-friendly notifications.
- **Axios** for API requests.

---

## Installation

### Prerequisites
- **Node.js** (v14 or higher)
- **MongoDB** or **MongoDB Atlas**

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/real-time-chat-application.git
   ```
2. Navigate to the project directory:
   ```bash
   cd real-time-chat-application
   ```
3. Install dependencies for the backend:
   ```bash
   cd backend
   npm install
   ```
4. Install dependencies for the frontend:
   ```bash
   cd ../frontend
   npm install
   ```
5. Set up environment variables:
   - Create a `.env` file in the `backend` directory with the following:
     ```env
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```
6. Start the backend server:
   ```bash
   cd backend
   npm start
   ```
7. Start the frontend server:
   ```bash
   cd ../frontend
   npm start
   ```
8. Open your browser and navigate to `http://localhost:3000` to access the application.

---

## Contributions
Contributions are welcome! Feel free to fork the repository, create a feature branch, and submit a pull request.

---

## License
This project is licensed under the [MIT License](LICENSE).

---






# OutPut images




