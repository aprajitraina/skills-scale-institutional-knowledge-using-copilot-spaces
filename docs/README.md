# OctoAcme Project Management Docs

## About OctoAcme Project Management
OctoAcme follows a customer-first, outcome-driven approach to project management focused on iterative delivery, clear ownership, and data‑informed decisions. We favor small, testable increments that deliver measurable value and iterate based on feedback and metrics.

## Process summary
Projects progress through a lightweight lifecycle: Initiation (one‑pager to validate need and success metrics), Planning (break work into shippable backlog items with acceptance criteria and a Definition of Done), Execution (daily standups, small PRs, CI-driven tests, and regular demos), Release (staging verification, automated deployment where possible, and post-deploy checks), and Retrospective (capture learnings and convert them into tracked action items). Risks are tracked in a simple register and reviewed regularly; escalation follows team → PM → Product Lead → Sponsor.

Quality is enforced through automated unit/integration/security checks in CI, size-bounded pull requests that include acceptance criteria and issue links, and manual QA or smoke tests for critical flows. Releases require passing CI, drafted release notes, rollback plans, and staged verification; incident handling uses an on-call notification and a blameless retrospective.

## Key roles
- Product Manager (PdM): defines outcomes, prioritizes backlog, measures success.
- Project Manager (PM): coordinates delivery, schedules, manages risks and communications.
- Developers: implement features, own tests and code quality.
- QA/Testing: validate acceptance criteria and run manual checks where needed.
- Stakeholders: provide input, approvals, and business context.

## Document index
Getting started
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

Project phases
- [Project Initiation](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)

Ongoing management
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

## Quick links
- All docs folder: https://github.com/aprajitraina/skills-scale-institutional-knowledge-using-copilot-spaces/tree/main/docs
- Issue templates: .github/ISSUE_TEMPLATE/
