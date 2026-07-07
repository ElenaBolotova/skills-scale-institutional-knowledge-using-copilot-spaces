# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas (new additions)

### Release Engineer / Release Coordinator
**Role Summary**
Owns release pipelines and deployment readiness, ensuring releases are delivered reliably and with minimal customer impact.

**Responsibilities**
- Coordinate staging and production deployments
- Validate rollback and mitigation plans
- Maintain deployment runbooks and post-release monitoring checks
- Oversee release automation and pipeline health

**Interactions**
- Works with Developers and QA during pre-release activities
- Reports deployment status to PM and Product Lead
- Coordinates with SRE / Platform teams for infrastructure changes

---

### Delivery Engineer / Technical Program Engineer
**Role Summary**
Bridges implementation and delivery by maintaining CI/CD configurations, automation, and cross-team integration support to reduce delivery friction.

**Responsibilities**
- Maintain CI/CD configurations and test automation
- Support complex integrations and unblock technical dependencies
- Implement deployment/rollback automation and validation
- Maintain a dependency matrix and automation health dashboard

**Interactions**
- Partners with Developers for infra-impacting changes
- Collaborates with PM for scheduling and dependency planning
- Works with SRE for production readiness and incident response

---

### UX Researcher / Design Lead
**Role Summary**
Leads user research and design validation to ensure product decisions are grounded in user needs.

**Responsibilities**
- Conduct usability testing and research studies
- Produce artifacts such as personas, journeys, and design specs
- Provide design acceptance criteria and accessibility guidance

**Interactions**
- Works with Product Manager to validate hypotheses and acceptance criteria
- Provides deliverables to Developers and QA for implementation and verification

---

### Security Reviewer / Security Contact
**Role Summary**
Serves as the security point-of-contact for projects, performing security reviews and ensuring compliance with security standards.

**Responsibilities**
- Conduct security reviews and threat modeling
- Flag vulnerabilities and recommend mitigations
- Ensure security scans are run and addressed before release
- Escalate high-risk issues to Product Lead and Security on-call

**Interactions**
- Engages with Developers and Delivery Engineer during design and PR reviews
- Coordinates with PM and Product Lead on remediation timelines

---

### Stakeholder Communications Lead / Customer Liaison
**Role Summary**
Manages stakeholder updates and external communications to ensure consistent messaging and capture stakeholder feedback.

**Responsibilities**
- Draft release announcements and stakeholder updates
- Coordinate feedback intake from sales, support, and customer success
- Maintain stakeholder communication templates and cadence

**Interactions**
- Coordinates with PM for weekly status and milestone announcements
- Works with Product Lead on messaging and decision communications

---

### Vendor / Third-party Integrations Owner
**Role Summary**
Manages relationships and technical integrations with external vendors and third-party services.

**Responsibilities**
- Coordinate integration testing with external providers
- Track contract constraints and third-party SLAs affecting delivery
- Own handoffs and acceptance criteria for vendor-related work

**Interactions**
- Works with PM and Delivery Engineer to align timelines and testing
- Informs Stakeholder Communications Lead of third-party constraints

---

### Data Analyst / Metrics Owner
**Role Summary**
Defines and tracks success metrics, implements event tracking, and analyzes results to inform product decisions.

**Responsibilities**
- Define success metrics and measurement plans
- Implement tracking and create dashboards for key signals
- Analyze post-release data and surface regressions or opportunities

**Interactions**
- Partners with Product Manager to set measurable outcomes
- Provides dashboards and reports to PM and Product Lead
- Works with Developers to instrument analytics
