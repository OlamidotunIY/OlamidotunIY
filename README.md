<!-- ========================================================================= -->
<!--                               HERO SECTION                                -->
<!-- ========================================================================= -->

<div align="center">

<img src="./assets/header-animation.svg" width="100%" alt="Header"/>

<br/>

# Dotun

### Backend Engineer • Distributed Systems • Fintech Infrastructure

Building resilient software through **Domain-Driven Design** and **Enterprise Integration Patterns**.

<p>

<a href="https://github.com/olamidotunIY">
<img src="https://komarev.com/ghpvc/?username=olamidotunIY&label=Profile%20Views&color=2563eb&style=flat-square"/>
</a>

<a href="https://github.com/olamidotunIY?tab=followers">
<img src="https://img.shields.io/github/followers/olamidotunIY?style=flat-square&color=2563eb"/>
</a>

<a href="https://github.com/olamidotunIY?tab=repositories">
<img src="https://img.shields.io/badge/dynamic/json?url=https://api.github.com/users/olamidotunIY&query=$.public_repos&label=Repositories&style=flat-square&color=0ea5e9"/>
</a>

<img src="https://img.shields.io/badge/Open%20Source-Love-red?style=flat-square"/>

<img src="https://img.shields.io/badge/Freelance-Available-success?style=flat-square"/>

</p>

</div>

---

<img src="./assets/divider.svg" width="100%"/>

# 💻 Backend Runtime

<div align="center">

<img src="./assets/terminal-runtime.svg" width="100%" alt="Backend runtime terminal"/>

</div>

---

<img src="./assets/divider.svg" width="100%"/>

# 👨‍💻 About Me

<table>

<tr>

<td width="56%" valign="top">

### Engineering Profile

| | |
|---|---|
| **Role** | Backend Engineer |
| **Experience** | 3+ years |
| **Mission** | Design backend systems that remain reliable, scalable, and maintainable as products evolve |

**Specialization**

<img src="https://img.shields.io/badge/-Backend%20Architecture-161b22?style=flat-square&color=1f2937"/> <img src="https://img.shields.io/badge/-Domain%20Driven%20Design-161b22?style=flat-square&color=1f2937"/> <img src="https://img.shields.io/badge/-Enterprise%20Integration%20Patterns-161b22?style=flat-square&color=1f2937"/>
<img src="https://img.shields.io/badge/-Event%20Driven%20Systems-161b22?style=flat-square&color=1f2937"/> <img src="https://img.shields.io/badge/-Payment%20Infrastructure-161b22?style=flat-square&color=1f2937"/> <img src="https://img.shields.io/badge/-Distributed%20Applications-161b22?style=flat-square&color=1f2937"/>

**Currently Deepening**

<img src="https://img.shields.io/badge/-Java-2563eb?style=flat-square"/> <img src="https://img.shields.io/badge/-Distributed%20Computing-2563eb?style=flat-square"/> <img src="https://img.shields.io/badge/-Algorithms%20%26%20Data%20Structures-2563eb?style=flat-square"/>

</td>

<td width="44%" valign="top">

### What I Build

- Payment & ledger systems
- Event-driven marketplaces
- Distributed applications
- ERP / commerce infrastructure
- Developer-facing SDKs

<br/>

### Philosophy

> Software should survive growth.

I solve hard engineering problems through
architecture, not temporary fixes — modeling
the domain properly before writing a line of
infrastructure code.

Right now that means going deep on Java,
hexagonal architecture, and the patterns
real payment processors run on.

</td>

</tr>

</table>

---

<img src="./assets/divider.svg" width="100%"/>

# 🚀 Current Focus

<div align="center">

| Mastering        | Building  |
| ----------------- | --------- |
| Java               | Errandy   |
| Domain-Driven Design | AtlasPay  |
| Enterprise Integration Patterns | Ventra    |
| Algorithms & Data Structures | — |

</div>

<br/>

> **"Good developers write code. Great engineers design systems."**

<img src="./assets/divider.svg" width="100%"/>

<!-- ========================================================================= -->
<!--                          FEATURED PROJECTS                                -->
<!-- ========================================================================= -->

# 🏗 Engineering Showcase

Instead of building isolated applications, I design systems that demonstrate
production-grade architecture, scalability, and long-term maintainability.

<br/>

<div align="center">

<img src="./assets/ecosystem-diagram.svg" width="100%" alt="Engineering ecosystem diagram"/>

</div>

---

## 🚀 Errandy

> **Service marketplace built around Domain-Driven Design and Enterprise Integration Patterns.**

<table>

<tr>

<td width="65%" valign="top">

### Overview

A NestJS + GraphQL + Prisma marketplace connecting clients and providers for
errands and tasks — currently undergoing a full DDD/EIP refactor across
bounded contexts, with **Wallet** and **Escrow** as the primary focus.

