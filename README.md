# Roman Zidinov · Senior Backend Engineer

Backend engineer with 6+ years of experience designing, implementing and operating production backends.  
Primary focus: **Python**, **FastAPI**, **async I/O**, **PostgreSQL**, **ETL/data pipelines**, **Docker** and **CI/CD**.

- Since 2019 I’ve been working in a US e-commerce company, growing from Junior Automation Developer to owning core backend services (tech owner role).
- Built and maintained internal platforms around orders, inventory, pricing and marketplace integrations
- Comfortable owning services end-to-end: design → implementation → deploy → observability → support

---

## Core Expertise

- **Backend & APIs**
  - Python 3, FastAPI, Django, REST APIs, WebSockets
  - Async services (asyncio, httpx, async SQLAlchemy)
  - Authentication & authorization (OAuth2, JWT)

- **Data & Storage**
  - PostgreSQL, SQLAlchemy (async), Alembic
  - Redis (caching, queues)
  - Basic MongoDB (Atlas) for document-style data

- **Integrations & ETL**
  - Design and implementation of integrations with 3rd-party APIs (marketplaces, payment providers, internal tools)
  - Async ETL pipelines for importing, normalizing and syncing data between systems

- **DevOps & Operations**
  - Docker, Docker Compose
  - CI/CD with GitHub Actions
  - Pre-commit hooks, code quality and formatting
  - Deployments to VPS / cloud (AWS EC2/S3, Hetzner, Render, Heroku)

---

## Selected Projects

### Telegram GPT PHP Translator Bot
**Stack:** Python · aiogram · OpenAI API · Docker · BeautifulSoup · Poetry  

Telegram bot that translates legacy `index.php` files with embedded HTML/PHP using OpenAI.  
Key points:
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

## Professional Experience

### Tekswamp, Inc. (USA) · 2019 → Present  
_Electronics company selling via Amazon, eBay, Walmart, Newegg_

**2022 – Now · Backend Engineer / Tech Owner**

Responsibility scope:
- Backend architecture and ownership of core internal services
- Design and evolution of APIs for internal tools and integrations
- CI/CD, deployment pipelines, Dockerization of services
- Technical decision-making and alignment with business requirements

Key contributions:
- Designed and maintained a **FastAPI + PostgreSQL** backend that powers internal operations
- Built **async ETL/data pipelines** for Amazon SP-API, eBay, Walmart, ShipStation and other services
- Introduced **Docker-based microservices**, background workers (Celery) and Redis caching
- Implemented **CI/CD pipelines** and pre-commit workflows to standardize development
- Improved stability and observability of services used daily by the operations team

**2020 – 2022 · Backend Developer**

- Development of backend services and internal APIs
- Implementation of automation around orders, inventory, repricing and reporting
- Migration of legacy scripts and spreadsheet-based processes into maintainable backend services

**2019 – 2020 · Junior Automation Developer**

- Google Apps Script automations and data sync tools
- Small internal tools for operations and reporting

---

## Tech Stack Overview

**Languages**
- Python 3
- Go (CLI tools, experiments)

**Frameworks & Libraries**
- FastAPI, Django
- aiogram (Telegram bots)
- Celery, APScheduler

**Databases & Storage**
- PostgreSQL, SQLAlchemy (async), Alembic
- Redis
- MongoDB Atlas (basic usage)
- MinIO, AWS S3

**DevOps & Tooling**
- Docker, Docker Compose
- Git, GitHub Actions, pre-commit
- Linux (server environments)

**Integrations**
- Amazon SP-API
- eBay, Walmart, Newegg
- ShipStation
- Shopify
- Paddle
- Google APIs
- Telegram Bot API
- OpenAI API

**Security & Testing**
- OAuth2.0, JWT, bcrypt
- pytest (incl. async tests), coverage

---

## How I Work

- Own backend services end-to-end: from clarifying requirements and designing data models/APIs to deployment, monitoring and incident response
- Start from explicit contracts (database schema, HTTP/REST APIs, background workflows) and then iterate on implementation
- Prefer simple, explicit solutions over “clever” abstractions, especially in critical paths
- Treat observability as a core requirement: structured logs, metrics and health checks by default
- Keep the codebase healthy: type hints, tests, CI, pre-commit hooks, clear PR descriptions and review discipline
- Communicate in a direct, written-first way with stakeholders (tickets, design docs, status updates)


---

## Contacts

- Email: roman.zidinov.dev@gmail.com
- LinkedIn: www.linkedin.com/in/roman-zidinov


- Open to **remote backend roles (full-time, part-time or contract)**


---


## GitHub Activity

<picture>
  <img src="./metrics.svg" alt="GitHub Metrics">
</picture>