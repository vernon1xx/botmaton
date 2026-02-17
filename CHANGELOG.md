# Changelog

All notable changes to Botmaton are documented in this file.

---

## [3.2] - 2026-02-17

### Added
- **Robotics Manager Preview** — 8th tool tile (🤖) on Tools face with orange PREVIEW badge, full description references Book 7 capabilities
- **Import/Migration Tool** — 7th tool tile (📥) on Tools face
- **Robot Fleet Overlay** — Toggle button on Facility Map showing 8 simulated robots (3 AGVs, 2 robotic arms, 1 inspection drone, 1 AMR, 1 android) across 6 buildings
- **Live AGV Movement** — Simulated position updates every 5 seconds for autonomous vehicles
- **Robot Fleet Summary Panel** — Active/Idle/Charging/E-Stop counts with per-building robot listings
- **Safety Dashboard** — Grafana-powered tile on Safety face (incident trends, inspection compliance, permit tracking)
- **Maintenance Dashboard** — Grafana-powered tile on Maintenance face (work order backlogs, PM compliance, MTBF/MTTR)
- **Aura Robot Intelligence** — New intent patterns for robot/AGV/drone/fleet/android/dashboard queries
- **Individual Robot Lookup** — Ask Aura about specific robots by name for location and task info
- **Fleet E-STOP Warnings** — Atlas-01 android in E-STOP state with red pulsing indicator

### Changed
- **Tools face expanded** from 3×2 (6 tiles) to 4×2 (8 tiles) with new `grid-4x2` CSS layout
- **Tour updated** — Safety/Maintenance steps mention dashboards, Tools step mentions Robotics Manager, Facility Map step auto-toggles robot fleet overlay
- **Chat placeholder** updated to reflect new capabilities
- **RobotFleetManager** class handles fleet state, rendering, simulation, and info queries

---

## [3.1] - 2026-02-09

### Added
- **Skip Tour Button** — Users can exit the onboarding tour at any time
- **ElevenLabs Integration** — Professional voice synthesis with Rachelle voice
- **Intelligent Voice Fallback** — Automatically selects female browser voice if ElevenLabs unavailable

### Fixed
- Browser speech synthesis now correctly selects female voice for fallback
- Tour audio stops immediately when skipped

---

## [3.0] - 2026-02-09

### Added
- **10-Step Onboarding Tour** — Aura narrates a guided introduction to the platform
- **Realigned 6-Face Architecture** — Cube faces now match finalized product architecture
- **Tools Face Redesign** — Face 5 uses 3×2 grid with 6 larger tiles for tool access
- **7th Navigation Button** — Facility Map opens as full-screen overlay (not a cube face)
- **72 Tiles** — Complete tile data across all 6 cube faces

### Changed
- Navigation restructured: 6 cube faces + dedicated Facility Map button
- Tools moved from scattered locations to dedicated Tools face
- Improved tile organization per domain

---

## [2.0] - 2026-02-08

### Added
- **Aura AI Assistant** — Voice-enabled AI with natural language queries
- **Audio-Reactive Visuals** — Cube glow, particle acceleration, and visualizer bars respond to Aura's voice
- **Voice Input/Output** — Web Speech API integration for hands-free operation
- **Time-Based Greetings** — Aura says good morning/afternoon/evening based on local time
- **Query Matching System** — Natural language navigation ("Show me LOTO for Boiler 1")

### Changed
- Complete visual overhaul with cyan/green color scheme
- Enhanced particle network with audio-reactive behaviors
- Status indicator shows "Aura Speaking..." during voice output

---

## [1.0] - 2026-02-07

### Added
- **3D Rotating Cube Interface** — CSS 3D transforms with drag-to-rotate
- **6 Configurable Faces** — Tile grids for organizing facility content
- **Bottom Navigation Bar** — Quick access to each cube face
- **Tile Detail Panels** — Click tiles to view expanded content
- **Particle Network Background** — Canvas-based animated background
- **Dark Futuristic Theme** — Industrial sci-fi aesthetic

### Technical
- Single-file HTML prototype (self-contained)
- Vanilla JavaScript (no frameworks)
- CSS 3D transforms for hardware acceleration
- Canvas API for particle effects

---

## Version Summary

| Version | Date | Highlight |
|---------|------|-----------|
| 3.2 | 2026-02-17 | Robotics Manager preview, dashboards, robot fleet overlay |
| 3.1 | 2026-02-09 | ElevenLabs voice + Skip Tour |
| 3.0 | 2026-02-09 | Onboarding tour + architecture alignment |
| 2.0 | 2026-02-08 | Aura AI + audio-reactive visuals |
| 1.0 | 2026-02-07 | Initial 3D cube prototype |

---

*For the complete product roadmap and development phases, contact vernonxx1@gmail.com*
