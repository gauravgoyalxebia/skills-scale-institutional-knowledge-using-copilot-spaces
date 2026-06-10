# OctoAcme Project Management Process Docs

Welcome! This folder centralizes OctoAcme’s project management guidance so contributors and stakeholders can quickly find processes, templates, and onboarding materials. The docs emphasize an iterative, customer-first approach and provide clear roles, artifacts, and checklists to help teams plan, deliver, and improve reliably.

## Brief Overview of Our Processes
OctoAcme runs projects through a lightweight, gated lifecycle: Initiation → Planning → Execution → Release → Retrospective. Initiation uses a one‑pager to confirm the problem, success metrics, stakeholders, and an initial timeline. Planning turns approved work into a prioritized backlog with clear acceptance criteria, estimates, and dependencies. Execution is iterative with small, reviewable PRs, CI checks, and a project board to visualize flow. Releases follow a checklist with smoke tests and rollback plans, and retrospectives capture action items that feed back into the backlog for continuous improvement.

We place strong emphasis on role clarity and communication cadence: named Project Manager and Product Lead, developers and QA with explicit responsibilities, daily standups, weekly delivery syncs, regular demo/review sessions, and monthly stakeholder updates. Quality is enforced through unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA as required. Risk management is handled via a simple risk register (impact, likelihood, owner, mitigation) and a clear escalation path from team → PM → Product Lead → Sponsor.

## Documentation Index
- [Project Management Overview](./docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](./docs/octoacme-project-initiation.md)
- [Project Planning](./docs/octoacme-project-planning.md)
- [Execution & Tracking](./docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./docs/octoacme-roles-and-personas.md)

## How to use this README (onboarding tips)
- Read the Project Management Overview for a quick orientation.
- Use the Project Initiation and Planning docs when starting new initiatives.
- Follow Execution & Tracking during sprints to align on workflows and CI requirements.
- Use the Release & Deployment guide when preparing releases and the Retrospective doc to capture improvements.
- Add updates via the GitHub issue template: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml

## Contact / Ownership
Maintainers: Project Manager and Product Lead defined per-project (see each project’s README). If you find gaps or want to propose changes, create an issue using the “Add Content to Project Management Process Docs” template.
