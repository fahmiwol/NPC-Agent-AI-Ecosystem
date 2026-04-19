# Agent Master Registry
**Mighantect 3D × 100-Agent Ecosystem Spec — Unified View**

> Combined registry of 28 live agents (Mighantect 3D) + 100-agent specification (Tiranyx/Omnyx/SIDIX roadmap).  
> Status: `🟢 Live` | `🟡 Planned` | `🔵 Mapped` (existing agent covers this role)

---

## Part 1 — Live Agents (Mighantect 3D, 28 agents)

These agents are active in the platform at `localhost:9797`. Each has a 3D NPC, identity, skills, and task modules.

| ID | Name | Role | Skills | Modules |
|----|------|------|--------|---------|
| `receptionist-ai` | Rina | Front Office / Brand Communication | client onboarding · marketing strategy · CRM | — |
| `designer` | Dina Mahesa | Visual Designer | visual design · AI image generation · microstock | `visual_design` · `media_generate` |
| `profesor` | Prof. Toard | Head of Innovation & Research | research synthesis · ideation · experiment design | `image_analyzer` |
| `iris` | Iris | Field Intelligence Agent | pipeline monitoring · anomaly detection · workflow orchestration | — |
| `pm-agent` | Dika | Project Manager | sprint planning · timeline · dependency mapping | `pm_tasks` · `content_pipeline` |
| `strategy-agent` | Maestro | Strategy Lead | market analysis · SWOT · competitive intelligence | `strategy_plan` · `marketing_analytics` |
| `hunter` | Hana Hunter | Product Researcher | trend spotting · product research · viral analysis | `product_hunt` · `kol_tracking` |
| `reviewer` | Reza Review | Content Reviewer | quality assessment · fact verification · rubric evaluation | `content_review` |
| `linker` | Lina Link | Affiliate Manager | affiliate links · funnel optimization · UTM tracking | `link_builder` |
| `social_bot` | Social Bot | Social Media Bot | multi-platform posting · engagement automation | `social_publish` |
| `yt_bot` | YT Bot | YouTube Bot | YouTube SEO · thumbnail · analytics | `yt_publish` |
| `jadwal_bot` | Jadwal Bot | Scheduler Bot | cron scheduling · calendar sync · batch publishing | `scheduler` |
| `maintenance-bot` | Bolt | System Maintenance | server health · error detection · uptime monitoring | `maintenance_check` |
| `thread_buzzer` | Tara Thread | X/Threads Buzzer | thread writing · X/Twitter engagement · reply automation | `social_buzz` |
| `fb_buzzer` | Fani FB | Facebook Buzzer | FB page management · community · audience segmentation | `fb_buzz` |
| `tiktok_buzzer` | Tino TikTok | TikTok Buzzer | short video scripting · trend riding · TikTok SEO | `tiktok_buzz` |
| `yt_buzzer` | Yudi YT | YouTube Buzzer | channel growth · subscriber acquisition · retention | `yt_buzz` |
| `blogger_bot` | Blog Bot | Blog Publisher | blog automation · on-page SEO · CMS management | `blog_publish` |
| `kurir` | Eko FTP | Upload Courier | FTP/SFTP upload · batch transfer · microstock submission | `upload_mgr` |
| `kurator` | Kania Putri | Content Curator / QC | quality assurance · compliance checking · approval workflow | `quality_check` |
| `pustakawan` | Bima Arsip | Metadata Librarian | keyword tagging · SEO taxonomy · archive organization | `keyword_research` |
| `wordsmith` | Wira Langit | Copywriter | copywriting · brand voice · prompt engineering | `prompt_gen` · `tts_generate` |
| `riset_bot` | Rio Riset | Content Researcher | topic research · trend analysis · viral identification | `research_content` |
| `penulis` | Putri Pena | Content Writer | article writing · script writing · SEO content | `write_content` |
| `editor_konten` | Edi Editor | Content Editor | copy editing · tone consistency · content approval | `edit_content` |
| `affiliate_mgr` | Ayu Afiliasi | Affiliate Program Manager | commission tracking · partner outreach · revenue reporting | `affiliate_manage` |
| `scheduler_konten` | Sari Jadwal | Content Scheduler | content calendar · editorial planning · batch scheduling | `post_schedule` |
| `monitor_bot` | Moni Watcher | Account Monitor | engagement tracking · shadowban detection · health reporting | `account_monitor` |

