
<div align="center">

```
███████╗██╗ ██████╗ ███╗   ██╗ █████╗ ██╗     ███████╗██╗      ██████╗ ██╗    ██╗
██╔════╝██║██╔════╝ ████╗  ██║██╔══██╗██║     ██╔════╝██║     ██╔═══██╗██║    ██║
███████╗██║██║  ███╗██╔██╗ ██║███████║██║     █████╗  ██║     ██║   ██║██║ █╗ ██║
╚════██║██║██║   ██║██║╚██╗██║██╔══██║██║     ██╔══╝  ██║     ██║   ██║██║███╗██║
███████║██║╚██████╔╝██║ ╚████║██║  ██║███████╗██║     ███████╗╚██████╔╝╚███╔███╔╝
╚══════╝╚═╝ ╚═════╝ ╚═╝  ╚═══╝╚═╝  ╚═╝╚══════╝╚═╝     ╚══════╝ ╚═════╝  ╚══╝╚══╝
```

### 🌊 AI-Powered Drop-Off Detector · Real-Time Funnel Intelligence.

<br/>

[![Live Status](https://img.shields.io/badge/●_LIVE-00FF88?style=for-the-badge&labelColor=0d1117)](https://signal-flow-ai-dashboard.onrender.com)
[![React 19](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black&labelColor=0d1117)](https://react.dev)
[![Node.js](https://img.shields.io/badge/Node.js-Express-339933?style=for-the-badge&logo=nodedotjs&logoColor=white&labelColor=0d1117)](https://nodejs.org)
[![Render](https://img.shields.io/badge/Deployed-Render-46E3B7?style=for-the-badge&logo=render&logoColor=white&labelColor=0d1117)](https://render.com)

<br/>

> **Standard analytics tell you *where* users leave.**
> **SignalFlow tells you *why.***

<br/>

[📺 Watch Demo](https://youtu.be/N4dFYWoTasc?si=oXm0m6Dpef4cDyEr) · [🌍 Live App](https://signal-flow-ai-dashboard.onrender.com) · [📂 Source Code](https://github.com/Surendra77-pixel/signal-flow-ai-dashboard)

</div>

---

## ⚡ What Is SignalFlow??

**SignalFlow** is an intelligent, real-time analytics dashboard that detects, analyzes, and diagnoses user drop-offs during complex signup flows. It goes beyond traditional funnel analytics by reading **behavioral signals** — rage clicks, hesitation patterns, tab switches — to pinpoint the *exact* reason users abandon your flow.

When a critical drop is detected, SignalFlow's built-in **AI Root-Cause Engine** maps the failure to a specific UX friction point and hands you an **actionable code patch** on the spot..

---

## 🎯 Core Features

| Feature | Description |
|---|---|
| 🔴 **Live Event Stream** | Real-time telemetry simulating thousands of concurrent users |
| 🧠 **AI Root-Cause Engine** | Maps drop-offs to specific UX friction points automatically |
| 😤 **Rage Click Detection** | Identifies frustration signals before users abandon |
| ⏱️ **Hesitation Tracking** | Flags form fields and steps that cause cognitive overload |
| 📱 **Mobile Friction Scoring** | Catches layout bugs on small screens before they cost conversions |
| 🔧 **Auto Code Patches** | Generates hypothetical fixes in real time for detected issues |
| 📊 **8 Funnel Templates** | SaaS, FinTech KYC, E-commerce, Gaming & more pre-loaded |

---

## 🛠️ Tech Stack

<details>
<summary><b>🖥️ Frontend</b></summary>
<br/>

- **React 19** — Highly dynamic, reactive UI with concurrent rendering
- **Vite** — Lightning-fast build tooling and HMR dev server
- **Recharts** — Live-updating funnel and behavioral data visualizations
- **Framer Motion** — Smooth transitions and polished micro-animations
- **Lucide React** — Clean, scalable dashboard iconography

</details>

<details>
<summary><b>⚙️ Backend</b></summary>
<br/>

- **Node.js + Express** — Robust API infrastructure & event simulation engine
- **CORS** — Secure cross-origin resource sharing for the streaming API
- **UUID** — Unique session ID generation for user simulation accuracy

</details>

<details>
<summary><b>🚀 Deployment & CI/CD</b></summary>
<br/>

- **Render** — Unified full-stack Web Service hosting with zero-config deploys
- **GitHub** — Source control + continuous integration triggers on every push

</details>

---

## 🔬 How It Works

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│   NODE.JS BACKEND                                               │
│   ┌──────────────────┐     ┌─────────────────────────────────┐ │
│   │  Simulation Engine│────▶│ 8 Signup Flow Templates         │ │
│   │  (Rage clicks,   │     │ SaaS · FinTech · E-com · Gaming │ │
│   │  Hesitation,     │     └─────────────────────────────────┘ │
│   │  Tab switches)   │                                         │
│   └────────┬─────────┘                                         │
│            │  /api/v1/metrics  (rapid polling)                  │
│            ▼                                                    │
│   REACT DASHBOARD                                               │
│   ┌──────────────────┐     ┌─────────────────────────────────┐ │
│   │  mockApi.js SDK  │────▶│  Live Charts · Drop-off Alerts  │ │
│   └──────────────────┘     └───────────────┬─────────────────┘ │
│                                            │  critical drop?    │
│                                            ▼                    │
│                             ┌─────────────────────────────────┐ │
│                             │  🧠 AI Root-Cause Engine        │ │
│                             │  → Diagnose friction point      │ │
│                             │  → Generate code patch          │ │
│                             └─────────────────────────────────┘ │
└─────────────────────────────────────────────────────────────────┘
```

**Step by step:**

1. **Simulated Event Engine** — The backend simulates 8 different signup flows, generating telemetry that mimics real user behavior at scale.
2. **Behavioral Tracking** — Psychological and technical friction signals (rage clicks, hesitation, tab switches) are captured and timestamped.
3. **SDK Polling** — `mockApi.js` polls `/api/v1/metrics` endpoints rapidly to pull the latest drops and UX anomalies.
4. **React Dashboard** — Live data is visualized through interactive Recharts components showing funnel health in real time.
5. **AI Diagnosis** — On critical drop detection, the Insights Engine identifies the root cause and produces a direct code fix.

---

## 🚀 Getting Started

### Prerequisites

- Node.js `v18+`
- npm `v9+`

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Surendra77-pixel/signal-flow-ai-dashboard.git
cd signal-flow-ai-dashboard

# 2. Install all dependencies
npm install

# 3. Launch both servers concurrently
npm run dev
```

> 🖥️ **Frontend** → `http://localhost:3200`
> ⚙️ **API Server** → `http://localhost:3001`

The `concurrently` package handles launching both the Vite dev server and the Node API in a single terminal session.

---

## 📁 Project Structure

```
signal-flow-ai-dashboard/
├── 📂 server/
│   └── index.js          # Express server + simulation engine
├── 📂 src/
│   ├── 📂 components/    # Dashboard UI components
│   ├── 📂 services/
│   │   └── mockApi.js    # SDK polling layer
│   └── main.jsx          # React entry point
├── 📂 dist/              # Vite production build (served by Express)
├── vite.config.js
└── package.json
```

---

## 🏗️ Development Journey

**Phase 1 — Architecture & API Design**
Built a heavy Node/Express backend capable of producing streaming mock data indistinguishable from real-world telemetry — incorporating varied drop rates and complex multi-step funnel definitions.

**Phase 2 — Dashboard UI Construction**
Scaffolded with Vite + React 19. Built reusable components for the live feed, funnel charts, and alerting panels. Focused strictly on a dark-mode, premium aesthetic suited to a high-end developer tool.

**Phase 3 — Production Deployment**
Modified the Express server to statically serve the compiled Vite `dist` folder. Updated Express routing wildcard mechanics (`app.use`) for full compatibility with Express 5.x — enabling seamless deployment to Render.

---

<div align="center">

---

**Built with 🌊 by [Surendra Manthri](https://github.com/Surendra77-pixel)**

*Have feedback or questions? Feel free to open an issue or reach out!*

[![GitHub](https://img.shields.io/badge/GitHub-Surendra77--pixel-181717?style=for-the-badge&logo=github&labelColor=0d1117)](https://github.com/Surendra77-pixel)

</div>
