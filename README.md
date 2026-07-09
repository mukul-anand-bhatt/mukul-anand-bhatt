<div align="center">

# MUKUL ANAND BHATT

**`FORWARD DEPLOYED ENGINEER`** · **`BENGALURU, IN`** · 🟢 **`OPEN TO WORK`**

I build production backend, automations, and integrations,<br/>
then get on the call to make sure it **actually ships**.

*I build backend. I deploy with customers. I automate workflows. I optimize systems.*

<br/>

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-mukul.live-c2f23f?style=for-the-badge&labelColor=0a0b0d)](https://mukul.live)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-mukulanandbhatt-5e74ff?style=for-the-badge&labelColor=0a0b0d&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mukulanandbhatt/)
[![X](https://img.shields.io/badge/X-@mukulanandbhatt-ECEDEE?style=for-the-badge&labelColor=0a0b0d&logo=x&logoColor=white)](https://x.com/mukulanandbhatt)
[![Email](https://img.shields.io/badge/EMAIL-anandbhatt.dev@gmail.com-ff7559?style=for-the-badge&labelColor=0a0b0d&logo=gmail&logoColor=white)](mailto:anandbhatt.dev@gmail.com)
[![Résumé](https://img.shields.io/badge/RÉSUMÉ-download_↓-c2f23f?style=for-the-badge&labelColor=0a0b0d)](https://drive.google.com/uc?export=download&id=1BLQa2Ni98CVrWoZUgJaGxovU-yr0QTNM)

</div>

<br/>

<div align="center">

| **30,000+** | **200+** | **$1000s** |
| :---: | :---: | :---: |
| USERS REACHED | COMPANIES REACHED | MRR SAVED FOR CLIENTS |

</div>

<br/>

## ■ 01 / WHAT I BRING

**BUILD — Production from scratch.**
Microservices, data pipelines, and third-party integrations that hold up under real load.
`Node` `TypeScript` `Python` `Postgres` `Mongo` `Redis`

**DEPLOY WITH CUSTOMERS — On the call, not behind it.**
Client calls, live troubleshooting, custom solutions. Shipped while the customer watches it work.
`client calls` `live debugging` `custom fixes`

**OPTIMIZE — Cheaper, harder, faster.**
Codebase optimizations that cut cost, raise reliability, and scale without drama.
`cost ↓` `reliability ↑` `scale`

## ■ 02 / SELECTED WORK — Built. Deployed. Owned.

| | | |
| :-- | :-- | :-- |
| `FLAGSHIP` | **[Data Connector: the core product](https://mukul.live/work/superjoin)** <br/> SUPERJOIN · FDE | End-to-end owner of the engine syncing 34+ third-party sources into Sheets & Excel as one source of truth. Now automating it to run on autopilot. 30k+ users, 200+ companies. |
| `AI-NATIVE` | **[Claude Pickup](https://mukul.live/work/claude-pickup)** <br/> AGENTIC DEV WORKFLOW | Non-technical testers file tickets → Claude drafts a PRD → I review → Claude builds → I test → merge. ~40% of issues resolved end-to-end. |
| `GOV SCALE` | **[Food-Safety Inspection Backend](https://mukul.live/work/irctc)** <br/> IRCTC · CONTRACT | Backend for India's national food-safety inspection platform. 1,000+ daily inspections with geo-location validation, at government scale. |
| `ENTERPRISE` | **[Kisna Jewellers Integration](https://mukul.live/work/kisna)** <br/> KISNA · BYTIVE | Microservice syncing MongoDB → MSSQL to feed Salesforce ingestion for an enterprise client, plus GoKwik + Reward Rally payment/rewards integration. |

## ■ 03 / MY CLAUDE SETUP — AI-native, safely.

From Slack, I pull the full picture on any user or issue: logs, data, code, usage, billing, recordings.
Every connection is **read-only**: it sees everything, changes nothing. Then **Hermes** turns the fix into a PR I just review.

```shell
> /diagnose acme-corp "Sheets sync stuck at 91%"
  ⋯ pulling read-only context: AWS logs · Mongo · PostHog · Intercom…
  session found: connector run #48122, source: HubSpot, 14,208 rows
  Grep("SYNC_STALLED" services/connector)        → 3 matches in retryQueue.ts, scheduler.ts
  Read(services/connector/retryQueue.ts)         → 212 lines, backoff logic located
  ⋯ root cause: retry backoff ceiling too low for >10k-row sources, queue starves at 91%
  diagnosis complete. zero writes made. handing fix to Hermes →
  Edit(retryQueue.ts: scale ceiling by row count) → +14 −3
  Bash(npm test -- connector)                     → 42 passed, 0 failed
✓ Hermes opened PR #214. I review & merge. Sync resumed: 100%.
```

## ■ 04 / EXPERIENCE — Where I've shipped.

| PERIOD | ROLE | WHAT |
| :-- | :-- | :-- |
| FEB 2026 – PRESENT | **Forward Deployed Engineer** · Superjoin | End-to-end owner of the Data Connector: 34+ sources → Sheets & Excel for 30k+ users across 200+ companies. Leading the automation push; on client calls shipping fixes live. |
| JUN 2025 – JAN 2026 | **Backend Developer** · bytive.in | Enterprise data integration for Kisna Jewellers: MongoDB → MSSQL sync unblocking Salesforce, plus GoKwik & Reward Rally integrations. |
| JUN 2025 – SEP 2025 | **Backend Developer · Contract** · IRCTC | Backend for India's national food-safety inspection platform: 1,000+ inspections/day with geo-location validation. |
| JUN 2024 – JUL 2024 | **Data Engineer Intern** · HERE Technologies | Pipelines processing geospatial data at global map scale. |

## ■ 05 / STACK — The toolbox.

**LANGUAGES** · `Python` `TypeScript` `JavaScript` `SQL`
**BACKEND** · `Node.js` `Express` `Prisma`
**DATA / STORAGE** · `PostgreSQL` `MongoDB` `Redis`
**INTEGRATIONS** · `data pipelines` `API connectors` `Sheets / Excel API`
**AI & AUTOMATION** · `Claude` `OpenAI APIs` `LLM integration` `agentic workflows` `n8n` `prompt engineering`
**CLOUD / DEVOPS** · `AWS` `Docker` `CI/CD`
**ARCHITECTURE** · `REST APIs` `microservices` `RBAC auth` `system optimization`

<br/>

<div align="center">

## LET'S BUILD AND **SHIP** IT.

[**anandbhatt.dev@gmail.com →**](mailto:anandbhatt.dev@gmail.com)

`B.Tech CS (AIML) · UPES · 2025` · `"Most Innovative Idea" · Hackathon 3.0` · `Azure Certified`

<sub>© 2026 MUKUL ANAND BHATT · BENGALURU, IN — BUILT WITH CLAUDE · SHIPPED ON THE CALL</sub>

</div>