**Task Modules: 33** (27 original + 6 new from Mighan-tasks)

---

## Part 2 — 100-Agent Spec × Mighantect Mapping

Each of the 100 planned agents mapped to: existing Mighantect agent (if covered) or target new agent ID.

### 🟠 Cluster 1 — Content & Creative (1–10)

| # | Spec Role | Status | Mighantect Agent | Notes |
|---|-----------|--------|-----------------|-------|
| 1 | Content Strategist Agent | 🔵 Mapped | `strategy-agent` (Maestro) | Add content strategy skill |
| 2 | Copywriter Agent | 🟢 Live | `wordsmith` (Wira Langit) | Fully covered |
| 3 | Visual Designer Agent | 🟢 Live | `designer` (Dina Mahesa) | Fully covered |
| 4 | Video Script Agent | 🟡 Planned | `video_script_agent` | New — needs TikTok Creative scraper |
| 5 | Video Editor Brief Agent | 🟡 Planned | `video_editor_agent` | New — FFmpeg + Whisper stack |
| 6 | Microstock Producer Agent | 🔵 Mapped | `designer` + `kurir` + `kurator` | Pipeline already live |
| 7 | Thumbnail Designer Agent | 🔵 Mapped | `designer` + `yt_bot` | Add CTR prediction module |
| 8 | Blog Writer Agent | 🟢 Live | `blogger_bot` + `penulis` | Covered |
| 9 | Caption Engine Agent | 🔵 Mapped | `penulis` + `social_bot` | Add multi-platform formatter |
| 10 | Music/SFX Curator Agent | 🟡 Planned | `music_agent` | New — TikTok audio + license check |

### 🔵 Cluster 2 — Research & Intelligence (11–18)

| # | Spec Role | Status | Mighantect Agent | Notes |
|---|-----------|--------|-----------------|-------|
| 11 | Market Research Agent | 🔵 Mapped | `strategy-agent` + `hunter` | Add TAM/SAM framework |
| 12 | Competitor Intelligence Agent | 🔵 Mapped | `hunter` (Hana) | Add Playwright scraper module |
| 13 | Trend Hunter Agent | 🔵 Mapped | `hunter` + `iris` | Velocity detection needed |
| 14 | SEO Research Agent | 🔵 Mapped | `pustakawan` + `hunter` | Add Ahrefs/Google module |
| 15 | Academic Research Agent | 🔵 Mapped | `profesor` (Prof. Toard) | Add arXiv/Semantic Scholar module |
| 16 | Price Intelligence Agent | 🟡 Planned | `price_agent` | New — marketplace scraper |
| 17 | Social Listening Agent | 🔵 Mapped | `monitor_bot` | Add sentiment analysis |
| 18 | Regulatory Watch Agent | 🟡 Planned | `compliance_agent` | New — BPOM/Kominfo scraper |

### 🟢 Cluster 3 — Sales, CRM & Customer (19–26)

| # | Spec Role | Status | Mighantect Agent | Notes |
|---|-----------|--------|-----------------|-------|
| 19 | Lead Qualifier Agent | 🔵 Mapped | `receptionist-ai` | Add BANT scoring |
| 20 | WA Customer Service Agent | 🟢 Live | WA agent (gateway) | Already running via Baileys |
| 21 | Sales Proposal Agent | 🟡 Planned | `proposal_agent` | New — PDF generation |
| 22 | Follow-Up Agent | 🟡 Planned | `followup_agent` | New — nurture sequence engine |
| 23 | Upsell/Cross-sell Agent | 🟡 Planned | `upsell_agent` | New — recommendation engine |
| 24 | Churn Prediction Agent | 🟡 Planned | `churn_agent` | New — ML risk scoring |
| 25 | KOL/Affiliate Manager Agent | 🔵 Mapped | `affiliate_mgr` + `hunter` | Add KOL discovery module |
| 26 | Live Commerce Assistant Agent | 🟡 Planned | `live_commerce_agent` | New — TikTok Live API |

