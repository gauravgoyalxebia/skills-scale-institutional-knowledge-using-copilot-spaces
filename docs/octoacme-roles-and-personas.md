# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Quality Assurance (QA) / Testing

### Role Summary
QA/Testing focuses on validating product quality through test strategies, automated and manual testing, and acceptance verification.

### Responsibilities
- Define test plans and acceptance criteria verification
- Implement or coordinate automated test suites
- Perform exploratory and manual testing when needed
- Work with developers to reproduce and prioritize defects

### Goals
- Ensure releases meet quality and acceptance criteria
- Reduce production defects and customer-impacting regressions
- Improve test coverage and test reliability

### Typical Communication
- QA reports in weekly syncs
- Test status in PRs and release notes
- Coordination with Developers and Product on acceptance

---

## New / Expanded Personas

The following personas are proposed additions to make responsibilities and handoffs explicit. Each has a short summary, responsibilities, and how they typically interact with existing roles.

### Design Lead

Role summary
- Owns the design vision and experience coherence across features.

Responsibilities
- Define UX/UI direction and component-level specifications for features.
- Produce or approve wireframes, mockups, and interaction specs.
- Ensure accessibility and usability requirements are captured in acceptance criteria.
- Collaborate with Product to trade off design scope and delivery timelines.

Interactions
- Works closely with Product Managers to translate goals into user flows.
- Reviews PRs and prototypes with Developers and QA to ensure design intent is preserved.
- Participates in sprint planning for design-ready tickets.

Why it helps
- Reduces rework due to missed UX requirements, clarifies acceptance criteria, and speeds handoffs between design and engineering.

---

### DevOps / Platform Engineer

Role summary
- Owns CI/CD, infra-as-code, deployment automation, observability, and production reliability.

Responsibilities
- Maintain and improve CI/CD pipelines, deployment automation, and infrastructure configuration.
- Define runbooks, deployment procedures, and rollback strategies.
- Collaborate on performance, availability, and security improvements.
- Support incident response and post-incident analysis.

Interactions
- Works with Developers to ensure production-safe deployments and test environments.
- Collaborates with Project Managers on deployment windows and release planning.
- Engages with QA for staging and smoke-test orchestration.

Why it helps
- Stabilizes deployments, shortens mean time to recovery, and clarifies ownership for production concerns and release readiness.

---

### Quality Assurance (QA) Lead

Role summary
- Coordinates testing strategy and ensures test coverage for releases.

Responsibilities
- Define overall test approach (automation vs. manual), entry/exit criteria, and release test scope.
- Coordinate QA resources, triage test failures, and track quality metrics.
- Mentor testers and support test automation efforts.

Interactions
- Works with Developers for testability and flaky test reduction.
- Partners with Product to ensure acceptance criteria map to test cases.
- Reports quality indicators to PM/PdM and flags release risks.

Why it helps
- Strengthens test planning, makes quality visibility clearer, and prevents quality regressions pre-release.

---

### Business Analyst (BA)

Role summary
- Bridges the gap between stakeholders, product, and engineering for complex requirements.

Responsibilities
- Elicit and refine business requirements into clear user stories and acceptance criteria.
- Model workflows, data flows, and edge cases.
- Maintain traceability between business needs and delivered functionality.

Interactions
- Works with Product to decompose initiatives and clarify scope.
- Engages Developers and QA early to clarify ambiguous requirements.
- Coordinates stakeholder reviews and documentation updates.

Why it helps
- Reduces ambiguity, speeds clarification cycles, and helps avoid scope creep by codifying stakeholder expectations.

---

## How to use these personas

- For each project or major feature, list primary and secondary role owners.
- Add role-specific acceptance criteria or checklist items to tickets (e.g., "Design sign-off", "DevOps deployment config reviewed", "QA test plan linked").
- Use role-onboarding and handoff templates (see docs/role-onboarding-and-raci-template.md and docs/role-responsibilities-and-handoffs.md).

---
