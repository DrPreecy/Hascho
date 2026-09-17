# Anti-vibe-coding guardrails

Status: candidate requirements to research, test, and refine before implementation.

Purpose: allow AI-assisted development without losing intent, understanding, security, maintainability, or human control.

## Intent before code

- No feature code without a clear problem, scope, and acceptance conditions appropriate to its risk.
- Separate exploratory prototypes from production work.
- Record material assumptions instead of embedding them silently.
- Do not invent requirements merely to keep coding.

## Inspect before changing

- Read relevant project state, existing code, conventions, tests, and architecture records first.
- Reuse repository-native patterns before adding abstractions or dependencies.
- Identify affected boundaries, data, permissions, integrations, and failure modes.
- Surface ambiguity when it can materially change behavior or architecture.

## Plan proportionally

- Use a visible implementation plan for non-trivial work.
- Break work into bounded, reviewable, reversible changes.
- Explain dependencies, migrations, risks, and verification.
- Do not create enterprise machinery for hypothetical scale.

## Build understandable systems

- The owner must be able to request a plain-language explanation of behavior, structure, and trade-offs.
- Prefer clear code and explicit contracts over cleverness.
- Add comments for reasoning and constraints, not to restate code.
- Architecture decisions with lasting consequences require a recorded decision.

## Verify claims

- A successful build is not proof that behavior is correct.
- Test against acceptance conditions and real failure modes at proportional depth.
- Never fabricate test results, reviews, logs, screenshots, or tool output.
- Distinguish static checks, automated tests, manual verification, security review, and observed production behavior.
- State what was not tested.

## Security and data integrity

- Derive trust boundaries from actual inputs, identities, permissions, persisted data, secrets, payments, external calls, and destructive operations.
- Validate at boundaries and enforce authorization server-side where applicable.
- Do not expose secrets or sensitive data in prompts, logs, fixtures, or commits.
- Require explicit approval for destructive actions, deployments, publication, remote changes, or irreversible migrations.

## Review and completion

- Review the complete change against the approved scope, not only individual snippets.
- Track findings and prevent unresolved critical issues from being declared complete.
- Update documentation, state, decisions, and handoff information when behavior changes.
- Completion requires evidence; confidence must match what was actually checked.

## Human control

- AI may recommend but must expose material choices.
- The Project Owner approves consequential product and architecture decisions.
- Automation must stop on unapproved scope expansion, unclear destructive action, failed safety gates, or conflicting evidence.
- Provider convenience must not become hidden project policy.

## Open design question

Determine which rules are universal, which belong only to software modules, and which should become configurable gates based on risk.
