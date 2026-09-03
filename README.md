# Hi, I'm Song Luo

I build **evidence-driven infrastructure for AI agents**: memory that survives lossy context, completion claims bound to current state, and reusable skills that can be tested and operated.

My work sits between **agent research, infrastructure engineering, and hands-on product building**. I prefer public artifacts, repeatable checks, bounded experiments, and honest negative results over convincing demos.

*Technical Staff of Myself.*

[Email](mailto:luosongred@gmail.com) · [X / Twitter](https://x.com/rrrrrredy) · [Hugging Face](https://huggingface.co/RedinGhost)

## Start here

- **[BeforeDone](https://github.com/rrrrrredy/beforedone)** binds coding-agent completion claims to fresh verification evidence from the repository state being described. [BeforeDone technical report](https://github.com/rrrrrredy/beforedone-paper) · [BeforeDone DOI](https://doi.org/10.5281/zenodo.21766277)
- **[Agent Memory System](https://github.com/rrrrrredy/agent-memory-system)** is a local-first, cross-agent memory layer that keeps raw evidence local and promotes only reviewed, redacted, portable memory. [Agent Memory live site](https://rrrrrredy.github.io/agent-memory-system/) · [Agent Memory on Hugging Face](https://huggingface.co/spaces/RedinGhost/agent-memory-system)
- **[Governed Skill Evolution](https://github.com/rrrrrredy/governed-skill-evolution)** compares no Wiki, flat history, and persistent Wiki in a prospective ablation and cross-model transfer study. Persistence reduced input tokens and final-rule length in this setting, but did not improve mean task quality. [Governed Skill Evolution PDF](https://github.com/rrrrrredy/governed-skill-evolution/releases/download/v1.0.0/governed-skill-evolution-paper-v1.0.0.pdf) · [Governed Skill Evolution DOI](https://doi.org/10.5281/zenodo.22240411)

## More work

<details>
<summary><strong>Papers and technical reports</strong></summary>

- **[Governed Skill Evolution from Persistent Agent Experience](https://github.com/rrrrrredy/governed-skill-evolution)** (2026, preprint). A prospective ablation and cross-model transfer study of no Wiki, flat history, and persistent Wiki. [GSE PDF](https://github.com/rrrrrredy/governed-skill-evolution/releases/download/v1.0.0/governed-skill-evolution-paper-v1.0.0.pdf) · [GSE DOI](https://doi.org/10.5281/zenodo.22240411)
- **[BeforeDone: Fresh, State-Bound Evidence for Coding-Agent Completion](https://github.com/rrrrrredy/beforedone-paper)** (2026, technical report). A frozen, reproducible study of whether completion claims carry passing verifier evidence bound to the repository state they describe. [BeforeDone DOI](https://doi.org/10.5281/zenodo.21766277)
- **[Thin Harness, Strong Contracts](https://github.com/rrrrrredy/agent-harness-paper)** (2026, preprint). A production-oriented study of agent harnesses as runtime, permission, state, replay, memory, evaluation, audit, and human-review infrastructure. [Thin Harness DOI](https://doi.org/10.5281/zenodo.20907471)
- **[SkillOps: A Practical Framework for Designing, Testing, and Operating Modular Skills in Personal AI Agents](https://github.com/rrrrrredy/skillops-paper)** (2026, paper and software artifact). A lifecycle framework for Skill contracts, tests, evaluation, versioning, safety, and operations. [SkillOps PDF](https://github.com/rrrrrredy/skillops-paper/blob/main/release/skillops-paper.pdf) · [SkillOps concept DOI](https://doi.org/10.5281/zenodo.20061198)

</details>

<details>
<summary><strong>Research and applied systems</strong></summary>

- **[Intent Formation](https://github.com/rrrrrredy/intent-loop):** a quiet Codex interaction layer that continues clear tasks and uses one focused question, concrete comparison, or small sample before a costly divergent choice. It includes an optional local State companion and a DeepSeek Harness adapter; the paired 80-task efficacy study has not run, so the beta makes no claim that it reduces rework or improves final results. [Intent Formation verification report](https://github.com/rrrrrredy/intent-loop/blob/main/docs/verification-report.md) · [Intent Formation prerelease](https://github.com/rrrrrredy/intent-loop/releases/tag/v0.2.0-beta.5)

- **Agent Run Evidence Toolkit:** independent repositories for retaining observable runs, evolving instructions, creating resettable scored workflow Cases, and exchanging portable evidence. [Runtime Evolution Workbench](https://github.com/rrrrrredy/runtime-evolution-workbench) · [Workflow Environment Factory](https://github.com/rrrrrredy/workflow-environment-factory) · [RunCase Interchange](https://github.com/rrrrrredy/runcase-interchange) · [DeepSeek RunCase adapter](https://github.com/rrrrrredy/deepseek-harness-runcase-adapter)
- **[Agent Memory System](https://github.com/rrrrrredy/agent-memory-system):** local-first, cross-agent memory with reviewed, redacted, portable outputs. [Agent Memory live site](https://rrrrrredy.github.io/agent-memory-system/) · [Agent Memory on Hugging Face](https://huggingface.co/spaces/RedinGhost/agent-memory-system)
- **[Context Continuity](https://github.com/rrrrrredy/context-continuity):** preserves task invariants across compaction, resume, and handoff without treating reconstructed context as user authority.
- **Completion and execution reliability:** fresh, file-bound completion evidence plus contract checks before high-impact actions. [BeforeDone](https://github.com/rrrrrredy/beforedone) · [Execution Fidelity Guard](https://github.com/rrrrrredy/execution-fidelity-guard) · [DeepSeek execution adapter](https://github.com/rrrrrredy/dsh-execution-fidelity-guard)
- **Skill lifecycle and safety:** an evidence-gated path from selected runs to one reviewable Skill change, paired with static scanning for risky Skill content and archives. [Experience to Skill](https://github.com/rrrrrredy/experience-to-skill) · [Skill Security Guard](https://github.com/rrrrrredy/skill-security-guard)
- **[Industry Research Framework](https://github.com/rrrrrredy/industry-research-framework):** an agent-agnostic workflow for source-backed industry research, claim discipline, staged drafting, adversarial review, and publication cleanup. [Read the framework](https://rrrrrredy.github.io/industry-research-framework/framework.html#fullmd)

</details>

**Working approach:** Bind important claims to observable evidence. Use deterministic checks for deterministic behavior and model evaluations where behavior is stochastic. Keep sensitive raw evidence local; publish reviewed, redacted, reproducible artifacts, including real failures and user corrections.

**Stack:** Go · Python · TypeScript · JavaScript · Shell · HTML/CSS