### 🟣 Cluster 4 — Operations & Internal (27–34)

| # | Spec Role | Status | Mighantect Agent | Notes |
|---|-----------|--------|-----------------|-------|
| 27 | HR/Absensi Agent | 🟡 Planned | `hr_agent` | New — Absensi Digital SaaS tie-in |
| 28 | Finance/Kas Agent | 🟡 Planned | `finance_agent` | New — HOT priority SaaS |
| 29 | Invoice & Collection Agent | 🟡 Planned | `invoice_agent` | New — Midtrans + WA |
| 30 | Procurement Agent | 🟡 Planned | `procurement_agent` | New — Abra Bioenergi use case |
| 31 | Inventory Agent | 🟡 Planned | `inventory_agent` | New — Gudang & Trading SaaS |
| 32 | Production Planner Agent | 🟡 Planned | `production_agent` | New — Abra Briket pabrik |
| 33 | Quality Control Agent | 🔵 Mapped | `kurator` (Kania) | Extend with lab parsing |
| 34 | Meeting Notes Agent | 🟡 Planned | `notulis_agent` | New — Whisper + Google Calendar |

### 🔴 Cluster 5 — Tech, Dev & Automation (35–42)

| # | Spec Role | Status | Mighantect Agent | Notes |
|---|-----------|--------|-----------------|-------|
| 35 | Code Reviewer Agent | 🔵 Mapped | `reviewer` (Reza) | Extend with AST/security scan |
| 36 | Bug Triage Agent | 🟡 Planned | `bug_triage_agent` | New — Linear MCP |
| 37 | DevOps/Deploy Agent | 🔵 Mapped | `maintenance-bot` (Bolt) | Add PM2/Nginx management |
| 38 | Database Agent | 🟡 Planned | `dba_agent` | New — query optimization |
| 39 | API Integration Agent | 🟡 Planned | `api_agent` | New — OpenAPI wrapper gen |
| 40 | Scraper/Crawler Agent | 🔵 Mapped | `iris` (field agent) | Add Playwright scraper module |
| 41 | RAG/Knowledge Base Agent | 🔵 Mapped | `profesor` (Prof. Toard) | SIDIX brain integration |
| 42 | Workflow Builder Agent | 🟢 Live | Visual Workflow Editor | Already built — SOP module |

### 🟡 Cluster 6 — Growth, Ads & Analytics (43–47)

| # | Spec Role | Status | Mighantect Agent | Notes |
|---|-----------|--------|-----------------|-------|
| 43 | Ads Manager Agent | 🟡 Planned | `ads_manager_agent` | New — Meta + TikTok Ads API |
| 44 | Ads Optimizer Agent | 🟡 Planned | `ads_optimizer_agent` | New — bid + A/B automation |
| 45 | Analytics Reporter Agent | 🔵 Mapped | `strategy-agent` + `marketing_analytics` | Module already added |
| 46 | Attribution Agent | 🟡 Planned | `attribution_agent` | New — MMM + touchpoint |
| 47 | Conversion Rate Optimizer | 🟡 Planned | `cro_agent` | New — funnel + hypothesis |

### ⚫ Cluster 7 — Experimental (48–50)

| # | Spec Role | Status | Mighantect Agent | Notes |
|---|-----------|--------|-----------------|-------|
| 48 | Token/Blockchain Agent | 🟡 Planned | `blockchain_agent` | New — Solana/ERC20 |
| 49 | Game Design Agent | 🟡 Planned | `game_design_agent` | New — Wrapcity use case |
| 50 | Self-Evolving Skill Learner | 🔵 Mapped | `iris` + SIDIX | Self-learning loop already in agent-autonomy.js |

### 🎮 Cluster 8 — Builder Agents (51–62)

