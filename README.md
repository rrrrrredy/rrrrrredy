# Hi, I'm Song Luo

*I am the Technical Staff of Myself.*

I am an **AI agent researcher and engineer** building evidence-driven systems around agent memory, completion verification, skill operations, safety, context management, observability, and evaluation.

My work sits between **agent research, infrastructure engineering, and hands-on product building**. I care about systems whose claims can be traced to public artifacts, repeatable checks, or clearly bounded experiments - not just convincing demos.

[Email](mailto:luosongred@gmail.com) | [X / Twitter](https://x.com/rrrrrredy) | [Hugging Face](https://huggingface.co/RedinGhost)

## Current Focus

| Area | What I build | Public evidence |
| --- | --- | --- |
| Agent memory and continuity | Local-first memory reconstructed from observable task evidence, with reviewed and redacted promotion instead of automatic transcript dumping. | [Agent Memory System](https://github.com/rrrrrredy/agent-memory-system) |
| Task continuity across lossy boundaries | Source-aware task invariants and bounded recovery across compaction, resume, handoff, and agent changes. | [Context Continuity](https://github.com/rrrrrredy/context-continuity) |
| Completion evidence and replay | Fresh, file-bound verification receipts; fail-closed completion gates; and incident reconstruction from observable events. | [BeforeDone](https://github.com/rrrrrredy/beforedone) |
| Skill operations and safety | Methods and tools for designing, testing, operating, and statically scanning reusable agent skills. | [SkillOps](https://github.com/rrrrrredy/skillops-paper), [Skill Security Guard](https://github.com/rrrrrredy/skill-security-guard) |
| Source-backed research workflows | Staged evidence collection, claim discipline, review loops, and publishable long-form research. | [Industry Research Framework](https://github.com/rrrrrredy/industry-research-framework) |

## Selected Work

| Project | Why it matters | Explore |
| --- | --- | --- |
| **Agent Memory System** | A local-first, cross-agent memory layer that keeps raw evidence local, builds an append-only task ledger, and promotes only reviewed portable memory. Missing or unobservable reasoning is marked explicitly rather than invented. | [Repository](https://github.com/rrrrrredy/agent-memory-system) / [Website](https://rrrrrredy.github.io/agent-memory-system/) / [Hugging Face](https://huggingface.co/spaces/RedinGhost/agent-memory-system) |
| **Context Continuity** | A local-first shared-core plugin that preserves task invariants across lossy context transitions. The Codex beta and pinned DeepSeek Harness developer-preview adapter use one state protocol on Windows, macOS, and Linux. | [Repository](https://github.com/rrrrrredy/context-continuity) / [v0.2.0-beta.1](https://github.com/rrrrrredy/context-continuity/releases/tag/v0.2.0-beta.1) / [Release evidence](https://github.com/rrrrrredy/context-continuity/blob/v0.2.0-beta.1/docs/release-readiness.md) |
| **BeforeDone** | A Go CLI and Codex integration that requires current verifier evidence before an agent declares completion. It also supports evidence-only incident replay without claiming access to hidden chain-of-thought. | [Repository](https://github.com/rrrrrredy/beforedone) / [Guide](https://rrrrrredy.github.io/beforedone/guide.html) / [Technical report](https://doi.org/10.5281/zenodo.21766277) |
| **Industry Research Framework** | An agent-agnostic workflow for source-backed industry research: task state, source and claim discipline, depth budgeting, staged drafting, adversarial review, and publication cleanup. | [Repository](https://github.com/rrrrrredy/industry-research-framework) / [Read the framework](https://rrrrrredy.github.io/industry-research-framework/framework.html#fullmd) |
| **SkillOps** | A practical framework for treating modular skills as operated software: design contracts, tests, evaluation, versioning, safety, and lifecycle management. | [Repository](https://github.com/rrrrrredy/skillops-paper) / [Paper](https://doi.org/10.5281/zenodo.20061198) |
| **Skill Security Guard** | A static security scanner for agent skills, with A-F risk ratings, safe archive scanning, CI-tested rules, and machine-readable findings. | [Repository](https://github.com/rrrrrredy/skill-security-guard) / [Releases](https://github.com/rrrrrredy/skill-security-guard/releases) |

## Research and Applied Systems

- [**Context Continuity**](https://github.com/rrrrrredy/context-continuity) is an applied agent-reliability system for source-aware recovery after context compaction, resume, and handoff. Its [v0.2.0-beta.1 prerelease](https://github.com/rrrrrredy/context-continuity/releases/tag/v0.2.0-beta.1) includes a pinned DeepSeek Harness adapter and a six-job Windows/macOS/Linux CI matrix; authenticated real-Mac Codex lifecycle evidence and efficacy results remain explicitly pending.
- [**Thin Harness, Strong Contracts**](https://github.com/rrrrrredy/agent-harness-paper) studies production-oriented agent harnesses as runtime, permission, state, replay, memory, evaluation, audit, and human-review infrastructure. [Preprint and artifact](https://doi.org/10.5281/zenodo.20907471).
- [**AI Knowledge Graph**](https://github.com/rrrrrredy/ai-knowledge-graph) and related radar projects turn reports and public data into explorable maps and monitoring workflows.

## Working Principles

- Bind important claims to observable evidence.
- Use deterministic checks for deterministic behavior, and model evaluations where behavior is genuinely stochastic.
- Keep sensitive raw evidence local; publish reviewed, redacted, and reproducible artifacts.
- Treat measured results as bounded evidence, not universal proof of efficacy.
- Preserve real failures and user corrections as future regression cases.

**Stack:** Go | Python | TypeScript | JavaScript | Shell | HTML/CSS
