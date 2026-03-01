# Warren Wu (吴鹏)

## 2026 Highlights

- **HappyCapy** — AI-native sandbox platform: shipped in **19 days**, **10,000 sandboxes** provisioned, **55 annual subscribers at $2,000/yr**
- **Data Analysis Agent MVP** — natural language to SQL for enterprise data platforms, built in **5 days** on the side; [live demo](https://data-analysis-agent-warren.fly.dev/)
- **build-my-own-coding-agent** — **5 versions** (V0→V5), **33 → 9,266 lines**, sub-agent delegation lifted task success rate from **60% → 85%**, conversation compression saves **40-60% tokens**; [open source](https://github.com/warren-wupeng/build-my-own-coding-agent)
- **3,700+** GitHub contributions in the past year

---

## 👋 About Me

I'm a full-stack engineer and product builder who has been among the first to ship at every AI inflection point:

- **2023** — ChatGPT wave → AI chatbot & RAG apps
- **2024** — Claude Sonnet 3.5 → Vibe Coding tool (websites for non-developers)
- **2026** — Agent era → HappyCapy + Data Analysis Agent MVP

I specialize in Python backend development, TypeScript/JavaScript SDK development, and AI-powered Agent systems. My work focuses on domain-driven design, event-driven architectures, and building production-grade AI products.

## 🛠️ Tech Stack

### Backend Development
- **Languages**: Python 3.11+, TypeScript, Go
- **Frameworks**: FastAPI, Express.js
- **Architecture Patterns**: DDD (Domain-Driven Design), CQRS, Event Sourcing, Hexagonal Architecture, TAO Pattern
- **Async Programming**: asyncio, async/await patterns
- **Data Validation**: Pydantic, Zod
- **Logging**: Loguru, Winston

### Infrastructure & DevOps
- **Cloud Platforms**: AWS (ECS, S3, CloudFront, DynamoDB), Cloudflare Workers, Fly.io
- **Databases**: MySQL (aiomysql), Redis, OpenSearch, DynamoDB
- **Containerization**: Docker, Docker Compose
- **CI/CD**: AWS ECR, Terraform
- **Message Queues**: Redis Pub/Sub, Celery

### Frontend & SDK Development
- **Languages**: TypeScript, JavaScript
- **Build Tools**: Vite, TypeScript Compiler
- **Module Formats**: ESM, UMD
- **Testing**: Vitest, Jest, pytest

### AI & Agent Systems
- **LLM Providers**: OpenAI, Anthropic, Google Gemini, DeepSeek, Mistral — unified abstraction layer across 5 providers
- **Agent Patterns**: sub-agent delegation, tool calling, conversation compression, SWE-bench evaluation
- **Browser Automation**: Playwright, Puppeteer
- **Sandbox Environments**: E2B, Daytona, Docker, Fly.io
- **Data**: Azure Databricks, Spark/Trino, natural language to SQL

## 🏗️ Architecture Expertise

### Domain-Driven Design (DDD)
I design and implement microservices following DDD principles with clear separation of concerns:
- **Domain Layer**: Business logic, entities, value objects, domain services
- **Application Layer**: Use cases, command/query handlers, event handlers
- **Infrastructure Layer**: Database repositories, external service integrations
- **API Layer**: FastAPI routers with proper dependency injection

### Event-Driven Architecture
- Message bus implementation for domain events
- CQRS (Command Query Responsibility Segregation) patterns
- Event sourcing for audit trails and state reconstruction
- WebSocket-based real-time event streaming

### Code Quality & Practices
- **Type Safety**: Full TypeScript coverage, Pydantic models for runtime validation
- **Testing**: Unit tests, integration tests, E2E tests with comprehensive coverage
- **Documentation**: Clear code comments, architecture documentation, API references
- **Async-First**: All I/O operations use async/await for optimal performance

## 💼 Key Projects

### HappyCapy
AI-native sandbox platform for developers. Built from zero to production in **19 days**:
- 10,000 user sandboxes provisioned
- 55 annual subscribers at $2,000/year
- Full-stack: FastAPI backend, TypeScript SDK, multi-sandbox support (E2B, Daytona, Docker, Fly.io)

### Data Analysis Agent (build-my-own-data-agent)
Natural language to SQL agent for enterprise data platforms:
- Built in **5 days** on the side as MVP
- Supports Azure Databricks Genie + Spark/Trino dual environments
- Context compression, confidence scoring, semantic layer
- [Live demo](https://data-analysis-agent-warren.fly.dev/)

**Technologies**: Python, FastAPI, LLM tool-calling, Fly.io

### build-my-own-coding-agent (Open Source)
An educational project demonstrating the evolution of AI coding agents from scratch to production:
- **5 progressive versions** (V0→V5) showing the full journey: **33 → 9,266 lines** of code
- **Sub-agent delegation** with 4 specialized agent types — task success rate lifted from **60% → 85%**
- **Intelligent conversation compression** — 40-60% token reduction in long conversations
- **Unified LLM abstraction** across 5 providers (OpenAI / Anthropic / Gemini / DeepSeek / Mistral)
- **V5**: SWE-bench evaluation framework for objective agent quality measurement
- 15 tools including file operations, search, system commands, and delegation

**Technologies**: Python 3.7+, multi-provider LLM, Modular OOP Architecture

### trickle-backend
A microservices platform built with FastAPI following DDD and TAO patterns. Features include:
- Multiple domain services (auth, subs, proto, buzz, nge, link, space)
- Async MySQL connections with connection pooling
- Event-driven architecture with message bus
- CQRS implementation for read/write separation
- OpenSearch integration for full-text search
- Stripe integration for subscription management
- AWS S3 for file storage and CloudFront CDN

**Technologies**: Python 3.12+, FastAPI, aiomysql, Redis, OpenSearch, Pydantic, Poetry

### trickle-backend-sdk
TypeScript/JavaScript SDK for Trickle Backend APIs:
- Full TypeScript type definitions
- Token management with automatic refresh
- Support for both browser and Node.js environments
- SSR support with custom storage
- Comprehensive error handling
- UMD and ESM module formats
- Complete test coverage with Vitest

**Technologies**: TypeScript, Vite, Vitest

## 🎯 Core Competencies

- **AI Product Building**: Shipping Agent systems from zero to production — HappyCapy in 19 days, Data Agent MVP in 5 days
- **System Design**: Designing scalable microservices with proper separation of concerns
- **API Development**: RESTful APIs with FastAPI and Express.js, WebSocket real-time communication
- **Database Design**: Relational database design, async query optimization, search indexing
- **SDK Development**: Creating developer-friendly SDKs with comprehensive type safety
- **AI Integration**: Building Agent systems with sub-agent delegation, tool calling, and LLM orchestration
- **DevOps**: Docker containerization, AWS cloud infrastructure, Fly.io, CI/CD pipelines
- **Code Quality**: Writing maintainable, testable code with proper error handling

## 📚 Development Philosophy

- **Architecture First**: Design systems with clear boundaries and responsibilities
- **Type Safety**: Leverage static typing to catch errors early
- **Async by Default**: Use async/await for all I/O operations
- **Test Coverage**: Write tests alongside code development
- **Documentation**: Keep code and architecture documentation up to date
- **Developer Experience**: Build tools and SDKs that are intuitive and easy to use

## 🔗 Links

- GitHub: [@warren-wupeng](https://github.com/warren-wupeng)
- Personal site: [about-me terminal](https://about-2xzap1qb1-warren-wupengs-projects.vercel.app)

---

*Building AI products at every wave — 2023 ChatGPT · 2024 Coding · 2026 Agent.*
