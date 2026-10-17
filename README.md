# 🚀 OnboardAI

> A modern, full-stack project management and team collaboration platform designed to streamline workspace management, project tracking, and task workflows with an intuitive user interface.

---

## 🌟 Key Features

* **🏢 Workspace & Project Management**: Create and manage multiple workspaces, invite team members, and organize projects effortlessly.
* **📋 Interactive Task Tracking**: Create, assign, update, and monitor task statuses and timelines with custom dialogs and sidebars.
* **📊 Real-time Analytics & Calendars**: Visual representation of project metrics, statistics, and a built-in project calendar to keep deadlines on track.
* **👥 Dynamic Team Collaboration**: Manage team member roles, view active recent activity feeds, and handle workspace settings seamlessly.
* **🎨 Modern UI/UX**: Built with a sleek, responsive design featuring theme-switching capabilities (Dark/Light mode).

---

## 🛠️ Tech Stack

### 🖥️ Client (Frontend)
* **Framework**: React (Vite)
* **State Management**: Redux Toolkit (`themeSlice`, `workspaceSlice`)
* **Routing & Styling**: React Router, Tailwind CSS / Modern CSS
* **Deployment**: Vercel

### ⚙️ Server (Backend)
* **Runtime**: Node.js, Express
* **Database & ORM**: Prisma ORM with PostgreSQL / Database schema support
* **Background Processing**: Inngest
* **Deployment**: Vercel

---

## 📁 Project Structure

```text
OnboardAI-main/
├── 📂 client/                 # Frontend React Application
│   ├── 📂 src/
│   │   ├── 📂 components/     # Reusable UI components (Modals, Sidebars, Cards, Navbar)
│   │   ├── 📂 features/       # Redux slices for state management
│   │   ├── 📂 pages/          # Application views (Dashboard, Projects, Team, TaskDetails)
│   │   └── 📜 App.jsx         # Root component
│   ├── 📜 package.json        # Client dependencies & scripts
│   └── 📜 vite.config.js      # Vite configuration
│
└── 📂 server/                 # Backend Node.js & Express Application
    ├── 📂 configs/            # Database and service configurations
    ├── 📂 inngest/            # Inngest functions and background triggers
    ├── 📂 prisma/             # Database schema and migrations
    ├── 📜 server.js           # Entry point for the backend server
    └── 📜 package.json        # Server dependencies & scripts
