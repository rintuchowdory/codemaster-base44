# 🎓 CodeMaster — Learn to Code the Fun Way! 🕹️💻

> **Learn • Practice • Master**

CodeMaster is an interactive coding education platform that helps students master Python, Java, and C through hands-on practice, gamified challenges, and real-world projects.

🌐 **Live App:** https://code-master-copy-52476006.base44.app

Built with [Base44](https://base44.com) — a no-code platform for building web apps with built-in backend, database, and authentication.

---

## ✨ Features

### 🧠 Learn by Playing
- Interactive lessons for **Python**, **Java**, and **C**
- Solve coding puzzles, complete challenges, and level up
- Hands-on practice in a safe, sandboxed environment

### 🏆 Gamified Progress
- Track your learning streaks and hours practiced
- Earn badges and achievements as you grow
- Visual progress dashboard with per-language completion

### 🎮 Practice Lab
- Built-in code editor supporting Python, Java, and C
- Run code instantly and see results
- Pro tips and guided examples to get you started

### 📊 Dashboard
- Real-time stats: Hours Learned, Lessons Completed, Current Streak, Projects Built
- Per-language progress tracking (Python, Java, C)
- Quick access to all courses and the Practice Lab

---

## 🗂️ App Structure

| Page | Route | Description |
|------|-------|-------------|
| Dashboard | `/` | Home page with stats and course paths |
| Python Course | `/python-course` | Beginner-level Python lessons |
| Java Course | `/java-course` | Intermediate-level Java lessons |
| C Programming | `/c-programming` | Intermediate-level C lessons |
| Practice Lab | `/practice-lab` | Interactive code editor (Python/Java/C) |
| Coding Games | `/coding-games` | Gamified coding challenges |
| Achievements | `/achievements` | Badges and progress milestones |
| Progress | `/progress` | Detailed learning progress |

---

## 🗃️ Data Model

### User Entity
| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `role` | string (enum: `admin`, `user`) | ✅ | The role of the user in the app |

> **Note:** Base44 automatically adds `id`, `created_date`, `updated_date`, and `created_by` to every entity.

---

## 🔐 Authentication

The app supports two authentication methods:
- **Google OAuth** — "Continue with Google" one-click login
- **Email/Password** — traditional sign-in and sign-up

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React + Next.js (Base44 managed) |
| Styling | Tailwind CSS |
| Backend | Base44 managed backend |
| Database | Base44 entity system |
| Auth | Base44 auth (Google OAuth + email/password) |
| Hosting | Base44 platform |

---

## 📋 Course Details

### 🐍 Python Programming (Beginner)
> Learn the most popular programming language for beginners. Perfect for data science, web development, and automation.

### ☕ Java Development (Intermediate)
> Master object-oriented programming with Java. Build robust applications and understand enterprise development.

### ⚡ C Programming (Intermediate)
> Understand the fundamentals of programming with C. Learn memory management and system-level programming.

---

## 🚀 Getting Started

This app is built and hosted on the [Base44](https://base44.com) platform. To access the app:

1. Visit https://code-master-copy-52476006.base44.app
2. Sign in with Google or create an email/password account
3. Choose a learning path (Python, Java, or C)
4. Start with lessons or jump into the Practice Lab

### For Developers

To modify this app, open it in the [Base44 builder](https://app.base44.com/apps/6a974c4534cc6f3052476006/editor/preview).

---

## 📄 License

This project is for educational purposes. See the Base44 terms of service for platform usage details.

---

Made with ❤️ using [Base44](https://base44.com)
