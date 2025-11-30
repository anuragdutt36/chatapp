```md
# 💬 Real-Time Chat Application (MERN Stack)

A fully functional **real-time one-on-one chat application** built using the **MERN Stack** and **Socket.IO**.  
This ChatApp includes **secure authentication**, **emoji support**, **dynamic avatars**, **online/offline status**, and **modern UI components** using Tailwind CSS and DaisyUI.

This project was created as part of my full-stack development learning journey.

---

## 🚀 Features

- 🔐 **JWT Authentication**
- 🔑 **Secure Password Hashing** (bcryptjs)
- 💬 **Real-Time Messaging** using Socket.IO
- 😀 **Emoji Support**
- 👤 **Dynamic Avatar Generator**
- 🟢 **Online User Indicator**
- 🔍 **Search Users to Start Chat**
- 🍪 **HTTP-Only Cookies for Security**
- 📱 **Fully Responsive Design**
- 🗂 **MongoDB Atlas Cloud Database**
- ⚡ **Fast & Lightweight UI**

---

## 🛠️ Tech Stack

### **Frontend**
- React.js  
- Tailwind CSS  
- DaisyUI  
- Emoji Picker  
- Axios  

### **Backend**
- Node.js  
- Express.js  
- Socket.IO  
- JWT  
- bcryptjs  
- Cookie-parser  
- CORS  

### **Database**
- MongoDB  
- MongoDB Atlas  

### **Tools & Services**
- VS Code  
- Nodemon  
- Git & GitHub  
- Avatar API  
  - 👦 `https://avatar.iran.liara.run/public/boy?username=${username}`  
  - 👧 `https://avatar.iran.liara.run/public/girl?username=${username}`  

```

---
### 📦 Installation & Setup
### **1️⃣ Clone the Respositiry**

```bash
git clone <your-repo-link>
cd ChatApp
```

---

### **2️⃣ Backend Setup**


```bash
cd backend
npm install
npm start
```

---

Create a `.env` file inside `backend`:

```
MONGODB_URI=your_mongodb_atlas_url
JWT_SECRET=your_secret_key
PORT=5000
```

---

### **3️⃣ Frontend Setup**

```bash
cd ../frontend
npm install
npm run dev
```

---

## 🔌 How Real-Time Chat Works

This ChatApp uses **Socket.IO** WebSockets.
When a user sends a message:

1. The message is emitted through Socket.IO
2. Server broadcasts it to the correct user room
3. The UI updates instantly without refresh

This achieves **fast, real-time communication**.

---

## 🔮 Future Enhancements

* 🧑‍🤝‍🧑 Group Chats
* 📤 Image & File Sharing
* 🔔 Push Notifications
* 🌓 Dark/Light Mode
* 🛡️ Two-Factor Authentication
* 📊 Message Analytics

---

## ⭐ Support the Project

If you like this project, please ⭐ the repository!
Your support motivates me to build more awesome projects.
