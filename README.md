# Hi, I'm Cameron 👋

I build autonomous AI systems and ship them to production.

Most recently: a modular Python framework for orchestrating prompt-driven
AI agents with persistent multi-layer memory, plus an MCP-based adapter
platform for wrapping any REST/GraphQL API as tools an LLM agent can call.

## What I'm working on

- **AI agent platforms** — multi-phase orchestration, phase trees, persistent memory,
  resume from crash, drift detection over time.
- **MCP servers** — adapter pattern over the Model Context Protocol. Wrap external APIs
  with auth, rate limiting, schema validation, async execution.
- **Self-hosted automation** — N8N + Ollama + Docker + Tailscale for security and
  business automation that doesn't leak data to SaaS.
- **Production Django** — payroll (SARS-compliant) and POS systems in production
  serving real customers.

## Selected repositories

- [ai-systems-portfolio](https://github.com/Koslovski79/ai-systems-portfolio) —
  Proof-of-existence writeups for 5 systems I've built: AI agent platform,
  MCP security platform, N8N workflows, payroll, POS.
- [prompt-orchestrator](https://github.com/Koslovski79/prompt-orchestrator) —
  Modular Python framework for prompt-driven multi-agent orchestration with
  persistent multi-layer memory. Domain-agnostic by design.
- [platform-adapter-mcp](https://github.com/Koslovski79/platform-adapter-mcp) —
  Reference implementation of the adapter pattern over MCP. Wrap any REST/GraphQL
  API as tools an LLM agent can call.
- [n8n-security-automation](https://github.com/Koslovski79/n8n-security-automation) —
  Self-hosted N8N workflows with local LLM inference (Ollama).

## How I work

- Take a messy real-world problem → turn it into a working system.
- Build the operational layer (memory, resume, drift detection) before the UI.
- Local-first where possible. Open-weighted models + self-hosted infra.
- Money math uses Decimal. Money math always uses Decimal.
- Audit logs are built on day one, not bolted on after the incident.

## Stack

Python · Django · PostgreSQL · MCP · FastAPI · SQLite · FAISS · Ollama · Docker ·
Tailscale · N8N · Celery · htmx · Tailwind

## Contact

GitHub: [@Koslovski79](https://github.com/Koslovski79)