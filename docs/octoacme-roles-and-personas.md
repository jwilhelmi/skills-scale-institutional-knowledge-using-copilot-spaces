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

## Additional Personas (New)

The following personas are commonly involved in cross-functional delivery and were added to clarify ownership and interactions.

### Release / Delivery Lead

Role Summary
- Coordinates release activities and owns the release checklist and deployment readiness.

Responsibilities
- Coordinate release windows and cutover plans
- Own and maintain deployment checklist and rollback plans
- Validate smoke tests and post-deploy verifications
- Liaise with SRE/Operations to schedule and run deployments
- Communicate release status to stakeholders and support

Typical Communication / Meetings
- Release planning meetings
- Pre-release readiness review
- Post-release verification syncs

Primary Interactions
- Works with PM (scheduling), Developers (release readiness), QA (sign-off), SRE/Operations (deployment), and Stakeholders (communication)

---

### Security Engineer / Security Reviewer

Role Summary
- Ensures changes meet security standards, performs threat modeling and security reviews for significant changes.

Responsibilities
- Conduct security reviews and threat modeling for changes with material risk
- Ensure CI security scanning is configured and alerts are triaged
- Advise on mitigation plans and security-oriented acceptance criteria
- Coordinate with Legal/Compliance for regulatory requirements

Typical Communication / Meetings
- Design reviews for high-risk features
- Security triage and remediation meetings

Primary Interactions
- Partners with Developers (fixes/remediations), PM/PdM (risk assessment), CI/DevOps (security tooling), and Legal/Security teams (compliance)

---

### UX Researcher / Designer

Role Summary
- Leads research and design to validate user value and usability of proposed solutions.

Responsibilities
- Run discovery and usability research
- Provide design artifacts, prototypes, and acceptance criteria for UX flows
- Validate accessibility and usability requirements
- Collaborate on acceptance criteria for features with significant UX components

Typical Communication / Meetings
- Design critique sessions
- Research findings review with product and engineering

Primary Interactions
- Collaborates with PdM (requirements), Developers (implement designs), QA (UX acceptance), and Stakeholders (user feedback)

---

### Data Analyst / Product Analyst

Role Summary
- Defines measurable success metrics, validates instrumentation, and provides analysis to inform decisions.

Responsibilities
- Define success metrics and key signals
- Specify telemetry and event instrumentation
- Validate data quality and dashboards
- Perform analysis to inform prioritization and measure impact

Typical Communication / Meetings
- Metrics review and dashboard syncs
- Post-release analysis and experiment reviews

Primary Interactions
- Partners with PdM (success metrics), Developers (telemetry implementation), PM (reporting), and Stakeholders (insights)

---

### SRE / On-call Engineer

Role Summary
- Owns production reliability, runbooks, and incident response for services in scope.

Responsibilities
- Maintain runbooks and runbook drills
- Participate in on-call rotations and incident response
- Tune observability and alerting thresholds
- Lead post-incident reviews and corrective action tracking

Typical Communication / Meetings
- On-call handovers
- Incident war rooms and post-incident retrospectives

Primary Interactions
- Coordinates with Developers (fixes), PM (incident impact assessment), Security (incident response), and Support (customer impact)

---

### Customer Success / Support Liaison

Role Summary
- Represents customers' operational needs, surfaces customer pain points, and coordinates communications for customer-impacting events.

Responsibilities
- Triage and report customer issues and patterns
- Validate release notes and customer communications for accuracy
- Coordinate escalations and customer-facing mitigations

Typical Communication / Meetings
- Support handoffs and weekly prioritization syncs
- Incident customer communications

Primary Interactions
- Works with PM/PdM (prioritization), QA (reproduction), Developers (investigation), and Stakeholders (customer updates)

---

## How to use these personas
- Each persona entry includes: Role Summary, Responsibilities, Typical Communication/Meetings, and Primary Interactions.
- Suggested next step: include an RACI or simple Responsibility matrix in the project README or project board for each major milestone to make ownership explicit.
