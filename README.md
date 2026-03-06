<!-- Header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=1A5F7A&height=110&section=header&text=Martin+Reiter&fontSize=38&fontColor=ffffff&fontAlignY=65&desc=Systems+Architect+%C2%B7+Rust+%26amp;+Python+%C2%B7+Sovereign+AI&descSize=16&descAlignY=85&descColor=c8dde6&v=3" width="100%"/>

<!-- Badges -->
<p align="left">
  <img src="https://img.shields.io/badge/Status-Available_for_Freelance-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Languages-DE_%7C_EN-1A5F7A?style=flat-square" />
  <img src="https://img.shields.io/badge/Location-La_Palma%2C_Canary_Islands_%F0%9F%8C%8B-555555?style=flat-square" />
  <img src="https://img.shields.io/badge/Focus-Sovereign_AI_%7C_EU_AI_Act-0E8A5F?style=flat-square" />
  <img src="https://komarev.com/ghpvc/?username=MartyR92&amp;color=1A5F7A&amp;style=flat-square&amp;label=Profile+Views" />
</p>

> **Building systems that work without babysitting.**  
> Autonomous AI/HITL pipelines · GDPR-compliant by architecture · EU infrastructure · Remote

---

## Deployed Projects

### A.R.E. — Autonomous Regenerative Engine
*Hybrid Rust/Python pipeline · Real-Estate Agency · Canary Islands · Production*

Government data ingestion (WFS, Kataster, BOC PDFs) → RAG-based legal compliance (Red Natura 2000) → AI-generated marketing assets. GDPR enforced at the Rust layer: PII stripped before any LLM call.

| Processing Time | Cost per Report | Compliance Errors | Time to Production |
|---|---|---|---|
| 14 days → **45 min** | €450 → **€3.50** | ~15% → **0%** | **4 weeks** |

→ Architecture & case study: [`are-demo-pipeline`](https://github.com/MartyR92/are-demo-pipeline)

---

### Growth Engine
*PydanticAI · Supabase state machine · Hetzner EU · Production*

Fully autonomous dual-pipeline sales system. Supabase is the queue — no message broker, no orchestrator.

```
Pipeline A — Freelance Inbound   5 agents · 5 platforms · auto-apply
Pipeline B — KMU Outbound        7 agents · SMB discovery → enrichment → PDF asset → outreach → Cal.com
```

> Each agent reads one input status. Writes one output status. A failure isolates to one lead.  
> Infra cost: **€3.79/month** (replaced Modal: 89% cost reduction)

→ Architecture docs: [`growth-engine-demo`](https://github.com/MartyR92/growth-engine-demo)

---

### Automated Lead Qualification — Rust + AI
*Rust · HubSpot API · GDPR Privacy Firewall · Production*

Rust main process classifies leads (email · web form · Idealista API) via AI intent recognition.  
Privacy firewall strips all PII locally before any external call.  
Qualified leads → HubSpot CRM entry + email draft + mobile notification. Automatically.

---

## Architecture Philosophy

**Rust as the controller. Python as the creative.**

```
Rust  →  business logic · data fetching · schema enforcement · GDPR compliance
         if data ≠ type definition → self-correct or halt

PyO3  →  secure bridge

Python →  LLM inference · computer vision (isolated, never touches raw data)
```

This isn't a preference. It's what holds up when no one is watching.

---

## Stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=rust,python,docker,supabase,vercel,nginx,git&amp;theme=dark" />
</p>

| Layer | Tools |
|---|---|
| **Languages** | Rust (Axum · Tokio · Polars · PyO3 · Rig · Spider\_rs) · Python (PydanticAI · OpenCV) |
| **AI / LLMs** | Claude · Mercury2 · Gemini Pro · OpenRouter · Google Vertex AI |
| **Agentic** | PydanticAI · RAG (Qdrant) · Context Engineering · LangChain |
| **Data** | Polars · PostGIS · Parquet · Supabase self-hosted |
| **Scraping** | Scrapling (Fetcher · StealthyFetcher · PlayWrightFetcher) |
| **Observability** | Logfire · OpenTelemetry |
| **Infra** | Hetzner (EU) · Docker · APScheduler · systemd · Vercel |
| **Automation** | n8n · Make · HubSpot · SvelteKit (CRM · Marketing · Sales · Email) |
| **Compliance** | GDPR / DSGVO · EU AI Act · Sovereign AI · PII-Stripping |

---

## GitHub Stats

<p align="left">
  <img height="160" src="https://github-stats-extended.vercel.app/api?username=MartyR92&show_icons=true&theme=dark&bg_color=0d1117&title_color=1A5F7A&icon_color=0E8A5F&text_color=c9d1d9&border_color=21262d&include_all_commits=true&count_private=true" />
  <img height="160" src="https://github-stats-extended.vercel.app/api/top-langs/?username=MartyR92&layout=compact&theme=dark&bg_color=0d1117&title_color=1A5F7A&text_color=c9d1d9&border_color=21262d&langs_count=6" />
</p>

<!-- Snake Animation -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MartyR92/MartyR92/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/MartyR92/MartyR92/output/github-contribution-grid-snake.svg" />
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/MartyR92/MartyR92/output/github-contribution-grid-snake.svg" />
</picture>

---

## Currently

- **Building:** [Re:Lyable-AI] — Sovereign AI micro-agency for EU-compliant agentic systems (DACH · Canary Islands)
- **Running:** [Revive La Palma Systems](https://revivelapalma.com) — regenerative real estate intelligence
- **Available for:** agentic AI pipelines · Rust/Python systems · GDPR-compliant AI architecture · KI-Strategie & Workshops

**Preferred scope:** remote · EU · defined deliverables

---

## Contact

**martin.reiter@revivelapalma.com** · +34 630 198 202  
[revivelapalma.com](https://revivelapalma.com) · [renatureforce.com](https://renatureforce.com)

*Most production code is in private repositories.  
Full A.R.E. case study (architecture, metrics, stack) available on request.*

<!-- Footer -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=1A5F7A&height=80&section=footer&v=3" width="100%"/>
