# OctoAcme Project Management Documentation

## Overview
OctoAcme uses a structured, iterative project management approach that emphasizes clear ownership, customer value, and continuous improvement. Our processes are designed to be lightweight, scalable, and supportive of cross-functional teams delivering features, services, and integrations.

## Core Principles
- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Deliver small, testable increments
- **Clear ownership:** Each project has named leadership and defined roles
- **Data-informed decisions:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

## How OctoAcme Runs Projects

OctoAcme operates on a lifecycle-driven project management approach centered around five key phases: **Initiation, Planning, Execution, Release, and Retrospective**. 

The **Initiation phase** establishes business alignment through lightweight Project One-pagers that define the problem statement, success metrics, stakeholder list, and initial resource needs. Once stakeholders approve the initiative, teams move into **Planning**, where work is broken into shippable increments with clear acceptance criteria, prioritized backlogs are created, and dependencies are mapped. This structured entry ensures projects start with clear success criteria and sponsor alignment before development begins.

Execution at OctoAcme emphasizes iterative delivery and transparency through a consistent team rhythm: daily standups (15 min), weekly delivery syncs, and demo/review sessions at sprint or milestone boundaries. Teams use GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) and follow small PR practices (≤400 lines when possible) with required automated CI testing, linting, and peer reviews before merge. Quality is built in through unit tests, integration tests, end-to-end smoke tests, and security scanning in CI. Risk management is continuous, with escalation pathways defined at team, product lead, and sponsor levels, and a Risk Register maintained and reviewed weekly.

Three core roles drive OctoAcme projects: **Project Managers** coordinate delivery, manage timelines and risks, and facilitate communication; **Product Managers** define outcomes, prioritize backlog, and measure success; and **Developers** implement features, write tests, and identify technical risks. Weekly syncs between PM and PdM, twice-weekly standups for delivery teams, and monthly stakeholder updates ensure alignment. **Release practices** are rigorous, requiring passing CI, security scans, release notes, and rollback plans before production deployment. Finally, **Retrospectives** held after each sprint or milestone capture learnings and convert them into prioritized action items, embedding continuous improvement into the culture and ensuring lessons feed back into planning and process refinement.

## Project Lifecycle & Process Docs

### 1. [Initiation](./octoacme-project-initiation.md)
Validate business need, align stakeholders, and create a lightweight plan. Deliverables include a Project One-pager, stakeholder list, and initial risk assessment.

**Key outputs:** Project Charter, Stakeholder alignment, Decision to proceed to Planning

### 2. [Planning](./octoacme-project-planning.md)
Turn an approved initiative into an actionable backlog and timeline. Includes work breakdown, estimation, dependency mapping, and release planning.

**Key outputs:** Prioritized backlog, Release plan, Definition of Done, Risk Register

### 3. [Execution & Tracking](./octoacme-execution-and-tracking.md)
Manage day-to-day execution with daily standups, weekly syncs, and consistent quality practices. Includes PR workflow, testing strategy, and blocker escalation.

**Key outputs:** Completed work, Metrics dashboards, Risk updates, Quality assurance

### 4. [Release & Deployment](./octoacme-release-and-deployment.md)
Standardize how features ship to production. Covers release types, pre-release requirements, deployment checklist, and rollback procedures.

**Key outputs:** Production release, Release notes, Post-deploy verification

### 5. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
Capture learnings after sprints or milestones and convert them into actionable improvements. Includes retrospective structure and action item tracking.

**Key outputs:** Retrospective notes, Action items, Process improvements

### 6. [Risk Management & Communication](./octoacme-risks-and-communication.md)
Identify, assess, and mitigate risks. Establish stakeholder communication cadence and escalation paths.

**Key outputs:** Risk Register, Communication plan, Escalation procedures

## Key References

- [Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, roles, artifacts, and communication cadence
- [Roles & Personas](./octoacme-roles-and-personas.md) — Definitions of core roles (Project Manager, Product Manager, Developer, QA/Testing) and their responsibilities

## Getting Started

- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md)
- **Starting a new project?** Follow the [Initiation](./octoacme-project-initiation.md) process
- **Team member looking for execution guidance?** See [Execution & Tracking](./octoacme-execution-and-tracking.md)
- **Need to understand risk escalation?** Check [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **Preparing for a release?** Review [Release & Deployment](./octoacme-release-and-deployment.md)
- **Wrapping up a project or sprint?** Follow [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

## Contributing to Process Documentation

To request updates or additions to OctoAcme's process documentation, use the [Process Doc Update issue template](./../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).
