# 🤖 Botmaton

**Industrial Facility Intelligence Platform**

*Powered by Aura AI*

<div align="center">

[![Live Demo](https://img.shields.io/badge/Demo-Live-00d4ff?style=for-the-badge)](https://vernon1xx.github.io/botmaton/prototypes/botmaton-v3.2-aura.html)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/Version-3.2-00ff88?style=for-the-badge)](#changelog)

**[🌟 Try the Live Demo →](https://vernon1xx.github.io/botmaton/prototypes/botmaton-v3.2-aura.html)**

</div>

---

## What is Botmaton?

Botmaton is an AI-powered industrial facility management platform featuring a **3D cube interface** for intuitive navigation of facility operations — maintenance, safety, production, environmental compliance, and more.

**Aura** is Botmaton's intelligent voice assistant. She responds to natural language queries, guides users through the platform, and brings the interface to life with audio-reactive visuals.

Built for **self-hosted deployment** with no cloud dependencies and no per-user subscription fees.

---

## 🎲 The 3D Cube Interface

Six configurable faces organize your facility's operational data:

| Face | Domain | What Lives Here |
|------|--------|-----------------|
| 🏢 **Administration** | HR & Policy | Employee directory, handbooks, training records, forms |
| 🛡️ **Safety** | Compliance & Protection | LOTO procedures, JSAs, incidents, PPE, safety dashboard |
| 🏭 **Production** | Operations | Schedules, output tracking, quality metrics, SOPs |
| 🔧 **Maintenance** | Asset Management | Work orders, PM schedules, equipment registry, maintenance dashboard |
| 🌿 **Environmental** | Regulatory | Air quality, water, waste tracking, permits |
| ⚙️ **Tools** | Configuration | 8 modular tools — platform setup, reports, data import, robotics preview |

Plus a **7th button** — the **Interactive Facility Map** — a full-screen drill-down view from campus level to individual equipment components, now with a **Robot Fleet overlay** showing real-time robot positions across your facility.

---

## 🌟 Meet Aura

Aura is more than a chatbot. She's a facility operations AI with full platform knowledge:

- **Natural Language Queries** — "Show me LOTO for Boiler 1" or "What's overdue in Building C?"
- **Voice Input/Output** — Hands-free operation with professional text-to-speech via ElevenLabs
- **Audio-Reactive Visuals** — The cube glows and particles dance when Aura speaks
- **Guided Onboarding** — "Take a Tour" and Aura walks you through the entire platform
- **Robot Fleet Awareness** — "Where is Atlas-01?" or "Show me robot fleet status"
- **Dashboard Navigation** — "Show me the safety dashboard" routes directly to the right face

> 💡 **Try it:** Open the [demo](https://vernon1xx.github.io/botmaton/prototypes/botmaton-v3.2-aura.html), enable sound, and click "Take a Tour"

---

## 🤖 Robotics Manager Preview

Version 3.2 introduces a preview of the **Robotics Manager** — Botmaton's 8th modular tool for training, monitoring, and controlling industrial robots:

- **Robot Fleet Overlay** — Toggle real-time robot positions on the Facility Map
- **8 Simulated Robots** — AGVs, robotic arms, inspection drone, AMR, and android
- **Live Movement** — AGVs simulate position updates every 5 seconds
- **Safety Monitoring** — E-STOP indicators with red pulsing alerts
- **Fleet Summary** — Active, idle, charging, and emergency stop counts at a glance

Robots are treated as equipment within the existing facility hierarchy — they inherit maintenance scheduling, LOTO procedures, and compliance tracking automatically. Full development coming in Book 7.

---

## 📊 Grafana-Powered Dashboards

New in v3.2 — dedicated operational dashboards on the Safety and Maintenance faces:

- **Safety Dashboard** — Incident trends, inspection compliance, permit tracking
- **Maintenance Dashboard** — Work order backlogs, PM compliance, MTBF/MTTR metrics

These demonstrate Botmaton's integration with the Grafana monitoring stack for real-time operational intelligence.

---

## 🎯 Built For Industry

Botmaton is designed for real industrial environments:

- **Lumber & Wood Products** — Sawmills, planer mills, dry kilns
- **Manufacturing** — Assembly lines, machine shops, fabrication
- **Food & Beverage** — Processing plants, packaging, cold storage
- **Chemical Processing** — Refineries, batch processing, hazmat
- **Water/Wastewater** — Treatment plants, pump stations
- **Energy & Utilities** — Power generation, distribution

The platform connects to backend infrastructure (Docker, Grafana, N8N, Ollama, PostgreSQL, InfluxDB) to deliver real operational intelligence — all self-hosted on your network.

---

## 📚 Documentation & Resources

### Interactive Resources

| Resource | Description |
|----------|-------------|
| [🎮 Live Demo](https://vernon1xx.github.io/botmaton/prototypes/botmaton-v3.2-aura.html) | Interactive prototype with Aura AI assistant |
| [🏗️ System Architecture](https://vernon1xx.github.io/botmaton/docs/Redundant_AI_Systems_Architecture_Version_3.html) | 5-tab visual architecture reference |

### The Industrial AI Platform Documentation Series

Botmaton is the capstone of a comprehensive **6-book technical documentation series** covering everything needed to deploy AI-powered systems in industrial facilities:

| Book | Title | What You'll Learn |
|------|-------|-------------------|
| 📕 **Book 1** | Getting Started | Docker fundamentals, container orchestration, development environment |
| 📗 **Book 2** | Mastering Your Foundation | MCP servers, database infrastructure, Ollama AI setup |
| 📘 **Book 3** | Building Real Applications | Grafana dashboards, N8N workflows, practical AI integration |
| 📙 **Book 4** | Advanced Integration | Predictive maintenance, compliance automation, alert intelligence |
| 📓 **Book 5** | AI Mastery | Model optimization, prompt engineering, production deployment |
| 📔 **Book 6** | Botmaton | Building the complete industrial intelligence platform (8 chapters, 52 images) |

**All 6 books complete** — 400+ pages of production-ready documentation with step-by-step instructions, screenshots, and real-world examples.

### 📩 Request Access

The documentation series is available upon request for facilities interested in implementing industrial AI systems.

**Contact:** vernonxx1@gmail.com

---

## 💻 Technology Stack

| Layer | Technology | Purpose |
|-------|------------|---------|
| **Frontend** | HTML5, CSS3, JavaScript | 3D cube interface |
| **3D Engine** | CSS 3D Transforms | Hardware-accelerated rotation |
| **Visuals** | Canvas API | Particle network background |
| **Voice** | Web Speech API + ElevenLabs | Voice I/O with professional TTS |
| **AI Backend** | Ollama | Local LLM for Aura intelligence |
| **API** | Node.js / Express | REST API with JWT auth & RBAC |
| **Database** | PostgreSQL | Operational data (47-table schema) |
| **Automation** | N8N | Workflow engine, backups, alerting |
| **Dashboards** | Grafana | Real-time monitoring and KPIs |
| **Time-Series** | InfluxDB | Sensor data, metrics, telemetry |
| **Containers** | Docker | Self-hosted deployment (7 services) |

**100% self-hosted** — Your data stays on your network.

---

## 🚀 Quick Start (Demo)

1. **[Open the Live Demo](https://vernon1xx.github.io/botmaton/prototypes/botmaton-v3.2-aura.html)**
2. Click **"Take a Tour"** to meet Aura
3. **Drag the cube** to explore different faces
4. **Click tiles** to see content panels
5. Try the **🎤 voice button** (Chrome recommended)
6. Click **"Facility Map"** and toggle **"Robot Fleet"** for the fleet overlay
7. Ask Aura: *"Where is Atlas-01?"* or *"Show me robot fleet status"*

---

## 📁 Repository Structure

```
botmaton/
├── prototypes/
│   ├── botmaton-v3.2-aura.html   ← Current version
│   ├── botmaton-v3.1-aura.html   ← ElevenLabs + Skip Tour
│   ├── botmaton-v3-aura.html     ← Onboarding tour
│   ├── botmaton-v2-aura.html     ← Audio-reactive update
│   └── botmaton-v1.html          ← Original prototype
├── docs/
│   └── Redundant_AI_Systems_Architecture_Version_3.html
├── CHANGELOG.md
├── LICENSE
└── README.md
```

---

## 🔮 Roadmap

**Completed:**
- ✅ 3D cube interface with 6 configurable faces
- ✅ Aura AI with voice I/O and ElevenLabs integration
- ✅ Audio-reactive visuals (Web Audio API)
- ✅ 10-step role-adaptive onboarding tour
- ✅ Interactive Facility Map with drill-down
- ✅ Complete 47-table database schema (deployed)
- ✅ REST API with JWT authentication & RBAC
- ✅ Aura Intelligence Engine (Ollama, personality system, context engine)
- ✅ Voice services (STT, TTS with ElevenLabs proxy)
- ✅ Cube navigation & action execution via chat
- ✅ Production containerization (Docker, 7 services)
- ✅ Monitoring dashboard (Grafana, 9 panels)
- ✅ Automated backup & alerting workflows (N8N)
- ✅ 6-book documentation series
- ✅ Standalone Deployment Guide
- ✅ Robotics Manager preview with robot fleet overlay

**Coming Next — Book 7: Industrial Robotics & Automation:**
- 📋 Robot registry & safety zone management
- 📋 Teach mode & waypoint programming
- 📋 Real-time telemetry (WebSocket streaming)
- 📋 Aura voice control for robots
- 📋 Protocol adapters (ROS, OPC-UA, MQTT)
- 📋 Simulation & testing without real hardware

---

## 📜 License

MIT License — See [LICENSE](LICENSE) for details.

---

## 👤 Author

Created by **Vernon Buchanan**

Industrial Systems • AI Integration • Facility Intelligence

📧 vernonxx1@gmail.com

---

<div align="center">

**Botmaton** — *Industrial Facility Intelligence* 🤖

**Aura** — *Adaptive Universal Response Agent* 🌟

---

*Built for the facilities that keep the world running.*

</div>
