# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management knowledge base. This directory contains our standardized processes for running projects from ideation through delivery.

## OctoAcme Project Management Overview

OctoAcme follows a structured, lifecycle-based approach to project management with emphasis on customer value, iterative delivery, clear ownership, and data-informed decisions.

**Core Principles:**
- Customer-first: prioritize customer value and usability
- Iterative delivery: deliver small, testable increments
- Clear ownership: each project has a named PM and Product Lead
- Data-informed decisions: measure impact and iterate based on evidence
- Psychological safety: encourage feedback and learning

## Project Lifecycle

Our projects follow a five-phase lifecycle:

1. **[Initiation](./octoacme-project-initiation.md)** — Validate business need, align stakeholders, create lightweight plan
2. **[Planning](./octoacme-project-planning.md)** — Break work into shippable increments, identify dependencies and risks
3. **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day delivery, maintain quality standards, track progress
4. **[Release & Deployment](./octoacme-release-and-deployment.md)** — Standardize release process, reduce risk, improve observability
5. **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings, convert to actionable improvements

## Key Processes Overview

### Workflow & Execution
OctoAcme uses a **sprint-based, project-board-driven workflow** to manage day-to-day execution. Work flows through standardized columns (Backlog → Ready → In Progress → In Review → QA → Done), with small PRs (≤400 lines preferred) requiring at least one approval before merge. The team rhythm consists of:

- **Daily standups (15 min)** — focused on progress, blockers, and dependencies
- **Weekly delivery sync** — show progress, updates, and flagged risks
- **Demo/Review** — at the end of each sprint or milestone

### Quality Assurance
Quality is embedded throughout the lifecycle via:
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

### Risk & Dependency Management
Risks are captured in a **Risk Register** (ID, Description, Impact, Likelihood, Owner, Mitigation, Status) and reviewed weekly. **Escalation is tiered**:
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

### Stakeholder Communication
Communication relies on a **weekly cadence** with status templates covering:
- Progress this week
- Next steps
- Risks & blockers
- Decisions needed

### Continuous Improvement
Projects close through **structured retrospectives (45–75 minutes)** that capture what went well, what could improve, and actionable next steps with assigned owners and due dates. Learning is systematized through action items tracked in the backlog or GitHub issues, reviewed in weekly PM syncs, and measured for impact.

## Key Resources

### Process Guides
- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to roles, artifacts, and lifecycle
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps to validate and authorize new projects
- **[Project Planning](./octoacme-project-planning.md)** — Creating actionable backlogs and release plans
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Daily operations, quality standards, and progress reporting
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identifying, managing, and communicating risks
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardized release procedures and rollback playbooks
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Running retros and tracking improvements

### Reference Materials
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Definitions of core roles (Developers, Product Managers, Project Managers)

## Key Roles & Responsibilities

- **Project Manager (PM):** Coordinates delivery, manages schedules, risk, and communications
- **Product Manager (PdM):** Defines outcomes, prioritizes backlog, measures success
- **Developers:** Implement features, collaborate on design and testability
- **QA/Testing:** Validate quality and acceptance criteria
- **Stakeholders:** Provide inputs and approvals

## Communication Cadence

- Daily standups (15 min) — progress, blockers, dependencies
- Weekly PM + PdM sync — alignment on priorities and risks
- Twice-weekly delivery team standups (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## Quick Start

**Starting a new project?**
1. Read the [Project Management Overview](./octoacme-project-management-overview.md) for context
2. Follow the [Project Initiation Guide](./octoacme-project-initiation.md) to validate and authorize work
3. Use the [Project Planning](./octoacme-project-planning.md) guide to create your backlog and roadmap

**Managing an active project?**
- Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) for daily operations
- Use [Risk Management & Communication](./octoacme-risks-and-communication.md) to manage risks and stakeholders
- Consult [Release & Deployment Guide](./octoacme-release-and-deployment.md) when preparing releases

**Capturing learnings?**
- Follow [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) after sprints or milestones

## How to Use This Knowledge Base

- Keep process documentation updated in this folder
- Reference specific guides for detailed workflows and templates
- Add new process docs and issue templates as organizational practices evolve
- Use these artifacts in Copilot Spaces to provide context-specific assistance to team members
