# 🚀 Social Media Platform Using MERN Stack

Enterprise-grade Social Media Web Application built with the **MERN stack** — **MongoDB**, **Express.js**, **React**, and **Node.js** — designed to emulate real-world social networking capabilities with high performance and scalability.

## 📖 Project Overview

This project implements a full-stack social media platform where users can:

- Register and authenticate securely
- Create, update, and delete posts
- Like/unlike and comment on posts
- Follow and unfollow other users
- View personalized feeds

This repository showcases practical application of RESTful API principles, JWT authentication, and modern front-end state management. :contentReference[oaicite:2]{index=2}

---

## 🧠 Key Features

- **User Authentication & Authorization**
- **Responsive UI with React**
- **REST API with Node & Express**
- **NoSQL Data Persistence with MongoDB**
- **Follow System & Personalized Feeds**
- **Post Interactions (Likes, Comments)**
- **Secure JWT Token-based Sessions**

---

## 📦 Technology Stack

| Layer | Technology |
|-------|------------|
| Frontend | React.JS, Redux (optional), CSS/Material UI |
| Backend | Node.js, Express.js |
| Database | MongoDB (Local or Atlas) |
| Auth | JWT (JSON Web Tokens) |
| API | RESTful Endpoints |

---

## 🛠️ Installation & Setup

### Prerequisites

Ensure the following are installed:

- **Node.js** (v14+)
- **npm / Yarn**
- **MongoDB** (Local or Atlas cluster)

### Local Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Reetkumarbind/Social-Media-Platform-Using-MERN-Stack.git
cd Social-Media-Platform-Using-MERN-Stack


PORT=5000
MONGO_URI=<Your MongoDB URI>
JWT_SECRET=<SecureRandomString>


📁 API Endpoints (Sample)
Method	Endpoint	Description
POST	/api/auth/register	Register a new user
POST	/api/auth/login	Authenticate and login
GET	/api/posts	Get all posts
POST	/api/posts	Create a post
PUT	/api/users/:id/follow	Follow a user
PUT	/api/users/:id/unfollow	Unfollow a user

(Detailed API documentation can be added here or in a separate API.md)
