# OctoAcme Project Management Docs

Welcome! This README collects all process and best-practice documentation for how OctoAcme manages projects. Use it as your starting point for onboarding or day-to-day reference.

## Brief Overview

OctoAcme organizes work around a clear project lifecycle — Initiation, Planning, Execution, Release, and Retrospective — supported by a small set of repeatable artifacts: a Project One‑pager (charter), prioritized backlog, release/milestone plan, risk register, and retrospective notes. Initiation produces a one‑pager that defines the problem, success metrics, stakeholders, and a go/no‑go for planning. Planning breaks approved initiatives into shippable backlog items (with acceptance criteria and estimates), defines a Definition of Done, identifies dependencies and risks, and produces a release timeline and checklist to guide execution.

Day‑to‑day workflows emphasize lightweight, visible execution: a project board with columns (Backlog, Ready, In Progress, In Review, QA, Done), timeboxed planning, and a PR-driven delivery flow. PR guidance calls for small changes (<= 400 lines when possible), linking the PR to its issue and acceptance criteria, running CI (tests, lint, security scans) before review, and requiring at least one approval. The team rhythm includes daily standups for progress and blockers, weekly delivery syncs for progress and risks, demos at sprint/milestone ends, and regular demos and status artifacts. Operational checklists (branching/PR conventions, CI configuration, demo schedule, risk register updates) ensure predictable handoffs.

Roles and communication are explicit: Product Managers set outcomes and prioritize; Project Managers coordinate schedules, risks, and stakeholder communications; Developers implement and test; QA validates acceptance. Communication cadence includes PM+PdM weekly alignment, delivery standups as agreed (twice weekly suggested), monthly stakeholder updates, and templates (weekly status summaries and incident communication) to standardize messaging. Escalation paths go from team triage to PM, Product Lead, and sponsor for business‑impacting issues; security incidents follow the security runbook and on‑call notification.

Quality practices are built into every stage: unit and integration tests for new logic, end‑to‑end smoke tests for critical flows, CI security scanning, and manual QA for acceptance when needed. Reporting tracks velocity, burndown, and success metrics from the one‑pager, with dashboards for errors, latency, and usage. Continuous improvement is enforced through regular retrospectives that capture 2–3 prioritized action items, track them into the backlog, and measure impact — closing the loop on learnings and reducing single‑person dependencies.

## Process Documents
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release &amp; Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective &amp; Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

## How to use these docs
- Keep the Project One-pager and key artifacts updated in each project repo under docs/ or .copilot/.  
- Use the issue template (/.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose updates to any process document.
