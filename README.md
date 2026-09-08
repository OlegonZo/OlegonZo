![Oleg Gulyaev — Python Automation & API Integrations](assets/banner.svg)

# Oleg Gulyaev

**Python automation & API integrations**

I build Python automation tools, webhook services, data-processing pipelines, and operator dashboards. My portfolio focuses on explicit business rules, testable behavior, and clear API boundaries. AI tools assist implementation; the repositories show the code, checks, and limitations.

Based in **Moscow, Russia (UTC+3)**. Open to **100% remote full-time or part-time roles** in Python automation, AI/API integrations, and data tooling. Web3 research is an additional domain, not a requirement for my next role.

[Резюме на русском](RESUME_RU.md) · [English resume](RESUME.md) · [Telegram](https://t.me/Olejo29) · [Email](mailto:gulaevoleg191@gmail.com) · [LinkedIn](https://www.linkedin.com/in/oleg-gulyaev-939186238/)

**Для работодателей:** разрабатываю Python-инструменты автоматизации, API-сервисы и интерфейсы мониторинга. Ниже — три основных примера с кодом и границами реализации. Ищу полностью удалённую работу; коммерческий эффект демонстрационным проектам не приписываю.

## What I build

- Python automation with explicit inputs, outputs, validation, and failure modes
- REST/API integrations, data normalization, SQLite storage, and Telegram-ready alerts
- FastAPI and n8n workflows with audit logs and human-review checkpoints
- operator dashboards, health monitoring, and incident runbooks
- reproducible research with tests, CI, synthetic fixtures, and documented limitations

## Start here: three engineering samples

| Project | Engineering evidence |
|---|---|
| [AI Document Review Pipeline](https://github.com/OlegonZo/ai-document-review-pipeline) | FastAPI webhook → deterministic classification → `ready/review` rules → SQLite records and decision log. Importable n8n routing example and tests. Local demo, no production LLM or Telegram integration. |
| [BotOps Control Center](https://github.com/OlegonZo/botops-control-center) | Deployed TypeScript/React operations dashboard with typed health endpoints, runbooks, CI, demo telemetry, and an optional server-side OpenAI Responses API integration. |
| [Exchange Monitoring Lab](https://github.com/OlegonZo/exchange-monitoring-lab) | Paper-only Python package for normalizing MEXC and Hyperliquid data. Typed models, `Decimal` arithmetic, synthetic fixtures, deterministic state transitions, tests, and CI. No exchange authentication or Telegram transport. |

For a quick technical review:

- **Python / workflows:** [API entry point](https://github.com/OlegonZo/ai-document-review-pipeline/blob/main/app/main.py), [decision rules](https://github.com/OlegonZo/ai-document-review-pipeline/blob/main/app/domain.py), [tests](https://github.com/OlegonZo/ai-document-review-pipeline/tree/main/tests).
- **UI / API:** [BotOps demo](https://botops-control-center-oleg.o38057979.chatgpt.site) and [server-side AI boundary](https://github.com/OlegonZo/botops-control-center/blob/main/app/api/brief/route.ts). Displayed telemetry is synthetic; the no-key path returns a deterministic demo brief.
- **Data tooling:** [Exchange Monitoring Lab walkthrough](https://github.com/OlegonZo/exchange-monitoring-lab#run-the-demo), runnable without API keys.

## Additional research and prototypes

| Project | Engineering evidence |
|---|---|
| [Solana Memecoin Analyzer](https://github.com/OlegonZo/solana-memecoin-analyzer) | Explainable scoring pipeline with validated models, dust filtering, wallet weighting, risk gates, deterministic tests, and synthetic data only. |
| [Polymarket BTC Research](https://github.com/OlegonZo/polymarket-btc-bot) | Resolver QA, shadow logging, filter attribution, and analysis of 1,485 resolved observations across 181 markets. The measured hypothesis was negative and documented as not deployable. |
| [AI Creator Scout](https://github.com/OlegonZo/ld-latte-ai-test) | Python prototype for cleaning a supplied list of public profile URLs, transparent scoring, risk flags, and mandatory human review. Not an Instagram API / Direct integration; no automatic messaging. |

## How I work with AI

I use Codex and other AI tools as engineering accelerators. The workflow remains specification-led:

1. define the task, boundaries, and acceptance criteria;
2. build a small working slice;
3. inspect logic and edge cases;
4. run deterministic tests on synthetic or paper data;
5. document limitations and what the evidence does not prove.

For me, “vibe coding” means fast AI-assisted iteration with human verification—not unreviewed generated code.

## Research integrity

A working monitoring system is not proof of a profitable strategy. My public market projects are sanitized, paper-only research artifacts. They do not place orders, use live capital, expose credentials, or claim validated profitability.

Dated cohort details live in the individual repositories rather than in this profile, so reviewers can see the methodology and the historical context together.

## Tools

`Python` · `FastAPI` · `REST APIs` · `JSON/JSON-RPC` · `SQLite` · `n8n` · `Telegram Bot API` · `TypeScript` · `React` · `OpenAI Responses API` · `Git/GitHub` · `GitHub Actions` · `pytest/unittest`

## Background

- Higher education — Saratov State Agrarian University, Engineer in Land Cadastre.
- English — technical reading and documentation with translation tools; actively improving spoken and written English.
- Interested roles — Python automation, AI integrations, data tooling, Web3 analytics, and rapid product prototyping.

## Contact

- Email: [gulaevoleg191@gmail.com](mailto:gulaevoleg191@gmail.com)
- Telegram: [@Olejo29](https://t.me/Olejo29)
- LinkedIn: [Oleg Gulyaev](https://www.linkedin.com/in/oleg-gulyaev-939186238/)

---

### Коротко по-русски

Создаю на Python и с помощью AI-инструментов автоматизации, API-интеграции, системы мониторинга, исследовательские пайплайны и интерфейсы для операторов. Делаю упор на проверяемую логику, тесты, документацию и честные границы результата. Ищу полностью удалённую работу в Python, AI-автоматизации, Web3-аналитике и быстром прототипировании.
