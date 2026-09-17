# Hascho — Universal Project Workbench

Hascho is the development repository for a reusable, project-local workbench that helps one human turn an early thought into a researched, decided, built, operated, and learnable project.

The intended result is not one giant interface containing every project. The finished workbench will be copied or installed into each individual project repository. Every project keeps its own state and adapts the workbench to its type, risk, maturity, and needs while preserving a stable universal core.

## Current status

This repository is currently a conception workspace, not the finished workbench and not an application.

The immediate job is to research, design, challenge, and approve the method before choosing a software architecture or technology stack.

Start with [docs/START-HERE.md](docs/START-HERE.md).

## Core idea

- Human-led, AI-supported.
- File-backed state survives chats, models, and providers.
- Universal core plus conditionally activated modules.
- One project per repository or workspace.
- Adaptive loops and gates instead of a rigid questionnaire.
- Evidence, assumptions, recommendations, and decisions remain visibly distinct.
- Visual orientation is important, but no single visualization must do every job.
- Complexity must earn its place by improving decisions, reducing uncertainty, preserving knowledge, exposing risk, easing work, raising quality, securing continuity, or enabling progress.

## Repository map

| Path | Purpose |
| --- | --- |
| [AGENTS.md](AGENTS.md) | Cross-agent operating contract |
| [.github/copilot-instructions.md](.github/copilot-instructions.md) | GitHub Copilot entry instructions |
| [docs/PRODUCT-BRIEF.md](docs/PRODUCT-BRIEF.md) | Authoritative product intent and boundaries |
| [docs/WORKING-MODEL.md](docs/WORKING-MODEL.md) | Current hypotheses for the adaptive workbench |
| [docs/RESEARCH-PLAN.md](docs/RESEARCH-PLAN.md) | Plan Copilot must refine and present for approval |
| [docs/REFERENCE-INPUTS.md](docs/REFERENCE-INPUTS.md) | Interpretation of the supplied process and software references |
| [docs/QUALITY-OF-LIFE.md](docs/QUALITY-OF-LIFE.md) | Guidance-layer, planning, to-do, prompt, and resume requirements |
| [docs/ANTI-VIBE-CODING.md](docs/ANTI-VIBE-CODING.md) | Candidate safeguards for responsible AI-assisted software work |
| [docs/DELIVERABLES-AND-GATES.md](docs/DELIVERABLES-AND-GATES.md) | Required outputs and approval gates |
| [project/STATE.yaml](project/STATE.yaml) | Machine-readable current project state |
| [project/DECISIONS.md](project/DECISIONS.md) | Human-approved decisions and provisional directions |
| [project/OPEN-QUESTIONS.md](project/OPEN-QUESTIONS.md) | Questions that can materially change the design |
| [project/RESEARCH-LOG.md](project/RESEARCH-LOG.md) | Sources, findings, synthesis, and gaps |
| [templates/](templates) | Small records for assumptions, evidence, decisions, and handoffs |

## Start with GitHub Copilot

Ask Copilot:

> Read AGENTS.md and docs/START-HERE.md. Reconstruct the current state from the repository. Then run the next action from project/STATE.yaml. Do not implement software or choose a stack.

Chat history is not the source of truth. Accepted state belongs in this repository.
