# OctoAcme Project Management Process Documentation

Welcome to OctoAcme's project management documentation. This folder serves as the single entry point for the processes, templates, and working agreements used to plan, deliver, and improve projects across OctoAcme. The documents here explain our core principles, roles, lifecycle stages, and practical checklists so teams and stakeholders can quickly find and apply a consistent approach to delivery.

## Quick start

New to OctoAcme? Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a high-level introduction to our principles, roles, and lifecycle. For initiating new work, use the Project Initiation Guide to create a one‑pager and confirm go/no‑go decisions. Planning converts approved initiatives into a prioritized, estimated backlog with clear acceptance criteria. Execution is coordinated through an explicit project board and a Pull Request workflow that enforces small changes, CI, and peer review. Releases follow a standardized checklist (pre‑release smoke tests, rollback plans, release notes), and retrospectives capture learnings and action items to continuously improve.

## Project Management Processes — Overview

OctoAcme runs projects through a structured, stage-gated flow that begins with a lightweight initiation and moves through planning, execution, release, and continuous improvement. Initiation focuses on validating the business need and defining measurable outcomes using a one‑pager that captures problem statements, success metrics, stakeholders, and a high‑level timeline. Teams only move to planning after stakeholders agree on priorities and team availability.

Planning turns approved initiatives into shippable work by breaking scope into backlog items with clear acceptance criteria and estimates, defining the Definition of Done, and mapping milestones. The planning rhythm includes kickoff meetings, prioritized backlog grooming, and estimation practices (T‑shirt sizing or story points) to align scope with team capacity while identifying dependencies and risks.

During execution, the team uses a visible project board (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined pull request workflow that favors small PRs, requires CI (tests and linting), and enforces peer review before merging. Daily standups and weekly delivery syncs keep work aligned and surface blockers; a risk register and escalation paths ensure issues are triaged and elevated as needed. Quality practices include unit and integration tests, end‑to‑end smoke tests for critical flows, security scans in CI, and manual QA for acceptance when required.

Release and close activities standardize deployments, verification, and learning. Releases follow a checklist (smoke tests, rollback plans, release notes), and post‑release retrospectives capture action items that are tracked as backlog work to continuously improve processes and reduce single‑person dependencies.

## Project lifecycle (use these docs by phase)

- Initiation
  - [Project Initiation Guide](./octoacme-project-initiation.md) — validate need, identify stakeholders, define success metrics
- Planning
  - [Project Planning](./octoacme-project-planning.md) — break work into shippable increments, define DoD, estimate and map milestones
- Execution
  - [Execution & Tracking](./octoacme-execution-and-tracking.md) — day-to-day delivery, project board conventions, PR workflow
  - [Risk Management & Communication](./octoacme-risks-and-communication.md) — risk register, stakeholder communication, escalation paths
- Release
  - [Release & Deployment Guide](./octoacme-release-and-deployment.md) — release types, deployment checklist, rollback playbook
- Close & Learn
  - [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — run retrospectives, track action items

## Reference

- [OctoAcme Personas](./octoacme-roles-and-personas.md) — role definitions and responsibilities for Product Managers, Project Managers, Developers, QA, and Stakeholders

## Core principles

- Customer-first: prioritize customer value and usability
- Iterative delivery: deliver small, testable increments
- Clear ownership: each project has a named PM and Product Lead
- Data-informed decision making: measure impact and iterate
- Psychological safety: encourage candid feedback and learning

## Communication cadence (quick reference)

- Daily standups (15 minutes) — focus on progress, blockers, dependencies
- Weekly PM + PdM sync — planning and risk alignment
- Twice-weekly delivery standups (or as agreed) — delivery coordination
- Monthly stakeholder updates — program-level status
- Ad-hoc escalations as needed — follow documented escalation paths in the Risk & Communication guide

---

This README complements the existing process documents in docs/ and is intended to be the primary entry point for new team members and stakeholders seeking an overview and links to detailed guidance.
