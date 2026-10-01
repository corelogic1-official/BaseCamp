# BaseCamp P2P ⚡

**BaseCamp P2P** is a serverless, peer-to-peer (P2P) chat workspace built entirely in a single HTML file. Utilizing **WebRTC** (via **PeerJS**) and the browser's `localStorage` / `sessionStorage`, it allows users to connect directly device-to-device to chat, manage contacts, and coordinate lightweight group meshes without requiring a centralized backend database.

---

## 🚀 Features

* **Serverless P2P Architecture:** Messages travel directly between connected browsers using WebRTC data channels.
* **Direct Friend Connections:** Connect instantly by sharing and pasting Peer IDs.
* **Lightweight Group Mesh:** Create and join groups using unique group codes.
* **Persistent Local Storage:** Contacts, profiles, and state are saved securely in your browser's local storage.
* **Zero Dependencies Setup:** Powered entirely by client-side JavaScript and a lightweight PeerJS CDN script.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Modern CSS Grid & Flexbox, Custom Properties/Variables)
* **Scripting:** Vanilla JavaScript (ES6+)
* **Networking:** WebRTC via [PeerJS](https://peerjs.com/) (using public signaling infrastructure)
* **Storage:** `localStorage` & `sessionStorage`

---

## 📦 Getting Started

Since BaseCamp is entirely client-side, you don't need to run `npm install` or set up a Node.js server!

### Running Locally

1. **Save the Code:** Save the HTML file as `index.html` on your computer.
2. **Open in Browser:** Double-click the file to open it in any modern web browser (Chrome, Firefox, Edge, Safari). Alternatively, serve it via a local static server:
   ```bash
   npx serve .
