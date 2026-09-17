# Quality-of-life and guidance layer requirements

Status: requirement input for research and conception.

Quality of life means more than visual polish or fewer clicks. It means the system actively reduces the mental work required to understand, start, continue, and verify responsible project work.

## Current Context

The workbench should make these immediately visible:

- what is being worked on;
- why it matters;
- the current question or objective;
- the accepted scope;
- the current stage and active work mode;
- what changed most recently;
- blockers, contradictions, and stale artifacts;
- the next sensible action;
- the next human decision.

## Plans

Depending on the stage, the workbench should be able to present:

- research plan;
- validation or experiment plan;
- project plan;
- implementation plan;
- review and verification plan;
- launch or operational plan.

A plan must show status, dependencies, assumptions, decision points, acceptance conditions, and updates caused by new evidence. A generated plan is a proposal until reviewed.

## Suggested Actions and Prompts

The workbench may suggest a small set of context-aware actions such as:

- continue the active thread;
- answer a blocking question;
- inspect evidence;
- compare alternatives;
- review a decision;
- create or refine a plan;
- run a check;
- pause safely.

It may also produce optional prompt text for the active AI tool. Prompts are an interaction convenience, not the product's source of truth. The underlying action, inputs, permissions, and expected output must remain understandable without a particular provider.

## Work Queue and To-dos

Do not flatten every open item into one to-do list. Distinguish:

- task;
- research question;
- decision needed;
- assumption to test;
- experiment;
- risk response;
- review;
- blocked item;
- follow-up or reminder.

Support focus views, low-energy work, deep work, quick capture, mobile sessions, and time-boxed sessions without changing the meaning of the underlying work.

## Handoffs and Resume

A resume view should reconstruct:

- last meaningful thought;
- last completed action;
- current state;
- changed context;
- unresolved threads;
- exact next action;
- files or evidence to read;
- decisions that may need revisiting.

Summaries must link back to underlying details and must not erase dissent, uncertainty, or rejected alternatives.

## Agent Visibility

When an agent is working, show or record:

- requested action;
- current scope;
- plan;
- files or artifacts affected;
- assumptions being used;
- approvals required;
- checks performed;
- result and remaining uncertainty.

## State language

The interface must distinguish captured, explored, researched, supported, decided, planned, implemented, verified, operated, and measured. Activity alone is not progress.

## Research questions

- Which elements belong in the universal core versus optional modules?
- What is the smallest useful Current Context view?
- How should prompt suggestions stay provider-independent?
- Which plan types can share a common structure?
- How should the system recommend work without creating an autopilot?
- Which agent activity is valuable to expose without overwhelming the user?