| # | Spec Role | Status | Mighantect Agent | Notes |
|---|-----------|--------|-----------------|-------|
| 51 | 3D Modeler Agent | 🟡 Planned | `modeler_3d_agent` | New — Meshy.ai / Tripo3D |
| 52 | 3D Scene Composer Agent | 🟡 Planned | `scene_composer_agent` | New — Three.js scene design |
| 53 | 3D Texture/Material Agent | 🟡 Planned | `texture_agent` | New — PBR material gen |
| 54 | Rigging & Animation Agent | 🟡 Planned | `rig_agent` | New — Mixamo pipeline |
| 55 | Game Logic Builder Agent | 🟡 Planned | `game_logic_agent` | New — FSM + combat system |
| 56 | Level/World Generator Agent | 🟡 Planned | `world_gen_agent` | New — WFC + procedural |
| 57 | UI/UX Designer Agent | 🟡 Planned | `uiux_agent` | New — Figma MCP |
| 58 | Design System Builder Agent | 🟡 Planned | `design_system_agent` | New — Storybook + tokens |
| 59 | Brand Identity Builder Agent | 🔵 Mapped | `designer` | Extend with brand guideline PDF |
| 60 | Pitch Deck Builder Agent | 🟡 Planned | `pitch_deck_agent` | New — Canva API |
| 61 | Landing Page Builder Agent | 🟡 Planned | `landing_page_agent` | New — Next.js template |
| 62 | Video Producer Agent | 🔵 Mapped | `youtube-agent` (gateway) | Already built — TTS+FFmpeg+YouTube |

### 💻 Cluster 9 — Programmer & Tech (63–70)

| # | Spec Role | Status | Mighantect Agent | Notes |
|---|-----------|--------|-----------------|-------|
| 63 | Frontend Developer Agent | 🟡 Planned | `frontend_dev_agent` | New — Figma-to-code |
| 64 | Backend Developer Agent | 🟡 Planned | `backend_dev_agent` | New — API scaffolder |
| 65 | Full-Stack Feature Agent | 🟡 Planned | `fullstack_agent` | New — Prisma + Next.js |
| 66 | Mobile Developer Agent | 🟡 Planned | `mobile_dev_agent` | New — Expo/RN |
| 67 | Smart Contract Developer Agent | 🟡 Planned | `contract_dev_agent` | New — Hardhat/Anchor |
| 68 | ML Engineer Agent | 🔵 Mapped | SIDIX / `profesor` | SIDIX training pipeline |
| 69 | Data Engineer Agent | 🟡 Planned | `data_eng_agent` | New — ETL + schema |
| 70 | Security Auditor Agent | 🟡 Planned | `security_agent` | New — OWASP/Semgrep |

### 🛒 Cluster 10 — Purchasing & Supply Chain (71–75)

| # | Spec Role | Status | Notes |
|---|-----------|--------|-------|
| 71 | Sourcing Agent | 🟡 Planned | Abra Bioenergi use case |
| 72 | RFQ/Tender Agent | 🟡 Planned | Email + WA automation |
| 73 | Negotiation Assistant Agent | 🟡 Planned | Claude Sonnet reasoning |
| 74 | Contract Management Agent | 🟡 Planned | Notion MCP |
| 75 | Logistics Coordinator Agent | 🟡 Planned | RajaOngkir / Biteship |

### 👥 Cluster 11 — Customer Service (76–80)

| # | Spec Role | Status | Mighantect Agent | Notes |
|---|-----------|--------|-----------------|-------|
| 76 | Multi-Channel CS Agent | 🔵 Mapped | WA agent + `receptionist-ai` | Extend with unified inbox |
| 77 | Ticket Resolution Agent | 🟡 Planned | `ticket_agent` | New — RAG + Linear MCP |
| 78 | Customer Onboarding Agent | 🔵 Mapped | `receptionist-ai` | Add onboarding sequence |
| 79 | Voice of Customer Agent | 🟡 Planned | `voc_agent` | New — review aggregator |
| 80 | Customer Health Score Agent | 🔵 Mapped | `monitor_bot` | Extend with usage scoring |

### 💼 Cluster 12–16 — Sales, PM, Finance, Legal, HR (81–100)

