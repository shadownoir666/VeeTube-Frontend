# 🎬 VeeTube — Frontend

VeeTube is a **next-generation content platform** that blends the best of **YouTube and Twitter** — allowing users to **upload videos, share tweets, like content, manage playlists, and subscribe to creators**.  
Built using **React + Vite**, it features a sleek **dark mode UI**, **real-time interactions**, and **3D-enhanced visuals** powered by Three.js.  

Developed by **Vansh** 💜

---

- 🛠️ Backend Repo: [VeeTube Backend](https://github.com/vsaini7351/VeeTube-Backend)

## 🌐 Project Overview

VeeTube provides a modern, responsive, and engaging interface for multimedia content sharing.  
It integrates seamlessly with the backend API (Node.js + Express + MongoDB) to handle authentication, uploads, subscriptions, and tweets.

**Core functionalities include:**
- 🎥 Video Upload, Edit & Delete  
- 💬 Tweet Posting & Management  
- ❤️ Like System (Videos & Tweets)  
- 📜 Playlist & Watch History  
- 👤 User Channel Pages  
- 🌌 Immersive Dark Theme  
- ⚡ Smooth Animations via Framer Motion  
- 🧠 State Management with Redux Toolkit  

---

## 🧩 Tech Stack

### **Frontend**
- ⚛️ React 19 (Vite)
- 🎨 Tailwind CSS 4
- 🌀 Framer Motion
- 🔮 Three.js + @react-three/fiber + drei
- 🧭 React Router DOM
- 🧱 Redux Toolkit
- 📅 date-fns
- 🔔 React Hot Toast / Toastify
- 🪶 Axios

### **Backend (Companion Repository)**
- 🚀 Node.js + Express
- 🧩 MongoDB + Mongoose
- 🔐 JWT Authentication
- ☁️ Cloudinary for Media Storage
- 🧂 bcrypt, multer, cookie-parser
- 🌍 CORS + dotenv

---

## 📦 Installation Guide

Follow the steps below to run **VeeTube Frontend** locally.

### **1️⃣ Clone the Repositories**

```bash
# Clone frontend
git clone https://github.com/shadownoir666/VeeTube-Frontend.git
# Clone backend
git clone https://github.com/shadownoir666/VeeTube-Backend.git

```

## 2️⃣ Setup Environment Variables

Make a `.env` file and fill in the required values.

### 🧭 Frontend `.env` example:
```env
VITE_SERVER=http://localhost:8000/api/v1

```

### ⚙️ Backend `.env` example:
```env
PORT=8000
CORS_ORIGIN=*
MONGODB_URI=mongodb+srv://username:password@cluster0.mongodb.net/veetube
ACCESS_TOKEN_SECRET=your_access_token_secret_here
ACCESS_TOKEN_EXPIRY=1d
REFRESH_TOKEN_SECRET=your_refresh_token_secret_here
REFRESH_TOKEN_EXPIRY=10d
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

## ⚙️ Installation & Run Commands

### Frontend Setup
```bash
cd veetube-frontend
npm install
npm run dev
```
Then open http://localhost:5173 in your browser.

### Backend Setup
```bash
cd veetube-backend
npm install
npm run dev
```

The backend will start at http://localhost:8000.


## 🧠 Key Features

- 🎞️ **Video Player** with Like, Share & Playlist options
- 📜 **Tweet Feed** integrated directly in-app
- 👤 **Channel Dashboard** for user uploads and analytics
- 💬 **Real-time Comments System**
- 🖼️ **Cover & Avatar Customization**
- 🌙 **Dark Neon-Themed UI**
- 🧭 **Full Routing & Navigation**

## 📸 Screenshots

| Home Page | Video Player | Your Videos |
|-----------|--------------|---------|
| ![Home Page](/screenshots/home.png) | ![Video Player](/screenshots/player.png) | ![Channel](/screenshots/videos.png) |

| Watch History | Tweets | Comments |
|---------------|--------|----------|
| ![Watch History](/screenshots/watchHistory.png) | ![Tweets](/screenshots/tweet.png) | ![Comments](/screenshots/comment.png) |

| Channel |
|-------------|
| ![Your Videos](/screenshots/channel.png) |


## 🧰 Troubleshooting

| Issue | Solution |
|-------|----------|
| API not responding | Check that the backend is running on the correct port and .env URL matches it |
| Video upload fails | Verify Cloudinary credentials in backend .env |
| Styling not applied | Ensure Tailwind is configured properly in vite.config.js |
| Build fails | Run `npm install` again or delete node_modules and reinstall |

## 💡 Developer

**Vansh** (@shadownoir666)

- 🖤 Creator & Frontend Developer of VeeTube  
- 📧 vansh7351saini@gmail.com

  ## 🚀 Future Enhancements

- 🔴 **Live Streaming Integration**
- 💭 **Real-time Chat / Comments**
- 🎨 **Video Thumbnails & Auto Captions**
- 📈 **Advanced Analytics Dashboard**
- 📱 **Progressive Web App (PWA) Support**


⭐️ Support the Project
If you like VeeTube, please consider giving it a ⭐ on GitHub.
Sharing it with others or contributing would mean a lot!
