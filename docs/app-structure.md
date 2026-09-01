# CodeMaster — App Structure Documentation

## Overview

CodeMaster is an interactive coding education platform built on [Base44](https://base44.com). It teaches Python, Java, and C through lessons, a practice lab, and gamified challenges.

- **Live URL:** https://code-master-copy-52476006.base44.app
- **Base44 App ID:** `6a974c4534cc6f3052476006`
- **Builder URL:** https://app.base44.com/apps/6a974c4534cc6f3052476006/editor/preview

## Navigation

The app has a sidebar navigation with the following sections:

1. **Dashboard** — Home page with stats and course paths
2. **Python Course** — 🐍 Beginner-level Python lessons
3. **Java Course** — ☕ Intermediate-level Java lessons
4. **C Programming** — ⚡ Intermediate-level C lessons
5. **Practice Lab** — Interactive code editor
6. **Coding Games** — Gamified coding challenges
7. **Achievements** — Badges and milestones
8. **Progress** — Learning progress tracker

## Dashboard

The dashboard displays:
- **Stats tiles:** Hours Learned, Lessons Completed, Current Streak (days), Projects Built
- **Language progress bars:** Python (0%), Java (0%), C (0%)
- **Three course path cards** with:
  - Course name and emoji
  - Difficulty level
  - Description
  - Lesson count and duration
  - Progress indicator
  - "Start Learning" button

## Practice Lab

The Practice Lab features:
- **Tabbed interface** for Python, Java, and C
- **Code editor** with syntax highlighting
- **Starter code** for each language (e.g., Hello World in Python)
- **Run Code** button to execute code
- **Pro Tips** section with guidance:
  - "Experiment Freely" — Don't be afraid to modify the code
  - "Start Small" — Begin with simple programs
  - "Practice Daily" — Consistent practice, even 15 minutes a day

### Python Starter Code
```python
# Welcome to Python!
# Let's start with a simple "Hello World" program

print("Hello, World!")
print("Welcome to CodeMaster!")

# Try modifying this code:
name = "Your Name"
print(f"Hello, {name}!")
```

## Authentication

- **Google OAuth:** One-click "Continue with Google" button
- **Email/Password:** Traditional sign-in with "Forgot password?" and "Sign up" links
- Auth is handled by Base44's built-in authentication system

## Entity Schema

### User
| Field | Type | Required | Enum Values |
|-------|------|----------|-------------|
| `role` | string | Yes | `admin`, `user` |

Base44 automatically adds: `id`, `created_date`, `updated_date`, `created_by`

## Design

- **Color scheme:** Light theme with off-white background, white cards, dark accents
- **Typography:** Sans-serif (Base44 default)
- **Icons:** Emoji-based language indicators (🐍 Python, ☕ Java, ⚡ C)
- **Layout:** Sidebar navigation + main content area
