# TwitKujo — Twitter-Like Social Network

> Academic project developed as part of my Web Technologies course at Sorbonne Université

A full-stack social networking application inspired by Twitter, built with the MERN stack (MongoDB, Express, React, Node.js). The project was an introduction to modern web development covering frontend architecture, REST APIs, authentication, and real-time features.

## 🛠️ Tech Stack

- **Frontend**: React, JavaScript, HTML, CSS
- **Backend**: Express.js, Node.js
- **Database**: MongoDB
- **Tools & Environment**: npm, Docker (optional)

## 📦 Installation & Setup

### Prerequisites

- Node.js 18+
- MongoDB (local or Atlas)
- npm

### Instructions

```bash
# 1. Clone the repository
git clone https://github.com/Tinshea/web-techology.git
cd web-techology

# 2. Install backend dependencies
cd server
npm install

# 3. Install frontend dependencies
cd ../client
npm install

# 4. Start the backend
cd ../server
npm start

# 5. Start the frontend (separate terminal)
cd ../client
npm start
```

## ✨ Features

- User registration and login with JWT authentication
- Tweet creation, reading, and deletion
- Follow / unfollow users
- Personalized feed showing tweets from followed accounts
- User profile pages
- Like and retweet mechanics

## 🗂️ Project Structure

```
web-techology/
├── client/         # React frontend
├── server/         # Express + Node.js REST API
└── docker-compose.yaml
```

## 👤 Author

**Malek Bouzarkouna & Philippe Tan** — Sorbonne Université

## 📄 License

No license specified.
