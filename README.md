# Jonathan Forbes

Banking professional, finance student, and product builder working across financial technology, defensive cybersecurity, applied cryptography, cloud infrastructure, and controlled AI-assisted systems.

## Driven Agentics

[Driven Agentics](https://drivenagentics.com) is being planned as the parent company for a portfolio of specialized research and software products. Its purpose is to turn complex analytical workflows into controlled, explainable, auditable, and deployable systems. Legal formation details remain pending until formally completed.

| Project | Purpose | Current phase |
|---|---|---|
| [PinkCharts](https://pinkcharts.com) | Market analytics and trading-model evaluation | Active private development and beta testing |
| [KoalaWire](https://koalawire.com) | Authorized defensive security assessment | Phase 3 desktop-alpha reliability and recovery hardening |
| [SHAsweeper](https://shasweeper.com) | Bitcoin cryptography, blockchain, compute, and mining research | Phase 0 local and regtest research foundation |

The product repositories are private. Public websites, distribution channels, and production availability are developed and reviewed separately from the underlying research and application code.

## Current Projects

### PinkCharts

PinkCharts is a private-beta market analytics and trading-model evaluation platform focused on repeatable backtests, paper-trading analysis, risk-adjusted performance, consistency, and trading behavior rather than headline returns alone.

**Current architecture and capabilities:**

- Python, FastAPI, Uvicorn, REST APIs, and WebSockets
- Next.js and TypeScript dashboard
- SQLAlchemy and Alembic persistence with PostgreSQL and SQLite
- Market, macroeconomic, and sector-data workflows
- Backtest and paper-trading session persistence
- Model scorecards, attribution, audit records, and durable action queues
- Risk limits, stale-data protections, emergency halts, and controlled broker-adapter contracts
- DigitalOcean backend infrastructure with Nginx and systemd
- Vercel frontend deployments and GitHub-based source control

Live brokerage order submission remains disabled by default. Financial calculations, provider integrations, persistence changes, and risk controls require explicit validation before deployment.

### KoalaWire

KoalaWire is a local-first defensive security platform for authorized assessment of source code, files, packages, websites, configurations, dependencies, and supported mobile artifacts.

**Implemented alpha foundation:**

- Authenticated loopback-only FastAPI sidecar with versioned local APIs
- SQLAlchemy and Alembic-managed SQLite persistence
- Durable queued, running, completed, failed, cancelled, and interrupted scan states
- Verified database backups, integrity checks, non-destructive recovery, and bounded diagnostic export
- Hash-chained audit events and evidence provenance
- Fixed-argument, no-shell scanner-worker contracts with bounded execution
- Separate repositories for scanners, rules, console, synthetic labs, and documentation
- Native desktop packaging and installer validation work coordinated through the console repository

KoalaWire is limited to systems, applications, files, and environments I own or have explicit permission to assess. It is not intended for unauthorized access, persistence, credential collection, or evasion.

### SHAsweeper

SHAsweeper is a local and regtest-first research platform for studying SHA-256, Bitcoin protocol behavior, blockchain data, compute performance, and deterministic mining-related contracts.

**Implemented Phase 0 foundation:**

- Rust SHA-256 reference laboratory, Bitcoin hashing primitives, test vectors, and provenance records
- Read-only, loopback-restricted Bitcoin Core RPC and ZMQ integration
- PostgreSQL-backed chain metadata indexing, checkpoints, and reorganization tracking
- Authorized local-compute inventory and reproducible benchmarking
- Regtest block-template and work-ledger contracts without production mining execution
- Local read-only Next.js and TypeScript research console
- Source-grounded architecture, threat-model, experiment, and review documentation

Phase 0 does not include wallet custody, payout handling, public Bitcoin Core RPC, cloud provisioning, mainnet mining, or block submission. Compute activity requires ownership or written authorization.

## My Role

I define product requirements, architecture, system behavior, risk controls, acceptance criteria, repository boundaries, research constraints, deployment strategy, and validation expectations. OpenAI Codex, Claude, v0, and other development tools assist with implementation, debugging, refactoring, testing, and documentation. I review and validate changes before deployment or experimentation.

## Working Stack

- **Languages:** Python, Rust, TypeScript, SQL, HTML, and CSS
- **Application:** FastAPI, Next.js, Tauri, Pydantic, SQLAlchemy, and Alembic
- **Data:** PostgreSQL, SQLite, REST APIs, WebSockets, and structured event contracts
- **Infrastructure:** DigitalOcean, Vercel, Cloudflare, Nginx, systemd, and PyInstaller
- **Engineering:** Git, GitHub, GitHub Actions, versioned schemas, automated testing, audit logging, and recovery controls

## Current Priorities

- Improve PinkCharts model evaluation, paper research, interface quality, and controlled AI-assisted workflows
- Advance KoalaWire desktop-alpha reliability, native packaging, scanner integration, and recovery behavior
- Expand SHAsweeper's source-grounded cryptography, chain, compute, and regtest research
- Strengthen cloud account security, origin protection, deployment boundaries, and infrastructure documentation

## Background

- Banking operations experience involving transaction controls, KYC/AML, fraud prevention, and exception escalation
- FINRA Securities Industry Essentials exam passed
- A.A. from Daytona State College and continuing finance studies at Baruch College
- Long-standing technical interest through game modification, Android rooting, custom ROM installation, operating-system flashing, and system recovery

## Development Principles

- AI-assisted work requires human review, testing, and documented acceptance criteria
- Secrets, credentials, private keys, and production tokens remain outside source control
- High-impact actions require deterministic authorization, auditability, and rollback controls
- Security testing must remain within explicit legal and technical scope
- Cryptographic and blockchain research must use lawful targets, controlled environments, and authorized compute
- Financial systems should be explainable, auditable, and designed around risk controls
- Research claims must be supported by reproducible experiments and source provenance
- Documentation must distinguish implemented capabilities from planned features

## Contact

- Email: forbes.exe@gmail.com
- Location: New York, NY
