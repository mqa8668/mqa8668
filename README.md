## Hi, I'm Loc Luong

**I build infrastructure that stays up, and the software that runs on it.**

Senior DevOps and Elixir backend engineer, based in Vietnam and working remotely. I've spent my career on the unglamorous systems that companies only notice when they break: clusters, identity, deployments, observability. Lately I also build AI-assisted workflows that let a small team ship like a big one.

Open to **remote** roles in DevOps, Platform/SRE, or Elixir backend engineering.

### What I bring

- **Infrastructure built to survive failure.** High-availability platforms from bare metal to Kubernetes, with failover and recovery planned up front rather than patched in later.
- **Security people trust.** Passwordless login, identity and zero-trust access for security-critical products.
- **Elixir from the ground up.** OTP, Phoenix, LiveView and Oban are my home turf: supervised services, real-time apps and job pipelines taken from idea to production. Python and TypeScript where they fit better.
- **Docs that ship with the system.** Architecture and deployment docs clear enough that a customer's infra team can run the system on their own.
- **AI as a force multiplier.** Spec-driven, agent-assisted development with guardrails, so the speed doesn't cost quality.

### Flagship

**[edge-to-trace](https://github.com/mqa8668/edge-to-trace)** - Observability lab you can break on purpose: inject a fault, watch the SLO burn-rate page fire, then click an exemplar to the exact trace. OpenTelemetry, Beyla eBPF, Prometheus, Tempo, Loki, Grafana and Alertmanager to Telegram, all as code.

### Backend & platforms

- [feedhound](https://github.com/mqa8668/feedhound) - Keyword watcher for public feeds with Telegram alerts: SSRF-safe fetcher, reconciler with a dead-letter queue, Prometheus metrics. Bun, TypeScript, Postgres.
- [edge-magazine](https://github.com/mqa8668/edge-magazine) - Publishing platform on Cloudflare Workers (Hono, D1, R2, KV, Queues) with a human-reviewed LLM drafting pipeline.

### Developer tooling

- [claude-workbench](https://github.com/mqa8668/claude-workbench) - Brakes, gauges and a flight recorder for Claude Code: config-driven gates, a context guard, checkpoints and a subagent cost ledger.
- [claude-skills](https://github.com/mqa8668/claude-skills) - Claude Code skills for consultant-grade docs, Figma architecture diagrams, and Vietnamese/bilingual engineering writing.
- [live-caption-translate](https://github.com/mqa8668/live-caption-translate) - Chrome extension for live meeting captions with Vietnamese translation.

### Selected private work

Client work stays private. The short version:

- **Elixir platform for e-commerce sellers.** Phoenix API with Oban job pipelines, marketplace integration, passkey sign-in and an LLM-assisted workflow with a person in the loop.
- **Customer-support RAG assistant.** Parallel retrieval, one streamed LLM call and a citation validator, built for speed and cost per question.

Happy to walk through any of these in an interview.

### Now building

An Elixir/OTP trading engine for Binance: supervised WebSocket streams, a risk engine, and an LLM reviewer that can veto or resize a trade but never place one.

### Toolbox

`Elixir` `OTP` `Phoenix` `LiveView` `Oban` `PostgreSQL` `Python` `TypeScript` `Bun` `Hono`
`Kubernetes` `Proxmox` `VMware vSAN` `Docker` `Ansible`
`Cloudflare Workers` `Grafana` `Loki` `Prometheus` `Tempo` `OpenTelemetry` `eBPF` `FIDO2 / WebAuthn`
