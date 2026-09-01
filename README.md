# Hi, I'm Song Luo

*I am the Technical Staff of Myself.*

I am an **AI agent researcher and engineer** building evidence-driven systems around agent memory, completion verification, skill operations, safety, context management, observability, and evaluation.

My work sits between **agent research, infrastructure engineering, and hands-on product building**. I care about systems whose claims can be traced to public artifacts, repeatable checks, or clearly bounded experiments - not just convincing demos.

[Email](mailto:luosongred@gmail.com) | [X / Twitter](https://x.com/rrrrrredy) | [Hugging Face](https://huggingface.co/RedinGhost)

## Current Focus

| Area | What I build | Public evidence |
| --- | --- | --- |
| Agent run evidence and workflow environments | Local-first Run retention, failure diagnosis, controlled instruction comparisons, and resettable workflow Cases with objective validators. | [Runtime Evolution Workbench](https://github.com/rrrrrredy/runtime-evolution-workbench) / [Workflow Environment Factory](https://github.com/rrrrrredy/workflow-environment-factory) / [RunCase Interchange](https://github.com/rrrrrredy/runcase-interchange) / [DeepSeek Harness adapter](https://github.com/rrrrrredy/deepseek-harness-runcase-adapter) |
| Agent memory and continuity | Local-first memory reconstructed from observable task evidence, with reviewed and redacted promotion instead of automatic transcript dumping. | [Agent Memory System](https://github.com/rrrrrredy/agent-memory-system) |
| Task continuity across lossy boundaries | Source-aware task invariants and bounded recovery across compaction, resume, handoff, and agent changes. | [Context Continuity](https://github.com/rrrrrredy/context-continuity) / [DeepSeek Harness adapter](https://github.com/rrrrrredy/context-continuity/tree/v0.2.0-beta.2/adapters/deepseek-harness) |
| Completion evidence and replay | Fresh, file-bound verification receipts; fail-closed completion gates; and incident reconstruction from observable events. | [BeforeDone](https://github.com/rrrrrredy/beforedone) |
| Execution fidelity | Contract-bound checks before high-impact actions and before completion claims, while reversible exploration stays quiet. | [Execution Fidelity Guard](https://github.com/rrrrrredy/execution-fidelity-guard), [DeepSeek Harness adapter](https://github.com/rrrrrredy/dsh-execution-fidelity-guard) |
| Skill operations and safety | Methods and tools for designing, testing, operating, and statically scanning reusable agent skills. | [SkillOps](https://github.com/rrrrrredy/skillops-paper), [Skill Security Guard](https://github.com/rrrrrredy/skill-security-guard) |
| Source-backed research workflows | Staged evidence collection, claim discipline, review loops, and publishable long-form research. | [Industry Research Framework](https://github.com/rrrrrredy/industry-research-framework) |

## Selected Work

| Project | Why it matters | Explore |
| --- | --- | --- |
| **Agent Run Evidence Toolkit** | Four independent Apache-2.0 repositories that preserve observable Agent runs, turn failures into reviewable improvement proposals, and convert confirmed workflows into resettable scored Cases. RunCase Interchange is the only shared boundary; the DeepSeek Harness adapter captures the same portable Run format. | [Runtime](https://github.com/rrrrrredy/runtime-evolution-workbench) / [Factory](https://github.com/rrrrrredy/workflow-environment-factory) / [Protocol](https://github.com/rrrrrredy/runcase-interchange) / [DeepSeek adapter](https://github.com/rrrrrredy/deepseek-harness-runcase-adapter) |
| **Agent Memory System** | A local-first, cross-agent memory layer that keeps raw evidence local, builds an append-only task ledger, and promotes only reviewed portable memory. Missing or unobservable reasoning is marked explicitly rather than invented. | [Repository](https://github.com/rrrrrredy/agent-memory-system) / [Website](https://rrrrrredy.github.io/agent-memory-system/) / [Hugging Face](https://huggingface.co/spaces/RedinGhost/agent-memory-system) |
| **Context Continuity** | A local-first shared-core plugin that preserves task invariants across compaction, resume, and handoff. It ships as a Codex beta plus a pinned DeepSeek Harness developer-preview adapter, using one state protocol on Windows, macOS, and Linux. | [Repository](https://github.com/rrrrrredy/context-continuity) / [DeepSeek Harness adapter](https://github.com/rrrrrredy/context-continuity/tree/v0.2.0-beta.2/adapters/deepseek-harness) / [v0.2.0-beta.2](https://github.com/rrrrrredy/context-continuity/releases/tag/v0.2.0-beta.2) / [Evidence](https://github.com/rrrrrredy/context-continuity/blob/v0.2.0-beta.2/docs/release-readiness.md) |
| **BeforeDone** | A Go CLI and Codex integration that requires current verifier evidence before an agent declares completion. It also supports evidence-only incident replay without claiming access to hidden chain-of-thought. | [Repository](https://github.com/rrrrrredy/beforedone) / [Guide](https://rrrrrredy.github.io/beforedone/guide.html) / [Technical report](https://doi.org/10.5281/zenodo.21766277) |
| **Execution Fidelity Guard** | A lightweight contract and evidence layer for agent actions and completion claims. The Codex release and unofficial DeepSeek Harness alpha share the same seven-field contract while leaving planning, permissions, and execution to their hosts. | [Codex repository](https://github.com/rrrrrredy/execution-fidelity-guard) / [v0.2.2](https://github.com/rrrrrredy/execution-fidelity-guard/releases/tag/v0.2.2) / [DeepSeek Harness alpha.2](https://github.com/rrrrrredy/dsh-execution-fidelity-guard/releases/tag/v0.1.0-alpha.2) |
| **Industry Research Framework** | An agent-agnostic workflow for source-backed industry research: task state, source and claim discipline, depth budgeting, staged drafting, adversarial review, and publication cleanup. | [Repository](https://github.com/rrrrrredy/industry-research-framework) / [Read the framework](https://rrrrrredy.github.io/industry-research-framework/framework.html#fullmd) |
| **SkillOps** | A practical framework for treating modular skills as operated software: design contracts, tests, evaluation, versioning, safety, and lifecycle management. | [Repository](https://github.com/rrrrrredy/skillops-paper) / [Paper](https://doi.org/10.5281/zenodo.20061198) |
| **Skill Security Guard** | A static security scanner for agent skills, with A-F risk ratings, safe archive scanning, CI-tested rules, and machine-readable findings. | [Repository](https://github.com/rrrrrredy/skill-security-guard) / [Releases](https://github.com/rrrrrredy/skill-security-guard/releases) |

## Research and Applied Systems

- **Agent run evidence and workflow environments**: [Runtime Evolution Workbench v0.2.0](https://github.com/rrrrrredy/runtime-evolution-workbench/releases/tag/v0.2.0) saves observable Codex runs, groups evidence-backed issues, and compares reviewable AGENTS.md or Skill changes; [Workflow Environment Factory v0.2.1](https://github.com/rrrrrredy/workflow-environment-factory/releases/tag/v0.2.1) turns confirmed repositories and Issue-to-PR flows into resettable, objectively scored Cases. [RunCase Interchange v0.1.2](https://github.com/rrrrrredy/runcase-interchange/releases/tag/v0.1.2) is their only shared protocol, and the [DeepSeek Harness v0.1.0 adapter](https://github.com/rrrrrredy/deepseek-harness-runcase-adapter/releases/tag/v0.1.0) captures compatible runs. Hosted Windows, Linux, and Apple Silicon macOS package lifecycles are public prerelease evidence; authenticated improvement efficacy, physical-Mac use, and a complete Factory Agent run remain unproven.
- [**Execution Fidelity Guard**](https://github.com/rrrrrredy/execution-fidelity-guard) explores a narrow execution-fidelity layer. Shadow mode reminds and proceeds; balanced mode can deny explicit contract conflicts, return user-owned choices to the Host, and request current contract-bound evidence. The [Codex v0.2.2 release](https://github.com/rrrrrredy/execution-fidelity-guard/releases/tag/v0.2.2) and separate unofficial [DeepSeek Harness v0.1.0-alpha.2 adapter](https://github.com/rrrrrredy/dsh-execution-fidelity-guard/releases/tag/v0.1.0-alpha.2) have source and integration paths in Windows, macOS, and Linux CI. Installed-client UX, online shadow results, and controlled-task efficacy remain pending.
- [**Context Continuity**](https://github.com/rrrrrredy/context-continuity) protects the small set of task facts an agent must not lose when context is compacted, resumed, or handed off. The same local-first core powers the Codex plugin and the [DeepSeek Harness adapter](https://github.com/rrrrrredy/context-continuity/tree/v0.2.0-beta.2/adapters/deepseek-harness) on Windows, macOS, and Linux. The [v0.2.0-beta.2 prerelease](https://github.com/rrrrrredy/context-continuity/releases/tag/v0.2.0-beta.2) passed its [six-job tagged CI matrix](https://github.com/rrrrrredy/context-continuity/actions/runs/33466096941); authenticated real-Mac Codex lifecycle evidence and efficacy results remain pending.
- [**Thin Harness, Strong Contracts**](https://github.com/rrrrrredy/agent-harness-paper) studies production-oriented agent harnesses as runtime, permission, state, replay, memory, evaluation, audit, and human-review infrastructure. [Preprint and artifact](https://doi.org/10.5281/zenodo.20907471).

## Working Principles

- Bind important claims to observable evidence.
- Use deterministic checks for deterministic behavior, and model evaluations where behavior is genuinely stochastic.
- Keep sensitive raw evidence local; publish reviewed, redacted, and reproducible artifacts.
- Treat measured results as bounded evidence, not universal proof of efficacy.
- Preserve real failures and user corrections as future regression cases.

**Stack:** Go | Python | TypeScript | JavaScript | Shell | HTML/CSS
