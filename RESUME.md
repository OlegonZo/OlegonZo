# Oleg Gulyaev

**Python Automation & API Integrations · AI-assisted Development**

Moscow, Russia · UTC+3 · Russian citizenship · 100% remote  
Full-time or part-time  
Email: [gulaevoleg191@gmail.com](mailto:gulaevoleg191@gmail.com) · Telegram: [@Olejo29](https://t.me/Olejo29)  
[GitHub](https://github.com/OlegonZo) · [LinkedIn](https://www.linkedin.com/in/oleg-gulyaev-939186238/) · [Резюме на русском](RESUME_RU.md)

## Professional summary

I build tested, documented tools that turn repetitive work and research questions into reproducible workflows. My portfolio covers Python automation, REST/API integrations, FastAPI services, SQLite data pipelines, n8n workflows, operational dashboards, Telegram-ready alerts, and AI-assisted review systems.

I am looking for work on workflow automation, API services, and internal tools. My portfolio demonstrates business-rule routing, data normalization, decision logging, and operational interfaces. Crypto/Web3 is an additional research domain. AI tools assist implementation; I define acceptance criteria, inspect logic, run checks, and document limitations. The projects below are portfolio and research work, not claims of commercial employment or measured client ROI.

## Selected project experience

### [AI Document Review Pipeline](https://github.com/OlegonZo/ai-document-review-pipeline)

- Built a FastAPI webhook that accepts synthetic document payloads and separates classification from business rules.
- Routes low-confidence or invalid cases into a SQLite review queue instead of making an unchecked automated decision.
- Records each decision and its reasons in SQLite in the same transaction as the document.
- Includes an importable n8n webhook → API → status-check example, OpenAPI preview, and unit tests. Notification delivery is not implemented.
- Demo only; no claim of bank, 1C, Telegram, or production LLM integration.

### [Exchange Monitoring Lab](https://github.com/OlegonZo/exchange-monitoring-lab)

- Built typed Python boundaries around synthetic MEXC and Hyperliquid payloads.
- Normalized exchange-specific instruments into comparison-only market snapshots.
- Implemented deterministic paper-position exit states, transparent regime checks, and Telegram-ready formatting.
- Added synthetic fixtures, unit tests, and GitHub Actions CI across Python 3.11–3.13.
- The public package cannot authenticate or place orders.

### [BotOps Control Center](https://github.com/OlegonZo/botops-control-center)

- Built and deployed a responsive operations dashboard for automated research systems.
- Separated process health, evidence quality, and strategy performance.
- Added typed server endpoints, incident context, recovery runbooks, request limiting, and CI.
- Integrated an optional server-side OpenAI Responses API path with deterministic no-key fallback.
- All displayed telemetry is explicitly marked as demo data.

### [Solana Memecoin Analyzer](https://github.com/OlegonZo/solana-memecoin-analyzer)

- Designed an explainable scoring pipeline using validated data models and synthetic snapshots.
- Added dust filtering, quality-weighted wallet aggregation, liquidity/volume gates, holder-concentration checks, and authority checks.
- Produces transparent `WATCH` or `REJECT` explanations and never places orders.
- Includes a dependency-free CLI, deterministic tests, and CI.

### [Polymarket BTC Research](https://github.com/OlegonZo/polymarket-btc-bot)

- Built shadow logging, outcome resolution, filter attribution, and exit-simulation tooling.
- Found and corrected a resolver defect before recomputing the affected dataset.
- Evaluated 1,485 resolved observations across 181 unique markets.
- The measured entry stream was negative after market-implied price; documented the version as not deployable.
- Reported clustering and pseudo-replication limitations instead of presenting row count as independent live trades.

### [AI Creator Scout](https://github.com/OlegonZo/ld-latte-ai-test)

- Built a Python tool that cleans a supplied creator list, removes irrelevant records, and ranks candidates with transparent criteria.
- Produces evidence, unknowns, risk flags, and a mandatory human-review status.
- Works from a supplied profile list, not Instagram Direct or the Instagram API; it does not automatically contact creators.
- Includes unit tests and a documented automation design.

## Technical skills

**Python and data:** Python 3, FastAPI, requests, REST APIs, JSON/JSON-RPC, dataclasses, Decimal, SQLite, JSON/JSONL  
**Automation:** n8n workflow design, Telegram Bot API formatting, webhooks, review queues, audit logs, scheduled monitoring  
**Frontend and operations:** TypeScript, React, operational dashboards, health metadata, runbooks  
**Web3 data:** Solana RPC, Helius, DexScreener, Chainlink, Polygon, Base, MegaETH (testnet), Polymarket CLOB, Binance, MEXC, Hyperliquid  
**Quality:** unittest/pytest, synthetic fixtures, GitHub Actions CI, reproducible research, explicit safety boundaries  
**AI-assisted workflow:** Codex and other AI tools, OpenAI Responses API, prompt and output review, human-in-the-loop design

## Working approach

- Start with a bounded problem and explicit acceptance criteria.
- Prefer a small runnable slice over an unverified large system.
- Keep credentials and private data outside public repositories.
- Use synthetic, paper, or shadow data when live execution is unnecessary.
- Treat negative and inconclusive results as valid evidence.
- Separate engineering reliability from claims about business or market performance.

## Education

**Saratov State Agrarian University**  
Higher education — Engineer in Land Cadastre

## Languages

- Russian — native.
- English — technical reading and documentation with translation tools; spoken and written English in active development.

## Target roles

Python Automation Developer · AI Automation / Integration Specialist · Junior Python Developer · Web3 Data / Research Analyst · Vibe Coding / Rapid Prototyping

## Portfolio

- [Exchange Monitoring Lab](https://github.com/OlegonZo/exchange-monitoring-lab)
- [AI Document Review Pipeline](https://github.com/OlegonZo/ai-document-review-pipeline)
- [BotOps Control Center](https://github.com/OlegonZo/botops-control-center)
- [Solana Memecoin Analyzer](https://github.com/OlegonZo/solana-memecoin-analyzer)
- [Polymarket BTC Research](https://github.com/OlegonZo/polymarket-btc-bot)
- [AI Creator Scout](https://github.com/OlegonZo/ld-latte-ai-test)

Public repositories are sanitized. Credentials, private wallet lists, raw logs, and live-order access are intentionally excluded.
