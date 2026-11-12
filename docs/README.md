# OctoAcme Project Management Docs

This documentation describes OctoAcme’s lightweight approach to delivering cross-functional projects, from validating an idea through release and continuous improvement. The lifecycle begins with initiation and stakeholder alignment, then moves into planning scope, backlog, milestones, risks, and dependencies. Teams execute iteratively, track progress and quality, release with verification and rollback plans, and use retrospectives to turn lessons into improvements.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md) — lifecycle, principles, roles, and key artifacts.
- [Project Initiation Guide](octoacme-project-initiation.md) — validate the need, align stakeholders, define success, and decide whether to proceed to planning.
- [Project Planning](octoacme-project-planning.md) — shape the backlog, estimates, Definition of Done, milestones, risks, and dependencies.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — team rhythm, project-board workflow, pull requests, quality checks, reporting, and blocker escalation.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — maintain the risk register, communicate status, and escalate issues.
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — release readiness, deployment verification, rollback, incident response, and release notes.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — capture learnings and track improvement actions after sprints, releases, milestones, or incidents.
- [Roles & Personas](octoacme-roles-and-personas.md) — responsibilities and communication patterns for developers, product managers, and project managers.

## How the Team Works

The Project Manager coordinates delivery, schedules, risks, and communication; the Product Manager defines outcomes, priorities, and success measures; developers build and test increments; QA validates quality and acceptance; and stakeholders provide input and approvals. The team plans prioritized work with clear acceptance criteria, tracks it through the project board, and favors small pull requests linked to issues.

Regular standups and delivery syncs surface progress, blockers, and dependencies; PM–Product Manager alignment and stakeholder updates keep decisions and status visible. Risks are reviewed regularly and escalated from the team through the PM and Product Lead to the sponsor when needed. Quality is supported through unit and applicable integration tests, CI checks for tests, lint, and security, code review, and manual QA where appropriate. Releases require acceptance criteria and checks to pass, plus release notes, smoke tests, and a rollback or mitigation plan; post-deployment verification and retrospectives help the team learn and improve.
