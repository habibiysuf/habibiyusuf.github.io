---
# If you rename this file to index.md, this front-matter lets GitHub Pages (Jekyll) render it as a website.
title: "Maulana Yusuf — Portfolio"
description: "Backend & Data Engineer — Powering data, building the backbone."
---

<h1 align="center">Hi, I’m Maulana Yusuf 👋</h1>

<p align="center">
  <strong>Backend & Data Engineer</strong> — I design reliable systems, scalable data flows, and developer-friendly APIs.<br/>
  <em>“Powering data, building the backbone.”</em>
</p>

<p align="center">
  <a href="#projects">Projects</a> •
  <a href="#skills--tooling">Skills</a> •
  <a href="#experience--impact">Experience</a> •
  <a href="#contact">Contact</a>
</p>

---

## About Me

I build robust backend services and data pipelines with a focus on **performance, reliability, and clarity**.  
I’m comfortable from **system design** to **production ops**: APIs, databases, queues, search, caching, CI/CD, containers, and observability.

- 🔧 Favorite stack: **TypeScript/NestJS**, **PostgreSQL/Prisma**, **Redis (Redlock)**, **RabbitMQ**, **Elasticsearch/App Search**, **Kubernetes/Docker**
- 📊 I enjoy making data useful: ingestion → processing → search/analytics → dashboards
- 🧪 Pragmatic engineering: small, testable modules; meaningful metrics; docs you can actually use

---

## Projects

### 1) Sribu — Marketplace Backend (Monorepo, Microservices)
**NestJS • GraphQL • Prisma (PostgreSQL) • Redis (Redlock) • RabbitMQ • Elasticsearch • K8s**

- Built core services (users, payments, reports, vouchers, corporate jobs) with **code-first GraphQL** and **Prisma**.
- Implemented **distributed locking** (Redlock) for race-free workflows and **idempotent** background jobs.
- Added **App Search** for fast, relevance-tuned queries with analyzers and synonyms.
- Observability: structured logs, key metrics, and actionable dashboards.

> Repo/Case Study: _private_ • Tech demo available on request.

---

### 2) IoT Core (ESP32) — Simple Cloud for Makers
**Arduino/ESP32 • MQTT • Device Provisioning • REST/GraphQL APIs • S3/MinIO**

- One-click device onboarding with **deviceKey/apiKey** flows and **BLE/Wi-Fi** provisioning.
- MQTT channels for telemetry and commands; cloud rules for storage/alerts.
- Lightweight **Arduino library** to get beginners productive in minutes.

> Demo: _ask for a live walkthrough_

---

### 3) Search & Analytics Pipeline
**Ingestion workers • ETL • PostgreSQL + Elasticsearch • Caching**

- Batched ingestion with **retry + DLQ**; metrics for throughput and error budgets.
- **Read-optimized** views, denormalized indices, and **query budgets** for predictable performance.
- Built result-ranking strategies + synonym dictionaries for better UX.

> Notebook + dashboard snippets available on request.

---

## Skills & Tooling

**Languages**  
TypeScript/JavaScript, SQL, Python (data/automation), Bash

**Backend / Data**  
NestJS, Express, GraphQL (code-first), Prisma (PostgreSQL), Redis (Redlock), RabbitMQ, Elasticsearch/App Search

**Infra / DevOps**  
Docker/Podman, Kubernetes, Helm, CI/CD, GitHub Actions, Nginx, Let’s Encrypt

**Patterns**  
Event-driven, Idempotency, Sagas/Workflows, Caching, Backpressure, Observability

---

## Experience & Impact

- Designed and operated **multi-service backends** serving real users and revenue-critical paths.
- Shipped **voucher/discount engine**, **invoice & tax flows**, **corporate job modules**, **member leveling** with grace periods.
- Scaled Elastic cluster usage; tuned analyzers, mappings, and JVM/heap settings for stability.
- Reduced failure rates via **Redlock-guarded critical sections** and **reliable retries**.

---

## Selected Talks / Writings

- **Designing Idempotent Workflows with Redlock** — notes and code patterns
- **From SQL to Search** — bridging PostgreSQL with Elasticsearch/App Search
- **Making IoT Friendly for Beginners** — device provisioning patterns that don’t hurt

> Ping me for slides or code samples.

---

## Contact

- 📫 Email: **habibiysuf@gmail.com**
- 🌐 Website (GitHub Pages): **https://habibiysuf.github.io**

> Prefer WhatsApp? I can share a portfolio link and brief case studies there.

---
