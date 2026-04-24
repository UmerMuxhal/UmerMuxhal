<p align="center">
  <img src="https://komarev.com/ghpvc/?username=UmerMuxhal&style=flat-square&color=00B4D8&label=Profile+Views" />
  <img src="https://img.shields.io/badge/Open%20to%20Remote%20Roles%20%26%20Freelance-%2300B4D8?style=flat-square&logo=briefcase&logoColor=white" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00B4D8&center=true&vCenter=true&width=650&lines=Python+%26+AWS+Engineer+%7C+6+Years;AI+Systems+%7C+Cloud+Infrastructure;FastAPI+%7C+Lambda+%7C+PostgreSQL+%7C+Redis;Building+things+that+ship+to+production" alt="Typing SVG" />
</p>

<h1 align="center">Umer Mughal</h1>

<p align="center">
I build AI-powered backend systems and cloud infrastructure that replace manual workflows, cut operational overhead, and ship to production — not just proof of concept.<br><br>
6 years of Python and AWS. I've built eDiscovery platforms that enterprises pay $500K/year for, AI scheduling tools that replace weeks of manual planning, and automation engines that run entire sales workflows without a human in the loop. I work across the full backend stack — from database schema to CI/CD pipeline — and I own the result end to end.<br><br>
<b>Available for remote roles and freelance engagements.</b>
</p>

---

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=UmerMuxhal&theme=tokyonight&no-frame=true&no-bg=true&margin-w=4&row=1" />
</p>

---

## What I'm Good At

<p>
  <img src="https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python&logoColor=00B4D8" />
  <img src="https://img.shields.io/badge/FastAPI-0D1117?style=for-the-badge&logo=fastapi&logoColor=00B4D8" />
  <img src="https://img.shields.io/badge/Django-0D1117?style=for-the-badge&logo=django&logoColor=00B4D8" />
  <img src="https://img.shields.io/badge/AWS-0D1117?style=for-the-badge&logo=amazonaws&logoColor=00B4D8" />
  <img src="https://img.shields.io/badge/PostgreSQL-0D1117?style=for-the-badge&logo=postgresql&logoColor=00B4D8" />
  <img src="https://img.shields.io/badge/Redis-0D1117?style=for-the-badge&logo=redis&logoColor=00B4D8" />
  <img src="https://img.shields.io/badge/Docker-0D1117?style=for-the-badge&logo=docker&logoColor=00B4D8" />
  <img src="https://img.shields.io/badge/React-0D1117?style=for-the-badge&logo=react&logoColor=00B4D8" />
  <img src="https://img.shields.io/badge/MongoDB-0D1117?style=for-the-badge&logo=mongodb&logoColor=00B4D8" />
  <img src="https://img.shields.io/badge/Celery-0D1117?style=for-the-badge&logo=celery&logoColor=00B4D8" />
  <img src="https://img.shields.io/badge/OpenAI-0D1117?style=for-the-badge&logo=openai&logoColor=00B4D8" />
  <img src="https://img.shields.io/badge/GitHub_Actions-0D1117?style=for-the-badge&logo=githubactions&logoColor=00B4D8" />
</p>

**Backend & APIs** — FastAPI, Django, Express, SQLAlchemy, Pydantic, REST, WebSockets, Celery

**Cloud & DevOps** — AWS (Lambda, EC2, RDS, S3, SQS, API Gateway, CodeArtifact, Secrets Manager), Azure, GCP, Docker, GitHub Actions CI/CD

**Databases** — PostgreSQL, MongoDB, Redis, MySQL, Apache Solr, Qdrant (vector search)

**AI & Automation** — OpenAI, Anthropic Claude, Azure OpenAI, LangChain, RAG pipelines, multi-LLM orchestration

**Auth & Security** — JWT, SAML SSO, MFA (TOTP), JWKS key rotation, RBAC, CSRF, CSP, SOC 2

**Frontend** — React, TypeScript, Vite, TanStack Query, Redux Toolkit

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=UmerMuxhal&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=UmerMuxhal&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" width="38%" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=UmerMuxhal&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" />
</p>

---

## Projects Worth Looking At

---

### AIDA — AI-Powered Legal Discovery Platform
*The kind of system law firms pay Relativity $500K/year to access. Built it from scratch.*

Enterprise eDiscovery platform with per-case database isolation across three storage engines (PostgreSQL + Apache Solr + Qdrant), 7 LLM providers behind a single abstraction layer, hybrid RAG retrieval fusing keyword and vector search, and SOC 2-certified multi-cloud deployment across AWS, Azure, and on-premise.

| Impact | Detail |
|--------|--------|
| 10x faster document review | ML-driven auto-classification across 100K+ document populations |
| 7 LLM providers unified | OpenAI, Anthropic, Gemini, Groq, Bedrock, HuggingFace, self-hosted — one interface |
| 5 Celery worker queues | ML inference, uploads, database ops, review tasks — each isolated |
| Zero-trust CI/CD | GitHub Actions dynamically opens and closes Azure NSG SSH rules per deployment |

`FastAPI` `React/TypeScript` `PostgreSQL` `Apache Solr` `Qdrant` `Redis` `Celery` `SAML SSO` `Docker` `AWS` `Azure`

---

### RANA — AI Project Scheduling SaaS
*Turns a 2-week manual planning process into a single document upload.*

