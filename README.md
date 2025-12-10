# Roman Zidinov · Python Backend Developer

6+ years of experience designing, implementing and operating production backends.

**Core focus:** Python · FastAPI · async I/O · PostgreSQL · Redis · ETL/data pipelines · Docker · CI/CD

---

## At a glance

- 6+ years building and running backends for a US e-commerce product company (remote since 2019)
- Migrated core operations from Google Sheets + Apps Script + JS/PHP/Excel formulas to a modular monolith on FastAPI + PostgreSQL
- Own and evolve a unified FastAPI + async SQLAlchemy platform for warehouse operations, inventory, pricing and marketplace integrations
- Act as a tech owner for the internal backend platform, driving technical decisions and roadmap
- Design a separate async ETL service using **Hexagonal (ports & adapters) architecture**
- Currently rolling out an observability stack (Prometheus + postgres-exporter + Grafana) for the main backend
- Open to **remote Python backend roles** (full-time, part-time or contract)

---

## Tech Stack

### Backend & Async

- Python 3.12 · FastAPI · Django  
- ASGI stack: uvicorn, gunicorn  
- Async I/O: `asyncio`, `httpx`, async SQLAlchemy 2.x (`sqlalchemy[asyncio]`, `asyncpg`, `aiosqlite`)  
- Background & scheduled jobs: Celery, Flower, APScheduler  
- Auth: OAuth2, JWT (`pyjwt[crypto]`), bcrypt  
- File upload / multipart: `python-multipart`

### Data & Storage

- PostgreSQL (primary) · SQL · SQLAlchemy (sync/async) · Alembic  
- Redis (caching, queues)  
- MongoDB (Atlas – basic usage)  
- Object storage: AWS S3, MinIO  
- SQLite (light workloads via `aiosqlite`)

### Integrations & ETL

- Marketplaces & commerce: Amazon SP-API & Feeds, eBay (SOAP/REST), Walmart, NewEgg / NewEggBusiness, Shopify, ShipStation  
- Cloud & APIs: AWS EC2/S3, Google APIs (Sheets/Drive, `google-api-python-client`, `google-auth-*`)  
- Telegram: Telegram Bot API, `aiogram`  
- Other: XML/JSON transforms (`xmltodict`), `requests`, `requests-toolbelt`, `BeautifulSoup`  
- Design and implementation of async ETL pipelines between internal DB and 3rd-party APIs

### Infra, Deployments & Observability

- Docker · Docker Compose  
- Nginx as reverse proxy  
- CI/CD: GitHub Actions, pre-commit, ruff, black  
- Environments: Linux servers (Hetzner, AWS EC2, Render, Heroku)  
- Monitoring & metrics: Prometheus, postgres-exporter, Grafana  
- Cloudflare (DNS/proxy setup)

### Testing & Quality

- pytest · pytest-asyncio  
- mypy (static typing), type-hints-first approach  
- ruff, black, isort, pre-commit hooks  
- Coverage tracking and simple quality gates in CI

### Frontend & Scripting (support-level, for internal tools)

- JavaScript / TypeScript · Node.js  
- React · Angular  
- Google Apps Script · AppSheet  
- Basic Firebase

---

## Architecture & Practices

- Modular monolith with **layered architecture** (domain/application/infrastructure separation)  
- Hexagonal (ports & adapters) design for a separate ETL service  
- Strong OOP & **SOLID** principles in core domains  
- Async-first mindset: non-blocking I/O, background workers, scheduled jobs  
- Clean contracts: explicit DB schemas, DTOs, HTTP APIs and background workflows  
- Observability as part of the design: structured logging, metrics, health checks  
- Production-oriented: rollback-safe deployments, feature flags where needed, gradual rollouts

---

## Featured Work

### Internal E-commerce Backend Platform (Tekswamp, Inc.) — core role

Unified backend platform (Python/FastAPI + PostgreSQL) for a US electronics seller operating on Amazon, eBay, Walmart and other marketplaces.

Key responsibilities & impact:

