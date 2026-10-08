Senior DevOps and Elixir backend engineer in Vietnam, working remotely. Most of my work is infrastructure that has to stay up (clusters, identity, deployments, observability) and the backend software that runs on it.

### What I work on

- High-availability platforms, from bare metal to Kubernetes, with failover and recovery planned at design time rather than patched in later.
- Passwordless login, identity and zero-trust access for security-critical products.
- Elixir is my main language: OTP services, Phoenix and LiveView apps, Oban job pipelines. I use Python or TypeScript when they fit the job better.
- Architecture and deployment docs that a customer's infra team can follow to run the system on their own.
- Spec-driven, agent-assisted development, with guardrails so a small team can move faster without the quality dropping.

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

Client work stays private, so these are described without names. I can go through them in an interview.

- An Elixir platform for e-commerce sellers: Phoenix API, Oban job pipelines, marketplace integration, passkey sign-in, and an LLM-assisted workflow where a person reviews every result.
- A customer-support RAG assistant that runs retrieval in parallel, makes one streamed LLM call and validates its citations, built to keep latency and cost per question low.

### Now building

An Elixir/OTP trading engine for Binance: supervised WebSocket streams, a risk engine, and an LLM reviewer that can veto or resize a trade but never place one.

### Toolbox

`Elixir` `OTP` `Phoenix` `LiveView` `Oban` `PostgreSQL` `Python` `TypeScript` `Bun` `Hono`
`Kubernetes` `Proxmox` `VMware vSAN` `Docker` `Ansible`
`Cloudflare Workers` `Grafana` `Loki` `Prometheus` `Tempo` `OpenTelemetry` `eBPF` `FIDO2 / WebAuthn`
