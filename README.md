# SkillPath AI — Frontend

A modern AI-powered Career Prediction & Skill Development platform built with **React + Vite**.

## 🚀 Quick Start

```bash
cd skillpath-ai
npm install
npm run dev
```

Open **http://localhost:5173** in your browser.

## 📁 Project Structure

```
src/
├── pages/          # All page components
├── components/
│   ├── layout/     # Navbar, Sidebar, Footer
│   └── ui/         # Toaster, shared UI
├── context/        # AppContext (global state + localStorage)
├── services/       # api.js — mock data + future Spring Boot stubs
└── index.css       # Global design system
```

## 🔌 Future Java Spring Boot Integration

Edit `src/services/api.js` — replace mock functions with real `fetch()` calls to:
- `POST /api/assessment`
- `GET /api/careers/recommendations`
- `GET /api/skills/gaps`
- `GET /api/roadmap`
- `POST /api/roadmap/progress`

## ⚠️ Demo Note

This is a **frontend-only demo**. No real AI/ML is used. All data is stored in `localStorage`.
