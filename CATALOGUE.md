# Agent Skills & Tools Catalogue

> Complete registry of agent capabilities, task modules, and media providers in the NPC Agent AI Ecosystem.

---

## Stats

| | Count |
|---|---|
| AI Agent NPCs | 22 |
| Task Modules | 27 |
| Image Providers | 15 |
| Video Providers | 6 |
| TTS Providers | 5 |
| Design Providers | 6 |

---

## Agents

| Agent | Role | Skills |
|-------|------|--------|
| **receptionist-ai** | Receptionist / Front Office | client onboarding · brand communication · marketing strategy · content briefing · social media planning · audience targeting · campaign monitoring · CRM management |
| **designer** | Visual Designer | visual design · microstock image creation · AI image generation · brand identity · color theory · prompt engineering for images · photo editing · thumbnail design |
| **profesor** | Head of Innovation & Research | research synthesis · ideation facilitation · trend analysis · experiment design · knowledge base building · innovation pipeline management · sandbox testing · idea lifecycle management |
| **iris** | Field Intelligence Agent | pipeline monitoring · data pattern recognition · system observability · real-time reporting · anomaly detection · automated research execution · workflow orchestration · field intelligence |
| **pm-agent** | Project Manager | task prioritization · sprint planning · timeline management · team coordination · bottleneck identification · project reporting · dependency mapping · deliverable tracking |
| **strategy-agent** | Strategy Lead | business strategy · market analysis · competitive intelligence · long-term planning · opportunity identification · SWOT analysis · content strategy · growth planning |
| **hunter** | Product Researcher | trend spotting · product research · competitor analysis · keyword research · market opportunity hunting · niche discovery · viral content analysis · consumer behavior analysis |
| **reviewer** | Content Reviewer | content quality assessment · code review · copy editing · brand consistency check · fact verification · structured feedback writing · rubric-based evaluation · revision management |
| **linker** | Affiliate Manager | affiliate link management · conversion funnel optimization · traffic monetization · partnership building · UTM tracking · CTA optimization · revenue attribution · distribution network mapping |
| **social_bot** | Social Media Bot | social media posting · multi-platform scheduling · engagement automation · hashtag optimization · comment management · follower growth tactics · viral content distribution · A/B post testing |
| **yt_bot** | YouTube Bot | YouTube SEO · thumbnail optimization · video metadata writing · watch time analysis · CTR improvement · playlist management · video publishing automation · analytics reporting |
| **jadwal_bot** | Scheduler Bot | content scheduling · cron job management · calendar synchronization · deadline tracking · batch publishing · timezone management · pipeline orchestration · recurring task automation |
| **maintenance-bot** | System Maintenance | server health monitoring · error detection and logging · auto-recovery procedures · dependency checking · file system cleanup · API health checks · uptime monitoring · system diagnostics |
| **thread_buzzer** | X/Threads Buzzer | thread writing · X/Twitter engagement · conversation starter creation · viral thread optimization · community interaction · trending topic participation · poll creation · reply automation |
| **fb_buzzer** | Facebook Buzzer | Facebook page management · community building · group engagement · post boosting strategy · comment interaction · content moderation · audience segmentation · Facebook Ads basics |
| **tiktok_buzzer** | TikTok Buzzer | TikTok content creation · short video scripting · trend riding · hashtag strategy · duet and stitch interaction · viral timing optimization · sound selection · TikTok SEO |
| **yt_buzzer** | YouTube Buzzer | YouTube channel growth · subscriber acquisition · video series planning · comment engagement · community posts · YouTube Shorts strategy · collaboration outreach · audience retention optimization |
| **blogger_bot** | Blog Publisher Bot | blog publishing automation · on-page SEO · meta description writing · internal linking · CMS management · content calendar execution · keyword placement · readability scoring |
| **kurir** | Upload Courier | FTP/SFTP upload · batch file transfer · microstock submission · API upload integration · file integrity verification · transfer retry management · platform-specific formatting · upload status tracking |
| **kurator** | Content Curator / QC | quality assurance · content moderation · compliance checking · brand standard enforcement · rejection reason analysis · approval workflow management · rubric-based evaluation · feedback documentation |
| **pustakawan** | Metadata Librarian | metadata management · keyword tagging · content categorization · SEO taxonomy · file naming conventions · archive organization · search index optimization · data standardization |
| **wordsmith** | Copywriter | copywriting · prompt engineering · brand voice writing · creative brief interpretation · ad copy creation · storytelling · product description writing · headline generation |

---

## Task Modules

Each module is a callable LLM execution unit assigned to a specific agent.

