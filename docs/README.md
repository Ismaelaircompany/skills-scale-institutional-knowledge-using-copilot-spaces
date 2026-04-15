# OctoAcme Project Management Docs

OctoAcme uses a lightweight project lifecycle to keep delivery predictable and iterative: **Initiation → Planning → Execution → Release → Close/Retro**. Initiation captures a one-pager/charter, stakeholders, success metrics, a high-level timeline, and initial risks. Planning turns that into an actionable backlog with acceptance criteria, estimates, a clear Definition of Done, dependency tracking, and milestone-based release planning.

Execution is managed through a project board workflow and small pull requests linked to issues and acceptance criteria. Teams rely on CI checks, peer reviews, and regular demos to keep quality and visibility high while work is in progress. Release follows a standard checklist: staging deployment and smoke tests, production deployment, post-deploy verification, stakeholder communication, and rollback readiness if needed.

Delivery is supported by clear roles: the **Project Manager** coordinates schedule, risks, and communications; the **Product Manager/Product Lead** owns outcomes, prioritization, and success metrics; **Developers** build, test, and review; **QA/Testing** validates acceptance criteria; and **Stakeholders/Sponsors** provide key inputs and approvals. Communication cadence includes standups, weekly delivery syncs, and sprint/milestone demos, with weekly status updates (progress, next steps, risks, asks), a single source of truth, and escalation from Team → PM → Product Lead → Sponsor.

Quality assurance is built into each phase through small reviewable PRs, CI tests/lint/security scans, unit and integration tests, and end-to-end smoke tests before release, with manual QA as needed. Releases include a checklist and rollback plan, and retrospectives produce owned action items for continuous improvement.

## Process Documents

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risks & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)
