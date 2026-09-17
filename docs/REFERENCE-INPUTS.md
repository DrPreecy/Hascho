# User reference inputs

These references express desired qualities and coverage. They are not architectures to copy literally.

## Company Building Operating System process architecture

Source: Company_Building_Operating_System_Prozessarchitektur.pdf, supplied by the Project Owner.

What matters:

- a visible transformation from an early starting point to an operational outcome;
- an understandable order of major steps;
- clarity about what each step needs and produces;
- gates and feedback paths that prevent activity from being mistaken for progress;
- a roadmap that helps the owner understand where they are and what comes next.

Required adaptation:

- remove the insurance-specific subject matter;
- do not assume every project is a company, startup, or software product;
- preserve the transformation logic while making content, depth, and optional modules project-dependent;
- allow parallel work, iteration, pausing, rejection, and return paths;
- separate lifecycle orientation from active work loops and evidence status.

This is a process-architecture reference, not a mandate to copy its stages word for word.

## Software Engineering Roadmap infographic

Source: Software Engineering Roadmap Infographic.png, supplied by the Project Owner.

Purpose: thematic orientation for software-containing projects.

It is not:

- a learning tracker that runs beside every project;
- a mandatory curriculum;
- a fixed project sequence;
- a claim that every software project needs every topic;
- a separate roadmap that the future tool must manage.

Themes shown in the reference:

1. Browser and web fundamentals: DevTools, HTTP, HTML and CSS where needed.
2. Language fundamentals: state, functions, objects, arrays, modules, errors, asynchronous work, fetching, and debugging.
3. Developer workflow and typed code: package tooling, Git and GitHub, branches and pull requests, types, refactoring, and code structure.
4. Backend and domain logic: APIs, validation, business rules, error handling, and authentication basics.
5. Data modeling and relational databases: entities, relationships, constraints, SQL, joins, transactions, and indexes.
6. Frontend engineering: components, state, forms, user flows, data fetching, and loading and error states.
7. Full-stack product slices: contracts, permissions, search, pagination, audit trails, and end-to-end UX.
8. Testing and quality: unit, integration, API, end-to-end and regression tests, including failure modes.
9. Security engineering: threat modeling, trust boundaries, validation, authorization, OWASP basics, and secrets.
10. Systems and networking: Linux, processes, memory, filesystems, TCP, DNS, TLS, ports, and concurrency basics.
11. Software architecture: C4, ADRs, boundaries, modularity, synchronous and asynchronous work, queues, failure isolation, and trade-offs.
12. Delivery and reliability: containers, CI and CD, environments, metrics, traces, logs, incidents, and postmortems.
13. AI engineering: model APIs, structured outputs, tools, retrieval, agents and workflows, human-in-the-loop, evaluations, and AI security.
14. Product engineering: workflow observation, stakeholders, requirements, user flows, success criteria, prioritization, and iteration.
15. Optional specialization based on the project.

How the workbench should use it:

- as a coverage checklist during research, planning, architecture review, and implementation planning for software modules;
- filtered by actual project needs, risk, and architecture;
- connected to requirements and tasks only when relevant;
- never displayed as progress merely because a topic was mentioned;
- never used to force technology or unnecessary complexity.

The reference also suggests a useful quality pattern: work should be explainable, recognizable in real systems, buildable at minimal scale, debuggable, and integrable. Research whether this can become a proportional review lens rather than a universal five-step gate.

## Quality-of-life expectations

The Project Owner expects the workbench to provide an active guidance layer comparable to the useful parts of modern coding agents:

- visible current plan and implementation plan when appropriate;
- a clear next action;
- suggested actions or prompts;
- actionable to-dos;
- separation of tasks, questions, decisions, risks, and experiments;
- progress and blocker visibility;
- easy pause, handoff, and resume;
- contextual explanations;
- review and verification guidance;
- protection against losing intent between sessions.

These features support the owner. They do not authorize autonomous decisions or execution.

## Anti-vibe-coding expectation

For software projects, AI assistance must not become unreviewed code generation. The workbench needs proportional guardrails for intent, scope, architecture, security, tests, evidence, review, and explanation. Candidate rules are recorded in docs/ANTI-VIBE-CODING.md.
