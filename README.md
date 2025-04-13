# Musika 🎵

<div align="center">
  <img src="./frontend/public/musika-logo.png" alt="Musika Logo" width="200">
  <h3>A Modern Music Player Web Application</h3>
  
  [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
  ![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=white)
  ![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white)
  ![MongoDB](https://img.shields.io/badge/MongoDB-6-47A248?logo=mongodb&logoColor=white)
</div>

## 📋 Overview

Musika is a feature-rich music player web application built with modern technologies. It provides an immersive music listening experience with real-time social features through Socket.IO, secure authentication via Clerk, and an intuitive user interface designed with Tailwind CSS and Shadcn components.

## ✨ Key Features

<div align="center">
  <table>
    <tr>
      <td align="center" width="33%">
        <h3>🎵 Music Playback</h3>
        <p>Seamless playback with intuitive controls for next/previous tracks and volume adjustment</p>
      </td>
      <td align="center" width="33%">
        <h3>💬 Real-Time Chat</h3>
        <p>Engage with other users through an integrated live chat system</p>
      </td>
      <td align="center" width="33%">
        <h3>👤 User Presence</h3>
        <p>See who's online and what they're listening to in real-time</p>
      </td>
    </tr>
    <tr>
      <td align="center" width="33%">
        <h3>🛠️ Admin Dashboard</h3>
        <p>Manage albums and songs through an intuitive admin interface</p>
      </td>
      <td align="center" width="33%">
        <h3>📊 Analytics</h3>
        <p>Track user activity and music listening trends</p>
      </td>
      <td align="center" width="33%">
        <h3>🔒 Secure Authentication</h3>
        <p>Powered by Clerk for safe and seamless user authentication</p>
      </td>
    </tr>
  </table>
</div>

## 🚀 Tech Stack

### Frontend

<div>
  <img src="./frontend/public/icons/react.png" alt="React" width="30" title="React" style="margin-right:10px;"/>
  <img src="./frontend/public/icons/ts.png" alt="TypeScript" width="30" title="TypeScript" style="margin-right:10px;"/>
  <img src="./frontend/public/icons/tailwind.png" alt="Tailwind CSS" width="30" title="Tailwind CSS" style="margin-right:10px;"/>
  <img src="./frontend/public/icons/shadcn.png" alt="shadcn/ui" width="30" title="shadcn/ui" style="margin-right:10px;"/>
  <img src="./frontend/public/icons/zustand.png" alt="Zustand" width="30" title="Zustand" style="margin-right:10px;"/>
</div>

### Backend

<div>
  <img src="./frontend/public/icons/node.png" alt="Node.js" width="30" title="Node.js" style="margin-right:10px;"/>
  <img src="./frontend/public/icons/express.png" alt="Express.js" width="30" title="Express.js" style="margin-right:10px;"/>
  <img src="./frontend/public/icons/mongodb.png" alt="MongoDB" width="30" title="MongoDB" style="margin-right:10px;"/>
  <img src="./frontend/public/icons/socket.png" alt="Socket IO" width="30" title="Socket.IO" style="margin-right:10px;"/>
  <img src="./frontend/public/icons/clerk.png" alt="Clerk" width="30" title="Clerk" style="margin-right:10px;"/>
</div>

## 🛠️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/akosikhada/musika.git
cd musika

# Frontend setup
cd frontend
npm install
cp .env.example .env.local  # Configure your environment variables
npm run dev

# Backend setup (in a new terminal)
cd backend
npm install
cp .env.example .env  # Configure your environment variables
npm run dev
```

## 📝 Environment Setup

### Frontend (.env.local)

```
VITE_API_URL=http://localhost:5000
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
```

### Backend (.env)

```
PORT=5000
MONGODB_URI=your_mongodb_connection_string
CLERK_SECRET_KEY=your_clerk_secret_key
```

## 🎨 UI Design

Musika's interface is inspired by modern music streaming platforms, with a focus on usability and aesthetics.

Design references:

- [Music Stream](<https://www.figma.com/design/SnYTU984TpKqGJ9EBJf0Vn/Music-Stream---Soundcloud-Web-Design-(Community)?node-id=2-2&p=f>)
- [Spotify Music](<https://www.figma.com/design/Zt34g8NAqDUtKMvawHum0C/Spotify-Music-UI-Design-%26-Prototype-(Community)?node-id=101-4&p=f>)
- [Auditica](https://www.figma.com/design/SsgtFJgR2yOcTPmseqi2oG/Auditica?node-id=1-274)

## 📈 Architecture

Musika follows a client-server architecture:

- **Frontend**: React application with TypeScript for type safety
- **Backend**: Node.js server with Express.js for API endpoints
- **Database**: MongoDB for storing user data, songs, and albums
- **Real-time Communication**: Socket.IO for chat and presence features

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgements

Special thanks to the developers and contributors of all the tools and libraries that made Musika possible.

---

<div align="center">
  <sub>Built with ❤️ by akosikhada</sub>
</div>
