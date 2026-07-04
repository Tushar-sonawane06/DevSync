# DevSync

DevSync is a real-time collaborative code editor that lets multiple people write and edit code simultaneously in the same session — like a shared coding room for pair programming, interviews, teaching, or quick collaborative debugging.

🔗 Live Demo:https://devsync.tushar-sonawane.xyz/

## 🚀 Features

- **Real-time collaboration** — Multiple users can join the same room and see each other's code changes instantly.
- **Live syncing** — Edits made by one user are reflected across all connected clients in real time.
- **Room-based sessions** — Create or join a room using a unique room ID to start collaborating.
- **Lightweight & fast** — No database dependency; everything runs in-memory for quick setup and low overhead.
- **Dockerized setup** — Easily spin up the app using Docker for consistent environments.

## 🛠️ Tech Stack

- **Frontend:** React, CSS
- **Backend:** Node.js
- **Real-time communication:** Socket.IO (or WebSockets)
- **Containerization:** Docker
- **Database:** None (in-memory state management)

## 📦 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- [Docker](https://www.docker.com/) (optional, for containerized setup)
- npm or yarn

### Installation (Manual Setup)

1. Clone the repository:
   ```bash
   git clone https://github.com/Tushar-sonawane06/DevSync.git
   cd DevSync
   ```

2. Install dependencies for both client and server:
   ```bash
   # Backend
   cd server
   npm install

   # Frontend
   cd ../client
   npm install
   ```

3. Start the backend server:
   ```bash
   cd server
   npm start
   ```

4. Start the frontend:
   ```bash
   cd client
   npm start
   ```

5. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

### Installation (Using Docker)

1. Clone the repository:
   ```bash
   git clone https://github.com/Tushar-sonawane06/DevSync.git
   cd DevSync
   ```

2. Build and run the containers:
   ```bash
   docker-compose up --build
   ```

3. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

## 🧑‍💻 How to Use

1. Open the app in your browser.
2. Create a new room or join an existing one using a Room ID.
3. Share the Room ID with your collaborators.
4. Start coding together — all changes sync in real time!

## 📁 Project Structure

```
DevSync/
├── client/          # React frontend
├── server/          # Node.js backend
├── docker-compose.yml
└── README.md
```

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🔗 Repository

[https://github.com/Tushar-sonawane06/DevSync](https://github.com/Tushar-sonawane06/DevSync)

---

⭐ If you find this project useful, consider giving it a star on GitHub!
