# 🧭 TaskPilot – Full Stack Project Management Platform

> 🚀 A modern, full-stack project management web app built with the **PERN Stack** (PostgreSQL, Express.js, React.js, Node.js). TaskPilot helps teams create organizations, manage projects, assign tasks, and stay on track with automated email reminders — all from one sleek dashboard.

---

## 📌 Overview

**TaskPilot** is designed to simplify project tracking and team collaboration.  
It enables users to:
- Create organizations & invite team members 👥  
- Add and assign tasks to specific users 📝  
- Track progress and deadlines 📅  
- Get automated email notifications for task updates and due dates ✉️  

> ⚙️ Currently in development.

---

## 🏗️ Tech Stack

| Layer | Technology |
|:------|:------------|
| **Frontend** | React.js, HTML5, CSS3, JavaScript |
| **Backend** | Node.js, Express.js |
| **Database** | PostgreSQL (Neon) |
| **Authentication** | Clerk |
| **Background Jobs** | Inngest (for email automation) |
| **Deployment** | Vercel |
| **Version Control** | Git & GitHub |

---

## 🧩 Features

✅ User Authentication (via Clerk)  
✅ Create & Manage Organizations  
✅ Add Projects and Assign Tasks  
✅ Automated Email Notifications (Inngest)  
✅ Responsive and Modern UI  
✅ Secure API Structure  
✅ Future scope: AI Assistant for task creation & project summaries  

---

## 🧠 Architecture

```text
React.js (Frontend)
     |
     v
Express.js (Backend API)
     |
     v
PostgreSQL (Database)
     |
     +--> Clerk (Auth)
     +--> Inngest (Email Jobs)
