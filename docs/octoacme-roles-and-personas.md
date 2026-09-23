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

## Release Managers / Delivery Coordinators

### Role Summary
Release Managers or Delivery Coordinators own the coordination and readiness of releases across teams. They make sure that approved work can move safely from development through deployment and that stakeholders understand the release plan.

### Responsibilities
- Define release scope, sequencing, milestones, and deployment windows with the PM and Product Manager
- Confirm acceptance criteria, quality checks, security reviews, release notes, and rollback plans are complete
- Coordinate staging validation, production deployment activities, and post-deployment verification
- Track release blockers and coordinate mitigations or rollback decisions
- Maintain the release checklist and communicate status, changes, and outcomes

### Decision Rights and Approval Boundaries
- May recommend delaying, rescheduling, or rolling back a release when readiness criteria are not met or risk exceeds the agreed tolerance
- Does not unilaterally change product scope, business priority, or technical standards; those decisions remain with the Product Manager, sponsor, and appropriate technical or security approvers

### Interactions Across the Lifecycle
- Partners with the PM on timelines, dependencies, and escalation; with the Product Manager on scope and acceptance; and with Developers and QA on validation and defect readiness
- Engages Security / Compliance Partners and Technical Architects before release when their approval or review is required
- Coordinates Customer Success / Support Liaisons and stakeholders on customer communications, support readiness, and release outcomes
- Participates most actively in planning, execution tracking, release review, deployment, and post-release follow-up

---

## Security / Compliance Partners

### Role Summary
Security / Compliance Partners identify and validate security, privacy, regulatory, and policy requirements so that delivery decisions account for risk from initiation through release.

### Responsibilities
- Translate applicable security, privacy, and compliance obligations into actionable requirements and acceptance checks
- Review designs, data flows, integrations, access controls, and operational plans for material risk
- Coordinate security testing, evidence collection, and remediation tracking
- Advise on exceptions, compensating controls, incident readiness, and post-release monitoring
- Confirm that required reviews and approvals are documented before launch

### Decision Rights and Approval Boundaries
- May require remediation, additional evidence, or escalation when a material security or compliance risk is unresolved
- Owns security and compliance recommendations and approval for requirements within its authority, but does not own product priority, delivery dates, or implementation design
- Security incidents follow the security incident runbook and escalation path rather than normal project decision-making

### Interactions Across the Lifecycle
- Works with the PM to add security and compliance work to the plan and risk register, and with the Product Manager to clarify customer and regulatory impact
- Advises the Technical Architect / Engineering Lead and Developers on secure designs and implementation trade-offs
- Partners with QA on test coverage and evidence, Release Managers on readiness gates, and Customer Success / Support Liaisons on customer-facing implications
- Participates early in initiation and planning, at design and review checkpoints, and before release approval; monitors material risks during execution

---

## Technical Architects / Engineering Leads

### Role Summary
Technical Architects or Engineering Leads guide the technical direction of a project. They turn product goals into maintainable architectures, coordinate engineering decisions, and make technical risks visible.

### Responsibilities
- Define architecture, integration patterns, interfaces, and non-functional requirements
- Facilitate technical design reviews and document significant decisions
- Evaluate feasibility, technical debt, scalability, reliability, and operational trade-offs
- Coordinate engineering estimates, sequencing, and cross-team dependencies
- Support Developers and QA with implementation strategy, testability, and observability guidance

### Decision Rights and Approval Boundaries
- Owns technical recommendations and architecture decisions within the agreed scope, standards, and governance model
- May reject or escalate an implementation that creates unacceptable technical, reliability, or operational risk
- Does not independently change product outcomes, priority, or committed scope; collaborates with the Product Manager and PM when technical constraints affect those decisions

### Interactions Across the Lifecycle
- Partners with the Product Manager on feasibility and trade-offs and with the PM on milestones, dependencies, and risk escalation
- Leads technical collaboration with Developers and QA and consults Security / Compliance Partners on controls and threat considerations
- Provides Release Managers with deployment, migration, monitoring, and rollback requirements
- Participates in initiation feasibility checks, planning and design, execution reviews, incident response, and release readiness

---

## Customer Success / Support Liaisons

### Role Summary
Customer Success / Support Liaisons represent customer-facing and service-operational needs during delivery. They connect project teams with user feedback, support readiness, and post-launch service continuity.

### Responsibilities
- Bring customer needs, recurring support issues, and usability feedback into discovery and prioritization
- Identify support workflows, training needs, documentation gaps, and customer communications required for launch
- Coordinate support readiness, escalation routes, known-issue handling, and feedback collection after release
- Help validate customer-facing acceptance criteria and participate in demos or user acceptance activities
- Report adoption signals, customer impact, and emerging issues to the project team

### Decision Rights and Approval Boundaries
- May require support-readiness actions or escalate a launch risk when customers cannot be supported safely or effectively
- Advises on customer impact and communication but does not set product priority, approve technical architecture, or replace formal QA or security approval

### Interactions Across the Lifecycle
- Works with the Product Manager on customer outcomes and prioritization and with the PM on communication plans, dependencies, and escalations
- Partners with Developers, QA, and Technical Architects to clarify user workflows and operational scenarios
- Coordinates with Release Managers on launch communications and verification, and with stakeholders on impact and feedback
- Participates in initiation discovery, planning, demos and acceptance review, release preparation, and post-release monitoring

---

## Documentation Stewards / Knowledge Owners

### Role Summary
Documentation Stewards or Knowledge Owners maintain the accuracy, discoverability, and continuity of project knowledge. They help the team preserve decisions and make processes repeatable as work moves across roles and phases.

### Responsibilities
- Define and maintain the project’s documentation structure, ownership, and update cadence
- Keep plans, decision logs, requirements, runbooks, release notes, and retrospective actions current
- Capture key decisions, assumptions, handoffs, and lessons learned in a searchable source of truth
- Check documentation for consistency with approved process guidance and link related artifacts
- Identify stale or missing information and coordinate updates with the accountable role

### Decision Rights and Approval Boundaries
- May request clarification or reject publication of incomplete or conflicting documentation until the accountable owner resolves it
- Owns documentation quality and continuity, but does not approve product, technical, security, or release decisions unless separately assigned that role

### Interactions Across the Lifecycle
- Works with the PM to maintain core project artifacts and status reporting, with the Product Manager on requirements and outcomes, and with Developers and QA on technical and test documentation
- Records decisions and approvals from Technical Architects, Security / Compliance Partners, Release Managers, Customer Success / Support Liaisons, and stakeholders
- Participates throughout initiation, planning, execution, review, release, and retrospective activities so that knowledge is updated as decisions change

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Assign a named person or team to each applicable persona at project initiation, and record overlapping responsibilities and approval boundaries in the project plan.
