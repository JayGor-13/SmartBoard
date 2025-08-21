# SmartBoard

Collaborative online whiteboard app powered by React, Fabric.js, and Socket.io. Draw, annotate, and chat in real-time with teammates. Designed for education, remote meetings, and creative brainstorming.

![SmartBoard Banner](https://github.com/JayGor-13/SmartBoard/raw/main/banner.png) <!-- Add banner if available -->

---

## 🚀 Features

- **Real-time Multi-user Collaboration:** Draw and annotate on a shared canvas, with live updates for all participants.
- **Fabric.js Drawing Engine:** Advanced drawing tools, shape manipulation, selection, scaling, and rotation.
- **Room-based Sessions:** Join or create rooms for focused collaboration.
- **Live Chat Panel:** Integrated chat with basic markdown support and optional AI assistant.
- **Customizable Properties:** Change colors, line thickness, and object properties from an intuitive panel.
- **User Cursors:** Visual indicators for each user's cursor position.
- **Keyboard Shortcuts:** Speed up your workflow with hotkeys for panning, selection, and more.
- **Responsive Design:** Works on desktops, tablets, and large screens.
- **Built with React & TailwindCSS:** Modern, maintainable frontend stack.

---

## 🏷️ Tags

`whiteboard` `collaboration` `react` `fabricjs` `socketio` `tailwindcss` `education` `drawing` `chat` `real-time`

---

## 📦 Tech Stack

- **Frontend:** React, Fabric.js, TailwindCSS, Vite
- **Backend:** Socket.io (see socket.js for connection)
- **Other:** ESLint configuration for code quality

---

## ⚡ Getting Started

### Prerequisites

- Node.js & npm
- Backend server running Socket.io (default: `http://localhost:3001`)

### Installation

```bash
# Clone the repository
git clone https://github.com/JayGor-13/SmartBoard.git
cd SmartBoard

# Install dependencies
npm install

# Start the development server
npm run dev
