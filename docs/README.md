# OctoAcme Project Management Docs

This guide is the entry point for OctoAcme's project management process documentation. It helps new team members quickly understand how projects are run and gives existing teams a fast reference for day-to-day execution.

OctoAcme uses a lifecycle-based model with five phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**. Teams start by validating business need, stakeholders, and success metrics, then move into planning where scope is broken into prioritized, testable increments with clear acceptance criteria and Definition of Done.

Execution is coordinated through a steady communication cadence and visible workflows. Delivery teams use standups, weekly syncs, and regular demos to surface blockers early, track progress, and keep priorities aligned. Pull requests are expected to be focused, traceable to issues, and validated through CI before merge.

Quality and risk management are integrated across all phases. OctoAcme emphasizes unit tests, integration tests, pre-release smoke tests, and security scanning, plus manual QA when required for acceptance. Risks are tracked in a register and escalated through a defined path (Team -> PM -> Product Lead -> Sponsor), reinforcing timely decision-making.

Throughout the process, teams operate with five core principles: **customer-first outcomes**, **iterative delivery**, **clear ownership**, **data-informed decisions**, and **psychological safety**. Core roles include the **Project Manager**, **Product Manager**, **Developers**, **QA/Testing**, and **Stakeholders**, each with clear responsibilities that keep delivery and communication accountable.

## Project Lifecycle at a Glance

### 1) Initiation
- Define the problem, goals, and success metrics
- Identify stakeholders and communication needs
- Confirm initial timeline, risks, and resource needs
- Decide go/no-go into planning

### 2) Planning
- Run kickoff and align delivery expectations
- Build a prioritized backlog with acceptance criteria
- Estimate work, define dependencies, and capture risks
- Document Definition of Done and initial QA/test approach

### 3) Execution
- Deliver in small, reviewable increments
- Track work on a project board (Backlog -> Ready -> In Progress -> In Review -> QA -> Done)
- Run daily team coordination and weekly delivery syncs
- Monitor delivery metrics and resolve blockers quickly

### 4) Release
- Validate acceptance criteria, CI, and security checks
- Prepare release notes and rollback plans
- Deploy through staging and production with smoke-test verification
- Communicate release outcomes to stakeholders and support

### 5) Retrospective
- Reflect on what worked and what to improve
- Capture actionable improvements with owner and due date
- Feed actions into backlog and review progress regularly
- Reinforce continuous improvement culture

## Communication Cadence

- **Daily standups**: progress, blockers, dependencies
- **Weekly PM/PdM and delivery syncs**: status, risks, trade-offs, decisions
- **Monthly stakeholder updates**: outcomes, timeline status, key risks, next milestones
- **Ad-hoc incident/escalation updates**: urgent business or security-impacting issues

## Quality Assurance Practices

- Unit tests for new or changed logic
- Integration tests for cross-component behavior
- End-to-end smoke tests for critical release flows
- Security scanning in CI
- Manual QA for feature acceptance where needed

## Risk Management and Escalation

- Maintain a Risk Register with impact, likelihood, owner, mitigation, and status
- Review risks in weekly syncs and update mitigation actions
- Escalation path: **Team-level triage -> PM -> Product Lead -> Sponsor**
- Security incidents also notify Security on-call per incident runbook

## Core Roles

- **Project Manager (PM):** delivery coordination, timelines, risk, and communication
- **Product Manager (PdM):** outcomes, prioritization, success metrics, and trade-offs
- **Developers:** implementation, testability, code quality, and technical risk input
- **QA/Testing:** validation of acceptance criteria and release confidence
- **Stakeholders:** requirements input, feedback, and key approvals

## Process Document Navigation

- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

## Quick Links: Process Improvement Issue Templates

- [Add / update content in process docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
