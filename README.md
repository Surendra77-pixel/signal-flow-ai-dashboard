# 🌊 SignalFlow: AI-Powered Drop-Off Detector

[Live Status](https://img.shields.io/badge/Status-Live-success)

[Render](https://img.shields.io/badge/Deployed_on-Render-46E3B7?logo=render&logoColor=white)

[React](https://img.shields.io/badge/Frontend-React_19-61DAFB?logo=react&logoColor=black)

[Node](https://img.shields.io/badge/Backend-Node.js_&_Express-339933?logo=nodedotjs&logoColor=white)

## 📌 Project Overview

**SignalFlow** is an intelligent, real-time analytics dashboard designed to detect, analyze, and diagnose user drop-offs during complex signup flows. Standard analytics tools only tell you *where* users leave; SignalFlow uses behavioral signals to tell you **why** they leave (e.g., rage clicks, hesitation, layout bugs, poor mobile optimization).

With a live data feed and a built-in AI root-cause engine, developers can instantly see precisely which step of a multi-stage funnel is failing and view direct, actionable code patches to fix the friction.

### 🔗 Quick Links

- **📺 Watch the Demo on YouTube: https://youtu.be/ZvjZD1BCiFw?si=fS8dQVyOi9grXtnU
- **🌍 View the Live Project: https://signal-flow-ai-dashboard.onrender.com

---

## 🛠️ Built With (Tech Stack)

### Frontend

- **React (v19):** For building a highly highly dynamic and reactive user interface.
- **Vite:** As the lightning-fast frontend build tool and development server.
- **Recharts:** To render the live-updating funnel and behavioral data charts.
- **Framer Motion:** For smooth, modern UI transitions and micro-animations.
- **Lucide React:** For clean, scalable dashboard iconography.

### Backend

- **Node.js & Express:** A robust backend server that powers the API infrastructure.
- **CORS & UUID:** For secure cross-origin streaming and unique session generation.

### Deployment & CI/CD

- **Render:** The application is hosted as a unified full-stack Web Service on [Render.com](http://render.com/).
- **GitHub:** Source code management and continuous integration triggers.

---

## ⚙️ How It Works

1. **The Simulated Event Engine:** The Node.js backend (server/index.js) runs a massive simulation of 8 different complex signup flows (e.g., SaaS, FinTech KYC, E-commerce, Gaming). It generates real-time telemetry mimicking thousands of users traversing these funnels.
2. **Behavioral Tracking:** The backend simulates psychological and technical friction like "rage clicks", "hesitation times", and "tab switches".
3. **The SDK API:** The mock SDK (src/services/mockApi.js) polls the backend `/api/v1/metrics` endpoints rapidly to pull down the newest simulated drops and UX anomalies.
4. **The React Dashboard:** The frontend consumes this data stream and visualizes where the funnels are failing using interactive Recharts unmounting elements.
5. **AI Root-Cause Analysis:** When a critical drop is detected, the "Insights Engine" maps the failure to a deeply specific UX friction point (like an un-optimized mobile layout) and generates a hypothetical code fix for the developer.

---

## 🚀 How i Made This Project

The development process was split into three major phases:

1. **Architecture & API Design:** We started by creating a heavy Node/Express backend capable of producing streaming mock data that looked indistinguishable from real-world telemetry (incorporating varied drop-rates and complex multi-step definitions).
2. **Dashboard UI Construction:** The frontend was scaffolded using Vite and React. We built reusable components for the live feed, the funnel charts, and the alerting panels. We focused strictly on a dark-mode, premium aesthetic suitable for a high-end developer tool.
3. **Production Deployment & Routing Fixes:** Moving the project from local development to production required modifying the Express server to statically serve the compiled Vite `dist` folder. We also updated the Express routing wildcard mechanics (`app.use`) to ensure compatibility with Express 5.x so it would deploy seamlessly to Render.

---

## 💻 Running the Project Locally

If you'd like to clone this repository and run it on your own machine:

1. **Clone the repo:**
    
    ```bash
    git clone <https://github.com/Surendra77-pixel/signal-flow-ai-dashboard.git>
    cd signal-flow-ai-dashboard
    ```
    
2. **Install dependencies:**
    
    ```
    bash
    npminstall
    ```
    
3. **Start the development servers:**
    
    ```
    bash
    npmrundev
    ```
    
    *This uses `concurrently` to launch both the Vite frontend on Port 3200 and the Node API on Port 3001.*
    
4. **View locally:** Open `http://localhost:3200` in your browser.

---

*Developed by Surendra manthri— For questions or feedback, feel free to reach out!*
