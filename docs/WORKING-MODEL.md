# Working model — hypotheses, not final architecture

This document captures the current direction so the conception process has a starting point. Items here remain subject to research and human approval.

## Stable universal core

A likely core includes:

- project identity and purpose;
- current context and next action;
- questions and work threads;
- assumptions and uncertainty;
- evidence with provenance;
- alternatives and decisions;
- tasks, artifacts, outcomes, and learning;
- human approval boundaries;
- pause and resume state;
- change and invalidation tracking.

The core should remain small and project-type neutral.

## Conditional modules

Possible modules include user discovery, market research, business modeling, product or service design, brand, technical feasibility, software delivery, legal, privacy, security, finance, go-to-market, launch, operations, and scaling.

Activation should depend on the project's intended outcome, uncertainty, risk, dependencies, and current decision. A module is not active merely because it exists.

## Three separate dimensions

Do not collapse these into one progress percentage:

1. Lifecycle orientation: broadly where the project is headed.
2. Active work loops: what kind of thinking or execution is happening now.
3. Epistemic and execution status: what is merely captured, investigated, supported, decided, validated, implemented, or measured.

## Project-local architecture

The desired distribution model is analogous to a file-backed workflow overlay:

- install or copy the base into a project;
- onboard it to the real project;
- preserve the universal contract;
- activate only relevant modules;
- keep state beside the project's own artifacts;
- allow different AI tools to read the same durable state.

This is a product direction, not yet a decided packaging mechanism.

## Transformation spine

A likely top-level orientation is a transformation spine: an understandable sequence from initial input to real-world outcome. It should communicate where the project is, what must become true next, and how work can loop back.

The spine must not contain industry-specific content and must not absorb all work into one linear status. Modules and work loops attach to it according to need.

## Software coverage reference

For software-containing projects, the supplied Software Engineering Roadmap acts as a thematic inventory. The system may use it to challenge omissions during planning or review, but not as a curriculum, progress tracker, or mandatory numbered sequence.

## Guidance layer

A likely cross-cutting layer provides:

- current context and next action;
- visible plan appropriate to the active work;
- differentiated work queue;
- suggested actions and optional provider-independent prompts;
- agent activity, approvals, checks, and results;
- handoff and resume support.

This layer helps the Project Owner navigate work. It must not make decisions or turn recommendations into actions without the required approval.

## Collaboration modes

The workbench should support three switchable collaboration modes:

1. **Auto:** AI completes an explicitly bounded and reversible activity independently, then provides a traceable report.
2. **Co-work:** human and AI complete a defined activity together through ongoing steering.
3. **Co-design:** human and AI iteratively form the problem, options, and artifacts before a recommendation is presented.

The selected mode changes the collaboration cadence, not the ownership model. Approval, provenance, security, and escalation requirements remain invariant. The exact default rules, scope level, and interface remain research questions.

## Anti-vibe-coding guardrails

When a software module is active, proportional guardrails should connect intent, requirements, implementation planning, architecture decisions, testing, security, review, and evidence. Candidate rules are in docs/ANTI-VIBE-CODING.md and remain subject to research and review.

## Visual Control Room

The preferred orientation experience is a visual Control Room showing current context, evidence health, decision pressure, open threads, risks, and next action.

It should link to specialized views rather than replace them. The canonical state should not depend on one visual interface.

## Preliminary architecture direction

The Project Owner selected direction D: an Adaptive Project Workbench, strengthened by the visual orientation benefits of a Control Room.

Status: provisional direction to research and refine. It is not permission to finalize implementation architecture.
