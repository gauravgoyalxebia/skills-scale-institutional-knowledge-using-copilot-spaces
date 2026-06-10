# Role Responsibilities & Handoffs

Purpose: Provide clear, actionable handoff steps and responsibility checklists to reduce ambiguity during planning, delivery, and release.

## Responsibility Checklist (per role)
- Role:
- Owner:
- Primary responsibilities (bulleted):
- Key artifacts owned (e.g., design spec, runbook, test plan):
- Acceptance / Exit criteria:
- Typical contacts for questions:

## Standard Handoff Flows

1. Idea → Planning
   - Product drafts one-pager and success metrics.
   - BA (if assigned) clarifies requirements and produces draft user stories.
   - Design Lead produces or comments on early wireframes.
   - PM schedules kickoff.

2. Planning → Implementation
   - Developers review acceptance criteria and estimate.
   - QA Lead drafts test plan linked to ticket.
   - DevOps reviews deployment constraints if infra changes are needed.
   - Owner confirms DoD before work starts.

3. Implementation → Release
   - QA completes testing and signals "QA Ready".
   - DevOps runs staging deploy and smoke tests.
   - Product confirms acceptance criteria met and signs off.
   - PM coordinates release window and communications.

## Handoff Checklist (example)
- [ ] Acceptance criteria documented in ticket
- [ ] Design assets attached and versioned
- [ ] Test plan linked
- [ ] Deployment/infrastructure changes listed
- [ ] Rollback plan / runbook present
- [ ] Stakeholder sign-off recorded

## Suggested reporting fields for PRs
- Design sign-off: @design-lead
- QA checklist status: [automated coverage / manual tests]
- Deployment changes included: yes/no + link to IaC PR
- Rollback steps included: yes/no + link
