<div align="center">

# Daniel Ude

### Backend engineer — I build the systems that stay up when it matters.

Async Python · FastAPI · PostgreSQL · Redis · Celery

**[→ dannyude.github.io/portfolio](https://dannyude.github.io/portfolio/)**

<br>

[![Portfolio](https://img.shields.io/badge/Portfolio-0A6E75?style=for-the-badge&logoColor=white)](https://dannyude.github.io/portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/daniel-ude-2b750a152/)
![Open to roles](https://img.shields.io/badge/Open_to_backend_roles-remote-22C55E?style=for-the-badge)

</div>

---

**4+ years building and shipping APIs in Python and FastAPI** — crash-ingestion pipelines for a
live game, multi-tenant SaaS, real-time clinical systems, distributed job processing. Built for
production, not for a screenshot: migration-managed, test-covered, shipped behind CI. My largest
system carries **248 passing tests** against a pipeline that stands up live Postgres and Redis on
every push.

I came to engineering from a law degree, retrained, and now **teach this stack to cohorts of 40
developers**. That route is also why picking up something unfamiliar fast is the normal case for
me — most recently a Web3 backend, shipped in a 48-hour hackathon, having never written one.

### What I've built

| | |
|:--|:--|
| **[Intentra](https://github.com/Soar-On-Technologies-Global-Concept-Ltd/ETHOnline-Startup/tree/main/intentra-monorepo)** | *ETHOnline 2026.* I owned the backend — a FastAPI modular monolith orchestrating EIP-712 mandates, a Solidity USDC escrow on Arc, and on-chain evidence. Money states commit on chain events only; a single state machine owns transaction state, enforced by an AST scan in the tests. `20 test suites · 48 hours · first Web3 project` |
| **[PatStat](https://github.com/dannyude/Pat-Stat)** | Hospital-grade real-time patient status platform. Tenant isolation enforced on every access path, RBAC, WebSocket updates, Firebase push. `248 tests · 12 migrations · CI` |
| **[DocFlow API](https://github.com/dannyude/DockFlow_API)** | Multi-tenant SaaS for LLM document extraction. Schema-driven map-reduce pipeline with reliability layers, Redis Bloom dedup, webhook callbacks. |
| **[MediReminder API](https://github.com/dannyude/medication-reminder-api)** | Async medication-adherence API. JWT rotation, session management, Redis rate limiting, Google OAuth. |
| **[ICBM Bootcamp](https://github.com/dannyude/ICBM-Technical-Bootcamp-Cohort-Two)** | The backend curriculum I teach — Python fundamentals through a full FastAPI REST API, with worked solutions. |

### How I work

- **Architecture** — per-feature modules; multi-tenancy and authorization enforced once, at the dependency layer
- **Data** — async SQLAlchemy 2.0 on PostgreSQL, every schema change through Alembic, no `create_all()` in anything that matters
- **Reliability** — Celery for anything slow, Redis for caching and rate limits, retry-and-fallback around third-party calls
- **Proof** — pytest suites covering failure paths, not just the happy one; CI on push and PR

### Stack

`Python` `FastAPI` `Flask` `SQLAlchemy 2.0` `Pydantic v2` `PostgreSQL` `Redis` `Celery`
`Docker` `Alembic` `GitHub Actions` `S3 / MinIO` `Pytest` `JWT / OAuth2` `RBAC` `WebSockets`
`Event-driven design` `EIP-712` `Solidity ABI / on-chain events`

---

<div align="center">
<sub>Open to backend engineering roles, remote — <a href="https://linkedin.com/in/daniel-ude-2b750a152/">let's talk</a>.</sub>
</div>
