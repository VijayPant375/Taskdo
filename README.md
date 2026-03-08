# 📝 TaskDo – Smart Todo Web Application

A modern task management web application that helps users organize daily tasks efficiently.  
TaskDo allows users to create, prioritize, and manage tasks while storing all data locally in the browser using **Local Storage**, ensuring tasks persist even after refreshing the page.

---

## 🔍 Features

* ✅ Create and manage tasks
* 🎯 Assign task priority (**High / Medium / Low**)
* ⏰ Add deadlines to tasks
* 🔔 Enable task notifications
* 🗑 Delete tasks
* 💾 Persistent storage using **Browser LocalStorage**
* 🌙 Clean dark themed UI
* ⚡ Fast and responsive interface
* 🔄 Tasks remain saved after page refresh

---

## ⚙️ Tech Stack

* React
* Vite
* TailwindCSS
* JavaScript
* HTML
* CSS
* Radix UI
* Lucide Icons
* React Hook Form
* Date-Fns
* Browser LocalStorage API

---

## 🚀 Live Demo

https://gizmo-gecko-25296878.figma.site/

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/VijayPant375/Taskdo.git
```

Navigate into the project directory

```bash
cd Taskdo
```

Install dependencies

```bash
npm install
```

Start the development server

```bash
npm run dev
```

The application will run at:

```
http://localhost:5173
```

---

## ⚙️ How It Works

TaskDo stores tasks directly in the browser using **Local Storage**.

Workflow:

1. User creates a task
2. Task is saved in `localStorage`
3. When the page reloads, tasks are retrieved from storage
4. The UI renders saved tasks automatically

Example stored task data:

```json
[
  {
    "name": "Test task",
    "description": "",
    "deadline": "2026-03-08T12:14:00.000Z",
    "priority": "medium"
  }
]
```

This allows the application to behave like a persistent task manager **without requiring a backend server or external database**.

---

## 📁 Project Structure

```
Taskdo
│
├── index.html
├── package.json
├── vite.config.ts
├── postcss.config.mjs
│
├── src
│   ├── components
│   ├── pages
│   ├── styles
│   └── main.jsx
│
├── guidelines
├── ATTRIBUTIONS.md
└── README.md
```

---

## 🧠 Future Improvements

Possible enhancements for the project:

* ✏️ Task editing functionality
* 📊 Task progress tracking
* 🔍 Task filtering (All / Completed / Pending)
* ↕️ Drag and drop task ordering
* ☁️ Cloud database integration
* 👤 User authentication
* 📱 Mobile optimized interface
