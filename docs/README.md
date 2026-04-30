# OctoAcme Project Management Docs

## Overview

OctoAcme follows a structured, lifecycle-based project management approach grounded in customer value, iterative delivery, and clear accountability. The framework spans five phases—Initiation, Planning, Execution, Release, and Close & Retrospective—each with defined deliverables and decision gates. At its core are three primary roles: the Project Manager (PM) who coordinates scheduling and risk management, the Product Manager (PdM) who defines outcomes and prioritizes work, and Developers who implement features collaboratively. This role clarity, combined with a lightweight one-pager template for project charters and a data-driven measurement philosophy, ensures stakeholders maintain alignment from day one and teams remain focused on measurable success metrics.

## Key Workflows and Execution Discipline

The execution phase emphasizes iterative, testable increments delivered through a structured pull request workflow with clear acceptance criteria. Teams operate within a project board using standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) and maintain a daily 15-minute standup focused on progress, blockers, and dependencies. Quality gates are enforced throughout: unit and integration tests are required for new logic, security scanning runs in CI, and manual QA validates feature acceptance. Risk management is embedded in the process through a risk register that captures likelihood, impact, and mitigation strategies, with escalation flowing through three levels—team triage, PM-to-Product Lead, and sponsor escalation—ensuring business-impacting issues surface quickly and transparently.

## Communication and Continuous Improvement

OctoAcme mandates consistent communication cadences: weekly syncs between PM and PdM, twice-weekly standups for delivery teams, and monthly stakeholder updates. Each project maintains a single source of truth (project README or release documentation) that stakeholders can reference, reducing confusion and enabling data-informed decisions. Release management is standardized with pre-release checklists, smoke tests, and documented rollback plans to minimize production risk. The framework closes each cycle with a structured retrospective—held after sprints, releases, or milestones—where teams capture learnings, prioritize 2–3 actionable improvements, and measure the impact of previous action items, embedding a culture of psychological safety and continuous iterative improvement.

---

## Documentation Index

Quick links to all OctoAcme project management process documents:

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to roles, artifacts, lifecycle, and principles
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Validate business need, align stakeholders, define success criteria
- **[Project Planning](octoacme-project-planning.md)** — Break work into increments, identify dependencies, create backlog and release plan
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day progress management, project boards, PR workflows, QA practices
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Risk registers, escalation paths, stakeholder communication templates
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Pre-release checklists, deployment procedures, rollback playbooks
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Running retros, capturing learnings, tracking action items
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Definitions of Project Managers, Product Managers, and Developers

---

## How to Use These Docs

- **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md)
- **Starting a new project?** Follow the [Initiation Guide](octoacme-project-initiation.md), then [Planning](octoacme-project-planning.md)
- **Day-to-day execution?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md)
- **Shipping a release?** Use the [Release & Deployment Guide](octoacme-release-and-deployment.md)
- **Wrapping up a phase or sprint?** Conduct a [Retrospective](octoacme-retrospective-and-continuous-improvement.md)

For role-specific guidance, see [Roles and Personas](octoacme-roles-and-personas.md).
