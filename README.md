# 🧠 OSAIX AgentOS

**Local-First. Privacy-Native. Revenue-Focused.**

> A production-grade, multi-agent operating system built for solo-preneurs and AI strategists who need data sovereignty, systematic automation, and measurable business outcomes — without sacrificing control.

---

## The Problem with AI Agents Today

Most teams plugging AI into their workflows hit the same wall within 90 days:

| Pain Point | Industry Reality |
|---|---|
| 🔓 **Data Leaks** | Sensitive customer data, leads, and IP flow to external cloud servers with zero visibility |
| 🌀 **Cognitive Overload** | Unstructured tools and endless context switching kill output quality and decision speed |
| 💸 **Exploding API Costs** | Long-running sessions bloat token usage — paying for the same context over and over |
| 💣 **Fragile Pipelines** | Multiple scripts writing to shared files cause race conditions, data corruption, and CRM chaos |

**AgentOS solves all four. Architecturally. Not with a prompt.**

---

## The Solution: An AI Operating System Built Around Your Data

AgentOS is a **local-first, layer-based multi-agent infrastructure** that keeps sensitive data on your hardware, automates repeatable decision workflows, and integrates production-grade governance principles into every operation.

It is not a wrapper around ChatGPT. It is the control system *behind* the AI.

---

## Architecture: 8-Layer Cognitive Stack

```text
/AgentOS/
├── 00_inbox/     ← Unfiltered input: notes, scrapes, triggers
├── 01_core/      ← System brain: policies, routing logic, hooks
├── 02_data/      ← Operational truth: SQLite DBs, KDBs, staging
├── 03_agents/    ← Specialized agent personas & orchestration roles
├── 04_logs/      ← Telemetry, session journals, hardening tickets
├── 05_sops/      ← Machine-executable Standard Operating Procedures
├── 06_outputs/   ← Deliverables: reports, client assets, audit trails
├── 07_harness/   ← Validation: health checks, fixtures, afk-watchdog
└── 08_archive/   ← Cold storage: versioned, auditable history
```

Every layer has a single, enforced purpose. No file lands in the wrong place. Ever.

---

## Core Capabilities

### 🔐 Data Sovereignty (Local-First by Design)
- All sensitive computation runs locally via **Apple Silicon GPU** (Ollama + LiteRT/Gemma 4)
- A hardened `.gitignore` ensures raw data, personal context, and credentials never leave your machine
- Three isolated Data Worlds (Private / Business / AgentOS) enforce strict separation of concerns
- DSGVO/GDPR-compliant by architecture, not by checkbox

### ⚡ Hardware-Aware Model Routing (RMM)
- The **Resource Management Module** pre-estimates token cost before every operation
- Tasks < 3,000 tokens → local edge model (zero cost)
- Complex reasoning tasks → routed to cloud fallback (Gemini / Claude)
- Real-time quota monitoring prevents surprise API bills

### 🤖 Specialized Agent Ecosystem
- **Orchestrator (OSAIX):** Master dispatcher — reads intent, assigns agents, enforces policy
- **Librarian:** Async indexing with semantic relevance scoring. Zero manual file management.
- **DB-Writer:** Single-writer SQLite gateway — eliminates race conditions across all databases
- **Hub-Guardian:** Self-healing watchdog that monitors and restores critical system services
- **Link-Cortex-Scanner:** Stealth-scans all directories for URL assets, builds searchable knowledge graph
- **Sales-Expert Agent:** Audits external-facing content to ensure it is technically sound and commercially sharp

### 📊 Real-Time Observability
- Standalone Vite/React dashboard: Live model status, Discord feed, semantic graph (Graphify), and pending approval queues.
- Session journals auto-generated at every closure with token metrics, model usage, and open loop detection.
- Hardening tickets (`HT-*`) auto-created for any unresolved system anomalies.

### 🔄 Decoupled Three-Repository System (Architecture Blueprint)

To maintain absolute data separation, service isolation, and code clarity, AgentOS is engineered as a decoupled, multi-repository ecosystem. The code and configuration are divided into three specialized private repositories (physically isolated, functionally mapped, and securely managed):

