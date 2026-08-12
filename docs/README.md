# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Docs. This directory contains comprehensive guidance for running projects using the OctoAcme approach.

## Quick Start

New to OctoAcme? Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand our core principles, roles, and lifecycle.

## OctoAcme Project Management Overview

OctoAcme is a customer-first, data-driven project management methodology designed for cross-functional teams delivering product features, services, and integrations. The approach emphasizes:

- **Clear Ownership:** Each project has a dedicated Project Manager (PM) and Product Manager (PdM) who own different aspects of delivery and outcomes
- **Iterative Delivery:** Work is broken into small, testable increments that deliver value incrementally
- **Psychological Safety:** Teams are encouraged to share feedback, raise concerns, and learn from challenges
- **Data-Informed Decisions:** Success is measured through defined metrics, and adjustments are made based on evidence
- **Quality & Testing:** Every feature undergoes unit testing, integration testing, and acceptance criteria validation before release

The methodology follows a structured 5-phase lifecycle with clear entry and exit criteria, regular communication cadences, and defined escalation paths for risks and blockers.

## Project Lifecycle

OctoAcme projects follow these phases:

1. **Initiation** — Define the problem, align stakeholders, decide go/no-go
2. **Planning** — Break work into actionable backlog and milestones
3. **Execution** — Build, test, review, and iterate with daily standups
4. **Release** — Deploy to production with controlled, verified rollout
5. **Close & Retro** — Capture learnings and drive continuous improvement

## Documentation Index

### Overview & Core Processes

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme approach, principles, roles, and key artifacts

### Lifecycle Phases

- **[Project Initiation](octoacme-project-initiation.md)** — Validate ideas, align stakeholders, create One-pager, go/no-go decision
- **[Project Planning](octoacme-project-planning.md)** — Create prioritized backlog, estimate, define DoD, identify dependencies
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day workflows, standups, quality standards, blocker escalation
- **[Release & Deployment](octoacme-release-and-deployment.md)** — Release types, pre-release requirements, deployment checklist, rollback playbook
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings, drive improvements, track action items

### Specialized Topics

- **[Risks & Communication](octoacme-risks-and-communication.md)** — Risk management, stakeholder communication, escalation paths
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Definitions and responsibilities for Developers, Product Managers, Project Managers

## Key Processes at a Glance

### Communication Cadence
- **Daily standups** (15 min) — Progress updates, blockers, dependencies
- **Weekly PM + PdM sync** — Alignment on priorities and risks
- **Twice-weekly team standups** — Delivery team coordination
- **Monthly stakeholder updates** — Status and progress reporting

### Quality Standards
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI pipeline
- Manual QA for feature acceptance when needed

### Risk & Blocker Escalation
- **Level 1:** Team-level triage in daily standup
- **Level 2:** PM escalates to Product Lead and dependent teams
- **Level 3:** Sponsor-level escalation for business-impacting issues

### Work Tracking
- Project board with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Small PRs (≤400 lines when possible)
- Issue links and acceptance criteria in PR descriptions
- At least one approval required before merging

## How to Use This Documentation

**For Project Managers:**  
Start with the [Overview](octoacme-project-management-overview.md), then follow the lifecycle phase docs in sequence as your project progresses. Use [Risks & Communication](octoacme-risks-and-communication.md) for managing escalations and stakeholder updates.

**For Product Managers:**  
Focus on [Initiation](octoacme-project-initiation.md) and [Planning](octoacme-project-planning.md) for defining scope and success metrics, then consult [Execution & Tracking](octoacme-execution-and-tracking.md) for day-to-day collaboration.

**For Developers:**  
See [Execution & Tracking](octoacme-execution-and-tracking.md) for PR workflows, quality standards, and sprint planning. Reference [Roles & Personas](octoacme-roles-and-personas.md) for context on your responsibilities.

**For Stakeholders:**  
Consult the [Communication](octoacme-risks-and-communication.md) doc for status reporting cadence and escalation paths.

## Key Principles

- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Deliver small, testable increments
- **Clear ownership:** Each project has named PM and PdM roles
- **Data-informed:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

## Getting Help

If you have questions about a specific process or need clarification, refer to the relevant doc or reach out to your Project Manager or Product Lead.
