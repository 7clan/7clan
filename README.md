# Mohammad Farhat

**Backend-focused full-stack developer working across AI systems, local-first software, and Flutter/mobile engineering.**

I build systems that combine practical software engineering with deeper questions around **information retrieval, grounded AI, local/private inference, agentic workflows, offline-first architecture, and reliability**. My recent work ranges from RAG and browser-run LLM experiments to privacy-conscious desktop software, production-style Flutter apps, and an experimental connectome-derived Drosophila simulation.

## Featured work

### [DigitalFlyLab](https://github.com/7clan/Fruit-fly-experiment-)
**Experimental connectome-derived Drosophila simulation & closed-loop control** · Python · neuroscience models · reproducible experiments

- Uses a pinned whole-brain Drosophila model built on the FlyWire connectome rather than an ordinary neural network labeled as a fruit-fly brain.
- Reproduces neural activity, sensory-to-motor pathways, and closed-loop target/escape control with explicit control conditions.
- Uses pre-registered gates and keeps failed learning experiments recorded instead of tuning them away.
- Current applied work is explicitly hybrid: biological/connectome-derived computation is separated from engineered perception, memory, planning, and control components.

### MediVault — private core / [public CI mirror](https://github.com/7clan/medivault-ci-public)
**Privacy-conscious clinical document system** · Next.js · Fastify · PostgreSQL/Prisma · Tauri

- Local-first application/service architecture with database provisioning, health/readiness checks, packaging, lifecycle validation, and recovery-oriented testing.
- Preserved and froze the Windows deployment path after the real target environment was identified as macOS, then qualified separate arm64/x86_64 macOS paths.
- Documents what CI proves separately from what still requires interactive user/device validation.

### [Mr Robot](https://github.com/7clan/mr-robot)
**Local AI assistant & developer environment** · TypeScript · Next.js · WebLLM · WebGPU · Prisma

- Runs pretrained language models in-browser through WebLLM/WebGPU.
- Includes educational implementations of tokenization, classification, neural-network code, and a compact transformer-style model.
- Adds grounded generation from retrieved web context, source references, follow-up resolution, and developer tooling.

### [Employee Management System + RAG](https://github.com/7clan/integrated-employee-management-system)
**Local document-grounded assistant** · Laravel · PostgreSQL/pgvector · Ollama

- Parses policy PDFs, chunks and embeds them locally, stores vectors in pgvector, retrieves relevant passages, and answers from retrieved context.
- Uses similarity gating and source metadata so unsupported questions can be refused rather than answered from guesswork.
- The RAG extension was developed independently after earlier professional exposure to semantic document search.

### [OfflineBoard](https://github.com/7clan/offlineboard-flutter)
**Offline-first Flutter project/task manager** · Flutter · Riverpod · Drift/SQLite · Dio

- Local database is the source of truth; writes work without connectivity and are delivered later through a durable mutation queue.
- Implements retry/backoff, conflict resolution, tombstones, idempotency, visible sync state, and deterministic test seams.
- CI runs formatting, static analysis, and tests on each push.

### [MarketFlow](https://github.com/7clan/marketflow-mobile) & [CareRoute](https://github.com/7clan/careroute-mobile)
**Production-style Flutter portfolio apps** · Flutter · Riverpod · Dio · secure/local persistence

- Built to demonstrate layered mobile architecture, typed networking/error handling, state management, accessibility, testing, and CI.
- MarketFlow covers marketplace/cart/checkout/order flows; CareRoute covers provider discovery, favorites, scheduling, and appointment requests.
- Both exercise the real client networking pipeline against deterministic local backends so error, timeout, cancellation, and validation paths can be tested reproducibly.

### [Money Machine](https://github.com/7clan/Money-Machine) & [Trio AI Convo](https://github.com/7clan/Trio-AI-Convo)
**Agentic and multi-model orchestration experiments**

- Money Machine explores autonomous research-to-production workflows with operating modes, safety gates, audit logging, durable artifacts, and analytics feedback.
- Trio coordinates three configurable model participants with shared context, search/fetch tools, provider fallbacks, retries, traces, and cancellation.

## Engineering stack

**Backend:** Python, PHP, Django, Laravel, Node.js, Fastify, REST APIs  
**Data:** PostgreSQL, SQLite, Prisma, pgvector, Drift  
**Frontend/mobile:** TypeScript, React, Next.js, Flutter/Dart  
**AI:** Ollama, WebLLM/WebGPU, RAG, embeddings, grounded generation, model/tool orchestration  
**Engineering:** Git/GitHub, GitHub Actions, Docker, Linux, OpenAPI/Swagger, testing, CI/CD, Tauri

## Current interests

- Information retrieval and retrieval-augmented generation
- Grounded and reliable LLM systems
- Local/private AI
- Agentic software and tool use
- Offline-first and distributed application architecture
- Privacy-conscious health/document systems
- CI, deployment, reproducibility, and reliability

## Development approach

Some recent projects use AI-assisted development tools as implementation accelerators. I retain responsibility for requirements, architecture, debugging, validation, integration, and deciding what the system should do. The project documentation distinguishes those engineering contributions from claims of manually typing every source line.

## Links

- Portfolio: https://mohammad-farhat.surge.sh/
- LinkedIn: https://linkedin.com/in/mohammad-linkedn
- Email: mohammadfarhat81000@gmail.com
