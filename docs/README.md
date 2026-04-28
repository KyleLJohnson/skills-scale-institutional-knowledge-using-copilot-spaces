# OctoAcme Project Management Docs

Welcome! This directory contains the key process documents for running projects at OctoAcme. Below you will find a brief overview of how we manage project work, plus quick links to each process doc.

## Overview

OctoAcme's project management approach follows a lightweight, end-to-end lifecycle that emphasizes iterative delivery, clear ownership, and measurable outcomes. Work typically progresses through initiation (clarifying the problem, defining success metrics, and aligning stakeholders), planning (turning the approved initiative into a prioritized backlog and release plan), execution (building and validating in small increments), and finally release and close/retrospective (deploying safely and capturing learnings). Across all phases, OctoAcme prioritizes customer value, data-informed decisions, and psychological safety so teams can surface risks early and improve continuously.

Roles and personas are explicitly defined to ensure accountability and smooth coordination. A named Project Manager (PM) coordinates delivery logistics (plans, schedules, risks, and communications), while the Product Manager (PdM) owns outcomes—problem definition, prioritization, and measuring success. Developers implement and test features, collaborate on design and reviews, and help identify technical risks; QA/Testing validates acceptance criteria and overall quality; and stakeholders provide input, approvals, and ongoing alignment. Key artifacts that anchor the work include a project one-pager/charter, roadmap and release plan, sprint backlog with acceptance criteria, Definition of Done, risk register, and retrospective action items.

Execution is managed through a consistent team rhythm and visible workflow. Teams use a project board (e.g., GitHub Projects) with stages like Backlog, Ready, In Progress, In Review, QA, and Done, supported by daily standups focused on progress and blockers, weekly delivery syncs for updates and risk flagging, and demos/reviews at the end of a sprint or milestone. Communication is structured around regular PM+PdM alignment, stakeholder updates (weekly or milestone-based), and clear escalation paths that move from team triage to PM/Product Lead coordination and, when necessary, sponsor-level escalation—especially for business-impacting issues.

Quality assurance and release practices are integrated throughout delivery to reduce risk and improve reliability. OctoAcme emphasizes small pull requests, linking work to issues and acceptance criteria, and ensuring CI runs tests, linting, and security scans before review/merge. New logic should be covered by unit tests, with integration tests and end-to-end smoke tests used where appropriate, plus manual QA for feature acceptance when needed. Releases follow a standardized checklist (staging deploy + smoke tests, production deployment, post-deploy verification, and stakeholder announcements) and require pre-release readiness such as completed acceptance criteria, drafted release notes, and a rollback/mitigation plan; retrospectives after sprints, releases, or incidents convert lessons learned into owned backlog items with clear success criteria.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
