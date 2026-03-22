# Differential AI Lab

We build open infrastructure for companies navigating the AI transition — from training and upskilling teams to deploying autonomous agents safely in production. Get in touch at [https://difflab.ai](https://difflab.ai)

Our work spans four areas: **AI Training**, **AI Transformation**, **Boundary Enforcement**, and **AI Native Software Engineering**.

---

## 🎓 AI Training

Helping organizations and individuals build genuine AI fluency — not just tool familiarity, but a deep understanding of how to work with and alongside AI systems.

| Repository | Description |
|---|---|
| [**ai-fluency-explorer**](https://github.com/difflabai/ai-fluency-explorer) | Interactive assessment platform covering prompt engineering, AI ethics, technical concepts, and practical applications. Five difficulty levels from Novice to Expert, with shareable results and a public leaderboard. Use it to benchmark your team's AI readiness. |
| [**tuneout**](https://github.com/difflabai/tuneout) | Open-source guide to cognitive security — understanding how algorithmic systems manipulate attention and how LLM filters can replace algorithmic feeds. Includes a Claude skill for personal digital attention auditing. Because the humans using your AI tools need to think clearly too. |
| [**protocols**](https://github.com/difflabai/protocols) | Open standards for AI development, including the `.project` standard — a vendor-neutral directory structure for AI project context that works across Claude, Codex, Cursor, Windsurf, Gemini, and any AI coding tool. Helps teams create consistent, AI-readable project context from day one. |

---

## ⚡ AI Transformation

Operational tooling for turning AI from a novelty into a force multiplier across your engineering and business workflows.

| Repository | Description |
|---|---|
| [**ats-dispatch**](https://github.com/difflabai/ats-dispatch) | Reference implementation of an autonomous task executor. Connects to an ATS channel via WebSocket, claims tasks, executes them through any subprocess (Claude, Python, bash, HTTP), and reports results back. The foundation for building agents that do real work. |
| [**pr-autofix**](https://github.com/difflabai/pr-autofix) | Automatically applies AI-generated code review suggestions to GitHub PRs using Claude Code. Polls open PRs, finds unresolved review comments, edits the code, commits, pushes, and resolves the thread. Zero manual intervention. |
| [**claude-automation**](https://github.com/difflabai/claude-automation) | Tooling for running and coordinating multiple Claude instances in parallel using tmux — including `claude-while`, a bash wrapper that keeps N Claude agents looping continuously on a shared task with built-in coordination via a shared state file. |
| [**xscout**](https://github.com/difflabai/xscout) | Multi-source AI intelligence pipeline. Pulls posts from X, Reddit, CivitAI, Arxiv, HackerNews, and Lobsters, then uses an LLM to generate structured, opinionated briefings. Keeps your team current on the AI landscape at roughly $0.001/run. |
| [**near-market-agent**](https://github.com/difflabai/near-market-agent) | Worker agent for [market.near.ai](https://market.near.ai) that autonomously bids on and completes music, code, and research jobs — a working example of an AI agent participating in an open task marketplace. |
| [**desktop-jobs**](https://github.com/difflabai/desktop-jobs) | Ada — a dead-simple service manager for desktop jobs. Keeps your local AI agents and background processes running reliably. |

---

## 🔒 Boundary Enforcement

AI systems that operate without proper safety boundaries create liability. We build infrastructure that enforces those boundaries cryptographically — without sacrificing user privacy.

| Repository | Description |
|---|---|
| [**confidential-safety**](https://github.com/difflabai/confidential-safety) | Safety evaluation layer for confidential AI inference and agentic workloads. Runs inside a Trusted Execution Environment (TEE) to classify inputs/outputs against risk categories, gate requests, and emit cryptographically attested verdicts — without raw user data ever leaving the TEE. Two tiers: stateless per-request inference safety, and stateful per-session agent safety with trajectory analysis and escalation. |
| [**prompt-bonk**](https://github.com/difflabai/prompt-bonk) | Fast, zero-dependency prompt injection scanner for Node.js. 498 regex patterns catch instruction hijacking, prompt extraction, data exfiltration, role hijacking, and obfuscation attacks in <1ms. First layer of defense before untrusted text reaches your LLM. |
| [**tuneout**](https://github.com/difflabai/tuneout) | Boundary enforcement for human cognition. Provides LLM-based content filters that replace algorithmic feeds, reducing the attack surface for attention manipulation. Research-backed, open-source, zero tracking. |

---

## 🏗️ AI Native Software Engineering

Tools and protocols for building software systems where AI agents are first-class participants — not bolt-ons, but integral parts of the engineering workflow.

| Repository | Description |
|---|---|
| [**protocols**](https://github.com/difflabai/protocols) | The `.project` standard — a vendor-neutral spec for structuring AI project context. Gives every AI coding tool the same shared understanding of your codebase: architecture decisions, conventions, constraints, and goals. Works today with Claude, Codex, Cursor, Windsurf, and Gemini. |
| [**marketplace**](https://github.com/difflabai/marketplace) | Public skills and plugins for Claude Code, including `dreamsolve` for project management and AI agents via DreamSolve MCP. Installable with `/plugin install`. |
| [**ats-dispatch**](https://github.com/difflabai/ats-dispatch) | The dispatch layer for AI agent systems: WebSocket-based task pickup, lease-based ownership, dependency graphs, encrypted task payloads, and graceful failure handling. Drop-in foundation for any autonomous software engineering agent. |
| [**ats-p2p**](https://github.com/difflabai/ats-p2p) | P2P file transfer for AI agents. ATS handles signaling; Hyperswarm handles Noise-encrypted byte transfer with NAT traversal. SHA-256 verified, peer allowlisted, full audit trail — no file data touches the task system. |
| [**pr-autofix**](https://github.com/difflabai/pr-autofix) | Closes the AI code review loop: picks up AI-generated PR review comments, applies fixes autonomously, and resolves threads. A working example of an AI agent participating directly in the software engineering lifecycle. |
| [**claude-automation**](https://github.com/difflabai/claude-automation) | Multi-agent coordination tooling for running parallel Claude instances on a shared codebase — with the `claude-while` loop wrapper for continuous autonomous iteration and a coordination pattern using shared state files to prevent duplicate work. |

---

## About

[Differential AI Lab](https://difflab.ai) is building the infrastructure layer for the AI transition. We work with organizations that are serious about deploying AI safely, upskilling their teams durably, and engineering software in an AI-first way.

All public repositories are open source under MIT unless otherwise noted.
