# OctoAcme Project Management Processes

Welcome to the OctoAcme project management documentation. This guide provides a comprehensive overview of how we plan, execute, and deliver projects across the organization.

## Our Approach

OctoAcme follows a structured, iterative project management methodology built on five core principles:
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named leaders with defined responsibilities
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

## Project Lifecycle

Every OctoAcme project moves through these five phases:

1. **Initiation** — Validate the problem, align stakeholders, and create a lightweight plan
2. **Planning** — Break work into shippable increments and establish timelines
3. **Execution** — Build, test, and iterate with daily standups and weekly syncs
4. **Release** — Deploy to production with quality checks and rollback plans
5. **Close & Retrospective** — Capture learnings and drive continuous improvement

## Core Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features and collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, feedback, and approvals

## Overview of OctoAcme Project Management Processes

OctoAcme operates a structured, lifecycle-based project management approach designed to deliver customer value through iterative development while maintaining clear ownership and accountability across the organization.

### Core Workflows and Lifecycle

OctoAcme projects follow a five-phase lifecycle: Initiation, Planning, Execution, Release, and Close & Retrospective. The **Initiation phase** validates business need through a lightweight Project One-pager that captures the problem statement, objectives, success metrics, stakeholders, and initial resource estimates. Once stakeholders align and success criteria are clear, the project moves to **Planning**, where the team breaks work into prioritized, estimated backlog items with defined acceptance criteria and a clear Definition of Done. During **Execution**, the team works in sprints or iterations using a project board (GitHub Projects) with columns for Backlog, Ready, In Progress, In Review, QA, and Done. Small pull requests (≤400 lines when possible) with automated CI/CD checks and at least one approval are required before merging. The **Release phase** emphasizes pre-release verification, smoke testing, and documented rollback plans, while the final **Close & Retrospective** phase captures learnings and converts them into actionable improvements tracked in the project backlog.

### Communication and Risk Management

Communication happens through a regular cadence including daily standups (15 minutes, focusing on progress and blockers), weekly delivery syncs with the PM and Product Lead, twice-weekly team standups, and monthly stakeholder updates. Risk management is formalized through a Risk Register that tracks ID, description, impact, likelihood, owner, and mitigation plan—escalation follows a three-level path from team-level triage to PM-to-Product Lead to sponsor-level escalation for business-impacting issues.

### Quality Assurance and Continuous Improvement

Quality is embedded throughout the delivery process: unit tests are written for new logic, integration tests validate cross-component interactions, and end-to-end smoke tests verify critical flows before release. Security scanning runs in CI, and manual QA is conducted for feature acceptance when needed. Beyond individual releases, OctoAcme emphasizes continuous improvement through structured retrospectives held after each sprint, release, or milestone. These 45-75 minute sessions explore what went well, what could improve, and generate 2-3 prioritized action items with named owners and due dates. Metrics such as velocity, burndown, error rates, and usage are tracked via dashboards to inform data-driven decisions.

## Documentation Index

### Getting Started
- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to roles, artifacts, and communication cadence
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Detailed descriptions of typical roles and responsibilities

### By Phase

**Initiation**
- **[Project Initiation Guide](octoacme-project-initiation.md)** — How to validate ideas, align stakeholders, and get go/no-go approval

**Planning**
- **[Project Planning](octoacme-project-planning.md)** — Creating backlog, estimating scope, and defining milestones

**Execution**
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day workflows, quality standards, and metrics

**Release**
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Pre-release checklist, deployment process, and rollback procedures

**Close & Retrospective**
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Running retros and capturing action items

### Cross-Cutting Concerns
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identifying risks, managing escalations, and stakeholder updates

## How to Use These Docs

- **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md) and [Roles and Personas](octoacme-roles-and-personas.md)
- **Starting a new project?** Follow the path: Initiation → Planning → Execution → Release → Retrospective
- **Need to manage risks or escalate?** See [Risk Management & Communication](octoacme-risks-and-communication.md)
- **Managing a specific phase?** Jump to the relevant phase documentation linked above

## Questions?

If you can't find what you need, reach out to your Product Manager or Project Manager for clarification.
