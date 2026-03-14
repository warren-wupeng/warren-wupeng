# Warren Wu (吴鹏)

**Full-stack engineer & product builder.** Every AI wave, I'm the first to ship.

Logistics management grad → IT consultant (cross-national projects) → Accenture (AI data engineer) → Huawei AI Platform (serving internal business units; architecture team: fault-tolerant, resilient systems) → AI startup (frontend-line product dev + global growth). I think from both business and engineering perspectives.

## 2026 Highlights

- **HappyCapy** — AI-native sandbox platform: **19 days** after launch, **12K users**, **476 paid** (4% conversion); PH launch day: **2,446 signups + 70 paid** in 24h; [product](https://happycapy.ai) · [Product Hunt](https://www.producthunt.com/products/happycapy/launches) (7 launches, 5K+ total votes)
- **build-my-own-coding-agent** — **6 versions** (V0→V6), **33 → 16K lines**; V4 sub-agent delegation **60%→85%** success rate, **40-60%** token savings; V6: **multi-agent autonomous team** (PM / Engineer / Strategist), 14 Issues, 67 tests; [open source](https://github.com/warren-wupeng/build-my-own-coding-agent)
- **atos — Agent Team OS** — CLI + MCP Server for multi-agent coordination; **npm**: `@warren-wu/atos-cli`; **19 MCP tools**; works with any agent runtime (Claude Code, Cursor, custom); SQLite zero-config; [open source](https://github.com/warren-wupeng/agent-team-os) · [npm](https://www.npmjs.com/package/@warren-wu/atos-cli)
- **da2** — Python DDD + Event-Driven Architecture framework with Event Sourcing; Entity, Repository, UnitOfWork, MessageBus, EventStore, Snapshots; full async support; [open source](https://github.com/warren-wupeng/da2)
- **Data Analysis Agent MVP** — NL→SQL for enterprise data platforms (Databricks + Spark/Trino), built in **5 days** on the side; [live demo](https://data-analysis-agent-warren.fly.dev/)
- **3,800+** GitHub contributions in the past year

---

## About Me

I build AI products at every inflection point:

- **2023** — ChatGPT wave → AI chatbot & RAG image-note app (OpenAI API)
- **2024** — Claude Sonnet 3.5 → Vibe Coding tool (websites for non-developers)
- **2026** — Agent era → HappyCapy (12K users, 476 paid) + atos (Agent Team OS, npm + MCP) + da2 (DDD/EDA framework)

I specialize in Python backend, TypeScript SDK, and AI-powered Agent systems. My work focuses on domain-driven design, event-driven architectures, and shipping production-grade AI products.

---

## Key Projects

### [HappyCapy](https://happycapy.ai) — AI Sandbox Platform
AI-native sandbox platform. I own the entire backend business layer: user registration, Stripe subscription billing, API key lifecycle management.
- **19 days** post-launch: 12K users, 476 paid (4% CVR)
- PH launch day: 2,446 signups + 70 paid, **zero downtime**
- Payment success rate 99.5%, Webhook P99 < 500ms

### [build-my-own-coding-agent](https://github.com/warren-wupeng/build-my-own-coding-agent) — Open Source
From 33 lines of bash to a 16K-line production system across 6 versions:

| Version | What it solves | Key result |
|---------|---------------|------------|
| V0-V2 | How does an agent call tools? | Working tool-calling agent |
| V3 | OOP architecture rewrite | Modular, testable codebase |
| V4 | Complex task decomposition | Sub-agent delegation: 60%→85% success rate; conversation compression: 40-60% token savings |
| V5 | How to measure agent quality? | SWE-bench evaluation framework |
| V6 | How do multiple agents work as a team? | Autonomous PM + Engineer + Strategist; 14 Issues, 67 tests, Git shared state + async mailbox + SOP-driven |

### [atos — Agent Team OS](https://github.com/warren-wupeng/agent-team-os) — Open Source · [npm](https://www.npmjs.com/package/@warren-wu/atos-cli)
CLI-first coordination tool for multi-AI-agent teams. Works with any agent runtime.
- **19 MCP tools**: mail, task, SOP, config, team — native Claude Code/Desktop integration
- **Architecture**: CLI + MCP Server · SQLite (zero-config) · FTS5 full-text search
- **Design**: Messages + Tasks + SOPs (not graphs/DAGs/hierarchies)
- Install: `npx @warren-wu/atos-cli`

### [da2](https://github.com/warren-wupeng/da2) — Open Source
Lightweight Python framework for DDD + Event-Driven Architecture with Event Sourcing.
- **Core**: Entity, Command, Event, Repository, UnitOfWork, MessageBus, Bootstrap DI
- **Event Sourcing**: EventSourcedEntity, EventStore, Snapshots, optimistic concurrency
- **Async-native**: Full async counterpart for every component
- **Design**: Minimal building blocks, not a heavy framework — understand patterns by building them

### [Data Analysis Agent MVP](https://data-analysis-agent-warren.fly.dev/)
NL→SQL agent for enterprise dual-environment data platforms (Azure Databricks + Spark/Trino). Built in 5 days.

---

## Tech Stack

**Backend**: Python 3.11+, TypeScript, Go · FastAPI, Express.js · DDD, CQRS, Event Sourcing (da2)

**Infrastructure**: AWS (ECS, S3, DynamoDB), Cloudflare Workers, Fly.io · Docker · MySQL, Redis, OpenSearch

**AI & Agent**: OpenAI / Anthropic / Gemini / DeepSeek / Mistral (unified abstraction) · MCP (Model Context Protocol) · Tool Calling · Sub-agent delegation · Multi-agent coordination (atos) · Playwright · E2B, Daytona

**Data**: Azure Databricks, Spark/Trino, NL→SQL · Pydantic, Zod

---

## Links

- [LinkedIn](https://linkedin.com/in/warren-wupeng) · [GitHub](https://github.com/warren-wupeng) · [小红书: Warren和他的Agent团队](https://www.xiaohongshu.com/user/profile/597f56f282ec393545fd6896)
- [Personal terminal site](https://warren-wupeng.github.io/about-me/)
- [atos on npm](https://www.npmjs.com/package/@warren-wu/atos-cli)

---

*Building AI products at every wave — 2023 ChatGPT · 2024 Coding · 2026 Agent.*
