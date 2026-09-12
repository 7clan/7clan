# Mohammad Farhat

Backend-focused full-stack developer building **AI-integrated, local-first, and privacy-conscious systems**.

My work started with practical backend engineering—APIs, databases, authentication, deployment, and production web applications—and has increasingly moved toward **retrieval-augmented generation, local language models, grounded AI, multi-model orchestration, autonomous agents, and reliable desktop/backend systems**.

I am especially interested in the engineering questions behind intelligent systems: how to ground model outputs in evidence, keep sensitive data local, build useful agent workflows, and make AI-enabled software reliable enough for real users.

## Selected work

### [Mr Robot](https://github.com/7clan/mr-robot)
**Local AI assistant and developer environment** · TypeScript · Next.js · WebLLM · WebGPU · Prisma

- Runs open-source LLMs in-browser through WebLLM/WebGPU.
- Includes hand-built educational NLP/ML components such as a BPE tokenizer, classifier, neural-network code, and a transformer-style implementation.
- Adds grounded generation from retrieved web context, inline source citations, follow-up reference resolution, and developer tooling.
- Includes training-data export workflows and local-first model experimentation.

### [Money Machine](https://github.com/7clan/Money-Machine)
**Autonomous content-production agent** · TypeScript · Next.js · Prisma · Remotion

- Implements an end-to-end agent loop for niche research, strategy, topic research, scripting, media production, quality review, publishing, and analytics.
- Uses explicit operating modes, an emergency stop, publishing safety gates, audit logging, and durable artifact tracking.
- Treats analytics as feedback for subsequent decisions rather than a separate dashboard-only feature.

### MediVault — in progress
**Privacy-conscious clinical document system** · private core repository · public [macOS CI mirror](https://github.com/7clan/medivault-ci-public)

- Built around patient/document workflows, local service architecture, authentication/device controls, encrypted document storage, backup/restore, and deployment validation.
- Originally developed around Windows deployment, then adapted toward macOS after the target user's actual environment became clear.
- The macOS work includes provisioning, launch/persistence behavior, CI validation, readiness checks, backup/restore proofs, and platform-specific packaging work.

### [Employee Management System + RAG](https://github.com/7clan/integrated-employee-management-system)
**Local document-grounded assistant** · Laravel · PostgreSQL/pgvector · Ollama

- Extends an employee-management application with a local RAG pipeline.
- Parses policy documents, chunks and embeds them with Ollama, stores vectors in PostgreSQL/pgvector, retrieves relevant passages, and answers from retrieved context.
- Uses a similarity threshold and source metadata so the assistant can refuse unsupported answers rather than inventing policy information.

### [Trio AI Convo](https://github.com/7clan/Trio-AI-Convo)
**Three-model collaborative chat system** · React · TypeScript · Node.js · Ollama

- Orchestrates three configurable AI participants across cloud/local model hosts.
- Supports repeated deliberation rounds in which each model receives the evolving conversation history.
- Adds search/fetch tools, provider fallbacks, tool traces, timeouts, retry/error handling, and cancellation.

## Software engineering work

I also build conventional production-oriented applications with **Python/Django, PHP/Laravel, Node.js, React, PostgreSQL, REST APIs, JWT/RBAC, Docker, Linux, Git, and CI/deployment tooling**.

During a six-month software-development internship, I worked on Django/Laravel backends, PostgreSQL-backed APIs, an Ollama-powered internal semantic-search assistant, OpenAPI/Swagger documentation, and collaborative Git/code-review workflows.

## Current technical interests

- Retrieval-augmented generation and information retrieval
- Grounded and reliable LLM systems
- Local/private AI
- Agentic software systems and tool use
- Backend and distributed application architecture
- Privacy-conscious health and document systems
- Deployment, CI, observability, and reliability

## Links

- Portfolio: https://mohammad-farhat.surge.sh/
- LinkedIn: https://linkedin.com/in/mohammad-linkedn
- Email: mohammadfarhat81000@gmail.com
