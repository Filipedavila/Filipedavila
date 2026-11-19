### Hi, I'm Filipe 👋

Backend & Full-Stack Software Engineer, focused on **distributed event-driven systems, idempotent data pipelines, and applied AI workflows** in Node.js and TypeScript.

My work centers on clean domain boundaries, end-to-end type safety, and observable production architectures. I specialize in decomposing legacy monoliths into modular systems, engineering OLTP/OLAP data pipelines, and building stateful, schema-validated LLM workflows.

---
### ⚡ Core Production Stack

- **Backend & Architecture:** Node.js, TypeScript, NestJS, PHP (Laravel), Modular Monoliths, Domain-Driven Design (DDD).
- **Data & Storage (OLTP / OLAP):** PostgreSQL, ClickHouse (Materialized Views, `MergeTree`), MySQL, AWS S3 (cold-storage payload offloading).
- **Async & Event-Driven Pipelines:** Redis Streams (`XACK` batch consumers), BullMQ, Transactional Outbox pattern, idempotent workers.
- **Applied AI & Agentic Workflows:** LangGraph (TypeScript), backpressure-aware LLM streaming (`ReadableStream`, `AbortController`), deterministic Zod schema validation.
- **AuthZ & Security:** OpenFGA (ReBAC / Zanzibar model), OAuth2 / OIDC, JWT, Shift-Left SAST (Semgrep).
- **Observability & Ops:** OpenTelemetry (OTel), Grafana, Docker, Docker Compose, Linux, AWS (EC2, S3), GitHub Actions CI/CD.
- **Frontend & Browser Runtime:** React, TypeScript, Vite, TanStack Query, Zustand, Chrome Extensions (Manifest V3), automated WCAG accessibility pipelines.

### 📖 Tech Horizon

- **GraphRAG & Context Retrieval:** Combining Neo4j knowledge graphs with document embeddings to improve retrieval accuracy.
  
### 🛠️ Tech Stack

![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=flat&logo=typescript&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-%2343853D.svg?style=flat&logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=flat&logo=nestjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=flat&logo=postgresql&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-%23FFCC00.svg?style=flat&logo=clickhouse&logoColor=black)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=flat&logo=redis&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat&logo=amazon-aws&logoColor=white)
![OpenFGA](https://img.shields.io/badge/OpenFGA-%234A2E2B.svg?style=flat&logo=openfga&logoColor=white)
![React](https://img.shields.io/badge/React-%2320232A.svg?style=flat&logo=react&logoColor=%2361DAFB)
![Docker](https://img.shields.io/badge/Docker-%232496ED.svg?style=flat&logo=docker&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-%231C3C3C.svg?style=flat&logo=langgraph&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-%23000000.svg?style=flat&logo=opentelemetry&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-%23F46800.svg?style=flat&logo=grafana&logoColor=white)

### 🚀 Featured Open Source Work

*   **[monitor-server](https://github.com/amagovpt/monitor-server/tree/develop-v2)** (v2 architecture)  
    The core auditing backend for AccessMonitor — the official national web accessibility evaluation platform maintained by AMA (Portugal's Agency for Administrative Modernization). Engineered the migration into a high-performance DDD modular monolith utilizing PostgreSQL (OLTP) / ClickHouse (OLAP), BullMQ event-driven parsing pipelines, and OpenFGA ReBAC authorization, and deep production observability powered by OpenTelemetry, ClickHouse Clickstack, and Grafana.

*   **[monitor-evaluations](https://github.com/amagovpt/monitor-evaluations/tree/develop)**
  Standalone pure Node.js worker runtime and containerized orchestration layer decoupled from the NestJS core. Consumes idempotent BullMQ jobs and delegates CPU- and memory-intensive page audits to isolated **Browserless Chromium** containers over **CDP / WebSockets**, eliminating API Event Loop blocking and OOM crashes under concurrent load.
  
*   **[accessmonitor-docker](https://github.com/amagovpt/accessmonitor-docker)**  
    A decoupled, lightweight orchestration service extracted directly from the core evaluation engine to run automated accessibility audits independently in containerized environments.
    
*   **[observatory](https://github.com/amagovpt/observatory/tree/develop-v2)** (develop-v2)  
    The frontend dashboard for the Portuguese Web Accessibility Observatory. Led the complete codebase refactoring from legacy JavaScript to TypeScript, implementing a high-performance build pipeline with Vite, and efficient data-fetching hooks using TanStack Query.

*  **[accessmonitor-ce](https://github.com/amagovpt/accessmonitor-ce)**  
  Official Chrome and Edge extension (Manifest V3, published on the Chrome Web Store) for auditing authenticated web pages and dynamic UI states against WCAG standards. Led the codebase migration from legacy JavaScript to strict TypeScript and React, centralizing scoring logic in `@a12e/accessmonitor-rulesets` and setting up automated release pipelines (Changesets, Webpack, Husky, commitlint, GitHub Actions).
