## Jacob

I'm building infrastructure for agentic workflows: budget monitoring and guardrails for agents.

[![Website](https://img.shields.io/badge/Website-slvr.mn-46a2f1.svg?&style=flat-square&logo=Google-Chrome&logoColor=white)](https://slvr.mn/)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/jacob0x/)

### Currently

**[Fairway](https://github.com/bespy/fairway)** — [claude-code-guide](https://github.com/zebbern/claude-code-guide) tells you what to do when you ask; fairway tells you what to do when you don't know what to ask, and gives you hooks to encourage patterns and discourage antipatterns. Nine small devtools sharing one Go binary, one WAL-mode SQLite store and one MCP server, so anything one tool writes another can read — each extending a command Claude Code already ships: `/insights`, `/usage`, `claude agents` and the tool hooks. Pick the ones you want: most are read-only pull commands that need nothing installed, and two wire into your setup with explicit `install` and `uninstall` verbs. The binary alone creates no files, opens no ports, writes no config. Next: budget management for agents, built on the reconciliation primitives from Ledger AI.

**[Ledger AI](https://ledgerai.fly.dev)** — high-volume financial reporting for crypto and fiat. Double-entry over both in one ledger, operated through an AI harness (Claude Code + domain skills) so the model proposes and a deterministic engine computes. FIFO cost basis, multi-chain event parsing, per-wallet audit trails, every figure traceable to the event and rule that produced it. Backend: React Router v7 + TypeScript on GCP Cloud Run with Postgres + Prisma (~120 tables / 18 schemas, GnuCash-shaped), Inngest-orchestrated Solana ingest, Postgres RLS as authorization. Frontend: a React component library of Excel-like accounting primitives (journal expand/split/merge, reconciliation, P&L and balance-sheet views) on a headless engine for distribution. Agent harness: Python pipeline for voice / vision / OCR on local MLX models, model choice per task via evals.

### Track record

**Regulated systems** — an approval engine for a regulated-sector client, with legally binding deadlines. Scoped directly with the non-engineers who own the process.

**Solana trading infrastructure** — P&L analytics and trade-ledger reconstruction for delta-neutral day-trading and DLMM market-making, across thousands of transactions.

**Local ML pipelines** — multi-modal (voice / vision / OCR) over 100GB+ on local models, parsing statements, screenshots and recordings into structured, sourced data.

### Writing

- [What are the types of agentic harness?](https://www.slvr.mn/writing/types-of-agentic-harness) — four types, told apart by what the model is pointed at.
- [Where to deploy an LLM in 2026](https://www.slvr.mn/writing/where-to-deploy-an-llm-in-2026) — why renting a GPU is getting hard to buy, and who is left needing it.
- [What is deterministic accounting software?](https://www.slvr.mn/writing/declarative-accounting) — derive the ledger from inputs and rules instead of storing rows you edit.

More, with live demos → **[slvr.mn](https://slvr.mn/)**

### Public code

- **[solana-app](https://github.com/bespy/solana-app)** — a Solana program (Rust / Anchor) plus a Node backend: an on-chain event listener over a Helius RPC WebSocket, and a transaction parser over the Helius API.

More code available on request — get in touch via **[slvr.mn](https://slvr.mn/)** or [LinkedIn](https://www.linkedin.com/in/jacob0x/) for a walkthrough.

### Stack

Agentic AI / LLM tools · RAG · Tool calling · Prompt & context engineering · Evals · Claude Code hooks / MCP · Local LLMs (Llama, MLX) · Multi-modal ML (Whisper, Qwen3-VL, OCR) · Inference optimization · TypeScript · Python · Rust · Go · React · React Router / Remix · Node · Motion · D3 / SVG · Tailwind · PostgreSQL · SQLite / FTS5 · Prisma / Drizzle · Docker · CI/CD · Fly.io · GCP · AWS

### Education

B.E. (Electrical), UNSW — Sydney, Australia
