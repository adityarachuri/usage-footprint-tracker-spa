# Aditya's Professional SPA Portfolio 🌐✨

Welcome to the source code for my Single Page Application (SPA) built with React, showcasing my professional journey, technical expertise, and creative flair.

## 🚀 Sections Included
- **Company Branding**: Name, logo, tagline
- **About Me**: A peek into my values and mission
- **Core Competencies & Tech Stack**: Skills and experience across .NET, Azure, React, and more
- **Education & Certifications**: Academic background and credentials
- **Professional Timeline**: Work experience highlights
- **Contact Gateway**: Let’s connect!

## 🧠 Architecture Highlights
- Context-based theme management
- Dynamic skill visualizations
- Responsive design with semantic HTML5
- Deployed securely on Vercel

---

📘 README Introduction (suggested draft)

`markdown

Aditya's Professional SPA Portfolio 🌐✨

Welcome to the source code for my Single Page Application (SPA) built with React, showcasing my professional journey, technical expertise, and creative flair.

🚀 Sections Included
- Company Branding: Name, logo, tagline
- About Me: A peek into my values and mission
- Core Competencies & Tech Stack: Skills and experience across .NET, Azure, React, and more
- Education & Certifications: Academic background and credentials
- Professional Timeline: Work experience highlights
- Contact Gateway: Let’s connect!

🧠 Architecture Highlights
- Context-based theme management
- Dynamic skill visualizations
- Responsive design with semantic HTML5
- Deployed securely on Vercel
`
---

🧩 GitHub Enhancements
- Repo description: 🌟 SPA Portfolio | Personal branding & React architecture by Aditya
- Topics:
  - react
  - portfolio
  - web-development
  - dotnet
  - azure
  - competitive-programming
  - personal-website 

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
