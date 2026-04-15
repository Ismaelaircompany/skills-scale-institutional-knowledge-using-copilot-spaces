# OctoAcme Role Interaction & RACI Matrix

Use this artifact with the [Roles & Personas](./octoacme-roles-and-personas.md) document to clarify accountability and handoffs.

## RACI Matrix (key project activities)

| Activity | Product Manager | Project Manager | Developer | Scrum Master / Agile Delivery Lead | UX Designer | Business Analyst | DevOps / Platform Engineer | QA Lead / Test Engineer |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Define problem statement and success metrics | A | C | I | I | C | R | I | I |
| Prioritize backlog and scope | A | C | C | C | C | R | I | C |
| Plan sprint / iteration commitments | C | A | R | R | I | C | I | C |
| Define acceptance criteria | A | C | C | I | C | R | I | R |
| Execute implementation | I | C | A/R | C | C | I | C | C |
| Manage CI/CD and environments | I | C | C | I | I | I | A/R | C |
| Validate quality and release readiness | C | C | C | I | I | I | C | A/R |
| Communicate delivery status and risks | C | A/R | I | C | I | C | I | C |
| Run retrospective and track improvements | C | A | C | R | I | C | I | C |

## Ceremony ownership and participation

| Ceremony / Touchpoint | Owner | Required Participants | Output |
| --- | --- | --- | --- |
| Project kickoff | Project Manager | Product Manager, Scrum Master / Agile Delivery Lead, Developers, Business Analyst, UX Designer | Agreed scope, timeline, risks, owners |
| Backlog refinement | Product Manager | Business Analyst, Developers, QA Lead, UX Designer, Project Manager | Prioritized and clarified backlog |
| Sprint planning | Scrum Master / Agile Delivery Lead | Project Manager, Product Manager, Developers, QA Lead | Sprint goal and committed items |
| Daily standup | Scrum Master / Agile Delivery Lead | Developers, Project Manager, QA Lead | Blockers surfaced and resolved path |
| Weekly status/risk sync | Project Manager | Product Manager, Scrum Master / Agile Delivery Lead, Business Analyst, QA Lead, DevOps / Platform Engineer | Updated status, risks, decisions |
| Release readiness review | Project Manager | QA Lead, DevOps / Platform Engineer, Developers, Product Manager | Go/no-go decision and release plan |
| Sprint review/demo | Product Manager | Developers, Project Manager, QA Lead, Stakeholders | Feedback and acceptance signals |
| Retrospective | Scrum Master / Agile Delivery Lead | Project Manager, Product Manager, Developers, QA Lead | 2–3 owned improvement actions |
