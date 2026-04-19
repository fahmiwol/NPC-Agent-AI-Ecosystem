# 🧠 NPC Agent AI Ecosystem

> **Build living AI-powered NPCs — identity, world, skills, tools, and workflows in one open platform.**

[![License: MIT](https://img.shields.io/badge/License-MIT-cyan.svg)](LICENSE)
[![Status](https://img.shields.io/badge/status-active%20development-7c3aed.svg)]()
[![Stack](https://img.shields.io/badge/stack-Three.js%20%7C%20Node.js%20%7C%20LLM-00f5ff.svg)]()

---

## What is this?

NPC Agent AI Ecosystem is an open platform for creating **Agentic AI NPCs** — characters that don't just look alive, they *are* alive. Each NPC has an identity, a skillset, a role in a 3D world, and the ability to execute real tasks using LLMs and connected tools.

Think of it as **hiring AI employees** — you define who they are, what they can do, and they work autonomously 24/7.

---

## 5 Core Modules

### 1. 🧑 NPC Identity System
Define who your agent is — not just a name, but a full profile.
- **Jobdesk** — role, responsibilities, daily tasks
- **Identity** — personality traits, speech style, backstory, gender
- **Skills** — granular capabilities (design, research, writing, coding…)
- **Capability** — linked LLM modules, tool access, media providers
- Visual avatar editor — skin tone, hair, outfit, accessories, rarity tier
- AI portrait generator — generate NPC portrait from appearance data

### 2. 🏗️ World & Room Builder
Design the space your agents live and work in.
- 3D isometric world (Three.js v0.162) — buildings, floors, rooms
- Drag-and-drop room layout + building position editor
- Day/night cycle, outdoor city with roads, parks, NPC crowd
- Per-room tile grid — place agents and objects anywhere

### 3. 📦 Object + Function System
Every object in the world can have a function — or just be decoration.
- Furniture catalogue (27+ items, 7 categories, rarity tiers)
- Objects can be: decorative, interactive, or AI-connected
- Click an object → trigger a workflow, open a panel, connect to a service
- Room Decoration Panel — buy objects with in-world coins

### 4. 🛠️ Tools & Skills Catalogue
A registry of everything agents can do.
- Module registry — 30+ task modules (research, write, design, analyze…)
- Media tools — 15 image + 6 video + 5 TTS + 6 design providers
- Per-agent tool assignment — each NPC has a preferred tool stack
- Skills grow over time — self-learning loop via web research + adoption

### 5. 📋 SOP Visual Script Builder
Build agent workflows without writing code.
- See: [AI-agent-Workflow-visual-script-builder](https://github.com/fahmiwol/AI-agent-Workflow-visual-script-builder)
- Node-based drag-drop editor, 4 step types: `agent` · `service` · `notify` · `wait`
- Multi-agent chains — output of one agent feeds the next
- Send to Engine — run workflows live against real LLMs
- Schedule triggers — cron, event, manual

---

## Architecture

```
Browser (Three.js 3D World)
    └── Agents / Rooms / Objects (interactive)
            │
            ▼
Gateway Server (Node.js :9797)
    ├── NPC Registry       — profiles, appearance, memory
    ├── Agent Capabilities — skills, tools, LLM routing
    ├── Module Registry    — task execution engine
    ├── Workflow Engine    — multi-step agent chains
    ├── Autonomy Loop      — heartbeat, emotions, self-learning
    └── Media Tools        — image / video / TTS / design providers
            │
            ▼
LLM Providers
Anthropic · OpenAI · Mistral · Gemini · OpenRouter · Ollama
```

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| 3D World | Three.js v0.162 |
| Backend | Node.js + Express + Socket.io |
| AI | Multi-provider LLM (Claude, GPT-4o, Mistral, Gemini, OpenRouter, Ollama) |
| Realtime | Socket.io — agent events, workflow steps, emotion updates |
| Media | Pollinations (free), HuggingFace, ComfyUI, Edge TTS, ffmpeg |
| Storage | JSON + atomic writes (no DB required) |

---

## Key Features

| Feature | Status |
|---------|--------|
| 48 AI agent NPCs with unique roles + personalities | ✅ |
| Per-agent model routing (Haiku, GPT-4o, Mistral…) | ✅ |
| SSE streaming — live token-by-token chat in 3D world | ✅ |
| Emotion system — 7 states, decay, affects behavior | ✅ |
| Self-learning loop — agents research + adopt new skills | ✅ |
| Content automation — microstock, social media, YouTube | ✅ |
| Design Studio — AI image gen, remove bg, canvas editor | ✅ |
| WA Agent — chat with NPCs via WhatsApp | ✅ |
| Credit system — in-world coin economy | ✅ |
| Autopilot — all agents auto-start on boot | ✅ |
| NPC Asset Generator | 🔧 In progress |
| Public demo mode | 📋 Planned |
| Multi-tenant SaaS | 📋 Planned |

---

## Getting Started

```bash
git clone https://github.com/fahmiwol/NPC-Agent-AI-Ecosystem.git
cd NPC-Agent-AI-Ecosystem
npm install
cp server/settings.example.json server/settings.json
node server/gateway.js
# → http://localhost:8080  (3D world)
# → http://localhost:9797/admin/  (admin panel)
```

> Requires: Node.js 18+ · Optional: Python 3.10+ for AI tools (rembg, edge-tts)

---

## Roadmap

| Phase | Focus | Status |
|-------|-------|--------|
| 1 | NPC Editor + Room Builder + Map Builder | ✅ Done |
| 2 | AI Portrait Generator + Outdoor NPC sync | ✅ Done |
| 3 | NPC Asset Generator + World Builder Full | 🔧 Active |
| 4 | SaaS extraction + multi-tenant + marketplace | 📋 Planned |

---

## Ecosystem

```
fahmiwol/mighantect-3d                           ← Private data source
fahmiwol/NPC-Agent-AI-Ecosystem                  ← This repo
fahmiwol/AI-agent-Workflow-visual-script-builder ← Visual scripting engine
```

---

## License

MIT — free to use, build on, and extend.  
Built by [Fahmi Ghani](https://github.com/fahmiwol) · Part of TIRANYX ecosystem

> *"An office that never sleeps."*
