# OctoAcme Project Management Docs (README)

This README provides a concise overview of OctoAcme's project management processes and links to the full process documents stored in the docs/ folder. It is intended to improve discoverability for new team members and centralize links to the process artifacts.

OctoAcme follows an iterative lifecycle that moves work from initiation through planning, execution, release, and retrospective. Initiation captures the idea and produces a one-pager that defines the problem, goals, success metrics, stakeholders, and a high-level timeline. Planning breaks approved initiatives into a prioritized backlog with acceptance criteria, estimates, a Definition of Done, and a release plan.

Execution is managed with a project board (Backlog → Ready → In Progress → In Review → QA → Done), a pull request workflow that emphasizes small, reviewable changes, and a CI gate that runs tests, linting, and security scans before review. Releases follow pre-release checks, automated pipelines when available, smoke tests, and a documented rollback plan. Retrospectives capture what went well and action items, which are tracked and reviewed to drive continuous improvement.

Roles are defined to ensure clear ownership: Product Managers (vision, prioritization, success metrics), Project Managers (schedules, risks, communications), Developers (implementation, tests, reviews), QA (validation and acceptance), and Stakeholders (inputs and approvals). Communication cadence includes daily standups, weekly delivery syncs, sprint demos, and regular stakeholder updates. Quality assurance practices include unit and integration tests, end-to-end smoke tests for critical flows, CI security scans, and manual QA for feature acceptance when required.

Links to process documents:
- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risks & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)

If you prefer the README at the repository root instead, you can place a short root README that links to this docs/README.md for discoverability.
