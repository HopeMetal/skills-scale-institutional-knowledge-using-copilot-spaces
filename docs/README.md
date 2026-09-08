# OctoAcme Project Management Process Docs

## Overview
OctoAcme follows a lightweight, stage-based project management approach that moves work from Initiation → Planning → Execution → Release → Retrospective. Initiation emphasizes a short Project One-pager to capture the problem, goals, success metrics, stakeholders, and a rough timeline. Planning turns approved initiatives into a prioritized, estimated backlog with a clear Definition of Done and an explicit release/milestone plan. Key artifacts include the one-pager, roadmap/release plan, backlog items with acceptance criteria, a risk register, and retrospective action items.

## Workflows & Quality
Day-to-day work is organized around a project board (Backlog → Ready → In Progress → In Review → QA → Done). Pull request conventions encourage small PRs (target <= 400 lines), include an issue link and acceptance criteria, and require CI (tests + linting) and at least one approval before merging. QA practices include unit tests, integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance. Releases follow a checklist (passing CI, release notes, rollback plan, staging smoke tests) and an incident/rollback playbook for failures.

## Personas & Communication
Roles are explicit: Product Managers own vision and prioritization; Project Managers coordinate delivery, scheduling, risk, and stakeholder communication; Developers implement and test features; QA validates acceptance criteria; Stakeholders provide input and approvals. The team rhythm consists of short daily standups focused on blockers, a weekly delivery sync and PM+PdM alignment, sprint demos, and monthly stakeholder updates. Blocker escalation is tiered from team-level triage up to sponsor-level escalation for business-impacting issues.

## How to use these docs
- Starting a new project? Begin with the Project Initiation Guide.
- Ready to plan? See Project Planning for backlog, estimates, and release mapping.
- Executing work? Follow Execution & Tracking and Risk Management & Communication.
- Preparing for release? Use Release & Deployment Guide and the deployment checklist.
- Project complete? Run Retrospective & Continuous Improvement and track action items.

## Complete Process Documentation
- Project Lifecycle Overview
  - [Project Management Overview](octoacme-project-management-overview.md) — high-level approach, roles, artifacts
- Initiation
  - [Project Initiation Guide](octoacme-project-initiation.md) — one-pager, stakeholder alignment, go/no-go
- Planning
  - [Project Planning](octoacme-project-planning.md) — backlog, estimates, DoD, risk register
- Execution
  - [Execution & Tracking](octoacme-execution-and-tracking.md) — daily execution, PR workflow, CI
  - [Risk Management & Communication](octoacme-risks-and-communication.md) — risk register, communication templates
- Release
  - [Release & Deployment Guide](octoacme-release-and-deployment.md) — release types, checklist, rollback playbook
- Close & Improve
  - [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — run retros, track action items
- Reference
  - [OctoAcme Personas](octoacme-roles-and-personas.md) — roles, responsibilities, communication patterns
