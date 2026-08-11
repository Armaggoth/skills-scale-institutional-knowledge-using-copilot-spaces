# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Knowledge Base. This folder contains the process documentation, templates, and guidance for running projects using the OctoAcme approach.

## Quick Start

### What is OctoAcme?
OctoAcme is a lightweight project management framework designed for cross-functional teams delivering product features, services, and integrations. It emphasizes customer value, iterative delivery, clear ownership, and data-informed decisions.

### Core Principles
- Customer-first: prioritize customer value and usability
- Iterative delivery: deliver small, testable increments
- Clear ownership: each project has a named PM and Product Lead
- Data-informed decisions: measure impact and iterate based on evidence
- Psychological safety: encourage feedback and learning

## Project Lifecycle

OctoAcme projects follow five phases:

Initiation → Planning → Execution → Release → Close & Retrospective

### Phase Overview
- Initiation: validate business need, align stakeholders, define success criteria
- Planning: break work into shippable increments, identify dependencies and risks
- Execution: build, test, review, and iterate toward delivery
- Release: deploy to production and verify success metrics
- Close & Retrospective: capture learnings and continuous improvements

## Project Management Processes (Overview)

OctoAcme's processes are built to move work from idea to production with clear roles, lightweight ceremonies, and built-in quality gates. Work begins with a Project One-pager to capture the problem, objective, success metrics, stakeholders, and a high-level timeline. Approved initiatives move into planning, where the team creates a prioritized backlog with acceptance criteria, estimates, and a release plan. Execution is tracked on a project board with columns for Backlog, Ready, In Progress, In Review, QA, and Done; PRs are kept small, linked to issues, and validated by CI and at least one reviewer before merging.

Communication focuses on a predictable cadence: short daily standups, weekly delivery syncs, regular demos at the end of sprints/milestones, and monthly stakeholder updates. Risks and dependencies are tracked in a Risk Register and escalated through a defined path (team → PM → Product Lead → Sponsor). Retrospectives after sprints, releases, and incidents capture learnings and convert them into action items added to the backlog.

Quality assurance is enforced through unit and integration tests, end-to-end smoke tests for critical flows, CI-based security scanning, and manual QA when required. Releases are categorized (patch/minor/major) and require pre-release checks (passing CI, release notes, rollback plans, and smoke tests). Incident and rollback playbooks are in place for production issues.

## Documentation Index

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

## By Role: Where to Start

- Project Managers: Overview → Initiation → Planning
- Product Managers: Overview → Roles → Planning
- Developers: Roles → Execution & Tracking
- QA / Testing: Execution & Tracking → Release & Deployment

## Contributing to Process Docs

Use the Add Content to Project Management Process Docs issue template: `/.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` to propose changes or additions.

*Last updated: 2026-08-11*
