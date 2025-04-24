# 💬 WhatsApp-Style Real-Time Chat App

This is a **real-time chat application** that mimics WhatsApp-style messaging. The frontend is built using **React.js** (not React Native), and the backend uses **Node.js with Socket.IO and Express** for real-time communication. A **dummy user login system** allows two users to simulate chatting in different browser tabs.

---

## 🌟 Features Implemented

### ✅ 1. React Frontend (Not React Native)
- Created using **React.js**.
- Users can open the chat in two tabs as "User 1" and "User 2" to simulate a conversation.
- WhatsApp-style chat design:
  - Messages are styled like chat bubbles.
  - Messages are aligned left/right based on the user.
  - Greenish background color like WhatsApp.
  - Input box centered at the bottom of the chat container.
  
### ✅ 2. Node.js Backend with Express + Socket.IO
- Built a backend server using **Node.js** and **Express**.
- Integrated **Socket.IO** to allow real-time communication between users.
- Handled:
  - Message sending (`POST`)
  - Message receiving (`GET`)
  - Broadcasting via sockets to other connected clients

### ✅ 3. Dummy User Login System
- Instead of complex authentication, a **simple dummy login** was implemented:
  - User enters their name to join.
  - This helps simulate "User 1" and "User 2" chatting.
- Username is attached to each message for clarity.

---

## 🧰 Tech Stack Used

| Layer       | Technology         |
|-------------|--------------------|
| Frontend    | React.js (not React Native) |
| Styling     | CSS (WhatsApp-inspired)     |
| Backend     | Node.js, Express.js, Socket.IO |
| Version Control | Git & GitHub     |

---

## 📸 UI Overview

> You can open the app in two tabs:
> - Tab 1: Login as **User 1**, send “Hello”
> - Tab 2: Login as **User 2**, reply “How are you?”
> → Real-time message sync like WhatsApp

---

## 📦 Installation & Running Locally

### 1. Clone the repository
```bash
git clone https://github.com/ssaniyyya/chat-app.git
cd chat-app