| Module ID | Name | Agent | Description |
|-----------|------|-------|-------------|
| `prompt_gen` | Prompt Generator | wordsmith | Generates creative prompts for AI image generation |
| `image_analyzer` | Image Analyzer | profesor | Analyzes images for composition, quality, and marketability |
| `keyword_research` | Keyword Researcher | pustakawan | Researches keywords for microstock metadata and SEO |
| `quality_check` | Quality Checker | kurator | Performs quality assurance checks before asset upload |
| `upload_mgr` | Upload Manager | kurir | Manages batch uploads to stock platforms |
| `visual_design` | Visual Designer | designer | Generates visual design concepts and mood boards |
| `product_hunt` | Product Hunter | hunter | Identifies affiliate products and opportunities |
| `content_review` | Content Reviewer | reviewer | Reviews and generates product review content |
| `link_builder` | Link Builder | linker | Generates affiliate links and tracking URLs |
| `blog_publish` | Blog Publisher | blogger_bot | Publishes content to WordPress and Medium |
| `social_publish` | Social Publisher | social_bot | Posts content to social media platforms |
| `yt_publish` | YouTube Publisher | yt_bot | Manages YouTube uploads and channel optimization |
| `scheduler` | Task Scheduler | jadwal_bot | Schedules and orchestrates publishing tasks |
| `research_content` | Content Researcher | riset_bot | Deep research on any topic for content creation |
| `write_content` | Content Writer | penulis | Writes full articles, captions, scripts, and any content |
| `edit_content` | Content Editor | editor_konten | Reviews, edits, and approves content for quality |
| `pm_tasks` | Project Manager | pm-agent | Creates project plans, task lists, and coordinates agents |
| `strategy_plan` | Strategy Planner | strategy-agent | Strategic analysis, business planning, and decision frameworks |
| `maintenance_check` | Maintenance Bot | maintenance-bot | System health checks, server monitoring, and maintenance tasks |
| `social_buzz` | Social Buzzer | thread_buzzer | Creates buzz content for Threads, Instagram, and social platforms |
| `fb_buzz` | Facebook Buzzer | fb_buzzer | Creates Facebook page content and community management |
| `tiktok_buzz` | TikTok Buzzer | tiktok_buzzer | Creates TikTok scripts and content strategies |
| `yt_buzz` | YouTube Buzzer | yt_buzzer | YouTube channel growth and video content strategy |
| `affiliate_manage` | Affiliate Manager | affiliate_mgr | Affiliate link management, commission tracking, and optimization |
| `post_schedule` | Posting Scheduler | scheduler_konten | Content calendar and posting schedule management |
| `account_monitor` | Account Monitor | monitor_bot | Social media account health monitoring and reporting |

---

## Media Providers

### Image Generation (15 providers)

| Provider | Key Required | Notes |
|----------|-------------|-------|
| `pollinations` | No | Free, no key needed — default |
| `huggingface` | Yes | Free tier via HF Inference API |
| `segmind` | Yes | Fast Flux/SDXL |
| `getimg` | Yes | Multiple base models |
| `novitaai` | Yes | Large model library |
| `together` | Yes | 29+ free models via Together |
| `replicate` | Yes | Stable Diffusion, SDXL, Flux |
| `cloudflare` | Yes | Workers AI — fast & cheap |
| `local_sd` | No | Local Stable Diffusion |
| `comfyui` | No | Local ComfyUI workflow |
| `openai` | Yes | DALL-E 3 |
| `ideogram` | Yes | Typography-strong model |
| `leonardo` | Yes | Cinematic + product imagery |
| `google` | Yes | Imagen 4 via Google AI Studio |
| `stability` | Yes | Stability AI SDXL |

### Video Generation (6 providers)

| Provider | Key Required | Notes |
|----------|-------------|-------|
| `pollinations_vid` | No | Free short video |
| `ffmpeg_local` | No | Local assembly (slides + audio) |
| `google_veo` | Yes | Veo 3.1 — highest quality |
| `hunyuan_vid` | No | Open source local |
| `wan_vid` | No | Alibaba open source |
| `ltx_vid` | No | LTX Video open source |
| `kling` | Yes | Kling AI |
| `runway` | Yes | Runway Gen-3 |
| `pika` | Yes | Pika Labs |
| `replicate_vid` | Yes | Various video models |
| `luma` | Yes | Luma Dream Machine |

### Text-to-Speech (5 providers)

| Provider | Key Required | Notes |
|----------|-------------|-------|
| `edge_tts` | No | Free — Microsoft Edge TTS |
| `fish_audio` | Yes | Voice cloning capable |
| `google_tts` | Yes | Google Cloud TTS |
| `elevenlabs` | Yes | Best quality + cloning |
| `openai_tts` | Yes | OpenAI TTS-1 / TTS-1-HD |

### Design Tools (6 providers)

| Provider | Key Required | Notes |
|----------|-------------|-------|
| `sharp_local` | No | Local image processing |
| `removebg` | Yes | Background removal API |
| `rembg_local` | No | Local rembg (Python) |
| `cloudinary` | Yes | CDN + transformation |
| `figma` | Yes | Figma API |
| `canva` | Yes | Canva Connect API |
| `upscayl` | No | Local AI upscaler |

---

## LLM Providers

| Provider | Models | Free Option |
|----------|--------|-------------|
| Anthropic | Claude Haiku, Sonnet, Opus | No (pay-per-token) |
| OpenAI | GPT-4o, GPT-4o-mini, GPT-4.1 | No |
| Mistral AI | mistral-small, mistral-large, codestral | No |
| Google Gemini | Gemini 2.0 Flash, 2.5 Pro | Yes (AI Studio free tier) |
| OpenRouter | 29+ free models | Yes (many free models) |
| Ollama | Any local model (Llama, Qwen, Mistral…) | Yes (fully local) |

---

## API Endpoint

```
GET /api/catalogue
GET /api/catalogue/agents     → sorted by skill count
GET /api/catalogue/skills     → skill → [agentIds] map
GET /api/catalogue/providers  → provider list with free/paid flag
```

---

## Part of NPC Agent AI Ecosystem

This catalogue is served live from the gateway at `localhost:9797/api/catalogue`.

👉 [NPC-Agent-AI-Ecosystem](https://github.com/fahmiwol/NPC-Agent-AI-Ecosystem)  
👉 [AI-agent-Workflow-visual-script-builder](https://github.com/fahmiwol/AI-agent-Workflow-visual-script-builder)