The wallet is ledger-only: an append-only `LedgerEntry` table is the source
of truth, with a `WalletBalanceSnapshot` as a read-side cache. Escrow runs a
two-phase hold flow. Idempotency is enforced at the database layer via a
unique constraint on the ledger key, not just application logic.

### Architecture

- Domain-Driven Design (DDD)
- Enterprise Integration Patterns (EIP)
- Event-driven architecture, domain events
- Idempotent, append-only ledger
- BullMQ background workers + retry queues
- CQRS-flavored read/write separation

</td>

<td width="35%" valign="top">

### Features

- ✔ Wallets (ledger-based)
- ✔ Escrow (two-phase hold)
- ✔ Provider matching
- ✔ Payments
- ✔ Organization accounts
- ✔ Chat & notifications
- ✔ Background processing
- ✔ Real-time updates

</td>

</tr>

</table>

---

## 💳 AtlasPay

> **Self-hosted payment infrastructure focused on financial correctness, not just payment processing.**

<table>

<tr>

<td width="65%" valign="top">

### Goal

A Java 21 / Spring Boot platform, built on hexagonal architecture, modeled
after systems like Stripe and Paystack. Instead of wrapping an existing
gateway, it recreates the core patterns those systems run on internally —
across seven domains: Identity & Onboarding, Accounts, Ledger, Transfers,
Cards, Limits, and Platform Access.

### Architecture

- Domain-Driven Design, hexagonal architecture
- Double-entry ledger + reconciliation
- Idempotent transaction pipelines
- Multi-module Gradle (Kotlin DSL)
- Event-driven processing, domain events

</td>

<td width="35%" valign="top">

### Modules

- ✔ Ledger
- ✔ Transfers
- ✔ Wallet engine
- ✔ Reconciliation
- ✔ Audit trail
- ✔ Event store
- ✔ Retry processing

</td>

</tr>

</table>

---

## 🧱 Ventra

> **Open-source ERP / commerce platform, built to be run — not just imported.**

<table>

<tr>

<td width="65%" valign="top">

### Vision

A Java 21 / Spring Boot ERP and commerce platform spanning 14 business
domains, architected as seven independent modules (core, persistence,
event bus, fraud, gRPC API, and the runnable app). Client SDKs connect over
gRPC — adopters run `ventra-app` as a long-lived service, the same way
they'd run Postgres or Kafka, rather than embedding the whole thing as a
library.

The `catalog` domain is fully implemented end-to-end, with Flyway
migrations and a booting app verified by smoke tests. `inventory` is
specced around an append-only `StockLedgerEntry` ledger with pessimistic
locking to prevent oversell.

### Architecture

- Domain-Driven Design across 14 business domains
- Multi-module Gradle (Kotlin DSL)
- gRPC-first SDK architecture
- Pluggable event bus (in-memory / Kafka)
- Append-only ledgers for inventory & stock

</td>

<td width="35%" valign="top">

### Status

- ✔ Catalog — shipped, smoke-tested
- ◐ Inventory — specced
- □ Sales / Orders — planned
- □ Fraud module — planned
- □ Public SDK launch

</td>

</tr>

</table>

---

<div align="center">

## ⚙ Core Engineering Principles

| Principle | Why |
|-----------|-----|
| Domain-Driven Design | Model business problems properly |
| Enterprise Integration Patterns | Reliable communication between systems |
| Event-Driven Architecture | Loose coupling & scalability |
| Hexagonal / Clean Architecture | Long-term maintainability |
| Idempotency by default | Financial systems can't double-process |

</div>

---

<img src="./assets/divider.svg" width="100%"/>

<!-- ========================================================================= -->
<!--                         ENGINEERING DASHBOARD                             -->
<!-- ========================================================================= -->

# 📊 Engineering Dashboard

<div align="center">

<table>

<tr>

<td align="center" width="50%">

<img
height="185"
src="https://github-readme-stats.vercel.app/api?username=olamidotunIY&show_icons=true&hide_border=true&theme=tokyonight"/>

</td>

<td align="center" width="50%">

<img
height="185"
src="https://github-readme-stats.vercel.app/api/top-langs/?username=olamidotunIY&layout=compact&hide_border=true&theme=tokyonight"/>

</td>

</tr>

</table>

<br/>

<img
width="100%"
src="https://github-readme-activity-graph.vercel.app/graph?username=olamidotunIY&bg_color=0d1117&color=58a6ff&line=3b82f6&point=f8fafc&area=true&hide_border=true&custom_title=Contribution%20Activity"/>

</div>

---

<img src="./assets/divider.svg" width="100%"/>

# 👾 Contribution Activity

<div align="center">

<picture>

<source
media="(prefers-color-scheme: dark)"
srcset="./assets/pacman-contribution-graph-dark.svg"/>

