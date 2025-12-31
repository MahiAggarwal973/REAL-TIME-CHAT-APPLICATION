PROJECT TITLE:
##Real-Time Chat Application (MERN Stack):
A full-stack Real-Time Chat Application built using the MERN stack with Socket.IO for instant messaging. This project demonstrates real-time communication, authentication, and scalable full-stack development practices.

##Features:
1.User Authentication (Login & Signup)
2.Real-time one-to-one messaging
3.Online / Offline user status
4.Instant message delivery using Socket.IO
5.User list with active chats
6.Responsive UI
7.Secure password hashing
8.MongoDB database integration

##Tech Stack:
1.Frontend:
-React.js
-Context API
-Axios
-CSS / Tailwind (if used)
2.Backend:
-Node.js
-Express.js
-Socket.IO
3.Database:
-MongoDB
-Mongoose
4.Authentication & Security:
-JWT (JSON Web Tokens)
-bcrypt.js

##Project Structure:
REAL-TIME-CHAT-APPLICATION
│
├── client/          # React frontend
│   ├── src/
│   └── public/
│
├── server/          # Node.js backend
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── socket/
│
├── .env
├── package.json
└── README.md

##Installation & Setup:
1.Clone the Repository:
-git clone https://github.com/MahiAggarwal973/REAL-TIME-CHAT-APPLICATION.git
-cd REAL-TIME-CHAT-APPLICATION
2.Backend Setup:
-cd server
-npm install
3.Start the backend server:
-npm run dev
4.Frontend Setup:
-cd client
-npm install
-npm start

##Application Flow:
1.User registers or logs in
2.JWT token is generated for authentication
3.User connects to Socket.IO server
4.Messages are sent & received in real time
5.Messages are stored in MongoDB
6.Online users are updated instantly

##What I Learned From This Project:
1.Implementing real-time communication using Socket.IO
2.Structuring a scalable MERN application
3.Handling authentication and authorization
4.Managing global state in React
5.Working with REST APIs and WebSockets
6.Debugging and deploying full-stack applications

##Future Improvements:
1.Group chats
2.File & image sharing
3.Push notifications
4.Typing indicators
5.Voice / Video chat

##AUTHOR
Mahi Aggarwal
GitHub: @MahiAggarwal973