- Migrated critical workflows from Google Sheets/App Script/JS/PHP/Excel formulas into a maintainable backend platform  
- Designed and implemented core services for inventory, product catalog, pricing and sales/profitability analytics  
- Ensure data consistency for **tens of thousands of physical items** and **hundreds of thousands of SKUs** across multiple marketplace accounts  
- Built async ETL pipelines and background jobs (Celery, APScheduler) for imports/exports, reconciliations and reporting without timeouts  
- Integrated with Amazon SP-API, eBay/Walmart/Newegg/Shopify/ShipStation and other external systems  
- Containerized services with Docker and set up CI/CD (GitHub Actions, tests, pre-commit hooks) for predictable, rollback-safe deployments  
- Introduced monitoring stack (Prometheus + postgres-exporter + Grafana) and health checks to keep production support manageable for a small team  

_Code is private (internal product), but I’m happy to walk through architecture and design decisions in an interview._

---

### Async ETL Service (Hexagonal Architecture)

Separate service that consolidates and syncs inventory/pricing data between internal DB and multiple marketplace APIs under constant change and volume.

Highlights:

- Designed with Hexagonal (ports & adapters) architecture to keep domain logic isolated from API/DB/integration details  
- Async data ingestion using FastAPI + async SQLAlchemy + `httpx` / `asyncpg`  
- Uses background jobs (Celery / APScheduler) for scheduled syncs and heavy workloads  
- Emits structured logs and metrics, integrates into the shared Prometheus + Grafana stack  

---

## Selected Side Projects

### Telegram GPT PHP Translator Bot

**Stack:** Python · FastAPI · aiogram · OpenAI API · Docker · BeautifulSoup · Poetry  

Telegram bot that translates legacy `index.php` files with embedded HTML/PHP using OpenAI.

Highlights:

- Preserves HTML/PHP structure while translating static content  
- Streams translated content in chunks back to the user  
- Packs results into a ZIP archive for download  

Repo: https://github.com/Aullum/telegram-gpt-php-translator-bot

---

### Telegram Toolbox Bot (Utilities Bot)

**Stack:** Python · aiogram · Docker  

Modular Telegram bot with a set of developer utilities:

- Password generator  
- Base64 encoder/decoder  
- XML ⇄ JSON converter  
- Fake profile generator  
- Lorem ipsum generator  

Designed with a pluggable module system and inline UI for extending the toolset.

Repo: https://github.com/Aullum/telegram-toolbox-bot

---

## Process & Collaboration

- Work in an iterative, Agile-style process (Scrum/Kanban-ish: short cycles, backlog grooming, priorities aligned with business)  
- Regular code reviews, lightweight design discussions before bigger changes  
- Comfortable working with tickets, written specs and async communication (remote team)  
- As a tech owner, align technical decisions with business constraints and operations team needs  

---

## How I Work

- Own backend services end-to-end: requirements → design → implementation → deploy → monitoring → incident response  
- Start from explicit contracts (DB schema, APIs, background workflows) and then iterate on implementation  
- Prefer simple, explicit solutions over “clever” abstractions, especially in critical paths  
- Treat observability as a core requirement, not an afterthought  
- Keep the codebase healthy: type hints, tests, CI, pre-commit hooks, clear PR descriptions and review discipline  
- Communicate in a direct, written-first way with stakeholders (tickets, design docs, status updates)  

---

## Education & Languages

- **BSc in Cybersecurity (in progress)** – Wyższa Szkoła Bezpieczeństwa Wewnętrznego w Łodzi (WSBW), remote  
- **Languages:** English B1 (confident reading & writing, improving speaking), Ukrainian (native), Russian (native)

---

## Contacts

- Email: **roman.zidinov.dev@gmail.com**  
- LinkedIn: **https://www.linkedin.com/in/roman-zidinov/**  
- Location: **Kyiv, Ukraine**  
- Open to: **remote backend roles (full-time, part-time or contract)**  

---

## GitHub Activity

<picture>
  <img src="./metrics.svg" alt="GitHub Metrics">
</picture>