1. 📂 **Core System & Database Backend (`OSAIRIX-AGENTOS-system-Privat`)**
   - **Role:** Serves as the central operating system and cognitive coordinator.
   - **Assets:** Implements the 8-layer cognitive stack (Inbox, Core, Data, Agents, Logs, SOPs, Outputs, Harness, Archive).
   - **Key Tech:** Single-Writer transaction engine (SQLite queue), Resource Management Module (RMM) for local-first model routing (Apple M3 GPU + LiteRT/Ollama), and the local command center.
   - **Security:** Standardized AI-native pre-commit hooks to block secrets/credential leaks and enforce formatting.

2. 📊 **Cockpit Visualizer & Dashboard GUI (`OSAIRIX-AGENTOS-system-Gui-Privat`)**
   - **Role:** Houses the system's graphical management panel and visual analytics.
   - **Assets:** A custom Vite & React single-page application.
   - **Key Tech:** Connects locally to the backend server via a secure Server-Sent Events (SSE) log stream, presenting real-time agent telemetry, model cost metrics, pending human-in-the-loop approvals, and interactive semantic graphs.

3. 💬 **Independent Messaging & Communication Hub (`OSAIX-Kommunikation-Privat`)**
   - **Role:** Handles external messaging tunnels, chat transport routing, and gateway bridges.
   - **Assets:** Host bridges, Discord bot containers, webhooks, and inbox parsers.
   - **Key Tech:** Decouples gateway connections from the core backend. If chat platforms change APIs, rate-limit, or fail, the core system remains 100% operational, isolating external network vulnerabilities.

*Synchronization & Backup Pipeline:* All changes across these repositories are pulled, validated, and pushed concurrently using our unified one-click sync process, which automatically tags commits with distinct AI/Human identity signatures for full auditability while creating a 1:1 backup mirror on secure cloud storage.

---

## Compliance & Standards

AgentOS is designed to enterprise standards from day one:

| Standard | Implementation |
|---|---|
| **NIST AI RMF (Govern/Measure)** | Risk-Gate with AUTO/AUDIT/HUMAN approval tiers |
| **OWASP LLM Top 10** | Scan-before-import, prompt sanitisation, no blind RAG ingestion |
| **ITIL Change Management** | Staged updates, Definition of Ready/Done, session audit logs |
| **ISO/IEC 42001 (AI Governance)** | Transparent decision records, audit trails, identity enforcement |

---

## Who This Is Built For

**AI Strategists & Solo-Preneurs** who run complex, multi-tool workflows and need a system that scales without adding headcount.

**Engineering Leads** evaluating local AI infrastructure for compliance-sensitive environments.

**Hiring Managers** looking for candidates with hands-on, production-grade AI systems architecture experience.

---

## Results & ROI

- **Sales prototypes** generated in < 60 seconds via Screenshot-to-UI pipeline
- **Zero data-leak incidents** — 100% local processing for sensitive operations
- **API cost reduction** through hardware-aware routing (up to 80% of tasks handled locally at zero cost)
- **Autonomous overnight operations** with afk-heartbeat monitoring and automatic error-ticketing

---

## 📬 Work With BlubMa

I build AI infrastructure that generates measurable business outcomes. My core motto is **"Ich bin Multi"** (or **"Ich bin 2-3"**) — acting as a capacity multiplier by designing cognitive assistance systems that deliver immediate ROI.

If you are:
- Evaluating local-first agentic infrastructure (data sovereignty, DSGVO compliance).
- Building automated sales-enablement and B2B hunting pipelines (+225% performance increase).
- Implementing structured ITIL-compliant AI governance.
- Looking for a strategic AI architect with a human-centric approach (Wirtschaftspsychologie) — let's connect.

**→ [Reach out via LinkedIn](https://linkedin.com/in/benjaminmast)** or explore the project documentation in this repository.

**→ Business context:** [umsatz-ki-architekten.com](https://umsatz-ki-architekten.com)
**→ Public GitHub:** [github.com/BlubMa/OSAIRIX-AGENTOS-system-Public](https://github.com/BlubMa/OSAIRIX-AGENTOS-system-Public)

---

<sub>Built by BlubMa · Maintained by OSAIX · Powered by Antigravity AI · Local-First · Privacy-Native</sub>
