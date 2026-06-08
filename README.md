# Kevin Atkinson

**AI Platform Architect.** I design and build production agent systems — memory, retrieval, orchestration, and provenance — that hold up under real enterprise load and scrutiny.

## 📌 Featured

**[evidence-grounded-memory](https://github.com/wasabikev/evidence-grounded-memory)** — A runnable reference implementation of agent memory as a *living evidentiary record* — where vector search is a derived retrieval path, not the memory substrate.

Durable markdown topic files are the source of truth; keyword (FTS5) and semantic search are derived, disposable views over them. Every fact carries authority-tiered provenance, and a fact's standing is **re-graded over time** — promoted when corroborated, superseded when contradicted — non-destructively, so the audit trail of *what the agent believed and why it changed* is preserved.

It reproduces the design decisions of a production memory system — the *what and why*, not the production code — with a full design narrative, seven named design decisions, an end-to-end runnable demo, and tests. Python · zero third-party dependencies.

## 🛠️ What I work on

**AI Agent Platform Architect at Asgard Systems AI (2024–present)** — enterprise-grade AI orchestration.

- **Agent memory & provenance** — persistent, cross-session knowledge with authority-tiered, evidence-based reasoning. (The architecture behind [evidence-grounded-memory](https://github.com/wasabikev/evidence-grounded-memory).)
- **Retrieval that isn't just top-k** — dual-path keyword + semantic recall, section-level indexing, and budgeted context injection. Vector search is *one retrieval path*, not the memory.
- **Async task orchestration** — 20+ minute LLM operations run to completion without HTTP timeouts, via Redis-backed queues and real-time WebSocket progress.
- **Multi-provider LLM routing** — OpenAI, Anthropic, Google, and Cerebras behind one interface, with intelligent fallbacks and cost optimization.
- **Multi-tenant architecture** — complete data isolation and role-based access control across organizations, with audit trails for regulated industries.

Most production work lives in private repositories due to IP considerations — [evidence-grounded-memory](https://github.com/wasabikev/evidence-grounded-memory) is the public reference implementation that reproduces the architecture in a neutral domain.

## 🚀 Selected work

**Production AI Platform (2024–present)**
- Architected a full-stack, multi-tenant SaaS platform for financial-services clients
- Built async task orchestration that eliminates HTTP timeouts for long-running AI operations
- Designed an evidence-based AI architecture that curbs hallucination through citation and provenance requirements
- Integrated 4+ LLM providers with intelligent routing and cost optimization
- Led an AWS → DigitalOcean migration that cut infrastructure costs ~60%, with an admin backup/restore system enabling zero-downtime cutover

## 🧰 Stack

**Core:** Python (async-first — Quart + async SQLAlchemy), TypeScript/React
**AI/ML:** OpenAI · Anthropic · Google · Cerebras · semantic + FTS5 retrieval (RAG) · token-budget & context-window management · document processing (PDF/Excel/Word) with OCR
**Data:** PostgreSQL (ltree, FTS5), Redis, SQLite, Pinecone
**Infra:** DigitalOcean, AWS, Docker, S3-compatible storage · CI/CD auto-deploy · structured logging & monitoring

## 📊 Background

20+ years shipping production systems for regulated industries — financial services, professional services, most recently as **Director of Technology at HKP Advisors**.

That background is the reason my AI work centers on provenance, data isolation, and auditability rather than demos: I treat agent memory as an *auditable evidentiary record*, not a black box. The hard problems in AI platforms are the ones regulated enterprise software already had to solve — trust, provenance, and isolation under real load.

## 📬 Let's connect

- **LinkedIn:** [linkedin.com/in/atkinsonkevin](https://www.linkedin.com/in/atkinsonkevin/)
- **Open to:** Staff / Principal AI Engineer and AI Platform Architecture roles

---

*Building the infrastructure that makes AI dependable in production.*
