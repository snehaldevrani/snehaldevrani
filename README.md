<div align="center">

# Snehal Devrani

SWE Intern @ EPAM · Distributed Systems · Data Engineering · AI

[![LinkedIn](https://img.shields.io/badge/LinkedIn-snehaldevrani-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/snehaldevrani)  [![Email](https://img.shields.io/badge/snehaldevrani%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:snehaldevrani@gmail.com)

</div>

---

I build things that run in production. At EPAM I work on PySpark ETL at scale, Kafka Structured Streaming pipelines, and LangGraph multi-agent systems with RAG and Presidio PII guardrails.

---

### SpendWise — AI Finance Tracker   [live ↗](https://spendwise-web-nine.vercel.app) · [repo ↗](https://github.com/snehaldevrani/SpendWise)

Full-stack personal finance app. Parses real bank statements (HDFC/ICICI/SBI), detects subscription leaks, and answers natural-language spending questions via RAG over the user's own transaction history.

| | |
|---|---|
| **Stack** | NestJS · Next.js 15 · TypeScript · PostgreSQL · pgvector (HNSW) · BullMQ · Redis · Docker |
| **Auth** | JWT httpOnly cookies · Google OAuth · bcrypt · Redis-backed rate limiting |
| **AI** | 768-dim pgvector HNSW search · Gemini 2.5 Flash · async BullMQ ingestion queue |
| **Quality** | 94 tests · GitHub Actions CI/CD · deployed on Vercel + Render |

---

### LiteStore — Redis-Inspired KV Server   [repo ↗](https://github.com/snehaldevrani/LiteStore)

Key-value store built from scratch in Python. 357,000 ops/sec on EC2. Replaced Redis's probabilistic TTL sampling with a deterministic timing wheel — evictions happen on schedule, not by chance.

`Python` · Custom RESP protocol · In-memory hash table · AOF persistence · Deterministic TTL eviction

---

### Real-Time Market Data Pipeline   [repo ↗](https://github.com/snehaldevrani/realtime-market-surveillance)

Fault-tolerant async pipeline processing 2.4M+ API requests/day across 300+ credentials. 99.9% uptime with adaptive rate limiting, circuit breakers, and credential rotation under systemd supervision.

`Python asyncio` · `aiohttp` · `SQLite` · Adaptive rate limiting · Circuit breakers · systemd
