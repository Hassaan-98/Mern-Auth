# MERN Auth App 🚀

![MERN Stack](https://img.shields.io/badge/MERN_Stack-20232A?style=for-the-badge&logo=javascript&logoColor=61DAFB)  
A full-stack authentication application built with the **MERN stack** (MongoDB, Express.js, React, Node.js). This repository combines both the **frontend** and **backend** code to deliver a secure, scalable user authentication system featuring JWT-based security, email integration via Mailtrap, and a sleek, responsive React-based user interface.

---

## ✨ Features
- **User Authentication**: Register, login, and logout with JWT-based security.
- **Backend API**: RESTful API built with Express.js and MongoDB.
- **Frontend UI**: Responsive React app with modern design.
- **Email Integration**: Uses Mailtrap for testing email functionality.
- **Environment Config**: Securely manage secrets with `.env` files.
- **Password Hashing**: Securely stores passwords using bcrypt.
- **Error Handling**: Robust error messages for a better user experience.

---

## 🛠️ Tech Stack

| Technology       | Icon                                                                 | Description                  |
|------------------|----------------------------------------------------------------------|------------------------------|
| MongoDB          | ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) | NoSQL Database for user data |
| Express.js       | ![Express](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white) | Backend Framework for APIs |
| React            | ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) | Frontend Library for UI      |
| Node.js          | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) | Runtime Environment         |

---


---

## ⚙️ Prerequisites
To run this app locally, ensure you have the following installed:
- ![Node.js](https://img.shields.io/badge/Node.js-16.x+-339933?style=flat-square&logo=nodedotjs&logoColor=white) (Recommended: v16 or higher)
- ![Yarn](https://img.shields.io/badge/Yarn-1.x-2C8EBB?style=flat-square&logo=yarn&logoColor=white) (Alternative: npm)
- A MongoDB instance (local via MongoDB Community Server or cloud-based like MongoDB Atlas)
- A Mailtrap account for email testing (free tier available)

---
--- ## 📂 Project Structure
📂 mern-auth/
│── 📂 backend/                # Express.js API and MongoDB logic  
│   ├── 📂 models/             # Mongoose schemas (e.g., User)  
│   ├── 📂 routes/             # API routes (e.g., auth, users)  
│   ├── 📂 config/             # Database connection and config  
│   └── 📄 server.js           # Entry point for the backend  
│  
│── 📂 frontend/               # React app for the UI  
│   ├── 📂 src/                # React components, hooks, and styles  
│   ├── 📂 public/             # Static assets  
│   └── 📄 package.json        # Frontend dependencies  
│  
├── 📄 .gitignore              # Git ignore file  
└── 📄 README.md               # You're reading it!  
 


## 🚀 Getting Started

### 1. Clone the Repository
Clone this repo to your local machine and navigate into the project directory:
```bash
git clone https://github.com/yourusername/mern-auth-app.git
cd mern-auth-app

```bash
MONGO_URI=your_mongo_uri
PORT=5000
JWT_SECRET=your_secret_key
NODE_ENV=development

MAILTRAP_TOKEN=your_mailtrap_token
MAILTRAP_ENDPOINT=https://send.api.mailtrap.io/

CLIENT_URL= http://localhost:5173
```

### Run this app locally
```shell
yarn install
```

### Start the app

```shell
yarn run dev
```

