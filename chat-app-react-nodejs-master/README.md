# 💬 Snappy - Chat Application  

Snappy is a real-time chat application built with the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**.  
It supports authentication, real-time messaging with **Socket.IO**, and MongoDB persistence.  

---

## 🖼️ Screenshots  

### 🔐 Login Page  
![Login Page](./images/snappy_login.png)  

### 💬 Chat Window  
![Chat Window](./images/snappy.png)  

---

## 🛠️ Tech Stack  

**Frontend**: React, Axios, Tailwind CSS  
**Backend**: Node.js, Express.js, Socket.IO  
**Database**: MongoDB, Mongoose  
**DevOps**: Docker, Docker Compose  

---

## 📂 Project Structure  

chat-app-react-nodejs-master/
│
├── public/ # React frontend
│ ├── src/ # Components & pages
│ └── .env.example
│
├── server/ # Express + Socket.IO backend
│ ├── models/ # Mongoose schemas
│ ├── routes/ # API routes
│ ├── server.js # Entry point
│ └── .env.example
│
├── images/ # Screenshots
├── docker-compose.yml
└── README.md


---

## ⚙️ Installation Guide  

### 🔧 Requirements  
- [Node.js](https://nodejs.org/en/download)  
- [MongoDB](https://www.mongodb.com/docs/manual/administration/install-community/)  

Make sure MongoDB service is running.  

---

### 🖥️ First Method (Manual Setup)  

Clone the repo:  
```bash
git clone https://github.com/Lavraj15/chat-app-react-nodejs-master.git
cd chat-app-react-nodejs-master
Setup environment files:

bash
Copy
Edit
cd public
mv .env.example .env
cd ../server
mv .env.example .env
cd ..
Install dependencies:

bash
Copy
Edit
cd server
yarn
cd ../public
yarn
Run frontend:

bash
Copy
Edit
cd public
yarn start
Run backend (in a new terminal, MongoDB must be running):

bash
Copy
Edit
cd server
yarn start
Now open http://localhost:3000 🎉

🐳 Second Method (Docker Setup)
This requires Docker and Docker Compose.

Build images (no cache):

bash
Copy
Edit
docker compose build --no-cache
Start containers:

bash
Copy
Edit
docker compose up
Access app at: http://localhost:3000

🚀 Future Improvements
✅ Private chats

✅ Group chat support

✅ File & image sharing

✅ Typing indicators & read receipts

✅ Deployment with Nginx reverse proxy

👨‍💻 Author
Developed by Lav Raj 🚀