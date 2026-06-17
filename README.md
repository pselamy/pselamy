# Patrick Selamy

**AI agent engineer.** I build production multi-agent systems — skills, MCP tooling, autonomous coding loops, evals — and run a **live fleet that does real work** under explicit security and reliability constraints. Formerly **Meta** and **Google** (Cloud Office of the CTO: first-wave agentic coding + SWE-bench eval harnesses).

🌐 [selamy.dev](https://selamy.dev) · 📄 [Resume](https://selamy.dev/resume/) · 💼 [LinkedIn](https://www.linkedin.com/in/patrickselamy) · ⚙️ [Speedforge](https://speedforge.dev)

### What I build
- **Multi-agent orchestration** — a lease-based priority queue ([laneq](https://github.com/selamy-labs/laneq)), parallel workers, self-healing watchdogs (park + stay-busy recovery), agent-team fan-out.
- **Skills & MCP** — a working framework for *when to use MCP (capabilities) vs skills (judgment)*; public [agent-skills](https://github.com/selamy-labs/agent-skills) plus MCP servers ([agent](https://github.com/selamy-labs/agent-mcp), [telemetry](https://github.com/selamy-labs/telemetry-mcp), [memory](https://github.com/selamy-labs/memory-mcp), [dispatch](https://github.com/selamy-labs/dispatch-mcp), [reddit](https://github.com/selamy-labs/reddit-mcp)); agents that author their own tools and skills behind privacy/security gates.
- **Observability** — OpenTelemetry across the fleet (tool-call / token / latency / trajectory telemetry) with live dashboards.
- **Production rigor** — per-agent isolation, a keyless secrets-broker, GitOps/IaC (OpenTofu + Argo CD), runtime knobs without restarts.

### Selected work
- **[framework-seed](https://github.com/pselamy/framework-seed)** — agent-orchestration + knowledge-management methodology (make "done" mean done).
- **[agent-skills](https://github.com/selamy-labs/agent-skills)** — public, reusable agent skills (MCP-vs-skills, verification, orchestration discipline).
- **[laneq](https://github.com/selamy-labs/laneq)** — the lease-based priority queue that schedules the fleet (priority lanes, leases, requeue).
- **[Speedforge](https://speedforge.dev)** — self-hosted GitHub Actions CI runners.
- **[polymarket-insider-tracker](https://github.com/pselamy/polymarket-insider-tracker)** — detect potential insider trading on prediction markets.
- **[resume](https://github.com/pselamy/resume)** — resume-as-code: base + per-role variants, CI-compiled, published.