<source
media="(prefers-color-scheme: light)"
srcset="./assets/pacman-contribution-graph.svg"/>

<img
width="100%"
src="./assets/pacman-contribution-graph-dark.svg"/>

</picture>

<br/>

*"Every green square represents another lesson learned."*

</div>

---

<img src="./assets/divider.svg" width="100%"/>

<!-- ========================================================================= -->
<!--                              SKILLS                                      -->
<!-- ========================================================================= -->

# ⚙ Engineering Stack

<div align="center">

| Category | Stack |
|---|---|
| **Languages** | <img src="https://skillicons.dev/icons?i=ts"/> <img src="https://skillicons.dev/icons?i=js"/> <img src="https://skillicons.dev/icons?i=java"/> <img src="https://skillicons.dev/icons?i=python"/> |
| **Backend** | <img src="https://skillicons.dev/icons?i=nestjs"/> <img src="https://skillicons.dev/icons?i=spring"/> <img src="https://skillicons.dev/icons?i=nodejs"/> <img src="https://skillicons.dev/icons?i=graphql"/> <img src="https://skillicons.dev/icons?i=prisma"/> |
| **Data** | <img src="https://skillicons.dev/icons?i=postgres"/> <img src="https://skillicons.dev/icons?i=mongodb"/> <img src="https://skillicons.dev/icons?i=redis"/> |
| **Infrastructure** | <img src="https://skillicons.dev/icons?i=docker"/> <img src="https://skillicons.dev/icons?i=aws"/> <img src="https://skillicons.dev/icons?i=linux"/> <img src="https://skillicons.dev/icons?i=githubactions"/> <img src="https://skillicons.dev/icons?i=git"/> |

</div>

---

<img src="./assets/divider.svg" width="100%"/>

<!-- ========================================================================= -->
<!--                           LEARNING ROADMAP                               -->
<!-- ========================================================================= -->

# 📈 Engineering Roadmap

```text
Backend Engineering        ████████████████████ 100%
Domain Driven Design       ████████████████████ 100%
Event Driven Systems       ███████████████████░ 95%
System Design              ██████████████████░░ 90%
Cloud Infrastructure       ████████████████░░░░ 80%
Java                       ███████████░░░░░░░░░ 55%
Algorithms                 ██████████░░░░░░░░░░ 50%
Data Structures            ██████████░░░░░░░░░░ 50%
```

---

> **"Software should outlive frameworks.**
>
> **Architecture should outlive developers.**
>
> **Great systems are designed for change — not rewritten because of it."**

<img src="./assets/divider.svg" width="100%"/>

<!-- ========================================================================= -->
<!--                          SERVICE DISCOVERY                               -->
<!-- ========================================================================= -->

# 🌐 Service Discovery

<div align="center">

<img src="./assets/terminal-service.svg" width="100%" alt="Service discovery terminal"/>

<br/>

<a href="https://github.com/olamidotunIY">
<img src="https://img.shields.io/badge/github.service-ONLINE-22c55e?style=for-the-badge&logo=github&logoColor=white&labelColor=111827"/>
</a>

<br/><br/>

<a href="https://linkedin.com/in/iyanda-olamidotun-531399257">
<img src="https://img.shields.io/badge/linkedin.service-ONLINE-2563eb?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=111827"/>
</a>

<br/><br/>

<a href="https://x.com/devpark1999">
<img src="https://img.shields.io/badge/x.service-ONLINE-black?style=for-the-badge&logo=x&logoColor=white&labelColor=111827"/>
</a>

<br/><br/>

<a href="mailto:olamidotun225@gmail.com">
<img src="https://img.shields.io/badge/email.service-ONLINE-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=111827"/>
</a>

</div>

---

<img src="./assets/divider.svg" width="100%"/>

<!-- ========================================================================= -->
<!--                         CURRENT OBJECTIVES                               -->
<!-- ========================================================================= -->

# 🎯 Current Objectives

<div align="center">

| Building | Studying | Long-term Goal |
|----------|----------|----------------|
| **Errandy** | Java | Senior Backend Engineer |
| **AtlasPay** | Distributed Systems | Fintech Infrastructure |
| **Ventra** | Algorithms & Data Structures | Open Source Infrastructure |

</div>

---

<img src="./assets/divider.svg" width="100%"/>

<!-- ========================================================================= -->
<!--                                FOOTER                                    -->
<!-- ========================================================================= -->

<div align="center">

<img src="./assets/footer.svg" width="100%"/>

<br/>

### Thanks for stopping by 👋

If you're interested in backend engineering, payment infrastructure,
Domain-Driven Design, or Enterprise Integration Patterns, I'd love to connect.

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:0f172a,30:1e293b,70:2563eb,100:3b82f6"/>

</div>

<!-- ========================================================================= -->
<!--                                END                                       -->
<!-- ========================================================================= -->
