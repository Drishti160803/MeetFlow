# 🌊 MeetFlow - Real-Time Video Conferencing

MeetFlow is a high-performance, full-stack video conferencing application built to provide seamless real-time communication. Inspired by platforms like Zoom, it leverages WebRTC for peer-to-peer media streaming and Socket.io for low-latency signaling.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=webrtc&logoColor=white)

---

## 🚀 Key Features

* **⚡ Real-Time Video/Audio:** Peer-to-peer high-quality media streaming using WebRTC.
* **📱 Dynamic Grid Layout:** Responsive UI that adjusts as users join or leave the room.
* **💬 Instant Messaging:** Integrated chat functionality via Socket.io.
* **🖥️ Screen Sharing:** Share your desktop or specific windows with other participants.
* **🔒 Room Logic:** Create and join unique meeting rooms via dynamic URLs.

## 🛠️ Tech Stack

**Frontend:**
* **React.js**: For building the component-based UI.
* **Simple-Peer**: A wrapper for WebRTC to handle handshakes.
* **Styled-Components**: For modern, scoped CSS styling.
* **Socket.io-Client**: For real-time event handling.

**Backend:**
* **Node.js & Express**: Handling the signaling server.
* **Socket.io**: Facilitating the WebRTC "Offer/Answer" exchange and chat.

---

## 📦 Installation & Setup

Follow these steps to get a local copy up and running.

### 1. Clone the Repository
```bash
git clone [https://github.com/YOUR_USERNAME/meet-flow.git](https://github.com/YOUR_USERNAME/meet-flow.git)
cd meet-flow
