# OctoAcme Project Management Docs

## Welcome!

This folder contains all the process documentation for how OctoAcme manages projects. Whether you're starting a new project, planning a release, or looking to understand our roles and processes, you'll find the guidance you need here.

## Quick Navigation

### Core Process Documentation

- [Project Management Overview](./octoacme-project-management-overview.md) — Start here for a high-level introduction to our approach, principles, and key artifacts.
- [Project Initiation Guide](./octoacme-project-initiation.md) — Steps to validate, authorize, and kickoff a new project.
- [Project Planning](./octoacme-project-planning.md) — How to scope, schedule, and resource a project.
- [Execution and Tracking](./octoacme-execution-and-tracking.md) — Managing day-to-day delivery, sprints, and progress.
- [Risks and Communication](./octoacme-risks-and-communication.md) — Identifying risks, escalating issues, and keeping stakeholders informed.
- [Release and Deployment](./octoacme-release-and-deployment.md) — Preparing for and executing a release.
- [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings and driving improvement.
- [Roles and Personas](./octoacme-roles-and-personas.md) — Understanding team roles and responsibilities.

## OctoAcme Project Management Principles

Our approach is built on five core principles:

1. **Customer-first**: We prioritize customer value and usability in every decision.
2. **Iterative delivery**: We deliver small, testable increments rather than waiting for big-bang releases.
3. **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead who own outcomes.
4. **Data-informed decisions**: We measure impact and iterate based on evidence, not assumptions.
5. **Psychological safety**: We encourage feedback, questions, and learning from mistakes.

## Project Lifecycle

All OctoAcme projects follow a consistent five-phase lifecycle:

1. **Initiation** — Define the problem, align stakeholders, and create a project one-pager.
2. **Planning** — Scope the work, assign resources, and set milestones.
3. **Execution** — Build, test, review, and iterate in short cycles.
4. **Release** — Deploy to production and verify success.
5. **Close & Retrospective** — Capture learnings and define next steps.

## OctoAcme Project Management Overview

OctoAcme operates on a structured five-phase project lifecycle—Initiation, Planning, Execution, Release, and Close & Retrospective—designed to deliver customer value iteratively while maintaining clear ownership and accountability. The approach is grounded in five core principles: customer-first prioritization, iterative delivery of small testable increments, clear role-based ownership, data-informed decision-making, and psychological safety. This framework ensures that projects are both strategically aligned and operationally executable, with each phase building on validated decisions from the previous one.

### Key Workflows and Execution Model

During **Initiation**, teams validate business needs by creating a lightweight Project One-pager that captures the problem statement, measurable success metrics, stakeholders, and initial resource requirements. Once stakeholder alignment is confirmed, the project moves into **Planning**, where work is broken into prioritized backlog items with clear acceptance criteria, dependencies are mapped, and a Definition of Done is established. **Execution** follows a regular cadence—daily standups, twice-weekly delivery team syncs, and weekly PM–Product Manager alignment—using GitHub Projects to track work through columns (Backlog, Ready, In Progress, In Review, QA, Done). Teams maintain a risk register for tracking and escalating blockers through three escalation levels: team-level triage, PM escalation to Product Lead, and sponsor-level involvement for business-critical issues.

### Roles, Communication, and Quality Assurance

OctoAcme defines clear ownership across core roles: the **Project Manager** coordinates delivery and manages risks; the **Product Manager** defines outcomes and prioritizes the backlog; **Developers** implement features and write tests; **QA/Testing** validates acceptance criteria; and **Stakeholders** provide inputs and approvals. Communication happens through a consistent cadence—weekly syncs between PM and Product Manager, twice-weekly standups, and monthly stakeholder updates—complemented by a risk register and status templates that maintain transparency. Quality assurance is embedded throughout the lifecycle: unit and integration tests are required for new logic, automated CI/CD runs security scans and linting before PRs are reviewed, smoke tests validate critical flows before release, and manual QA confirms feature acceptance. After each release or sprint, teams conduct retrospectives to capture learnings, prioritize 2–3 improvement actions, and measure the impact of changes—closing the loop on continuous improvement and building institutional knowledge.

## Key Roles

- **Project Manager (PM)** — Coordinates delivery, manages schedule and risks, drives communications.
- **Product Manager (PdM)** — Defines outcomes, prioritizes work, and measures success.
- **Developers** — Implement features and collaborate on design and testability.
- **QA/Testing** — Validates quality and acceptance criteria.
- **Stakeholders** — Provide inputs, feedback, and approvals.

## Communication Cadence

- Weekly sync between PM and Product Manager
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## Getting Started

**New to OctoAcme projects?** Start with the [Project Management Overview](./octoacme-project-management-overview.md), then dive into the specific phase guides as needed.

**Managing a project?** Bookmark this README and refer to the appropriate phase guide throughout your project.

## Contributing to These Docs

To suggest updates or additions to the OctoAcme project management documentation, please use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.
