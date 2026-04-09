# Roman Zidinov · Python Backend Engineer

7+ years of experience building, evolving, and operating production backend systems.

**Core focus:** Python · FastAPI · PostgreSQL · async integrations · ETL/data pipelines · Docker · CI/CD · observability

---

## At a glance

- 7+ years in commercial development, remote since 2019
- Built and evolved backend platforms for warehouse operations, inventory, pricing, analytics, and marketplace synchronization
- Grew from automation and legacy spreadsheet-driven operations into ownership of a unified FastAPI + PostgreSQL backend platform
- Worked with large-scale operational data, including **hundreds of thousands of product records** and **millions of marketplace listings**
- Built synchronization flows across eBay, Amazon, Walmart, Newegg, Shopify, and ShipStation
- Use a consistent engineering baseline across backend services: **pre-commit + CI/CD + pytest + mypy + ruff**
- Recent client work also includes **ML tooling**, **API-driven platform migration**, and **marketplace product support**

---

## Tech Stack

### Backend & Async

- Python 3.12 · FastAPI
- ASGI stack: uvicorn, gunicorn
- Async I/O: `asyncio`, `httpx`, async SQLAlchemy 2.x
- Background & scheduled jobs: Celery, APScheduler
- Auth: OAuth2, JWT
- API design for internal systems, integrations, and operational workflows

### Data & Storage

- PostgreSQL (primary) · SQL · SQLAlchemy · Alembic
- Redis
- Object storage: AWS S3, MinIO
- SQLite for light workloads where appropriate

### Integrations & ETL

- Marketplaces & commerce: Amazon SP-API and Feeds, eBay (SOAP/REST), Walmart, Newegg, Shopify, ShipStation
- Google APIs: Sheets, Drive
- Telegram Bot API, `aiogram`
- OpenAI API
- Design and implementation of async ETL pipelines between internal systems and 3rd-party APIs

### Infra, Deployments & Observability

- Docker · Docker Compose
- Nginx as reverse proxy
- CI/CD: GitHub Actions, pre-commit, ruff, mypy
- Environments: Linux servers, AWS EC2, Render, Heroku
- Monitoring & metrics: Prometheus, postgres-exporter, Grafana

### Testing & Quality

- pytest · pytest-asyncio
- mypy, type-hints-first approach
- ruff, pre-commit hooks
- CI quality checks and maintainable development workflows

### Additional Exposure

- Starlette Admin
- Marimo
- Google Apps Script
- Django
- Next.js
- JavaScript / Node.js for support-level tooling and legacy automation

---

## Architecture & Practices

- Maintainable backend design with explicit contracts, testable business logic, and clear service boundaries
- OOP and SOLID principles in domain-oriented backend services and internal platform workflows
- Layered / clean-onion-like service design where separation between use cases, domain logic, and infrastructure concerns matters
- Ports-and-adapters boundaries, Unit of Work, and dependency injection in internal APIs and synchronization services
- Async-first mindset for I/O-heavy integrations, background workers, and scheduled jobs
- Observability as part of delivery: metrics, health checks, logging, and production diagnostics
- Production-oriented backend development with containerized deployment and delivery discipline

---

## Featured Work

### Internal E-commerce Backend Platform (Tekswamp, Inc.) — core role

Long-term backend role in a US e-commerce product company.

I joined a legacy operations environment heavily built around Google Sheets, formulas, manual workflows, and ad-hoc scripts. Over time, I grew from automation and support work into ownership of a unified FastAPI + PostgreSQL backend platform for warehouse operations, inventory, pricing, analytics, and marketplace synchronization.

Key responsibilities & impact:

- Replaced critical spreadsheet- and script-driven workflows with maintainable backend services and a normalized data model
- Designed and evolved a unified backend platform for warehouse operations, inventory, pricing, and sales/profitability analytics
- Built and operated synchronization flows across eBay, Amazon, Walmart, Newegg, Shopify, and ShipStation
- Supported large-scale operational data, including **hundreds of thousands of product records** and **millions of marketplace listings**
- Implemented background workflows for synchronization, imports/exports, picklist generation, and automated order write-off processes
- Developed **300+ API endpoints** for internal operational and marketplace workflows
- Standardized engineering quality practices with **pre-commit, CI/CD, pytest, mypy, and ruff**

