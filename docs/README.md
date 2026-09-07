# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Docs repository. This is the central hub for all program management processes, guidance, and best practices used across OctoAcme teams.

## What is OctoAcme?

OctoAcme follows a structured, customer-first approach to project management that emphasizes iterative delivery, clear ownership, and data-informed decisions. Our process ensures psychological safety, transparency, and continuous improvement across all cross-functional projects.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named PM and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

```
Initiation → Planning → Execution → Release → Close & Retrospective
```

## OctoAcme Project Management Approach

OctoAcme follows a structured project lifecycle that moves work through five distinct phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During Initiation, teams validate business needs by creating a lightweight One-pager that defines the problem, objective, success metrics, stakeholders, and initial timeline. In the Planning phase, approved initiatives are broken into shippable increments with prioritized backlogs, acceptance criteria, and estimates. The team then moves into Execution, where work flows through a project board (Backlog → Ready → In Progress → In Review → QA → Done) using small pull requests (≤400 lines) backed by automated testing and security scanning in CI. Once features meet acceptance criteria, the Release phase requires pre-deployment verification including smoke tests, rollback plans, and release notes. Finally, the Close & Retrospective phase captures learnings and converts them into actionable improvements.

### Roles and Communication

OctoAcme defines clear ownership across four core personas: **Project Managers** coordinate schedules, risks, and stakeholder communication; **Product Managers** define customer value, prioritize the roadmap, and measure outcomes; **Developers** implement features with quality and testability focus; and **QA/Testing** validates acceptance criteria and quality standards. The organization maintains a structured communication rhythm—daily standups (15 min) for progress and blockers, weekly delivery syncs between PM and Product Lead, and monthly stakeholder updates. Risk escalation follows three levels: team-level triage in standups, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues.

### Quality and Risk Management

Quality is embedded throughout OctoAcme's execution model. Teams implement unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows before release. Security scanning runs in CI pipelines, and manual QA validates feature acceptance when needed. Risk management is continuous—risks are captured in a register (ID, description, impact, likelihood, owner, mitigation, status) and reviewed at weekly syncs. By combining iterative delivery, clear ownership, data-informed decisions, and psychological safety, OctoAcme enables teams to deliver customer value consistently while maintaining quality and reducing single-person dependency risk.

## Process Documents

### Getting Started
- **[OctoAcme Project Management Overview](octoacme-project-management-overview.md)** — Start here for a concise introduction to OctoAcme's approach, key roles, and artifacts

### Project Stages

1. **[Project Initiation Guide](octoacme-project-initiation.md)** — Define the initial steps to validate and authorize work, align stakeholders, and create a lightweight plan
2. **[Project Planning](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog for delivery
3. **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution and tracking progress toward milestones
4. **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize how OctoAcme releases features to production to reduce risk and improve observability
5. **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements

### Cross-Cutting Concerns

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies throughout the project lifecycle
- **[OctoAcme Personas](octoacme-roles-and-personas.md)** — Definitions of typical roles (Developers, Product Managers, Project Managers) and responsibilities

## Quick Reference

| Need | Document |
|------|----------|
| Understand OctoAcme approach | [Project Management Overview](octoacme-project-management-overview.md) |
| Start a new project | [Project Initiation Guide](octoacme-project-initiation.md) |
| Create a project plan | [Project Planning](octoacme-project-planning.md) |
| Manage daily delivery | [Execution & Tracking](octoacme-execution-and-tracking.md) |
| Handle risks & blockers | [Risk Management & Communication](octoacme-risks-and-communication.md) |
| Release to production | [Release & Deployment Guide](octoacme-release-and-deployment.md) |
| Run a retrospective | [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) |
| Learn about roles | [OctoAcme Personas](octoacme-roles-and-personas.md) |

## Contributing

To suggest updates, improvements, or new content for these process documents, please open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
