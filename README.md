<p align="center">
  <img src="https://veilfire.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Ffullsizetext.8c7c5295.png&w=256&q=75" alt="Veilfire" width="200"/>
</p>

<h3 align="center">Safe, Secure, Ethical Artificial Intelligence</h3>
<p align="center"><strong>Governance infrastructure for agentic AI</strong></p>

<p align="center">
  <a href="https://veilfire.io">Website</a> · <a href="https://veilfire.medium.com">Blog</a>
</p>

---

## What is Veilfire?

Veilfire builds the governance layer for agentic AI.

As organizations deploy AI agents that can reason, act, and interact autonomously, they need infrastructure that keeps those agents **within defined authority boundaries**, **observable**, and **aligned to policy and regulatory requirements** (e.g., EU AI Act, ISO/IEC 42001, NIST AI RMF).

We're building a **full-stack agentic AI governance platform** — from agent framework to runtime control, real-time policy enforcement, and compliance evaluation.

## Why Veilfire Exists

Agent adoption is accelerating, but governance is still fragmented and reactive.

- **Agents exceed their authority.** Without bounded autonomy, agents can access data they shouldn't, invoke tools they shouldn't, or take actions beyond their mandate.
- **Compliance is stitched together manually.** Teams rely on spreadsheets, periodic audits, and disconnected tools that don't map cleanly to agent runtime behavior.
- **Governance often becomes the bottleneck.** Many control layers add enough latency to create engineering and product friction.
- **Privacy gets compromised in the name of safety.** Traditional monitoring approaches capture raw content, creating new exposure risks while trying to reduce AI risk.

## How Veilfire Solves It

Veilfire spans four layers of the AI agent governance stack:

| Product | What It Does |
|---|---|
| **Ember** | Agent framework with the GAME methodology — bounded autonomy, multi-agent coordination, deterministic failure handling, and native governance integration. |
| **FireDeck** | Operational control plane — identity, authentication, execution control, cluster governance, budget controls, and drift monitoring. |
| **Lens** | Real-time governance engine — inline policy enforcement (low-latency fast path), privacy-preserving telemetry, cryptographic Merkle-chain audit trails, and HITL escalation workflows. |
| **Insight** | Evaluation & compliance — five-pillar AI safety evaluation, scenario-based testing, and certification-ready reporting for frameworks such as EU AI Act, ISO/IEC 42001, NIST AI RMF, SOC 2, and Canada's AIDA. |

### Core Technical Principles

- **Privacy-preserving by design.** Metadata-first telemetry and minimization by default. Raw content is not collected as part of standard operations.
- **Low-latency inline governance.** Real-time policy enforcement designed to be operationally viable at scale.
- **Bounded autonomy.** Agents cannot escalate their own permissions; authority boundaries are enforced at the framework and runtime layers.
- **Tamper-evident auditability.** Cryptographic Merkle-chain audit trails with KMS-backed signing for non-repudiation.
- **Tiered response model.** `ALLOW > WARN > THROTTLE > DENY > QUARANTINE > TERMINATE > HITL` — not just allow/deny.

## Research & Writing

We publish on AI governance, agent security, privacy-preserving oversight, and compliance engineering.

- [Why Most AI Agent Guardrails Fail in Production](https://veilfire.medium.com) — OWASP-aligned agent security (series)
- [Tracking Agent Behaviour & Identifying Drift](https://veilfire.medium.com) — Governance operations for agentic systems
- [Threat Modeling AI Agents: Hotel Customer Support Case Study](https://veilfire.medium.com) — Practical agent threat modeling
- [Human-in-the-Loop Is a Privacy Trap](https://veilfire.medium.com) — Why naive HITL can create data exposure risk

## Get Involved

We're building an open community around **agentic AI governance**.

If you're working on agent systems and thinking seriously about safety, governance, privacy, or compliance, we'd love to connect.

- **Read our work** on [Medium](https://veilfire.medium.com) for technical deep-dives
- **Star / watch** repos to follow development
- **Open an issue** to discuss ideas, problems, or governance patterns

## About

Veilfire is founded and built in Canada by Jesse C, with a background in Computer Science, AI/ML, and Cybersecurity.

<p align="center">
  <sub>&copy; 2026 Veilfire &middot; <a href="https://veilfire.io">veilfire.io</a></sub>
</p>
