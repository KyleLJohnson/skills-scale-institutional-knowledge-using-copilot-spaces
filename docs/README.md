# OctoAcme Project Management Docs

Welcome! This directory contains the key process documents for running projects at OctoAcme. Below you will find a brief overview of how we manage project work, plus quick links to each process doc.

## Overview

OctoAcme runs projects with a lightweight, end-to-end lifecycle that prioritizes iterative delivery and clear ownership. Work typically moves from **Initiation** (clarifying the problem, objective, success metrics, stakeholders, timeline, and early risks) into **Planning** (kickoff, breaking scope into shippable increments, defining Definition of Done, and building an estimated, prioritized backlog), then through **Execution** (building, testing, reviewing, and tracking progress), followed by **Release** (deploying with safeguards and verification), and finally **Close/Retrospective** (capturing learnings and converting them into actionable improvements). Across all phases, OctoAcme emphasizes measurable outcomes, transparency, and small increments that can be reviewed and shipped reliably.

Roles are explicitly defined to reduce ambiguity and improve decision-making speed. **Project Managers (PMs)** coordinate delivery mechanics—plans, schedules, risks, dependencies, meetings, and consistent status reporting—while **Product Managers (PdMs)** own the "why" and "what" by defining outcomes, prioritizing the backlog, and measuring success. **Developers** design and implement solutions with testability and maintainability in mind, participate in estimation and reviews, and help identify technical risks. **QA/Testing** supports validation against acceptance criteria, and **stakeholders** provide inputs, alignment, and approvals as needed. This role clarity is reinforced by standard artifacts such as the one-pager/charter, backlog items with acceptance criteria, a risk register, and retrospective action items.

Communication is structured around a predictable team rhythm and stakeholder-facing updates. Day-to-day coordination relies on short standups focused on progress, blockers, and dependencies, complemented by weekly delivery syncs to surface risks and show progress, plus regular demos/reviews at sprint or milestone boundaries. Stakeholder communication is kept consistent through a weekly status template (progress, next steps, risks/blockers, and asks/decisions), and a "single source of truth" document is recommended for status. Escalation is intentional and tiered: team triage first, then PM escalation to leads and dependent teams, and sponsor-level escalation when business impact demands it; security incidents follow a dedicated incident path.

Quality assurance is built into both delivery and release practices. During execution, OctoAcme favors small pull requests, requires issue linkage and acceptance criteria in PR descriptions, expects automated tests and linting to pass in CI before review, and uses at least one approval before merging (or a team-defined policy). Testing expectations scale with risk: unit tests for new logic, integration tests where needed, and end-to-end smoke tests for critical flows before release, alongside security scanning in CI and manual QA when appropriate for acceptance. Releases are standardized with pre-release requirements (criteria met, CI/security green, release notes, rollback/mitigation plan, smoke tests), staged deployments when applicable, post-deploy verification, and clear incident/rollback procedures—followed by retrospectives that turn outcomes into tracked improvement actions with owners and due dates.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
