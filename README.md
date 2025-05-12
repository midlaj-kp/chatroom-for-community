# 🗨️ Real-Time Chatroom with File Sharing

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)

> A real-time chatroom built with **Node.js**, **Socket.io**, and **Express** featuring **live messaging** and **file sharing** capabilities. Ideal for learning WebSockets, file handling, and real-time systems.

---

## 📌 Table of Contents

- [About the Project](#-about-the-project)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Installation](#-installation)
- [Usage](#-usage)
- [File Sharing](#-file-sharing)
- [Project Structure](#-project-structure)
- [Screenshots](#-screenshots)
- [Contributing](#-contributing)
- [License](#-license)

---

## 📖 About the Project

This Node.js chatroom enables users to communicate in real time and securely share files with others in the same room. It uses **Socket.io** for WebSocket communication and optionally **Multer** or **Base64 encoding** for file transfers.

---

## ✨ Features

- 🔄 Real-time chat using WebSockets  
- 👥 Multi-user environment  
- 🛎️ User join and leave notifications  
- 📁 File sharing (images, docs, etc.)  
- 🧾 File download for all participants  
- 🌐 Responsive frontend  

---

## ⚙️ Tech Stack

**Frontend:**
- HTML
- CSS
- JavaScript

**Backend:**
- Node.js
- Express.js
- Socket.io
- Multer (for file uploads)

---

## 🛠️ Installation

1. **Clone the repo:**
   ```bash
   git clone https://github.com/yourusername/nodejs-chatroom.git
   cd nodejs-chatroom
   ```

2. **Install dependencies:**
   ```bash
   npm install socket.io multer express
   ```

3. **Start the server:**
   ```bash
   node server.js
   ```

4. **Visit in browser:**
   ```
   http://localhost:3000
   ```

---

## 🚀 Usage

- Enter your username to join the chat.  
- Start sending messages instantly.  
- Use the file upload button to share files with others.  

---

## 📁 File Sharing

- Supported file types: `.jpg`, `.png`, `.pdf`, `.docx`, etc.
- Files are either:
  - Temporarily stored on the server using `Multer`, **or**
  - Shared via Base64 encoding through WebSocket
- Other users receive a **download link** or **preview** depending on file type.

---

## 📁 Project Structure

```
nodejs-chatroom/
├── public/
│   ├── join
│   ├── main
│   ├── create
│   ├── chat
│   ├── uploads
│   ├── style.css
│   ├── script.js        
├── uploads/            
├── server.js               
├── package.json
└── README.md
```

---

## 📸 Screenshots

<!-- Replace these with actual screenshots -->
- **Chat UI**  
  ![Chat UI](https://github.com/midlaj-kp/chatroom-for-community/blob/main/chat.png)

- **Other**  
  ![png](https://github.com/midlaj-kp/chatroom-for-community/blob/main/login.png)
  ![png](https://github.com/midlaj-kp/chatroom-for-community/blob/main/main.png)
  ![png](https://github.com/midlaj-kp/chatroom-for-community/blob/main/create.png)
  ![png](https://github.com/midlaj-kp/chatroom-for-community/blob/main/join.png)
---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to fork the repo and submit a pull request.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙏 Acknowledgements

- [Node.js Docs](https://nodejs.org/en/docs/)
- [Socket.io Docs](https://socket.io/docs/)
- [Multer for File Uploads](https://github.com/expressjs/multer)
