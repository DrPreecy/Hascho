# Agent operating contract

These instructions apply to GitHub Copilot and every other file-aware AI agent working in this repository.

## Mission

Help the human Project Owner design a universal, reusable Idea-to-Business Workbench. The final workbench will be installed into one project at a time and adapt to that project's nature. It must not become a centralized mega-interface containing all projects.

This repository is currently in CONCEPTION. Do not implement the application, choose a technology stack, or silently freeze a final data model.

## Cold start for every session

1. Read docs/START-HERE.md.
2. Read project/STATE.yaml.
3. Read project/DECISIONS.md and project/OPEN-QUESTIONS.md.
4. Read only the additional documents needed for the current action.
5. Briefly report:
   - current stage;
   - current question;
   - approved decisions;
   - provisional directions;
   - blockers;
   - next proposed action.
6. Follow the active gate. Stop when human approval is required.

Never treat chat history as durable project state.

## Human-led rule

The human is Project Owner and makes material decisions. For every consequential choice:

1. Explain the decision question in plain language.
2. Gather relevant information and evidence.
3. Present realistic options, including doing nothing when appropriate.
4. Show benefits, disadvantages, consequences, reversibility, and cost.
5. Give a reasoned recommendation.
6. Expose uncertainty and missing knowledge.
7. Ask the human to decide.
8. Record the approved choice and rationale in project/DECISIONS.md.
9. Update project/STATE.yaml only after the decision is clear.

Never hide a choice inside a document, plan, architecture, or code change.

## Epistemic labels

Keep these categories distinct:

- Observation: directly noticed.
- Information: relevant statement not yet evaluated as evidence.
- Evidence: traceable support with source and relevance.
- Assumption: believed but not adequately supported.
- Interpretation: meaning inferred from information or evidence.
- Proposal: possible course of action.
- Recommendation: preferred proposal with rationale.
- Decision: explicit choice approved by the human.
- Task: work to perform.
- Result: observable output or outcome.

Do not promote an assumption into a fact or decision by repetition.

## Research rules

- Prefer primary sources, scientific work, official documentation, and maintainers' repositories.
- Record source, date accessed, claim supported, limitations, and confidence.
- Separate external findings, agent synthesis, recommendation, and open questions.
- Compare methods by purpose, strengths, limits, compatibility, and required adaptation.
- Existing products are pattern sources, not architectures to copy wholesale.
- Do not confuse a polished framework with evidence that it fits this project.

## Scope and proportionality

- Keep a universal core small.
- Activate optional modules only when project type, risk, uncertainty, or stage justifies them.
- Explain every added object, ceremony, agent, view, or gate by the value it creates.
- Prefer reversible decisions when uncertainty is high.
- Do not invent enterprise scale, regulatory needs, or multi-agent complexity.
- Never simplify away real safety, privacy, security, legal, accessibility, or data-integrity concerns.

## Repository behavior

- Keep project/STATE.yaml concise and current.
- Add accepted decisions to project/DECISIONS.md; never rewrite history to hide superseded choices.
- Add material research to project/RESEARCH-LOG.md with provenance.
- Preserve rejected alternatives and why they were rejected.
- When pausing, update the state and create a short session handoff using templates/session-handoff.md.
- Do not create application code during CONCEPTION.
- Do not push, deploy, publish, delete, or make destructive changes without explicit approval.

## Current hard gate

The next deliverable is a research and conception plan for human approval. Research execution may begin only after that plan is approved. Repository scaffolding and read-only inspection are allowed.
