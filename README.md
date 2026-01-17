# 💬 Chat-Fiesta

Chat-Fiesta is a **full-stack real-time chat application** built using **WebSockets**, **Node.js**, **TypeScript**, and **React (Vite)**.  
It supports live messaging with a clean separation between backend and frontend.

---

## 📌 Features

- 🔴 Real-time chat using WebSockets
- 👤 Username-based messaging
- 🧩 Modular backend architecture (rooms, clients, router)
- ⚡ Fast frontend with Vite + React
- 🛠️ TypeScript for type safety (backend)
- 📂 Clean monorepo structure

---

## 🏗️ Project Structure
Chat-fiesta/
├── backend/
│ ├── src/
│ │ ├── clients.ts
│ │ ├── router.ts
│ │ ├── rooms.ts
│ │ ├── server.ts
│ │ ├── index.ts
│ │ └── types.ts
│ ├── dist/
│ ├── package.json
│ └── tsconfig.json
│
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ │ └── Chat.jsx
│ │ ├── App.jsx
│ │ ├── main.jsx
│ │ └── index.css
│ ├── public/
│ ├── package.json
│ └── vite.config.js
│
└── .gitignore

