<div align="center">
  <br />
  <div>
    <img src="https://img.shields.io/badge/-React-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="react" />
    <img src="https://img.shields.io/badge/-Vite-black?style=for-the-badge&logoColor=white&logo=vite&color=646CFF" alt="vite" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-Node.js-black?style=for-the-badge&logoColor=white&logo=node.js&color=339933" alt="nodejs" />
    <img src="https://img.shields.io/badge/-PostgreSQL-black?style=for-the-badge&logoColor=white&logo=postgresql&color=4169E1" alt="postgres" />
  </div>

  <h1 align="center">Classroom Manager</h1>
  <h3 align="center">A Modern Full-Stack Classroom Management System</h3>
</div>

## 📋 <a name="table">Table of Contents</a>
1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 📂 [Project Structure](#project-structure)

## 🤖 <a name="introduction">Introduction</a>
**Classroom Manager** is a full-stack educational platform built to streamline the management of classes, departments, subjects, faculty, and enrollments. It offers a beautiful, responsive user interface powered by Refine and React, backed by a robust and secure Node.js backend.

## ⚙️ <a name="tech-stack">Tech Stack</a>

### Frontend (`/classroom`)
- **Framework:** React 19 + Vite
- **UI & State:** Refine (Headless UI framework), Tailwind CSS, Shadcn UI
- **Forms & Validation:** React Hook Form, Zod
- **Media & Charts:** Cloudinary, Recharts

### Backend (`/classroom-backend`)
- **Runtime:** Node.js
- **Database:** PostgreSQL (Neon) with Drizzle ORM
- **Authentication:** Better-Auth (Secure, scalable auth)
- **Security:** Arcjet (Bot protection and rate-limiting)

## 🔋 <a name="features">Features</a>
- 🔐 **Secure Authentication:** Complete login and registration flows via Better-Auth.
- 🏫 **Classroom Administration:** Create and manage Departments, Classes, and Subjects.
- 👨‍🏫 **Faculty Management:** Maintain faculty records and assign them to classes.
- 🎓 **Enrollment System:** Seamlessly enroll users into classes.
- 📊 **Dashboard Analytics:** Beautiful data visualizations for system metrics.
- 🛡️ **Advanced Security:** Rate limiting and attack prevention via Arcjet.
- 📱 **Fully Responsive:** Stunning UI that works flawlessly on desktop and mobile.

## 🤸 <a name="quick-start">Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**
Make sure you have [Node.js](https://nodejs.org/) installed on your machine.

**Clone the Repository**
```bash
git clone https://github.com/Santaingamba/Classroom-Manager.git
cd Classroom-Manager
```

### 1. Backend Setup
Navigate to the backend directory:
```bash
cd classroom-backend
npm install
```
Create a `.env` file in `classroom-backend` and add your database and auth credentials (refer to the backend's internal README for specifics). Then start the development server:
```bash
npm run dev
```

### 2. Frontend Setup
Open a new terminal and navigate to the frontend directory:
```bash
cd classroom
npm install
```
Create a `.env` file in the `classroom` directory with your VITE API URLs. Then start the frontend:
```bash
npm run dev
```

## 📂 <a name="project-structure">Project Structure</a>
This is a monorepo containing both the frontend and backend in their respective directories:

- `/classroom`: The React/Vite frontend application.
- `/classroom-backend`: The Node.js/Express backend application.
