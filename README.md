<div align="center">

# Daniel Ude

### Backend engineer — Python, FastAPI, PostgreSQL, built test-first.

Async Python · FastAPI · PostgreSQL · Redis · Celery

**[→ dannyude.github.io/portfolio](https://dannyude.github.io/portfolio/)**

<br>

[![Portfolio](https://img.shields.io/badge/Portfolio-0A6E75?style=for-the-badge&logoColor=white)](https://dannyude.github.io/portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/daniel-ude-2b750a152/)
![Open to roles](https://img.shields.io/badge/Open_to_backend_roles-remote-22C55E?style=for-the-badge)

</div>

---

**4+ years building APIs in Python and FastAPI**: a crash-detection pipeline for a game with 4,000+
installations, multi-tenant clinical and document-processing backends, and APIs for 15 freelance clients.
I write the tests first and set up the CI that runs them. My largest system carries **248 passing tests**,
run by GitHub Actions against PostgreSQL 16 and Redis 7 service containers.

I came to engineering from a law degree, retrained, and in 2026 **led a backend cohort of 40 developers**,
writing the curriculum and reviewing their code. I'm also writing a book on test-driven backend development
with Claude Code.

### What I've built

| | |
|:--|:--|
| **[Puente](https://github.com/dannyude/pollar-app)** | *Fintech hackathon project.* Naira ↔ USDC agent escrow on Stellar. I wrote the backend and wired a teammate's Next.js UI to it by directing AI coding subagents test-first; idempotent order creation. `64 tests · live demo` |
| **[PatStat](https://github.com/dannyude/Pat-Stat)** | Multi-tenant patient status platform. Tenant-scoped routes with cross-hospital refusal tests, role-based access, real-time updates over authenticated WebSockets, Firebase push via Celery. `248 tests · 12 migrations · CI` |
| **[Intentra](https://github.com/Soar-On-Technologies-Global-Concept-Ltd/ETHOnline-Startup/tree/main/intentra-monorepo)** | *ETHOnline 2026, four-person team.* I wrote the FastAPI backend: a transaction state machine with a transition table, row locks and an audit log; EIP-712 signature checks; idempotency keys. `150 tests · first Web3 project` |
| **[DocFlow API](https://github.com/dannyude/DockFlow_API)** | LLM document extraction: documents are split, extracted concurrently and merged into schema-driven JSON on Celery workers; Redis circuit breaker, Bloom-filter dedup, webhook callbacks. |
| **[MediReminder API](https://github.com/dannyude/medication-reminder-api)** | Refresh-token rotation with reuse detection, Redis rate limiting, Google OAuth; Firebase push with SMS fallback. `73 tests` |
| **[System design guide](https://github.com/dannyude/system-design-fundamentals)** | Free, 71 pages, 30 diagrams, CC BY 4.0: one app grown from a single server, adding each component when it's needed. |
| **[ICBM Bootcamp](https://github.com/dannyude/ICBM-Technical-Bootcamp-Cohort-Two)** | The backend curriculum I wrote for my cohort: Python fundamentals through a full FastAPI REST API, with worked solutions. |

### How I work

- **Tests first**: pytest suites that cover failure paths, validation errors and cross-tenant access, not just the happy path
- **Data**: async SQLAlchemy 2.0 on PostgreSQL, schema changes through Alembic migrations
- **Reliability**: Celery for slow work; Redis for rate limits, circuit breakers and deduplication; retries with backoff around third-party calls
- **CI**: GitHub Actions running the suite against real PostgreSQL and Redis

### Stack

`Python` `FastAPI` `Flask` `SQLAlchemy 2.0` `Pydantic` `PostgreSQL` `Redis` `Celery`
`Docker` `Alembic` `GitHub Actions` `MinIO` `Pytest` `JWT / OAuth2` `WebSockets` `Sentry` `Claude Code`

---

<div align="center">
<sub>Open to backend engineering roles, remote — <a href="https://linkedin.com/in/daniel-ude-2b750a152/">let's talk</a>.</sub>
</div>
