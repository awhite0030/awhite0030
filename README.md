<h1 align="center">A. White</h1>

<p align="center">
  <strong>Software Engineer</strong><br>
  Privacy infrastructure · Edge systems · Production automation
</p>

<p align="center">
  I design and ship high-reliability systems at the edge — disposable communication,<br>
  multi-provider AI routing, and operational tooling that runs under real load.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Cloudflare%20Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare Workers"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis"/>
</p>

---

## Current work

### [Nanocoder](https://github.com/Nano-Collective/nanocoder) `Core`

An open coding agent for your terminal, built by a community collective rather than a company. Bring your own model, keep your code on your machine, and owe nothing to anyone.

<p>
  <img src="https://img.shields.io/badge/Cold%20start-~0ms-00C853?style=flat-square" alt="Cold start"/>
  <img src="https://img.shields.io/badge/Edge%20latency-%3C50ms-00C853?style=flat-square" alt="Latency"/>
  <img src="https://img.shields.io/badge/Persistence-0-00C853?style=flat-square" alt="Persistence"/>
  <img src="https://img.shields.io/badge/Runtime-Cloudflare%20Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Runtime"/>
  <a href="https://atommail.vercel.app"><img src="https://img.shields.io/badge/Demo-Live-blue?style=flat-square" alt="Demo"/></a>
</p>

### [AtomMail](https://github.com/awhite0030/atommail) `maintainer`

Zero-registration disposable email on Cloudflare Workers + Email Routing. No accounts, no persistence, no tracking. Privacy by architecture.

<p>
  <img src="https://img.shields.io/badge/Cold%20start-~0ms-00C853?style=flat-square" alt="Cold start"/>
  <img src="https://img.shields.io/badge/Edge%20latency-%3C50ms-00C853?style=flat-square" alt="Latency"/>
  <img src="https://img.shields.io/badge/Persistence-0-00C853?style=flat-square" alt="Persistence"/>
  <img src="https://img.shields.io/badge/Runtime-Cloudflare%20Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Runtime"/>
  <a href="https://atommail.vercel.app"><img src="https://img.shields.io/badge/Demo-Live-blue?style=flat-square" alt="Demo"/></a>
</p>

### [ERouter](https://github.com/awhite0030/ERouter) `maintainer`

Open-source AI gateway unifying 40+ providers behind one OpenAI-compatible endpoint. Auto-failover, token optimization (RTK), observability dashboard.

<p>
  <img src="https://img.shields.io/badge/Providers-40%2B-6366F1?style=flat-square" alt="Providers"/>
  <img src="https://img.shields.io/badge/API-OpenAI%20compatible-412991?style=flat-square&logo=openai&logoColor=white" alt="API"/>
  <img src="https://img.shields.io/badge/Failover-Automatic-00C853?style=flat-square" alt="Failover"/>
  <img src="https://img.shields.io/badge/Token%20saver-RTK-8B5CF6?style=flat-square" alt="RTK"/>
</p>

### [smm-support-bot](https://github.com/awhite0030/smm-support-bot) `maintainer`

Production Telegram support platform: topic isolation, anti-spam, Redis state, SLA automation. Built for high-volume operational queues.

<p>
  <img src="https://img.shields.io/badge/Stack-Python%20%7C%20aiogram%20%7C%20Redis-3776AB?style=flat-square&logo=python&logoColor=white" alt="Stack"/>
  <img src="https://img.shields.io/badge/SLA-Automated-00C853?style=flat-square" alt="SLA"/>
  <img src="https://img.shields.io/badge/Anti--spam-Built--in-E53935?style=flat-square" alt="Anti-spam"/>
</p>

## Performance highlights

| System | Metric | Value |
| --- | --- | --- |
| **AtomMail** | Cold start (Workers) | ~0 ms (isolate reuse) |
| **AtomMail** | Edge response | < 50 ms typical |
| **AtomMail** | Data retention | 0 (TTL-only, no permanent store) |
| **ERouter** | Upstream providers | 40+ with ordered failover |
| **ERouter** | API surface | Single OpenAI-compatible `/v1` |
| **Support bot** | State layer | Redis-backed, multi-topic |

## Focus areas

`Edge Computing` · `Cloudflare Workers` · `Privacy Engineering` · `Serverless Architecture` · `AI Gateways` · `Operational Automation` · `API Design`

## Maintainer & contributions

### Maintainer

| Repository | Role |
| --- | --- |
| **[atommail](https://github.com/awhite0030/atommail)** | Maintainer — privacy-native disposable email at the edge |
| **[ERouter](https://github.com/awhite0030/ERouter)** | Maintainer — multi-provider AI router & token optimizer |
| **[smm-support-bot](https://github.com/awhite0030/smm-support-bot)** | Maintainer — high-volume Telegram support with SLA |
| **[smm-shop-bot](https://github.com/awhite0030/smm-shop-bot)** | Maintainer — Telegram commerce with payments & RBAC |
| **[atommail-admin](https://github.com/awhite0030/atommail-admin)** | Maintainer — operational control plane for AtomMail |

### Contributor

| Repository | Role |
| --- | --- |
| **[nanocoder](https://github.com/Nano-Collective/nanocoder)** | Contributor — open coding agent for the terminal (Nano Collective) |

## Engineering principles

Systems that remain understandable under load and ownership pressure. Minimal surface area, explicit constraints, architectures a small team can fully reason about and operate without ceremony.

Privacy is a structural property, not a feature flag.

---

<p align="center">
  <em>Systems that stay private, fast, and fully ownable.</em>
</p>
