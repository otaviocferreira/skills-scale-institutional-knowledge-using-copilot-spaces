# OctoAcme Project Management Documentation

## Overview

OctoAcme follows a structured, customer-first approach to project management that emphasizes iterative delivery, clear ownership, and data-informed decisions. The organization operates across five key lifecycle phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**.

During initiation, teams validate business needs and create a lightweight Project One-pager that captures the problem statement, success metrics, stakeholders, and initial timeline. Once approved by the Product Lead and sponsor, projects move into planning, where the work is broken into shippable increments with prioritized backlogs, acceptance criteria, and clear definitions of done.

Execution and delivery are coordinated through a well-defined team rhythm that includes daily standups (15 minutes), weekly delivery syncs, and regular demos at sprint or milestone ends. The project board serves as the central tracking mechanism, organizing work through columns: Backlog, Ready, In Progress, In Review, QA, and Done. Small pull requests (≤400 lines) are encouraged, and all code must pass automated tests, linting, and security scanning before requiring at least one approval and merge.

OctoAcme defines clear roles and responsibilities to ensure accountability and smooth coordination. **Project Managers** own schedules, risks, dependencies, and stakeholder communications; **Product Managers** define what should be built, prioritize the backlog, and measure outcomes; **Developers** implement features and collaborate on design and testability; and **QA/Testing** validates quality against acceptance criteria.

Release and deployment are standardized to reduce risk and improve observability, with pre-release requirements including passing all acceptance criteria, CI/security scans, drafted release notes, and a documented rollback plan. Finally, OctoAcme institutionalizes learning through retrospectives held after each sprint, release, or milestone, where teams capture what went well, identify improvements, and track action items with clear owners and timelines.

## Quick Navigation

- [Project Management Overview](./octoacme-project-management-overview.md) — Introduction to OctoAcme principles, roles, and artifacts
- [Project Initiation Guide](./octoacme-project-initiation.md) — Steps to validate and authorize new work
- [Project Planning](./octoacme-project-planning.md) — Breaking work into shippable increments
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day delivery and progress tracking
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Risk identification and stakeholder updates
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardized release and deployment processes
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings and improvements
- [Roles & Personas](./octoacme-roles-and-personas.md) — Definitions of Developers, Product Managers, and Project Managers

## Getting Started

1. **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand core principles and the project lifecycle.

2. **Starting a new project?** Follow the [Initiation Guide](./octoacme-project-initiation.md) to validate business need and align stakeholders.

3. **Planning a project?** Use the [Project Planning](./octoacme-project-planning.md) guide to break work into shippable increments and establish your backlog.

4. **In execution?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) for day-to-day workflows, quality practices, and blocker escalation.

5. **Managing risks or communicating status?** Consult [Risk Management & Communication](./octoacme-risks-and-communication.md) for risk registers and stakeholder updates.

6. **Preparing for release?** Use the [Release & Deployment Guide](./octoacme-release-and-deployment.md) to standardize your deployment process and minimize production risk.

7. **Running retrospectives?** Follow the [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) guide to capture learnings and drive improvements.

8. **Need clarification on roles?** See [Roles & Personas](./octoacme-roles-and-personas.md) for detailed responsibilities and communication patterns for Developers, Product Managers, and Project Managers.

## Key Principles

- **Customer-first:** Prioritize customer value and usability in all decisions
- **Iterative delivery:** Deliver small, testable increments regularly
- **Clear ownership:** Each project has named Project Manager (PM) and Product Lead
- **Data-informed:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback, learning, and continuous improvement

## Using These Docs with Copilot Spaces

These process documents are designed to be attached to Copilot Spaces as institutional knowledge. By grounding Copilot in these processes, your team can:

- Get consistent, role-specific guidance based on OctoAcme methodology
- Accelerate onboarding by making tacit knowledge searchable and version-controlled
- Reduce dependency on individuals and ensure processes are repeatable
- Standardize execution across projects and teams

Attach these docs to a Copilot Space and reference them to get context-aware guidance for your project phases and workflows.
