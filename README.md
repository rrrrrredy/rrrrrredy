# Hi, I'm Song Luo

*I am the Technical Staff of Myself.*

I am an **AI agent researcher and engineer** building evidence-driven systems around agent memory, completion verification, skill operations, safety, context management, observability, and evaluation.

My work sits between **agent research, infrastructure engineering, and hands-on product building**. I care about systems whose claims can be traced to public artifacts, repeatable checks, or clearly bounded experiments - not just convincing demos.

[Email](mailto:luosongred@gmail.com) | [X / Twitter](https://x.com/rrrrrredy) | [Hugging Face](https://huggingface.co/RedinGhost)

## Research Focus

- **Agent evidence, evaluation, and evolution:** observable Run retention, failure diagnosis, controlled comparisons, resettable workflow environments, and bounded capability evolution.
- **Memory, continuity, and intent:** local-first state reconstructed from evidence, with explicit handling of unknowns, disagreement, compaction, resume, and handoff.
- **Completion and execution reliability:** fresh verification evidence, contract-bound actions, replayable events, permission boundaries, and human-owned decisions.
- **Skill engineering and research workflows:** turning experience into reviewable procedural knowledge, testing and operating reusable Skills, static security analysis, and source-backed research.

## Papers & Technical Reports

- **Governed Skill Evolution from Persistent Agent Experience** (2026, preprint) - A prospective ablation and cross-model transfer study of no Wiki, flat history, and persistent Wiki. Persistence used fewer input tokens and shorter final rules than flat history in this setting, but did not improve mean task quality. [Repository](https://github.com/rrrrrredy/governed-skill-evolution) / [PDF](https://github.com/rrrrrredy/governed-skill-evolution/releases/download/v1.0.0/governed-skill-evolution-paper-v1.0.0.pdf) / [DOI](https://doi.org/10.5281/zenodo.22240411)
- **BeforeDone: Fresh, State-Bound Evidence for Coding-Agent Completion** (2026, technical report) - A frozen, reproducible study of whether completion claims carry passing verifier evidence bound to the repository state they describe. [Repository](https://github.com/rrrrrredy/beforedone-paper) / [DOI](https://doi.org/10.5281/zenodo.21766277)
- **Thin Harness, Strong Contracts** (2026, preprint) - A production-oriented study of agent harnesses as runtime, permission, state, replay, memory, evaluation, audit, and human-review infrastructure. [Repository](https://github.com/rrrrrredy/agent-harness-paper) / [DOI](https://doi.org/10.5281/zenodo.20907471)
- **SkillOps: A Practical Framework for Designing, Testing, and Operating Modular Skills in Personal AI Agents** (2026, paper and software artifact) - A lifecycle framework covering Skill contracts, tests, evaluation, versioning, safety, and operations. [Repository](https://github.com/rrrrrredy/skillops-paper) / [Paper](https://github.com/rrrrrredy/skillops-paper/blob/main/release/skillops-paper.pdf) / [Concept DOI](https://doi.org/10.5281/zenodo.20061198)

## Selected Systems

- **Agent Run Evidence Toolkit:** independent repositories for retaining observable runs, evolving instructions, creating resettable scored workflow Cases, and exchanging portable evidence. [Runtime](https://github.com/rrrrrredy/runtime-evolution-workbench) / [Factory](https://github.com/rrrrrredy/workflow-environment-factory) / [Protocol](https://github.com/rrrrrredy/runcase-interchange) / [DeepSeek adapter](https://github.com/rrrrrredy/deepseek-harness-runcase-adapter)
- **Agent Memory System:** a local-first, cross-agent memory layer that keeps raw evidence local and promotes only reviewed, redacted, portable memory. [Repository](https://github.com/rrrrrredy/agent-memory-system) / [Website](https://rrrrrredy.github.io/agent-memory-system/) / [Hugging Face](https://huggingface.co/spaces/RedinGhost/agent-memory-system)
- **Continuity and intent:** two local-first systems for preserving task invariants across lossy boundaries and keeping statements, inferences, evidence, unknowns, disagreements, and superseded claims distinct. [Context Continuity](https://github.com/rrrrrredy/context-continuity) / [Intent Loop](https://github.com/rrrrrredy/intent-loop)
- **Completion and execution reliability:** fresh, file-bound completion evidence plus contract checks before high-impact actions, without taking planning or permissions away from the host. [BeforeDone](https://github.com/rrrrrredy/beforedone) / [Execution Fidelity Guard](https://github.com/rrrrrredy/execution-fidelity-guard) / [DeepSeek adapter](https://github.com/rrrrrredy/dsh-execution-fidelity-guard)
- **Skill lifecycle and safety:** an evidence-gated path from selected runs to one reviewable Skill change, paired with static scanning for risky Skill content and archives. [Experience to Skill](https://github.com/rrrrrredy/experience-to-skill) / [Skill Security Guard](https://github.com/rrrrrredy/skill-security-guard)
- **Industry Research Framework:** an agent-agnostic workflow for source-backed industry research, claim discipline, staged drafting, adversarial review, and publication cleanup. [Repository](https://github.com/rrrrrredy/industry-research-framework) / [Read the framework](https://rrrrrredy.github.io/industry-research-framework/framework.html#fullmd)

## Working Principles

- Bind important claims to observable evidence.
- Use deterministic checks for deterministic behavior, and model evaluations where behavior is genuinely stochastic.
- Keep sensitive raw evidence local; publish reviewed, redacted, and reproducible artifacts.
- Treat measured results as bounded evidence, and preserve real failures and user corrections as future regression cases.

**Stack:** Go | Python | TypeScript | JavaScript | Shell | HTML/CSS
