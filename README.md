Hi, I'm Filipe 👋

I am a **Software Engineering Consultant focused on engineering resilient modular monoliths, high-throughput asynchronous pipelines, and low-latency OLAP data architectures for mission-critical platforms.**

My work centers on strict domain invariants, end-to-end type safety, and observable, maintainable boundaries in enterprise environments.

---

### ⚡ Core Production Stack
* **Modular Backend Architecture:** Designing highly cohesive, domain-driven application structures with NestJS and Node.js.
* **Data Architecture (OLTP, OLAP & Relational Persistence):** High-performance transactional modeling and query optimization across PostgreSQL, MySQL, and real-time analytical workloads using ClickHouse.
*  **Cloud-Native & AWS Infrastructure:** Designing scalable, fault-tolerant cloud architectures on AWS, leveraging robust compute, serverless pipelines, and container orchestration.
* **Observability & Telemetry:** Instrumenting production distributed systems and modular monoliths with OpenTelemetry (OTel), Prometheus, and Grafana.
* **Asynchronous Processing & Inter-Service Communication:** Building decoupled, fault-tolerant event-driven pipelines and cross-service communication layers using BullMQ and Redis Streams to orchestrate distributed workflows between monolithic cores and independent microservices.
* **Fine-Grained Authorization:** Implementing context-aware Relationship-Based Access Control (ReBAC) with OpenFGA (Zanzibar model).
* **Security & IAM:** OAuth2, OpenID Connect (OIDC), JWT, OpenFGA (ReBAC / Zanzibar), RBAC, Shift-Left Security (SAST/DAST).
* **Fullstack Capability:** Building performant, data-dense interfaces and dashboards in React (TypeScript, Zustand, TanStack Query).
* **Web Accessibility:** Orchestrating automated accessibility evaluation pipelines and auditing compliant with WCAG standards.
* **Containerization & Infrastructure:** Architecting fully containerized, production-grade microservices and modular architectures using Docker and Docker Compose, ensuring absolute environment parity, isolated runtime sandboxes, and robust volume/network management.

### 📖 Tech Horizon
* **Agentic Workflows:** Exploring stateful, deterministic multi-agent orchestration patterns using LangGraph.
  
🛠️ Tech Stack

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
![Prometheus](https://img.shields.io/badge/Prometheus-%23E6522C.svg?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-%23F46800.svg?style=flat&logo=grafana&logoColor=white)

🚀 Featured Open Source Work

*   **[monitor-server](https://github.com/amagovpt/monitor-server/tree/develop-v2)** (v2 architecture)  
    The core auditing backend for AccessMonitor — the official national web accessibility evaluation platform maintained by AMA (Portugal's Agency for Administrative Modernization). Engineered the migration into a high-performance DDD modular monolith utilizing PostgreSQL (OLTP) / ClickHouse (OLAP), BullMQ event-driven parsing pipelines, and OpenFGA ReBAC authorization, and deep production observability powered by OpenTelemetry, Prometheus, and Grafana.
*    **[monitor-evaluations](https://github.com/amagovpt/monitor-evaluations/tree/develop)**
A standalone, pure Node.js microservice engineered to isolate resource-intensive web accessibility evaluation workloads from the monolithic core. Built by decoupling the heavy evaluation engine into a lightweight runtime (dropping NestJS), it leverages optimized Alpine Chromium processes, strict V8 memory guards, and asynchronous BullMQ pipelines to eliminate resource contention and scale cleanly in containerized environments.
*   **[accessmonitor-docker](https://github.com/amagovpt/accessmonitor-docker)**  
    A decoupled, lightweight orchestration service extracted directly from the core evaluation engine to run automated accessibility audits independently in containerized environments.
*   **[observatory (develop-v2)](https://github.com/amagovpt/observatory/tree/develop-v2)** (develop-v2)  
    The frontend dashboard for the Portuguese Web Accessibility Observatory. Led the complete codebase refactoring from legacy JavaScript to TypeScript, implementing a high-performance build pipeline with Vite, and efficient data-fetching hooks using TanStack Query.
