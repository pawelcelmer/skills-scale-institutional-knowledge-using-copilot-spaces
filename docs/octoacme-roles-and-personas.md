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

## New / Cross-cutting Personas (proposed additions)

These roles are commonly needed across programs and help clarify ownership for cross-cutting responsibilities. Additions below include a short role summary, typical responsibilities, and how they interact with existing roles.

### Program Owner
- Role summary: Owns program-level outcomes across multiple projects; bridges strategy and delivery for a program of work.
- Responsibilities:
  - Define program success criteria and measurable outcomes
  - Coordinate cross-project priorities, budgets, and resource allocation
  - Own program-level risk register and mitigation decisions
  - Approve major timeline or scope shifts
- Interactions:
  - Works with Project Managers (PMs) to align schedules and resolve cross-project dependencies
  - Works with Product Managers (PdMs) on prioritization across the program
  - Communicates with Stakeholders and Sponsors about program status and funding

### Technical Lead
- Role summary: Senior engineer responsible for architecture and technical direction for a team or area.
- Responsibilities:
  - Propose and defend architecture and design approaches
  - Scope technical tasks and estimate effort
  - Ensure code quality, maintainability, and observability
  - Mentor engineers and guide technical onboarding
- Interactions:
  - Collaborates with Developers on design and implementation
  - Advises PM/PdM on technical trade-offs and effort
  - Works with QA to ensure test coverage and verification strategy

### UX Researcher
- Role summary: Leads user research and validation to inform product decisions and define acceptance criteria.
- Responsibilities:
  - Plan and run user research and usability sessions
  - Synthesize findings into actionable recommendations
  - Help define user-centered acceptance criteria and success metrics
  - Support prototyping and iterative validation
- Interactions:
  - Works with PdM on success metrics and research questions
  - Partners with Designers and Developers to translate findings into requirements
  - Shares results with Stakeholders and Product teams

### Security Engineer
- Role summary: Ensures security and compliance considerations are integrated into design, code, and operations.
- Responsibilities:
  - Conduct threat modeling and security reviews
  - Triage vulnerabilities and propose fixes or mitigations
  - Define security gates and compliance checks for releases
  - Advise on secrets management, access controls, and incident response
- Interactions:
  - Engages early with Technical Leads and Developers during planning
  - Works with Release Engineer to include security checks in CI/CD
  - Communicates risk and remediation timelines to PMs and PdMs

### Release Engineer
- Role summary: Owns release pipelines, deployment safety, and rollback procedures.
- Responsibilities:
  - Maintain CI/CD pipelines and release automation
  - Coordinate release windows and run deployments as needed
  - Implement automated verification and rollback plans
  - Maintain runbooks for production deploys and rollbacks
- Interactions:
  - Works with Developers and QA for staging verification
  - Coordinates with PM for scheduling and communication
  - Engages Security for gated checks before production deploys

### Data Analyst
- Role summary: Defines and validates metrics, implements instrumentation guidance, and analyzes results to validate outcomes.
- Responsibilities:
  - Define success metrics and event instrumentation requirements
  - Build dashboards, run analyses, and produce insights
  - Validate experiments and measure feature impact
  - Support data-driven decision making for PdMs and stakeholders
- Interactions:
  - Works with PdM to define A/B experiments and metrics
  - Collaborates with Developers on instrumentation and data quality
  - Presents findings to Stakeholders and PMs to influence roadmaps

---

## Cross-reference: persona responsibilities vs existing roles

A simple mapping to help teams quickly find who to contact for common responsibilities:

- Program-level strategy & prioritization: Program Owner (contact), PM, PdM
- Architecture & technical design: Technical Lead (contact), Developers
- Security & compliance: Security Engineer (contact), Technical Lead
- Release pipelines & deploy safety: Release Engineer (contact), Developers, QA
- UX validation & acceptance criteria: UX Researcher (contact), PdM, Designers
- Metrics, dashboards & analysis: Data Analyst (contact), PdM, Developers

(Teams may adapt titles and scope to match their org; these are suggested defaults.)

---

## How to use these personas
- Include the relevant personas in kickoff and planning artifacts (project one-pager, backlog items, and risk register).
- Add named owners for each action item and decision in planning and retrospectives.
- If a role isn’t available full-time (e.g., shared Security Engineer), document the expected level of support and escalation path.

---
