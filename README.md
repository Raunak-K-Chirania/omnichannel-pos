# Omnichannel POS System

A scalable full-stack Omnichannel POS system built with Node.js, Express, TypeScript, MongoDB, and Redis.

## 🚀 Features

- JWT Authentication
- Role-Based Access Control (RBAC)
- Multi-store Management
- Product & Inventory Management
- Order Management
- Dockerized Development Setup
- REST API Architecture
- TypeScript Support

## 🛠️ Tech Stack

- Node.js
- Express.js
- TypeScript
- MongoDB + Mongoose
- Redis
- JWT
- Bcrypt
- Docker
- Docker Compose
- ESLint
- Vitest

## 📁 Folder Structure

```bash
omnichannel-pos/
├── client/
├── server/
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── types/
│   │   ├── utils/
│   │   ├── app.ts
│   │   └── server.ts
├── docker-compose.yml
└── README.md
```

## ⚙️ Environment Variables

Create a `.env` file inside `server/`.

```env
PORT=5000
MONGO_URI=mongodb://localhost:27017/omnichannel-pos
REDIS_URL=redis://localhost:6379
JWT_SECRET=your_secret_key
JWT_EXPIRES_IN=7d
NODE_ENV=development
```

## 🐳 Docker Setup

```bash
docker-compose up -d
```

To stop containers:

```bash
docker-compose down
```

## 📦 Installation

```bash
git clone https://github.com/Raunak-K-Chirania/omnichannel-pos.git
cd omnichannel-pos
cd server
npm install
```

## ▶️ Run Server

```bash
npm run dev
```

Server runs on:

```bash
http://localhost:5000
```

## 🔐 Authentication Routes

| Method | Route | Description |
|---|---|---|
| POST | /api/auth/register | Register user |
| POST | /api/auth/login | Login user |
| GET | /api/auth/me | Get logged-in user |

## 🌿 Git Workflow

```bash
git checkout -b feat/feature-name
git add .
git commit -m "feat: add authentication"
git push -u origin feat/feature-name
```

## ✅ Week 1 Goals

- Docker setup completed
- MongoDB and Redis connected
- All schemas created
- JWT authentication implemented
- RBAC middleware added
- Auth routes working
- GitHub workflow followed
