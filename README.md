<div align="center">

# 🧶 Yarn - Real Time ChatApp

**A modern, real-time messaging platform built for seamless conversations and a stunning user experience.**

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)](https://vitejs.dev/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)](https://socket.io/)
[![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

<br />

> **[🚀 View Live Demo](https://your-live-link.com)** &nbsp; | &nbsp; **[📱 Frontend Repository](https://github.com/yourusername/yarn-frontend)** &nbsp; | &nbsp; **[💻 Backend Repository](https://github.com/yourusername/yarn-backend)**

<br />

<img src="https://media.giphy.com/media/13HgwGsXF0aiGY/giphy.gif" alt="Anime Typing" width="300" />

</div>

---

## 📖 About The Project

**Yarn** is a full-stack, real-time chat application designed to connect people instantly. Unlike traditional chat apps, Yarn features a gorgeous **Glassmorphism UI**, customized **Anime profile avatars**, and buttery-smooth real-time updates powered by WebSockets. 

Whether it's sending a quick message, seeing who's online, or getting a glowing notification for a new chat, Yarn provides a top-tier messaging experience.

---

## ✨ Features

### 🔐 Authentication & Security
*   **JWT Authentication:** Secure login and signup using JSON Web Tokens stored in HTTP-only cookies.
*   **Password Hashing:** Passwords are encrypted using `bcryptjs` before hitting the database.
*   **Protected Routes:** Both frontend and backend routes are protected to ensure only logged-in users can access chats.
*   **Auto-Login:** Persistent sessions using Local Storage and Context API.

### ⚡ Real-Time Capabilities (Socket.io)
*   **Live Messaging:** Messages are delivered instantly without refreshing the page.
*   **Online Status:** Real-time "Green Dot" indicators showing exactly who is online and ready to chat.
*   **Dynamic Updates:** Sidebar and chat windows update dynamically as new messages arrive.

### 🎨 UI/UX & Design
*   **Glassmorphism:** Beautiful frosted-glass effects using Tailwind CSS `backdrop-blur`.
*   **Custom Animations:** Glowing incoming message effects and hover-scaling micro-interactions.
*   **Anime Integration:** Dynamically generated anime avatars based on user gender.
*   **Dark Mode:** A sleek, dark-themed interface optimized for late-night conversations.
*   **Responsive Layout:** Custom scrollbar styling and mobile-friendly flexbox layouts.

### 🧠 State Management & Performance
*   **Zustand:** Lightweight, lightning-fast global state management for conversations and messages.
*   **React Context:** Used for global Auth state.
*   **Custom Hooks:** Abstracted API fetching and error handling into reusable hooks (`useLogin`, `useSignup`, `useSendMessage`, etc.).
*   **Toast Notifications:** Beautiful, non-blocking alerts using `react-hot-toast`.

---

<div align="center">
  <img src="https://media.giphy.com/media/d2lcHJTG5Tscg/giphy.gif" alt="Anime Happy" width="200" />
</div>

---

## 🛠️ Tech Stack

**Frontend:**
*   **React (Vite):** Fast, modern frontend framework.
*   **Tailwind CSS & DaisyUI:** For rapid, responsive, and beautiful UI styling.
*   **Zustand:** Simplified state management.
*   **Socket.io-client:** For real-time WebSocket connections.
*   **React Router DOM:** For seamless client-side routing.

**Backend:**
*   **Node.js & Express:** Scalable server environment.
*   **MongoDB & Mongoose:** NoSQL database for flexible data models.
*   **Socket.io:** WebSocket server for bidirectional communication.
*   **JWT & Cookie-Parser:** Secure authentication.
*   **Bcryptjs:** Password encryption.

---

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites
*   Node.js installed on your machine.
*   A MongoDB database (Local or Atlas).

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/yarn-chatapp.git
   cd yarn-chatapp
