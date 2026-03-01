# 🚀 Future_fs_01
Personal Portfolio Website
# 🚀 Overview
This is my personal full-stack portfolio website built to showcase my skills, projects, and development experience.
The website includes a responsive frontend and a backend-powered contact form for handling user inquiries.
It demonstrates real-world full-stack architecture, API integration, and deployment workflow.

## 🚀 Live Demo
**Frontend:** https://future-fs-01-brown.vercel.app
---

## 🛠 Tech Stack

| Layer | Technology |
|-------|-----------|
| **Frontend** | React + Vite (Deployed on Vercel) |
| **Backend** | Node.js + Express (CORS configured, Deployed on Render) |
| **Database** | MongoDB Atlas |

## 📁 Project Structure
```
Future_fs_01/
│
├── portfolio-frontend/        # React Vite App
│
├── portfolio-backend/         # Express Backend
│   ├── server.js
│   ├── db.js
│   ├── routes/
│   │   └── contactRoute.js
│   ├── models/
│   │   └── Contact.js
│
└── README.md
```

## ⚙️ Getting Started Locally

### 🔷 Backend Setup

```bash
cd portfolio-backend
npm install
```

Create a \`.env\` file inside \`portfolio-backend\` and add:

```env
MONGO_URI=your_mongodb_connection_string
```

Then run:

```bash
node server.js
```

### 🔷 Frontend Setup

```bash
cd portfolio-frontend
npm install
npm run dev
```


## 📌 Features

- Responsive dark-themed UI
- Contact form integrated with MongoDB
- REST API built using Express
- Full-stack deployment (Vercel + Render)
