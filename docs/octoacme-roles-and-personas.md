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

## QA / Test Engineers

### Role Summary
QA / Test Engineers validate that features meet acceptance criteria and quality standards before release.

### Responsibilities
- Define the test plan and QA approach during planning
- Validate acceptance criteria and run smoke and regression tests
- Report defects and quality status
- Sign off on quality before release

### Goals
- Catch defects early and prevent regressions
- Keep quality criteria clear and testable

### Interactions with Other Roles
- Developers: collaborate on testability, defect triage, and fixes
- Product Managers: clarify and confirm acceptance criteria
- Project Managers: report quality status and risks
- Release Managers: provide go/no-go quality sign-off

---

## Product Leads

### Role Summary
Product Leads own product direction across projects and make the decisions that move work through the initiation and escalation gates.

### Responsibilities
- Review the Project One-pager and approve moving into planning
- Align priorities across projects and stakeholders
- Act as the Level 2 escalation point for blockers
- Support Product Managers with prioritization trade-offs

### Goals
- Ensure work aligns with business strategy
- Resolve escalations quickly with clear decisions

### Interactions with Other Roles
- Product Managers: guide priorities and outcomes
- Project Managers: receive escalations and risk updates
- Sponsors: align on priority and business impact; escalate Level 3 issues

---

## Sponsors / Stakeholders

### Role Summary
Sponsors and Stakeholders provide business direction, approvals, and resources, and are kept informed of progress.

### Responsibilities
- Confirm the business need and approve priorities and resources
- Provide input at decision gates and reviews
- Decide on Level 3 (business-impacting) escalations
- Review milestone and status updates

### Goals
- Realize the expected business value
- Stay informed without being a bottleneck

### Interactions with Other Roles
- Project Managers: receive weekly or milestone updates and escalations
- Product Leads and Product Managers: consulted on priorities and outcomes
- Support: provide customer and business context

---

## Release Managers / DevOps Engineers

### Role Summary
Release Managers / DevOps Engineers own the pipelines and procedures that deploy changes safely to production.

### Responsibilities
- Maintain CI/CD pipelines and environments
- Schedule deployment windows and run staging and production deployments
- Execute post-deploy verification and rollbacks
- Prepare release notes and coordinate release announcements

### Goals
- Reliable, repeatable, low-risk releases
- Fast recovery when a deployment fails

### Interactions with Other Roles
- Developers: receive merged, release-ready changes and fix pipeline issues
- QA / Test Engineers: depend on their sign-off before release
- Project Managers: coordinate timing and stakeholder announcements
- Support: notify of releases and known issues

---

## Security Champions

### Role Summary
Security Champions advise on security risks and lead the response to security incidents.

### Responsibilities
- Review security scan results and security risks
- Advise on secure design and code review
- Follow the security incident runbook and act as Security on-call contact
- Help track security items in the risk register

### Goals
- Find and fix security issues before release
- Respond to incidents quickly and transparently

### Interactions with Other Roles
- Developers: consult during design and code review
- Project Managers: notified of incidents and risks
- Release Managers: confirm scans pass before release

---

## Support / Customer Success

### Role Summary
Support / Customer Success represent customers after release and relay feedback to the team.

### Responsibilities
- Prepare for releases using release notes and known issues
- Handle customer issues and escalate incidents
- Relay customer feedback and usage insights

### Goals
- Customers are informed and issues are resolved quickly
- Feedback reaches the team and informs priorities

### Interactions with Other Roles
- Release Managers: receive release announcements
- Product Managers: provide customer feedback for prioritization
- Developers and QA: report reproducible issues

---

## UX / Design

### Role Summary
UX / Design shapes usable, accessible experiences that meet customer needs.

### Responsibilities
- Conduct user research and usability validation
- Create flows, prototypes, and design specifications
- Support acceptance of the implemented design

### Goals
- Deliver intuitive, accessible experiences
- Reduce rework by validating designs early

### Interactions with Other Roles
- Product Managers: translate outcomes into designs
- Developers: hand off designs and review implementation
- QA: align on design acceptance criteria

---

## Scrum Masters / Delivery Facilitators (Optional)

### Role Summary
An optional role for teams that want dedicated facilitation of agile ceremonies and impediment removal.

### Responsibilities
- Facilitate standups, sprint planning, and retrospectives
- Remove team-level blockers (Level 1 escalation)
- Coach the team on process and continuous improvement

### Goals
- Predictable team flow and healthy team practices

### Interactions with Other Roles
- Project Managers: share facilitation and blocker triage, escalate Level 2 issues
- Developers and QA: support day-to-day process
- Product Managers: help keep the backlog ready for planning

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