Multi-tenant SaaS for construction managers and planning consultants. Ingests PDF/DOCX scope documents, runs them through a custom Azure OpenAI pipeline to generate WBS hierarchies, then resolves dependencies via topological sort (Kahn's algorithm) with FS/SS/FF/SF relationship types and working-calendar arithmetic — the same constraint logic as Primavera P6.

| Impact | Detail |
|--------|--------|
| ~80% planning time reduction | Minutes instead of weeks |
| Custom scheduling engine | Topological sort with 4 dependency types — built from scratch, not a library |
| Zero-downtime JWT migration | HS256 static secrets to RS256/ES256 JWKS key rotation |
| Full Stripe billing lifecycle | Checkout, webhooks, real-time tenant role sync on subscription changes |

`FastAPI` `React/Vite` `Azure OpenAI` `PostgreSQL` `Stripe` `JWKS JWT` `Syncfusion Gantt` `Render`

---

### StoreWise — Serverless Retail Collaboration Platform
*20+ Lambda functions, real-time messaging, and an AI retail assistant — all for distributed retail teams.*

Fully serverless AWS architecture serving multi-tenant retail organizations. Real-time messaging via Pusher, multi-platform notification fan-out across 6 channels, and an AI assistant built on LangChain agents with 6 tools including GPT-4 Vision, DALL-E 3, FAISS vector retrieval, and Square POS integration. Bitwise RBAC encodes 26 permissions as a single integer for O(1) authorization.

| Impact | Detail |
|--------|--------|
| 20+ Lambda functions | Independently deployable across 4 environments via differential CI/CD |
| 3 internal Python packages | Distributed via AWS CodeArtifact — consistent standards fleet-wide |
| Sub-second message delivery | Thousands of concurrent users via Pusher presence channels |
| 6 notification channels | Mobile push, email, SMS, WhatsApp, Viber, Teams — unified pipeline |

`AWS Lambda` `API Gateway` `SQS` `CodeArtifact` `Pusher` `MySQL/RDS` `LangChain` `GPT-4` `DALL-E 3` `FAISS` `Firebase Auth`

---

### NurtureFlow AI — Autonomous Sales Engine
*Replaced a 2-person SDR team. Runs every minute during business hours without anyone touching it.*

Sales automation engine processing 1,000+ Pipedrive deals across three pipeline stages. Generates GPT follow-up emails from actual Gmail conversation history, threads replies via RFC822 header injection, detects responses to reset the nurture sequence, and auto-closes unresponsive deals with loss marking.

| Impact | Detail |
|--------|--------|
| 24-72 hours to under 60 seconds | Follow-up latency via minute-level cron scheduling |
| 2-person SDR workflow replaced | Fully autonomous pipeline with no human checkpoints |
| Context-aware GPT emails | Generated from last 10 decoded Gmail thread messages |
| Database-driven state machine | Modify follow-up cadence without touching code |

`Node.js` `MongoDB` `OpenAI GPT-4o-mini` `Pipedrive SDK` `Gmail API OAuth2` `node-cron`

---

### Direct Peptides — E-Commerce Operations Platform
*Eliminated 6 separate tools. Reduced daily ops overhead from 3 hours to 30 minutes.*

Full-stack operations platform for a DTC brand processing hundreds of orders monthly. Multi-source order ingestion (Ecwid webhooks + API polling + Google Sheets sync), automated SMS lifecycle via a three-scenario LinQ messaging engine, dual Kanban CRM with cross-entity SQL deduplication, and one-click USPS batch processing.

| Impact | Detail |
|--------|--------|
| ~85% order processing time reduction | Batch selection, auto-USPS CSV, inline tracking |
| 6 tools consolidated into one | Sheets, Ecwid dashboard, texting, CRM, inventory — gone |
| NLP name extractor | Parses SMS history against 130+ word exclusion dictionary |
| 7,166-line API layer | Order orchestration, messaging, CRM lifecycle, inventory, webhooks |

`Express/TypeScript` `React/TypeScript` `Neon PostgreSQL` `Drizzle ORM` `Ecwid API` `LinQ API` `Google Sheets API` `WebSocket`

---

## Open Source

### Python Lambda Layer — GitHub Action

[![GitHub Marketplace](https://img.shields.io/badge/Marketplace-Python%20Lambda%20Layer-00B4D8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/marketplace/actions/python-lambda-layer)

Published on the GitHub Marketplace. Automates packaging and publishing of AWS Lambda Layers directly from GitHub Actions — no manual dependency bundling, no complex CI scripts. Supports versioned Python runtimes, S3 upload, and permission handling out of the box.

---

## Contribution Activity

<p align="center">
  <img src="https://raw.githubusercontent.com/UmerMuxhal/UmerMuxhal/output/github-contribution-grid-snake-dark.svg" />
</p>

---

## Currently Working On

Deepening distributed system design patterns — event-driven architectures, high-throughput async pipelines, and advanced serverless patterns on AWS. Also exploring agentic AI workflows where LLMs coordinate multi-step tasks without human checkpoints.

---

## Let's Talk

I'm open to **remote full-time roles** and **freelance engagements** — particularly around AI-powered backends, cloud infrastructure, and automation systems.

<p>
  <a href="mailto:umermuxhal@gmail.com">
    <img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=00B4D8" />
  </a>
  <a href="https://www.linkedin.com/in/umermuxhal" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=00B4D8" />
  </a>
  <a href="https://github.com/marketplace/actions/python-lambda-layer" target="_blank">
    <img src="https://img.shields.io/badge/GitHub_Action-0D1117?style=for-the-badge&logo=github&logoColor=00B4D8" />
  </a>
</p>

If you need someone who can own the full backend stack, make hard architectural decisions under real constraints, and ship systems that handle actual production load — reach out.
