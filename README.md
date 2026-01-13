# Warren Wu (吴鹏)

## 👋 About Me

I'm a full-stack engineer passionate about building scalable, maintainable systems with modern architecture patterns. I specialize in Python backend development, TypeScript/JavaScript SDK development, and AI-powered automation systems. My work focuses on domain-driven design, event-driven architectures, and creating developer-friendly tools.

## 🛠️ Tech Stack

### Backend Development
- **Languages**: Python 3.11+, TypeScript, Go
- **Frameworks**: FastAPI, Express.js
- **Architecture Patterns**: DDD (Domain-Driven Design), CQRS, Event Sourcing, Hexagonal Architecture, TAO Pattern
- **Async Programming**: asyncio, async/await patterns
- **Data Validation**: Pydantic, Zod
- **Logging**: Loguru, Winston

### Infrastructure & DevOps
- **Cloud Platforms**: AWS (ECS, S3, CloudFront, DynamoDB), Cloudflare Workers
- **Databases**: MySQL (aiomysql), Redis, OpenSearch, DynamoDB
- **Containerization**: Docker, Docker Compose
- **CI/CD**: AWS ECR, Terraform
- **Message Queues**: Redis Pub/Sub, Celery

### Frontend & SDK Development
- **Languages**: TypeScript, JavaScript
- **Build Tools**: Vite, TypeScript Compiler
- **Module Formats**: ESM, UMD
- **Testing**: Vitest, Jest, pytest

### AI & Automation
- **LLM Integration**: LangChain, OpenAI, Anthropic, Google Gemini
- **Browser Automation**: Playwright, Puppeteer
- **Sandbox Environments**: E2B, Daytona, Docker, Fly.io

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

### general-agent
An AI-powered task automation system with real-time WebSocket communication:
- Long-running async task management
- Multi-sandbox support (E2B, Daytona, Docker, Fly.io)
- Real-time task state streaming via WebSocket
- Multi-LLM support (GPT, Claude, Gemini)
- Browser automation with Playwright
- Distributed architecture on AWS ECS + ELB
- Celery for background task processing

**Technologies**: Python 3.11+, FastAPI, SocketIO, Celery, Redis, LangChain, Playwright, Poetry

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

### trickle-slide/server
Image processing and OCR service:
- Multi-provider OCR support (Google Cloud Vision, Azure Computer Vision)
- Image segmentation and extraction
- Express.js REST API
- Cloudflare Workers for edge computing
- Sharp for image processing
- Rate limiting and security middleware

**Technologies**: TypeScript, Express.js, Google Cloud Vision, Azure Computer Vision, Sharp, Cloudflare Workers

### my-coding-agents (Open Source)
An educational project demonstrating the evolution of AI coding assistants from simple to complex:
- **4 progressive versions** (v0-v4) showing 16,703% code growth journey (33 → 5,546 lines)
- **Modular architecture** with event-driven design and sub-agent delegation system
- **15 tools** including file operations, search, system commands, conversation management, and delegation
- **Intelligent conversation compression** with 40-60% token reduction in long conversations
- **Sub-agent delegation** with 4 specialized agent types and restricted tool sets
- **Comprehensive testing** with 960+ lines of test coverage
- **Complete documentation** showing architecture evolution and best practices
- Demonstrates DDD principles, tool system design, and production-ready patterns

**Technologies**: Python 3.7+, OpenRouter API, DeepSeek v3.2, Modular OOP Architecture


## 🎯 Core Competencies

- **System Design**: Designing scalable microservices with proper separation of concerns
- **API Development**: RESTful APIs with FastAPI and Express.js, WebSocket real-time communication
- **Database Design**: Relational database design, async query optimization, search indexing
- **SDK Development**: Creating developer-friendly SDKs with comprehensive type safety
- **AI Integration**: Building AI-powered systems with LLM orchestration and tool calling
- **DevOps**: Docker containerization, AWS cloud infrastructure, CI/CD pipelines
- **Code Quality**: Writing maintainable, testable code with proper error handling

## 📚 Development Philosophy

- **Architecture First**: Design systems with clear boundaries and responsibilities
- **Type Safety**: Leverage static typing to catch errors early
- **Async by Default**: Use async/await for all I/O operations
- **Test Coverage**: Write tests alongside code development
- **Documentation**: Keep code and architecture documentation up to date
- **Developer Experience**: Build tools and SDKs that are intuitive and easy to use

## 🔗 Links

- GitHub: [@wupeng](https://github.com/wupeng)
- Projects: Check out my repositories for detailed code examples and architecture decisions

---

*Building robust, scalable systems with modern architecture patterns and best practices.*
