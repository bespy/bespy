## Jacob

I build infrastructure for agentic workflows — accounting components for React, and guardrails for coding agents.

[![Website](https://img.shields.io/badge/Website-slvr.mn-46a2f1.svg?&style=flat-square&logo=Google-Chrome&logoColor=white)](https://slvr.mn/)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/jacob-silverman-0a1022242/)
[![Mail](https://img.shields.io/badge/Email-jacob@slvr.mn-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:jacob@slvr.mn)

### Currently

**[Fairway](https://github.com/bespy/fairway)** — [claude-code-guide](https://github.com/zebbern/claude-code-guide) tells you what to do when you ask; fairway tells you what to do when you don't know what to ask, and gives you hooks to encourage patterns and discourage antipatterns. Nine small devtools sharing one Go binary, one WAL-mode SQLite store and one MCP server, so anything one tool writes another can read — each extending a command Claude Code already ships: `/insights`, `/usage`, `claude agents` and the tool hooks. Pick the ones you want: most are read-only pull commands that need nothing installed, and two wire into your setup with explicit `install` and `uninstall` verbs. The binary alone creates no files, opens no ports, writes no config.

**[Ledger AI](https://ledgerai.fly.dev)** — high-volume financial reporting for crypto and fiat. Double-entry over both in one ledger, operated through an AI harness (Claude Code + domain skills) so the model proposes and a deterministic engine computes. FIFO cost basis, multi-chain event parsing, per-wallet audit trails, every figure traceable to the event and rule that produced it.

**[Ledger UI](https://ledgerui.fly.dev/)** — a React component library of animated, Excel-like accounting primitives: journal entries expanding to their debit and credit legs, split and merge, reconciliation matching, P&L and balance-sheet views, and entry forms with spreadsheet input semantics. Built to play nice with popular frameworks such as shadcn/ui, Tailwind, Motion.

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

- **[fairway](https://github.com/bespy/fairway)** — install, the tool catalogue, the ruleset, and how the hooks are derived from your own session history.
- **[solana-app](https://github.com/bespy/solana-app)** — a Solana program (Rust / Anchor) plus a Node backend: an on-chain event listener over a Helius RPC WebSocket, and a transaction parser over the Helius API.

Most current work is private — email **jacob@slvr.mn** for a code walkthrough.

### Stack

TypeScript · React · React Router / Remix · Node · Go · Python · Rust · Motion · PostgreSQL · SQLite / FTS5 · Prisma / Drizzle · Claude Code hooks / MCP · Local LLMs (Llama, MLX) · Whisper / Qwen3-VL · D3 / SVG · Tailwind · Docker · CI/CD · Fly.io · GCP · AWS

### Education

B.E. (Electrical), UNSW — Sydney, Australia
