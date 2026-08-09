# Victor Ajao

<div align="center">

**Tier‑1 Enterprise Architect | Senior Full‑Stack Engineer | System Design Specialist**

*Designing and delivering production-grade systems that scale to millions of transactions — microservices, fintech, healthcare, and AI.*

[LinkedIn](https://www.linkedin.com/in/victor-ajao-970771253/) • [GitHub](https://github.com/Ajao-Victor) • [Email](mailto:victoroluwatimileyin3@gmail.com)

[![GitHub followers](https://img.shields.io/github/followers/Ajao-Victor?style=social)](https://github.com/Ajao-Victor)
[![GitHub User's stars](https://img.shields.io/github/stars/Ajao-Victor?style=social)](https://github.com/Ajao-Victor)

</div>

---

## About Me

I am a Tier‑1 Enterprise Architect and Senior Full‑Stack Engineer focused on designing resilient, secure, and observable systems for fintech, healthcare, and enterprise SaaS. I design production architectures, lead delivery, and mentor engineering teams to ship reliable software at scale.

Core strengths: system design, distributed transactions, observability, security‑first architecture, operational excellence, and a production-minded frontend stack.

### What I Do
- Enterprise Architecture — microservices, event-driven platforms, bounded contexts
- System Design — distributed transactions, real-time ledgers, high-throughput processing
- Frontend Engineering — React, TypeScript, Next.js, Vite, performance tuning and UI architecture
- Fintech — wallets, payment rails, reconciliation, regulatory compliance
- Healthcare — HIPAA-aware architectures, encrypted records, auditable workflows
- AI Integration — LLM-driven agents, embeddings, and analytics pipelines
- Security — OAuth2, JWT, RBAC, encryption, hardened input validation

### Specializations
- Backend: NestJS, Node.js, TypeScript, SOLID & DDD
- Frontend: React (Hooks, Suspense), Next.js/SSR, Vite, TypeScript, Redux/Zustand, Tailwind, MUI
- Databases: PostgreSQL (partitioning, indexing), Prisma, TypeORM
- Messaging: Redis, BullMQ, event streaming
- Real-time: Socket.io, WebSockets
- DevOps: Docker, CI/CD (GitHub Actions), Prometheus/Grafana

---

## Enterprise Portfolio: Tier‑1 Projects

Below are the projects I lead or architect at the enterprise level. Each entry includes a concise professional summary and technical highlights.

### JustXend Backend — Enterprise Fintech Platform
Status: Production | Team Size: 4–6 engineers

Summary: JustXend is a high‑throughput payments and wallet platform that supports multi‑currency wallets, instant transfers, and virtual IBAN provisioning. The system focuses on transactional correctness, regulatory compliance, and low‑latency settlement.

What it does (business value):
- Enables multi‑currency account management and on/off ramps for fiat flows
- Provides real‑time balance updates, atomic transfers, and double‑entry ledger accounting
- Automates settlement reconciliation and flags variances for operations teams
- Exposes audit trails and reporting for compliance and forensic analysis

Technical highlights:
- Modular NestJS microservice architecture with domain separation (payments, ledger, reconciliation)
- PostgreSQL with strong transactional guarantees and Prisma ORM for type‑safe access
- BullMQ job queues for settlement, retries and reconciliation workflows
- Redis for caching balances, rate limiting and distributed locks
- Security: JWT + Passport, HSM or key‑management for transaction signing, encryption at rest
- Observability: structured logs, distributed tracing, SLOs and alerting

Repository: (if you want a direct link include `https://github.com/Ajao-Victor/JustXend-Backend` — add or update if repo name differs)

---

### AjiCore — B2B SaaS Enterprise Platform
Status: Production

Summary: AjiCore is a multi‑tenant B2B SaaS platform offering workspace and tenant isolation, enterprise-grade permissions, analytics, and extensible integrations for customers.

What it does (business value):
- Provides isolated tenant workspaces with row‑level security and configurable features per tenant
- Offers admin tooling for customer onboarding, API key management and webhook integrations
- Delivers analytics and reporting to customers and internal teams

Technical highlights:
- NestJS back end with modular services and tenant routing
- React + TypeScript frontend with configurable theming per tenant
- PostgreSQL with Row‑Level Security (RLS) and Prisma for migrations and ORM
- Webhooks, API rate limiting, and SSO readiness for enterprise customers
- CI/CD and automated tests to maintain high quality across tenants

Repository: (if you have a repo link, I’ll add it; common placeholder: `https://github.com/Ajao-Victor/AJICOR_CORE`)

---

### Project KLC — Full‑Stack Church Management Platform
Status: Active / Deployable

Summary: Project KLC manages members, attendance, contributions, and communications for churches with transactional integrity and automation (WhatsApp/email).

What it does (business value):
- Tracks member data, events and attendance with exportable reports
- Automates event reminders and contribution receipts via WhatsApp integrations
- Provides admin dashboards for operations and finance teams

Technical highlights:
- React + Vite frontend, NestJS backend, Prisma + PostgreSQL, BullMQ for background jobs
- Role‑based access control (ADMIN / LEADER / USER), Swagger API docs and CI integration

Repository: https://github.com/Ajao-Victor/Project-KLC

---

### Project AEGIS — Live Clinical Event Sentinel
Status: Hackathon → Clinical pilot-ready

Summary: AEGIS streams Digital Twin clinical telemetry and applies rule evaluation for metabolic and DDI (Drug‑Drug Interaction) screening, surfacing critical events to clinicians in near real‑time.

What it does (business value):
- Reduces time‑to‑alert for critical lab values or medication interactions during patient care
- Provides auditable incident records for clinical governance and follow‑up

Technical highlights:
- React dashboard, NestJS rules engine, TypeORM + PostgreSQL persistence
- Integration with Ontomorph DTP SDK (OAuth2) for Digital Twin context

Repository: https://github.com/Ajao-Victor/Project-AEGIS-Sentinel

---

### Tonash Hospital — Healthcare Management System
Status: Production / Clinical use

Summary: Tonash Hospital provides patient management, appointment scheduling, prescribing workflows, and encrypted medical records for healthcare teams.

What it does (business value):
- Streamlines patient intake and clinical workflows, reducing administrative overhead
- Ensures secure record‑keeping and audit trails for compliance

Technical highlights:
- React frontend, Node.js/Express backend, PostgreSQL, JWT authentication and encryption
- Production deployment (Vercel link available in repo)

Repository: https://github.com/Ajao-Victor/Tonash-Hospital

---

## Tier‑2 & Tier‑3 Projects (select highlights)

- folConnect — Real‑time conferencing & collaboration (React, Socket.io)
- folCommerce — E‑commerce storefront & backend (Stripe payments, Next.js)
- Fol — Learning platform and code demos (React, Node.js)
- Printiv — Print order management (React, Node.js)
- Robot‑Friends / RobotApp‑React — Frontend educational projects and Redux patterns

Full repo list: https://github.com/Ajao-Victor?tab=repositories

---

## Frontend Expertise (expanded)

I lead frontend engineering with a production focus — architecture, types, performance and accessibility.
- TypeScript-first component design and strongly typed contracts
- Component architecture: atomic design, hooks, and reusable patterns
- Performance: code‑splitting, SSR/ISR (Next.js), memoization, bundle analysis
- State: Redux (Saga/Thunk), Zustand, Context API
- Styling & Accessibility: Tailwind, MUI, ARIA-first approach
- Testing: React Testing Library, Jest, Cypress

---

## How I can help / Work with me

- Architecture reviews and ADRs for new systems
- Building production microservices with observability and SLOs
- Full‑stack implementation & deployment (CI/CD + infra)
- Mentorship and technical leadership for engineering teams

---

## Next steps

1. Confirm whether the actual repository names/URLs for JustXend and AjiCore differ from the placeholders — I’ll convert placeholders to direct links.
2. Pick any 3 projects to expand next (diagrams, quickstart, API examples) and I’ll add them.
3. Supply screenshots/diagrams if you want visuals included; otherwise I’ll add placeholders.

---

## Let's Connect
- LinkedIn: https://www.linkedin.com/in/victor-ajao-970771253/
- GitHub: https://github.com/Ajao-Victor
- Email: victoroluwatimileyin3@gmail.com

---

**Building systems that scale. Architecture that endures. Code that matters.** 🚀
