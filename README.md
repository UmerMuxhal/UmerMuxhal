<img src="https://komarev.com/ghpvc/?username=UmerMuxhal&style=flat-square&color=00B4D8&label=Profile+Views" />
&nbsp;
<img src="https://img.shields.io/badge/Open%20to%20Remote%20%26%20Freelance-00B4D8?style=flat-square&logoColor=white" />

<br />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=00B4D8&width=620&lines=Python+%26+AWS+Engineer+%7C+6+Years;AI+Systems+%7C+Cloud+Infrastructure;FastAPI+%7C+Lambda+%7C+PostgreSQL+%7C+Redis;Building+things+that+ship+to+production" alt="Typing SVG" />

# Umer Mughal

I build AI-powered backend systems and cloud infrastructure that replace manual workflows, cut operational overhead, and ship to production. Not just proof of concept.

6 years of Python and AWS. I've built eDiscovery platforms that enterprises pay $500K/year for, AI scheduling tools that replace weeks of manual planning, and automation engines that run entire sales workflows without a human in the loop. I work across the full backend stack from database schema to CI/CD pipeline and I own the result end to end.

**Available for remote roles and freelance engagements.**

---

## What I Work With

**Backend and APIs** &nbsp; FastAPI · Django · Express · SQLAlchemy · Pydantic · Celery · WebSockets

**Cloud and DevOps** &nbsp; AWS (Lambda · EC2 · RDS · S3 · SQS · API Gateway · CodeArtifact · Secrets Manager) · Azure · GCP · Docker · GitHub Actions

**Databases** &nbsp; PostgreSQL · MongoDB · Redis · MySQL · Apache Solr · Qdrant

**AI and Automation** &nbsp; OpenAI · Anthropic Claude · Azure OpenAI · LangChain · RAG pipelines · multi-LLM orchestration

**Auth and Security** &nbsp; JWT · SAML SSO · MFA (TOTP) · JWKS key rotation · RBAC · CSRF · CSP · SOC 2

**Frontend** &nbsp; React · TypeScript · Vite · TanStack Query · Redux Toolkit

---

## GitHub Stats

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=UmerMuxhal&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=UmerMuxhal&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" width="38%" />
</p>

<img src="https://streak-stats.demolab.com?user=UmerMuxhal&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" />

---

## Projects

---

### AIDA — AI-Powered Legal Discovery Platform

*The kind of system law firms pay Relativity $500K/year to access. Built it from scratch.*

Enterprise eDiscovery platform with per-case database isolation across three storage engines (PostgreSQL + Apache Solr + Qdrant), 7 LLM providers behind a single abstraction layer, hybrid RAG retrieval fusing keyword and vector search, and SOC 2-certified multi-cloud deployment across AWS, Azure, and on-premise.

| Impact | Detail |
|---|---|
| 10x faster document review | ML-driven auto-classification across 100K+ document populations |
| 7 LLM providers unified | OpenAI, Anthropic, Gemini, Groq, Bedrock, HuggingFace, self-hosted behind one interface |
| 5 Celery worker queues | ML inference, uploads, database ops, review tasks, each isolated |
| Zero-trust CI/CD | GitHub Actions dynamically opens and closes Azure NSG SSH rules per deployment |

`FastAPI` `React/TypeScript` `PostgreSQL` `Apache Solr` `Qdrant` `Redis` `Celery` `SAML SSO` `Docker` `AWS` `Azure`

---

### RANA — AI Project Scheduling SaaS

*Turns a 2-week manual planning process into a single document upload.*

