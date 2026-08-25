# Bishnu Bista

**Hands-on engineering leader building dependable AI-agent systems, evaluation infrastructure, and security tooling.**

I turn ambiguous ideas into tested, operable products—from architecture and agent workflows to full-stack implementation, security boundaries, release engineering, and contributor experience. I maintain [SAF-MCP](https://github.com/secure-agentic-framework/saf-mcp), contribute to [Promptfoo](https://github.com/promptfoo/promptfoo), and co-authored **ConformalGuard**, accepted at COLM 2026. Previously at American Express and Wells Fargo.

I am especially interested in startup conversations where technical leadership, product ownership, and hands-on founding-engineer execution matter.

## At a Glance

- **Technical leadership:** architecture, 0→1 product engineering, platform design, full-stack delivery, release operations, and open-source maintenance
- **AI systems:** coding agents, multi-agent workflows, LLM evaluation and red teaming, human-approval boundaries, retrieval, and local-first AI
- **Security:** Model Context Protocol (MCP), threat modeling, detection engineering, least privilege, auditability, and privacy-preserving system design
- **Core stack:** Python, TypeScript, React, FastAPI, Hono, Cloudflare Workers/D1/R2, SQLite, Swift/SwiftUI, and agent-development tooling
- **Based in:** San Francisco Bay Area

---

## Open-Source Leadership

### [SAF-MCP](https://github.com/secure-agentic-framework/saf-mcp) — Maintainer

A MITRE ATT&CK-style framework for documenting and mitigating threats in Model Context Protocol and agentic systems. My contributions span threat research, Sigma detection rules, security-control design, catalog validation, and contributor infrastructure.

Selected work:

- Documented and tested detection for [MCP Inspector exploitation](https://github.com/secure-agentic-framework/saf-mcp/pull/1), [path traversal through file tools](https://github.com/secure-agentic-framework/saf-mcp/pull/19), and [AI agent CLI weaponization](https://github.com/secure-agentic-framework/saf-mcp/pull/49)
- Designed [out-of-band authorization, anomaly detection, query guardrails, and output DLP](https://github.com/secure-agentic-framework/saf-mcp/pull/193) for privileged tool invocations
- Strengthened catalog integrity through [detection-rule coverage, MITRE mapping corrections, and mitigation cross-references](https://github.com/secure-agentic-framework/saf-mcp/pull/198)
- Built contributor validation and approval-gated onboarding workflows for [SAF Agentic Use Case Analysis](https://github.com/secure-agentic-framework/saf-agentic-use-cases)

### [Promptfoo](https://github.com/promptfoo/promptfoo) — Contributor

Merged contributions to the open-source platform for testing and red-teaming prompts, agents, and RAG systems:

- Made `afterEach` evaluation-hook metadata and named scores flow through to [database persistence, file outputs, metrics, and the web viewer](https://github.com/promptfoo/promptfoo/pull/7731)
- Fixed [OpenAI Codex SDK cached-token and cost accounting](https://github.com/promptfoo/promptfoo/pull/7617)
- Added [CLI list-command coverage and provider-validation edge-case tests](https://github.com/promptfoo/promptfoo/pull/7616)

Additional upstream work includes a benchmark-backed [audit-log read-replica fix in Pangolin](https://github.com/fosrl/pangolin/pull/3148), a [Python library behavior fix in Supabase](https://github.com/supabase/supabase-py/pull/1380), and [module caching in the American Express One App platform](https://github.com/americanexpress/one-app/pull/1094).

---

## Research

### [ConformalGuard: False-Positive-Controlled Action Gating for LM Classifiers](https://openreview.net/forum?id=bPUdqX3pCF&noteId=bPUdqX3pCF)

Accepted at the **Conference on Language Modeling (COLM) 2026**.

ConformalGuard is a model-agnostic calibration layer for choosing pre-deployment action thresholds with finite-sample false-positive control under exchangeability. We evaluated it with fine-tuned BERT, Claude Sonnet 4, and GPT-4o on public email corpora, exposing the recall and robustness trade-offs of coarse zero-shot LM scores.

[Code and reproducibility](https://github.com/bishnubista/conformalguard-colm-2026) · [Paper PDF](papers/conformalguard-colm-2026.pdf) · [OpenReview record](https://openreview.net/forum?id=bPUdqX3pCF&noteId=bPUdqX3pCF)

---

## Products and Developer Infrastructure

| Project | Technical focus |
| --- | --- |
| [OpenBird](https://github.com/bishnubista/openbird) | Open-source, local-first personal AI memory for macOS. Text-first capture, transient on-device OCR, SQLite/FTS5/vector retrieval, cited answers, Ollama/BYO-model support, and bounded read-only MCP access. |
| [ConfPilot](https://github.com/bishnubista/confpilot-open-source) | Open-source conference program operations from CFP to published schedule. Role-scoped workflows, idempotent lifecycle transitions, React/Hono, and runtime ports for Cloudflare D1/R2 or Node/SQLite. |
| **CyclePel** | Native SwiftUI indoor-cycling platform with FTMS smart-trainer control, structured ERG workouts, route simulation, and hardware safety gates. Currently private and being prepared for a future open-source release. |
| [cc-statusline](https://github.com/bishnubista/cc-statusline) | A focused Claude Code statusline for model, directory, Git branch, and output-style context. |
| [PlanGate](https://github.com/bishnubista/plangate) | PLAN.md-driven development with explicit quality gates for Claude Code workflows. |

---

## Engineering Approach

- **Agent-native delivery:** decompose work into bounded workstreams, use coding agents for implementation and review, and require exact verification before integration
- **Dependability by design:** deterministic evaluations, human approval for consequential actions, audit trails, privacy boundaries, and explicit failure states
- **Full-lifecycle ownership:** product definition, system architecture, implementation, testing, packaging, release operations, documentation, and contributor workflows
- **Leader who still builds:** stay close to code and users while creating the technical systems that let a team move quickly without losing correctness

---

## Community

- Organize Bay Area events through **The AI Agents Community**
- Teach workshops on Claude Code, Cursor, and AI-powered software development
- Build and contribute in public across agent security, evaluations, local-first AI, and developer infrastructure

---

## Connect

If you are building coding agents, agent infrastructure, AI security, evaluation systems, or ambitious developer products—and need a hands-on technical leader who can move from architecture to shipped systems—let's connect.

[LinkedIn](https://www.linkedin.com/in/bishnubista/) · [X](https://x.com/bishnubista_) · [AI events](https://luma.com/user/bbista)

Outside software, I run marathons and train for triathlons.