_Code is private (internal product), but I’m happy to walk through architecture and design decisions in an interview._

---

### Jellyfish.tech — Backend Engineer

Worked across multiple client engagements in different domains, including ML tooling, platform migration, and marketplace product support.

Highlights:

- Developed backend functionality for a FastAPI-based platform used for model uploads, analysis, testing workflows, analytics, and cost/performance forecasting
- Improved internal admin and operational tooling with Starlette Admin and Marimo in a distributed multi-team setup
- Supported API-driven migration of users and content from Circle to Hivebrite using APIs, Google Sheets, and Apps Script
- Delivered backend fixes, product improvements, and stabilization work in an existing marketplace/forum product using Django, Celery, Celery Beat, and Redis
- Participated in discovery work: requirements analysis, phased plans, roadmaps, and scoped delivery planning
- Applied the same engineering baseline across Python backend work: **pre-commit, CI checks, pytest, mypy, and ruff**

---

## Selected Side / Freelance Projects

### Internal Warehouse Operations Backend

Internal inventory API for stock operations, shelf management, and authenticated access flows.

Highlights:

- Structured with layered architecture across API, application use cases, domain model, and infrastructure adapters
- Applied ports-and-adapters boundaries so business rules stayed independent from FastAPI and SQLAlchemy details
- Implemented explicit transaction handling with Unit of Work and dependency injection through the composition root
- Enforced domain invariants for stock, reservation, shelf, and details updates
- Supported the service with automated tests, CI checks, and containerized deployment

**Technologies:** Python · FastAPI · PostgreSQL · SQLAlchemy · Docker · Nginx · Alembic · Pydantic · JWT

---

### Marketplace Synchronization Service

Dedicated backend service for synchronizing warehouse data with eBay, Amazon, Walmart, Newegg, Shopify, and ShipStation.

Highlights:

- Built with layered architecture and ports/adapters boundaries
- Designed so new connectors could be added and existing integrations changed with minimal impact on core synchronization workflows
- Isolated synchronization orchestration from platform-specific API logic and persistence concerns
- Consolidated inventory, listing, and operational synchronization flows into a dedicated backend service

**Technologies:** Python · FastAPI · Docker · Nginx · JWT

---

### Landing Page Localization Tool

Telegram-based automation tool for translating PHP landing pages into target languages.

Highlights:

- Extracts readable content from mixed PHP/HTML templates while preserving page structure
- Splits large payloads into chunks for API-safe translation workflows
- Stitches translated content back into the source layout
- Automates end-to-end delivery through the OpenAI API and Telegram workflow

**Technologies:** Python · aiogram · OpenAI API · tiktoken · BeautifulSoup · lxml · aiofiles · Pydantic

---

## Process & Collaboration

- Work well in written-first remote environments with tickets, specs, async communication, and iterative delivery
- Regular code reviews and lightweight design discussions before bigger changes
- Comfortable aligning technical decisions with business constraints and operational needs
- Participate not only in implementation, but also in discovery, scoping, and phased delivery planning when needed

---

## How I Work

- Own backend delivery end-to-end: requirements → implementation → deployment → observability → support
- Prefer simple, explicit, maintainable solutions over clever abstractions in critical paths
- Start from explicit contracts between DB schemas, APIs, and background workflows
- Treat observability and delivery safety as part of engineering, not post-factum additions
- Keep codebases healthy through type hints, tests, CI, and review discipline
- Interested in backend engineering that moves toward stronger architecture and cleaner system design without abstraction theater

---

## Education & Languages

- **BSc in Cybersecurity (in progress)** – Wyższa Szkoła Bezpieczeństwa Wewnętrznego w Łodzi (WSBW), remote
- **Languages:** English B1 (comfortable with written communication and documentation; spoken level improving), Ukrainian (native), Russian (native)

---

## Contacts

- Email: **roman.zidinov.dev@gmail.com**
- LinkedIn: **https://www.linkedin.com/in/roman-zidinov/**
- GitHub: **https://github.com/Aullum**
- Location: **Kyiv, Ukraine**
- Open to: **remote backend roles (full-time, part-time or contract)**

---

## GitHub Activity

<picture>
  <img src="./metrics.svg" alt="GitHub Metrics">
</picture>
