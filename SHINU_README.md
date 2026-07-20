# 🤖 Shinu AI Labs — code-review-graph

> **Forked from [tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph)**  
> Local-first code intelligence graph for MCP and CLI — purpose-built for AI-driven Quality Engineering.

---

## Why Shinu AI Labs Maintains This Fork

As part of our **AI-native Quality Engineering** toolkit, we integrate `code-review-graph` into quality workflows:

- 🔍 **Blast-Radius Analysis** — When a bug fix or change is made, instantly know every test, caller, and dependency affected. This turns code review from guesswork into **traceable impact analysis**.
- ⚡ **82x Median Token Reduction** — AI agents (our QA Copilot, BrowserPilot, etc.) read only what matters instead of entire codebases.
- 🧩 **MCP Integration** — 30 MCP tools that plug directly into Hermes Agent and our QA automation stack.
- 🛡️ **Local-First** — Zero source code egress. All graph operations run on your CI runner.

**Shinu AI Labs applies this to:** Quality Engineering, AI-driven test automation, Bug Triage Agents, and RAG-enhanced code review pipelines.

---

## Quick Start

```bash
pip install code-review-graph
code-review-graph install          # Auto-detects tools, writes MCP config
code-review-graph build            # Parse your codebase into a graph
```

See the [original README](./README.md) for full documentation, benchmarks, and language support.

---

## Shinu AI Labs Integration

| Component | Integration |
|-----------|-------------|
| **QA Copilot** | MCP tools for test-impact analysis |
| **Bug Triage Agent** | Blast-radius for defect localization |
| **BrowserPilot** | Context-aware test generation |
| **Blog** | [shinuailabs.com/blog](https://www.shinuailabs.com/blog) |

---

<p align="center">
  <sub>Maintained by <a href="https://shinuailabs.com">Shinu AI Labs</a> — Engineering Intelligent Quality Systems for the AI Era</sub>
</p>
