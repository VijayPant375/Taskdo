<div align="center">

# ✅ TaskDo — Smart Todo Web Application

**A clean, fast, and persistent task manager built with React. No backend required.**

[![React](https://img.shields.io/badge/React-Frontend-61DAFB?style=flat-square&logo=react&logoColor=black)](https://react.dev)
[![Vite](https://img.shields.io/badge/Vite-Build%20Tool-646CFF?style=flat-square&logo=vite&logoColor=white)](https://vitejs.dev)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-Styling-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![TypeScript](https://img.shields.io/badge/TypeScript-96.6%25-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Live Demo](https://img.shields.io/badge/Live-Demo-22C55E?style=flat-square&logo=vercel&logoColor=white)](https://gizmo-gecko-25296878.figma.site/)

</div>

---

## 📖 Overview

**TaskDo** is a lightweight, zero-backend task management app that lets users create, prioritize, and track their daily tasks directly in the browser. All data is persisted via **Browser LocalStorage**, meaning tasks survive page refreshes with no server, no database, and no setup friction.

Built with a modern React + Vite stack and a focused dark UI, TaskDo is designed to be fast, distraction-free, and immediately useful.

🔗 **[Try the live demo →](https://gizmo-gecko-25296878.figma.site/)**

---

## ✨ Features

| Feature | Description |
|---|---|
| ✅ Task Management | Create and delete tasks with ease |
| 🎯 Priority Levels | Tag each task as **High**, **Medium**, or **Low** priority |
| ⏰ Deadlines | Attach due dates to keep work on schedule |
| 🔔 Notifications | Enable reminders for upcoming tasks |
| 💾 Persistent Storage | Tasks saved in **LocalStorage** — no refresh loss |
| 🌙 Dark UI | Clean, focused dark-themed interface |
| ⚡ Fast & Responsive | Instant interactions powered by Vite |

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Framework | [React](https://react.dev) |
| Build Tool | [Vite](https://vitejs.dev) |
| Styling | [TailwindCSS](https://tailwindcss.com) |
| Language | TypeScript / JavaScript |
| UI Components | [Radix UI](https://www.radix-ui.com) |
| Icons | [Lucide React](https://lucide.dev) |
| Forms | [React Hook Form](https://react-hook-form.com) |
| Date Utilities | [date-fns](https://date-fns.org) |
| Storage | Browser LocalStorage API |

---

## ⚙️ How It Works

TaskDo uses the browser's built-in **LocalStorage API** as its persistence layer — no backend, no database, no auth required.
```
User creates a task
        │
        ▼
Task saved to localStorage
        │
        ▼
Page reloads / revisited
        │
        ▼
Tasks retrieved from localStorage
        │
        ▼
UI renders saved tasks automatically
```

**Example stored task object:**
```json
{
  "name": "Finish project report",
  "description": "Include Q4 metrics",
  "deadline": "2026-03-08T12:14:00.000Z",
  "priority": "high"
}
```

This makes TaskDo fully functional as a persistent task manager with zero infrastructure overhead.

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v18+)
- npm

### Installation

1. **Clone the repository**
```bash
   git clone https://github.com/VijayPant375/Taskdo.git
   cd Taskdo
```

2. **Install dependencies**
```bash
   npm install
```

3. **Start the development server**
```bash
   npm run dev
```

4. **Open in browser**
```
   http://localhost:5173
```

---

## 📁 Project Structure
```
Taskdo/
│
├── index.html
├── package.json
├── vite.config.ts
├── postcss.config.mjs
│
├── src/
│   ├── components/        # Reusable UI components
│   ├── pages/             # Page-level views
│   ├── styles/            # Global styles
│   └── main.jsx           # App entry point
│
├── guidelines/            # Design and contribution guidelines
├── ATTRIBUTIONS.md        # Third-party attributions
└── README.md
```

---

## 🗺️ Roadmap

Planned improvements for future versions:

- [ ] ✏️ Task editing functionality
- [ ] 📊 Progress tracking and completion stats
- [ ] 🔍 Filter tasks by status (All / Pending / Completed)
- [ ] ↕️ Drag-and-drop task reordering
- [ ] ☁️ Cloud sync with backend database
- [ ] 👤 User authentication and multi-device support
- [ ] 📱 Mobile-optimized layout

---

## 📬 Contributing

Contributions, bug reports, and feature suggestions are welcome. Please open an issue or submit a pull request.

---

<div align="center">

Built by [VijayPant375](https://github.com/VijayPant375)

</div>