| # | Spec Role | Status | Notes |
|---|-----------|--------|-------|
| 81 | Prospecting/Hunter | 🔵 Mapped | `hunter` | Add LinkedIn scraper |
| 82 | SDR/Outreach Agent | 🟡 Planned | New |
| 83 | Account Executive Agent | 🟡 Planned | New |
| 84 | Account Manager Agent | 🟡 Planned | New |
| 85 | Sales Forecaster Agent | 🔵 Mapped | `strategy-agent` | Add pipeline weighting |
| 86 | Project Manager Agent | 🔵 Mapped | `pm-agent` | Add Linear MCP |
| 87 | Scrum Master Agent | 🔵 Mapped | `pm-agent` | Add sprint/retro modules |
| 88 | Program/Portfolio Manager | 🟡 Planned | New — multi-project |
| 89 | OKR/Goal Tracker | 🟡 Planned | New — Notion MCP |
| 90 | Bookkeeper Agent | 🟡 Planned | New — double-entry + OCR |
| 91 | Financial Reporter Agent | 🟡 Planned | New — PSAK P&L |
| 92 | FP&A Agent | 🟡 Planned | New — scenario modeling |
| 93 | Tax Agent | 🟡 Planned | New — PPh/PPN/DJP |
| 94 | Treasury/Cash Agent | 🟡 Planned | New — cashflow daily |
| 95 | Legal Drafter Agent | 🟡 Planned | New — NDA/PKS/kontrak |
| 96 | Compliance Agent | 🟡 Planned | New — BPOM/UU PDP |
| 97 | HR Recruitment Agent | 🟡 Planned | New — JD + CV screening |
| 98 | HR Performance Agent | 🟡 Planned | New — 1:1 + 360 review |
| 99 | IHOS Philosophy Curator | 🟡 Planned | New — SIDIX governance |
| 100 | Mighan Orchestrator | 🔵 Mapped | WA Role Router + AgentBrain.js | Core routing already live |

---

## Part 3 — Gap Analysis

### Agents Already Live (🟢 or 🔵): 28 + 18 mapped = **46 roles covered**
### Agents Needing New Build: **54 new agents**

**Highest Priority New Agents (revenue impact, 4–8 weeks):**

| Priority | Agent | Why Now |
|----------|-------|---------|
| 🔴 S | `finance_agent` | HOT SaaS — bookkeeping + kasir |
| 🔴 S | `video_script_agent` | TikTok affiliate daily output |
| 🔴 S | `proposal_agent` | Agency sales velocity |
| 🟠 A | `ads_manager_agent` | Client ROAS improvement |
| 🟠 A | `hr_agent` | Absensi Digital SaaS |
| 🟠 A | `ticket_agent` | Support automation Tiranyx |
| 🟡 B | `uiux_agent` | Figma MCP fast design |
| 🟡 B | `modeler_3d_agent` | Wrapcity 2.0 asset pipeline |

---

## Part 4 — Shared Infrastructure (Cross-Cutting)

All 100 agents share these base modules (already implemented in Mighantect):

| Module | Status | File |
|--------|--------|------|
| Multi-LLM routing | 🟢 Live | `server/ai-connector.js` |
| Per-agent model override | 🟢 Live | `server/agent-settings.js` |
| SSE streaming | 🟢 Live | `POST /api/chat/stream` |
| Emotion system | 🟢 Live | `server/agent-autonomy.js` |
| Self-learning loop | 🟢 Live | `server/agent-learning.js` |
| Cost/coin tracking | 🟢 Live | `server/credit-ledger.js` |
| Workflow engine | 🟢 Live | `server/workflow-engine.js` |
| Content backlog queue | 🟢 Live | `server/content-backlog.js` |
| Social account registry | 🟢 Live | `server/social-accounts.js` |
| Media tools (32 providers) | 🟢 Live | `server/media-tools.js` |
| WhatsApp integration | 🟢 Live | WA gateway proxy |
| Visual workflow builder | 🟢 Live | SOP Editor UI |
| 3D NPC world | 🟢 Live | `src/world/OutdoorWorld.js` |

---

## Stats Summary

| | Count |
|-|-------|
| Live agents in Mighantect | 28 |
| 100-spec roles covered by existing | ~46 |
| New agents to build (roadmap) | ~54 |
| Task modules live | 33 |
| Media providers | 32 |
| LLM providers | 6 |

---

*Registry auto-synced from `config/agent-ledger.json` — run `GET /api/catalogue` for live data.*  
*Built by [Fahmi Ghani](https://github.com/fahmiwol) · TIRANYX ecosystem*
