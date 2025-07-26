# Usage Footprint Tracker SPA

A modern, single-page application (SPA) that visualizes digital resource usage through dynamic charts and theme-based storytelling. Built with React, TailwindCSS, and Vite, this tracker empowers users to explore data across monthly, weekly, and daily granularities, with slick transitions and accessibility features.

---

## 🧩 Architecture Overview

### Tech Stack:
- **Framework**: React + Vite
- **Styling**: TailwindCSS
- **Data Viz**: Chart.js via React wrapper components
- **State Management**: React Context API
- **Routing**: React Router (SPA behavior)
- **Deployment**: Vercel with GitHub Actions CI/CD

### Folder Structure:
Here’s your fully structured and polished README.md—ready to copy straight into your repo. It lays out everything from high-level architecture down to chart component behaviors. Let’s make your project as clear and compelling as it is sophisticated. 🚀

📦src
 ┣ 📂assets             # Logo, fonts, styles
 ┣ 📂components         # Reusable UI sections
 ┣ 📂charts             # Chart components
 ┣ 📂contexts           # Theme & granularity logic
 ┣ 📂hooks              # Ripple effect, dark mode toggle
 ┣ 📂routes             # Page-level components
 ┗ 📜main.jsx           # Entry point
`

---

## 🧠 High-Level Design (HLD)

- Component-driven structure ensures maintainability
- Theme & granularity contexts offer global UX control
- Data loaded via Axios and stored in JSON (API-ready)
- Vercel deployment with automated builds & previews
- Dark/light theme persistence via localStorage

*Visual architecture diagram link (optional):* [Add a Lucidchart/Excalidraw URL]

---

## 🔍 Low-Level Design (LLD)

### Granularity Toggle
- Controlled by `UsageContext`
- Updates all child charts dynamically

### Charts
- `UsageTimeline`: Bar chart with animation & time labeling
- `FootprintPie`: Pie chart segmenting usage categories
- Reusable `ChartWrapper` adjusts size, data, interactivity

### Visual UX
- Ripple effect via `useRipple` hook
- Smooth transitions & fade-ins powered by Tailwind classes
- Button accessibility, focus indicators, and semantic HTML included

---

## 🔐 Security Measures

- HTTPS-first setup via `vercel.json`
- Secure headers: `Content-Security-Policy`, `X-Content-Type-Options`
- `.env.example` outlines config requirements
- Scalable for Entra ID or Auth0 integration if backend expands

---

## ⚙️ Getting Started

### Prerequisites
- Node.js ≥ 18.x
- npm or Yarn

### Local Setup
```bash
git clone https://github.com/adityarachuri/usage-footprint-tracker-spa
cd usage-footprint-tracker-spa
npm install
npm run dev
npm run test