Multi-tenant SaaS for construction managers and planning consultants. Ingests PDF/DOCX scope documents, runs them through a custom Azure OpenAI pipeline to generate WBS hierarchies, then resolves dependencies via topological sort (Kahn's algorithm) with FS/SS/FF/SF relationship types and working-calendar arithmetic matching the constraint logic of Primavera P6. Full Stripe billing lifecycle, JWKS JWT auth, and bidirectional Primavera P6 Excel import/export.

| Impact | Detail |
|---|---|
| ~80% planning time reduction | Minutes instead of weeks |
| Custom scheduling engine | Topological sort with 4 dependency types, built from scratch |
| Zero-downtime JWT migration | HS256 static secrets to RS256/ES256 with JWKS key rotation |
| Full Stripe billing lifecycle | Checkout, webhooks, real-time tenant role sync on subscription changes |

`FastAPI` `React/Vite` `Azure OpenAI` `PostgreSQL` `Stripe` `JWKS JWT` `Syncfusion Gantt` `Render`

---

### StoreWise — Serverless Retail Collaboration Platform

*20+ Lambda functions, real-time messaging, and an AI retail assistant built for distributed retail teams.*

Fully serverless AWS architecture serving multi-tenant retail organizations. Real-time messaging via Pusher, multi-platform notification fan-out across 6 channels (mobile push, email, SMS, WhatsApp, Viber, Teams), and an AI assistant built on LangChain agents with 6 tools including GPT-4 Vision, DALL-E 3, FAISS vector retrieval, and Square POS integration. Bitwise RBAC encodes 26 permissions as a single integer for O(1) authorization.

| Impact | Detail |
|---|---|
| 20+ Lambda functions | Independently deployable across 4 environments via differential CI/CD |
| 3 internal Python packages | Distributed via AWS CodeArtifact for consistent standards across the fleet |
| Sub-second message delivery | Thousands of concurrent users via Pusher presence channels |
| 6 notification channels | Mobile push, email, SMS, WhatsApp, Viber, Teams in a unified pipeline |

`AWS Lambda` `API Gateway` `SQS` `CodeArtifact` `Pusher` `MySQL/RDS` `LangChain` `GPT-4` `DALL-E 3` `FAISS` `Firebase Auth`

---

### NurtureFlow AI — Autonomous Sales Engine

*Replaced a 2-person SDR team. Runs every minute during business hours without anyone touching it.*

Sales automation engine processing 1,000+ Pipedrive deals across three pipeline stages. Generates GPT follow-up emails from actual Gmail conversation history, threads replies via RFC822 header injection, detects responses to reset the nurture sequence, and auto-closes unresponsive deals with loss marking.

| Impact | Detail |
|---|---|
| 24-72 hours to under 60 seconds | Follow-up latency via minute-level cron scheduling |
| 2-person SDR workflow replaced | Fully autonomous pipeline with no human checkpoints |
| Context-aware GPT emails | Generated from the last 10 decoded Gmail thread messages |
| Database-driven state machine | Modify the follow-up cadence without touching code |

`Node.js` `MongoDB` `OpenAI GPT-4o-mini` `Pipedrive SDK` `Gmail API OAuth2` `node-cron`

---

### Direct Peptides — E-Commerce Operations Platform

*Eliminated 6 separate tools. Reduced daily ops overhead from 3 hours to 30 minutes.*

Full-stack operations platform for a DTC brand processing hundreds of orders monthly. Multi-source order ingestion (Ecwid webhooks + API polling + Google Sheets sync), automated SMS lifecycle via a three-scenario LinQ messaging engine, dual Kanban CRM with cross-entity SQL deduplication running every 5 minutes, and one-click USPS batch processing.

| Impact | Detail |
|---|---|
| ~85% order processing time reduction | Batch selection, auto-USPS CSV generation, inline tracking |
| 6 tools consolidated into one | Sheets, Ecwid dashboard, texting, CRM, inventory, all replaced |
| NLP name extractor | Parses SMS history against a 130+ word exclusion dictionary |
| 7,166-line API layer | Order orchestration, messaging, CRM lifecycle, inventory, webhooks |

`Express/TypeScript` `React/TypeScript` `Neon PostgreSQL` `Drizzle ORM` `Ecwid API` `LinQ API` `Google Sheets API` `WebSocket`

---

## Open Source

### Python Lambda Layer — GitHub Action

[![GitHub Marketplace](https://img.shields.io/badge/Marketplace-Python%20Lambda%20Layer-00B4D8?style=flat-square&logo=github&logoColor=white)](https://github.com/marketplace/actions/python-lambda-layer)

Published on the GitHub Marketplace. Automates packaging and publishing of AWS Lambda Layers directly from GitHub Actions. No manual dependency bundling, no complex CI scripts. Supports versioned Python runtimes, S3 upload, and permission handling out of the box.

---

## Contribution Activity

<img src="https://raw.githubusercontent.com/UmerMuxhal/UmerMuxhal/output/github-contribution-grid-snake-dark.svg" />

---

## Currently Working On

Deepening distributed system design patterns: event-driven architectures, high-throughput async pipelines, and advanced serverless patterns on AWS. Also exploring agentic AI workflows where LLMs coordinate multi-step tasks without human checkpoints.

---

## Let's Talk

I'm open to remote full-time roles and freelance engagements, particularly around AI-powered backends, cloud infrastructure, and automation systems.

**Email** &nbsp; umermuxhal@gmail.com

**LinkedIn** &nbsp; [linkedin.com/in/umermuxhal](https://www.linkedin.com/in/umermuxhal)

If you need someone who can own the full backend stack, make hard architectural decisions under real constraints, and ship systems that handle actual production load, reach out.
