# Iyanda Dotun

### Software Engineer · Backend & Full-Stack

I build software from APIs and data models to web interfaces and mobile releases. I have **6 years of professional experience**, beginning in August 2020, across freelance consulting, client delivery, and product engineering.

My work includes real-time collaboration, social video, service marketplaces, payment integrations, and retail operations. My main backend tools are **Java, Spring Boot, TypeScript, Node.js, and NestJS**, with product delivery across **React, Next.js, React Native, and Flutter**.

Based in **Ibadan, Nigeria**. Open to remote work and relocation.

[Portfolio](https://iyandadotun.name.ng) · [LinkedIn](https://www.linkedin.com/in/iyanda-olamidotun-531399257) · [Email](mailto:olamidotun225@gmail.com)

## Selected work

### Real-time collaboration — Dialects, for Sammir

**Full-Stack Developer & Consultant · Freelance · August 2020–June 2024**

- Built the web frontend, backend, and React Native app for a project-management product with team messaging.
- Delivered GraphQL subscription messaging with observed production delivery times of **100 ms to under 300 ms**, persistent message storage, and automatic recovery of missed messages after reconnection.
- Kept web and mobile data current through subscription-driven cache and state updates; enforced workspace membership and permissions on the backend and reflected them in the clients.
- Achieved **1 second to under 2 seconds LCP** in real-user measurements and ran backend, web, and React Native tests in CI.

### Client products — Smarthive

**Lead Engineer · June 2024–August 2025**

- Led and mentored **2–3 developers and interns** at a software consultancy through technical planning, task assignment, code reviews, and delivery.
- Built a cryptocurrency and gift-card exchange backend and React Native/Expo app, released on **Google Play and the Apple App Store**, supporting **200+ completed transactions** during my engagement.
- Integrated Paystack with server-side payment verification, webhook signature validation, and duplicate-payment protection.
- Built and deployed a React retail ERP for **1–5 staff members**, managing **100+ SKUs** and producing stock-reconciliation results in **under one minute**.
- Ran automated backend, web, and mobile tests in CI.

### Social video — Tezda / PingTop

**Senior Backend Developer · September 2025–April 2026**

- Worked in a seven-person engineering team on a platform with approximately **2 million registered users** during my engagement.
- Owned backend work across authentication, live-stream initiation, social interactions, and video scoring.
- Reduced interaction response times from **3–5 seconds to under 500 ms** through event-driven processing, caching, and data-access improvements.

### Services marketplace — UVS

**Software Engineer · Freelance · April–May 2026**

- Independently built the NestJS/GraphQL backend, Flutter client, and Next.js admin application across bookings, contracts, payments, wallets, chat, and onboarding.
- Handed over a product supporting approximately **200 users, 15 businesses, and 180+ transactions**, with key backend read and write operations below **500 ms**.

## Featured projects

### [AtlasHub — Modular Business Platform](https://github.com/OlamidotunIY/atlashub_backend)

**May 2026–present · Independent project**

**Java 25 · Spring Boot 3.5 · MySQL · Redis · Kafka · Gradle**

AtlasHub brings together business capabilities for **payments, commerce, HR, and logistics**. Its internal Platform module provides shared capabilities for the products. I am implementing the foundation using DDD, hexagonal architecture, CQRS, and event-driven integration.

The implemented foundations include:

- **Identity and access:** organization/accounts management, JWT authentication, Redis-backed sessions and token revocation, trusted devices, organization switching, RBAC, and an API-key lifecycle.
- **Payment accounts and ledger:** balanced debit/credit validation, idempotent transaction references, pessimistic account locking, account-state controls, and balance snapshots.
- **Kafka event infrastructure:** transactional outbox persistence, consumer-delivery tracking, replay support, pending-event recovery, scheduled retries, and distributed locking.
- **Business compliance:** a five-step workflow covering company details, contacts, owners/officers, documents, service agreements, and provider verification outcomes.
- **Infrastructure and observability:** Terraform, Azure/K3s, Kubernetes manifests, MySQL, Redis, Kafka, Prometheus, Grafana, and Tempo. I start and stop deployments manually to control testing costs.
- **Automated test foundations:** Spring Boot Test, Testcontainers for MySQL, and WireMock.

Payments, commerce, HR, and logistics describe AtlasHub's scope; individual capabilities remain at different stages of development.

### [Errandy — Service Marketplace](https://github.com/OlamidotunIY/errandy_backend)

**NestJS · GraphQL · Prisma · Redis · BullMQ**

Errandy connects clients and providers for errands and tasks. Current engineering work focuses on a DDD refactor of wallet and escrow workflows.

- Uses append-only ledger records as the source of truth, with balance snapshots for reads.
- Enforces transaction idempotency at the database layer.
- Coordinates background processing with BullMQ workers and retry queues.
- Separates business contexts around marketplace workflows, wallets, and escrow.

## Technology

| Area | Tools I work with |
| --- | --- |
| Languages | Java, TypeScript, JavaScript, Dart |
| Backend | Spring Boot, Node.js, NestJS, Express, GraphQL, REST, WebSockets |
| Web | React, Next.js |
| Mobile | React Native, Expo, Flutter |
| Data & messaging | MySQL, PostgreSQL, MongoDB, DynamoDB, Redis, Kafka, Kinesis, Prisma |
| Cloud & delivery | AWS, Azure, Docker, Kubernetes, Terraform, GitHub Actions |
| Testing & observability | Spring Boot Test, Testcontainers, WireMock, Prometheus, Grafana, Tempo |

## How I work

I take responsibility for the full path from a business requirement to a working release: data and API design, implementation, testing, deployment, and handover.

For backend work, I pay particular attention to permissions, duplicate processing, concurrency, and recovery after failure. On web and mobile, I focus on responsive interfaces, consistent state, and performance that can be measured in use.

I also enjoy helping other developers through code reviews, technical planning, and practical mentoring.

## Let's connect

I'm interested primarily in **backend and full-stack engineering roles**, bringing experience across web and mobile product delivery.

- [Portfolio — iyandadotun.name.ng](https://iyandadotun.name.ng)
- [LinkedIn — Iyanda Dotun](https://www.linkedin.com/in/iyanda-olamidotun-531399257)
- [Email — olamidotun225@gmail.com](mailto:olamidotun225@gmail.com)
