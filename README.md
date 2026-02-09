# 🤖 Botmaton

**Industrial Facility Intelligence Platform**

*Powered by Aura AI*

<div align="center">

[![Live Demo](https://img.shields.io/badge/Demo-Live-00d4ff?style=for-the-badge)](https://vernon1xx.github.io/botmaton/prototypes/botmaton-v3.1-aura.html)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/Version-3.1-00ff88?style=for-the-badge)](#changelog)

**[🌟 Try the Live Demo →](https://vernon1xx.github.io/botmaton/prototypes/botmaton-v3.1-aura.html)**

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
| 🛡️ **Safety** | Compliance & Protection | LOTO procedures, JSAs, incidents, PPE, permits |
| 🏭 **Production** | Operations | Schedules, output tracking, quality metrics, SOPs |
| 🔧 **Maintenance** | Asset Management | Work orders, PM schedules, equipment registry, parts |
| 🌿 **Environmental** | Regulatory | Air quality, water, waste tracking, permits |
| ⚙️ **Tools** | Configuration | Platform setup, reports, data import |

Plus a **7th button** — the **Interactive Facility Map** — a full-screen drill-down view from campus level to individual equipment components.

---

## 🌟 Meet Aura

Aura is more than a chatbot. She's a facility operations AI with full platform knowledge:

- **Natural Language Queries** — "Show me LOTO for Boiler 1" or "What's overdue in Building C?"
- **Voice Input/Output** — Hands-free operation with professional text-to-speech
- **Audio-Reactive Visuals** — The cube glows and particles dance when Aura speaks
- **Guided Onboarding** — "Take a Tour" and Aura walks you through the entire platform
- **Time-Aware Greetings** — Good morning, afternoon, or evening based on your local time

> 💡 **Try it:** Open the [demo](https://vernon1xx.github.io/botmaton/prototypes/botmaton-v3.1-aura.html), enable sound, and click "Take a Tour"

---

## 🎯 Built For Industry

Botmaton is designed for real industrial environments:

- **Lumber & Wood Products** — Sawmills, planer mills, dry kilns
- **Manufacturing** — Assembly lines, machine shops, fabrication
- **Food & Beverage** — Processing plants, packaging, cold storage
- **Chemical Processing** — Refineries, batch processing, hazmat
- **Water/Wastewater** — Treatment plants, pump stations
- **Energy & Utilities** — Power generation, distribution

The platform connects to the backend infrastructure taught in our documentation series (Docker, Grafana, N8N, Ollama, PostgreSQL, InfluxDB) to deliver real operational intelligence.

---

## 📚 The Industrial AI Platform Documentation Series

Botmaton is the capstone of a comprehensive **6-book technical documentation series** covering everything needed to deploy AI-powered systems in industrial facilities:

| Book | Title | What You'll Learn |
|------|-------|-------------------|
| 📕 **Book 1** | Getting Started | Docker fundamentals, container orchestration, development environment |
| 📗 **Book 2** | Mastering Your Foundation | MCP servers, database infrastructure, Ollama AI setup |
| 📘 **Book 3** | Building Real Applications | Grafana dashboards, N8N workflows, practical AI integration |
| 📙 **Book 4** | Advanced Integration | Predictive maintenance, compliance automation, alert intelligence |
| 📓 **Book 5** | AI Mastery | Model optimization, prompt engineering, production deployment |
| 📔 **Book 6** | Botmaton | Building the complete industrial intelligence platform |

**340+ pages** of production-ready documentation with step-by-step instructions, screenshots, and real-world examples.

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
| **Database** | PostgreSQL | Operational data (36-table schema) |
| **Automation** | N8N | Workflow engine and integrations |
| **Dashboards** | Grafana | Real-time monitoring and KPIs |
| **Time-Series** | InfluxDB | Sensor data and metrics |
| **Containers** | Docker | Self-hosted deployment |

**100% self-hosted** — Your data stays on your network.

---

## 🚀 Quick Start (Demo)

1. **[Open the Live Demo](https://vernon1xx.github.io/botmaton/prototypes/botmaton-v3.1-aura.html)**
2. Click **"Take a Tour"** to meet Aura
3. **Drag the cube** to explore different faces
4. **Click tiles** to see content panels
5. Try the **🎤 voice button** (Chrome recommended)
6. Click **"Facility Map"** for the full-screen spatial view

---

## 📁 Repository Structure

```
botmaton/
├── prototypes/
│   ├── botmaton-v3.1-aura.html   ← Current version
│   ├── botmaton-v3-aura.html     ← Previous release
│   ├── botmaton-v2-aura.html     ← Audio-reactive update
│   └── botmaton-v1.html          ← Original prototype
├── docs/
│   └── README.md
├── CHANGELOG.md
├── LICENSE
└── README.md
```

---

## 🔮 Roadmap

**Completed:**
- ✅ 3D cube interface with 6 faces
- ✅ Aura AI with voice I/O
- ✅ Audio-reactive visuals
- ✅ ElevenLabs professional voice integration
- ✅ 10-step onboarding tour
- ✅ Interactive Facility Map (7th button)
- ✅ Complete 36-table database schema
- ✅ 6-book documentation series

**In Development:**
- 🔨 Botmaton Core API layer
- 🔨 User management & role-based access
- 🔨 Facility Builder tool
- 🔨 Maintenance Manager (CMMS)

**Planned:**
- 📋 LOTO Builder
- 📋 Compliance Tracker
- 📋 Report Builder
- 📋 Industry template packs
- 📋 Mobile-responsive design
- 📋 Offline mode

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
