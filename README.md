# Roman Zidinov · Python Backend Engineer

Kyiv, Ukraine (UTC+2/+3) · **roman.zidinov.dev@gmail.com**

About 8 years in commercial software development, remote since 2019. I design and build backend platforms end to
end — architecture and data model, integrations, background processing — with quality and security gates built in,
and explain the trade-offs to non-technical stakeholders in plain language.

**Domains:** Fintech (payments) · E-commerce (marketplaces, warehouse)

_Most of my work lives in private repositories; happy to walk through code and design on request._

---

## What I Do Well

- **Payments.** 9 payment gateways integrated end to end; Apple Pay and Google Pay in three models (encrypted
  pass-through, decrypted DSRP, hosted); refunds and cancellations that never treat a possibly executed operation as
  failed; PAN-safe card handling.
- **Marketplaces and warehouse.** Multi-marketplace inventory sync, picklists with idempotent stock deduction, a
  per-unit ledger reconciled daily from stock and sales (341,000+ units).
- **Architecture and data integrity.** Ports and adapters with a DI container and Unit of Work, multi-tenant
  isolation, transactional outbox, error mapping kept as data, zero-downtime schema changes, incremental
  watermark-driven loads.
- **Quality and security gates.** A type checker taken from 1,300+ diagnostics to a blocking CI gate with `Any`
  banned, Semgrep team rules, supply-chain scanning, hardened GitHub Actions and containers.
- **AI coding agents, under control.** Custom agents and project rules, scanners on every edit, every change checked
  against tests and project rules and reviewed by me before it lands.

---

## Tech Stack

- **Backend:** Python · FastAPI · Pydantic v2 · async SQLAlchemy 2.x · httpx · OAuth2 / JWT · Starlette Admin
- **Jobs:** Celery + Celery Beat · ARQ · APScheduler
- **Data:** PostgreSQL · Alembic · Redis / Valkey · MinIO
- **Payments:** 3-D Secure / 2D · BLIK · iDEAL · Bancontact · paysafecard · EPS · SEPA · HMAC webhooks
- **Integrations:** Amazon SP-API · eBay · Walmart · Newegg · Shopify · ShipStation · Google Sheets / Drive · Customer.io · OpenAI API · Telegram Bot API
- **Infra:** Docker · Nginx · Cloudflare · GitHub Actions · Argo CD (GitOps; cluster run by DevOps) · Hetzner · bastion / OpenVPN
- **AWS:** EC2 · S3 · IAM · KMS · Secrets Manager · SNS · CloudWatch Logs
- **Observability:** Prometheus · Grafana · Sentry · structlog
- **Testing & quality:** pytest · respx · ty · mypy · Ruff · SonarQube · pre-commit
- **Security tooling:** gitleaks · Semgrep · OSV-Scanner · zizmor · actionlint · Hadolint · Trivy
- **Also:** Django · Angular · Marimo · AppSheet · Google Apps Script · JavaScript

---

## Education & Languages

- **BSc in Cybersecurity (in progress)** – Wyższa Szkoła Bezpieczeństwa Wewnętrznego w Łodzi (WSBW), remote
- **Languages:** English B1 (daily written work: documentation, specifications, API docs), Ukrainian (native), Russian (native)
