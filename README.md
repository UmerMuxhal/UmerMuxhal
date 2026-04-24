# Umer Mughal

**I build AI-powered backend systems and cloud infrastructure that replace manual workflows, cut operational overhead, and ship to production — not just proof of concept.**

6 years of Python and AWS. I've built eDiscovery platforms that enterprises pay $500K/year for, AI scheduling tools that replace weeks of manual planning, and automation engines that run entire sales workflows without a human in the loop. I work across the full backend stack — from database schema to CI/CD pipeline — and I own the result end to end.

Available for remote roles and freelance engagements.

---

## What I'm Good At

**Backend & APIs** — FastAPI, Django, Express, SQLAlchemy, Pydantic, REST, WebSockets, Celery

**Cloud & DevOps** — AWS (Lambda, EC2, RDS, S3, SQS, API Gateway, CodeArtifact, Secrets Manager), Azure, GCP, Docker, GitHub Actions CI/CD

**Databases** — PostgreSQL, MongoDB, Redis, MySQL, Apache Solr, Qdrant (vector search)

**AI & Automation** — OpenAI, Anthropic Claude, Azure OpenAI, LangChain, RAG pipelines, Celery task queues, multi-LLM orchestration

**Auth & Security** — JWT, SAML SSO, MFA (TOTP), JWKS key rotation, RBAC, CSRF, CSP, SOC 2

**Frontend** — React, TypeScript, Vite, TanStack Query, Redux Toolkit

---

## Projects Worth Looking At

---

### AIDA — AI-Powered Legal Discovery Platform
*The kind of system law firms pay Relativity $500K/year to access. Built it from scratch.*

Enterprise eDiscovery platform with per-case database isolation across three storage engines (PostgreSQL + Apache Solr + Qdrant), 7 LLM providers behind a single abstraction layer, hybrid RAG retrieval fusing keyword and vector search, and SOC 2-certified multi-cloud deployment across AWS, Azure, and on-premise.

- **10x reduction** in document review time via ML-driven auto-classification across 100K+ document populations
- **7 LLM providers** (OpenAI, Anthropic, Gemini, Groq, Bedrock, HuggingFace, self-hosted) abstracted behind a unified generation interface
- **5 Celery worker queues** partitioned by workload — ML inference, uploads, database ops, review tasks — preventing GPU-heavy jobs from starving time-sensitive workflows
- **Zero-trust CI/CD** — GitHub Actions dynamically opens and closes Azure NSG SSH rules per deployment, never leaving SSH exposed

`FastAPI` `React/TypeScript` `PostgreSQL` `Apache Solr` `Qdrant` `Redis` `Celery` `SAML SSO` `Docker` `GitHub Actions` `AWS` `Azure`

---

### RANA — AI Project Scheduling SaaS
*Turns a 2-week manual planning process into a single document upload.*

Multi-tenant SaaS for construction managers and planning consultants. Ingests PDF/DOCX scope documents, runs them through a custom Azure OpenAI pipeline to generate WBS hierarchies, then resolves dependencies via topological sort (Kahn's algorithm) with FS/SS/FF/SF relationship types and working-calendar arithmetic — the same constraint logic as Primavera P6. Full Stripe billing lifecycle, JWKS JWT auth, and bidirectional Primavera P6 Excel import/export.

- **~80% reduction** in project planning time — minutes instead of weeks
- Built the scheduling engine from scratch — not wrapped around a library
- Zero-downtime JWT migration from HS256 static secrets to RS256/ES256 with JWKS key rotation

`FastAPI` `React/Vite` `Azure OpenAI` `PostgreSQL` `Stripe` `JWKS JWT` `Syncfusion Gantt` `Render`

---

### StoreWise — Serverless Retail Collaboration Platform
*20+ Lambda functions, real-time messaging, and an AI retail assistant — all for distributed retail teams.*

Fully serverless AWS architecture serving multi-tenant retail organizations. Real-time messaging via Pusher presence channels, multi-platform notification fan-out across 6 channels (mobile push, email, SMS, WhatsApp, Viber, Teams), and an AI assistant ("Ella") built on LangChain agents with 6 tools including GPT-4 Vision, DALL·E 3, FAISS vector retrieval, and Square POS integration. Bitwise RBAC encodes 26 permissions as a single integer for O(1) authorization.

- **20+ independently deployable Lambda functions** across 4 environments via differential CI/CD (only modified functions rebuild)
- **3 shared internal Python packages** distributed via AWS CodeArtifact — consistent standards across the entire function fleet
- **Sub-second message delivery** to thousands of concurrent users

`AWS Lambda` `API Gateway` `SQS` `CodeArtifact` `Pusher` `MySQL/RDS` `LangChain` `GPT-4` `DALL·E 3` `FAISS` `Firebase Auth`

---

### NurtureFlow AI — Autonomous Sales Engine
*Replaced a 2-person SDR team. Runs every minute during business hours without anyone touching it.*

Sales automation engine that processes 1,000+ Pipedrive deals across three pipeline stages, generates GPT follow-up emails from actual Gmail conversation history, threads replies into existing conversations via RFC822 header injection, detects responses to reset the nurture sequence, and auto-closes unresponsive deals with loss marking.

- **Follow-up latency from 24–72 hours → under 60 seconds**
- GPT emails are generated from the last 10 decoded Gmail thread messages — they read like a human wrote them because they reference the actual conversation
- Full deal lifecycle state machine: first contact → follow-up cadence → reply detection → auto-close — all database-driven, no code changes needed to modify the cadence

`Node.js` `MongoDB` `OpenAI GPT-4o-mini` `Pipedrive SDK` `Gmail API OAuth2` `node-cron`

---

### Direct Peptides — E-Commerce Operations Platform
*Eliminated 6 separate tools. Reduced daily ops overhead from 3 hours to 30 minutes.*

Full-stack operations platform for a DTC brand processing hundreds of orders monthly. Multi-source order ingestion (Ecwid webhooks + API polling + Google Sheets sync), automated SMS lifecycle via a three-scenario LinQ messaging engine, dual Kanban CRM with cross-entity SQL deduplication running every 5 minutes, NLP-based name extraction from SMS conversations, and one-click USPS batch processing.

- **~85% reduction** in per-order processing time
- 7,166-line API layer handling order orchestration, messaging, CRM lifecycle, inventory, and webhook processing
- NLP name extractor parses SMS history against a 130+ word exclusion dictionary to identify customer names without any human tagging

`Express/TypeScript` `React/TypeScript` `Neon PostgreSQL` `Drizzle ORM` `Ecwid API` `LinQ API` `Google Sheets API` `WebSocket`

---

## Open Source

### [Python Lambda Layer — GitHub Action](https://github.com/marketplace/actions/python-lambda-layer)

Published on the GitHub Marketplace. Automates the packaging and publishing of AWS Lambda Layers directly from GitHub Actions — no manual dependency bundling, no complex CI scripts. Supports versioned Python runtimes, S3 upload, and permission handling out of the box.

---

## Currently Working On

Deepening distributed system design patterns — specifically event-driven architectures, high-throughput async pipelines, and advanced serverless patterns on AWS. Also exploring agentic AI workflows where LLMs coordinate multi-step tasks without human checkpoints.

---

## Let's Talk

I'm open to **remote full-time roles** and **freelance engagements** — particularly around AI-powered backends, cloud infrastructure, and automation systems.

**Email:** umermuxhal@gmail.com
**LinkedIn:** [linkedin.com/in/umermuxhal](https://linkedin.com/in/umermuxhal)

If you need someone who can own the full backend stack, make hard architectural decisions under real constraints, and ship systems that handle actual production load — reach out.
