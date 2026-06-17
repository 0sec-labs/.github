# 0sec Labs

**We hack software to secure it.**

0sec Labs is an applied cybersecurity research lab building autonomous, agent-native systems that attack software the way real attackers do — then prove what breaks with working exploits and explain how to fix it.

AI writes and ships code faster than humans can review it. We think the next security layer has to attack continuously, prove impact with evidence instead of scores, and hand engineers — and AI agents — a reproducible fix.

## What we build

- **pwnkit** — our autonomous hacking engine. Research agents find vulnerabilities; independent verify agents re-exploit each one and kill anything they can't reproduce. Closed source. → [0sec.ai/pwnkit](https://0sec.ai/pwnkit)
- **0cloud** — the managed product around pwnkit: scoped targets, recurring runs, exploit-backed evidence, and triage workflows. → [0sec.ai](https://0sec.ai)
- **[foxguard](https://github.com/0sec-labs/foxguard)** — open-source, linter-fast security scanning and policy checks that catch regressions before deploy. Our open trust signal.
- **[opensoar](https://github.com/opensoar-hq/opensoar-core)** — response and orchestration for routing validated failures into real operator workflows.
- **[noeris](https://github.com/0sec-labs/noeris)** — our research OS for autonomous empirical discovery, currently led by a flagship GPU kernel-optimization track.

## How we think about it

Most AI-reliability tooling measures prompts, traces, and outputs. We care about whether a capable system can actually be broken, exploited, or pushed outside its intended bounds.

- attacks and working exploits, not happy-path evals
- evidence-backed findings, not vibe-based scores
- prevention and response, not detection alone

## Why now

AI agents are being shipped into real workflows faster than teams can verify them. The bottleneck is no longer generation — it's trust. 0sec Labs exists to close that gap.

## Status

Consolidating around the core company products:

- **pwnkit** is the flagship engine (closed source)
- **0cloud** is the managed, hosted surface
- **foxguard** and **opensoar** are open-source siblings in the same story
- **noeris** strengthens the shared research and evaluation substrate the products build on

Built in Switzerland · [0sec.ai](https://0sec.ai)
