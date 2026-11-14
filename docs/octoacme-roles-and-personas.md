# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It describes role ownership, decision authority, handoffs, and collaboration across the project lifecycle. Roles are responsibilities, not mandatory separate job titles; adapt participation to project size, risk, and context.

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

### Interactions and Handoffs
- Confirm product intent and acceptance criteria with the Product Manager.
- Share estimates, blockers, technical risks, and delivery progress with the Project Manager.
- Work with the Technical Lead on design and implementation decisions and with the Quality / Test Lead on prevention and defect resolution.

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Clarify product scope and acceptance expectations

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with project and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

### Interactions and Handoffs
- Align outcomes and major product trade-offs with the Executive Sponsor / Business Owner.
- Partner with the Project Manager on sequencing, risks, and stakeholder updates.
- Work with Developers and the Technical Lead to assess feasibility, and with the Customer / User Representative to understand needs and validate outcomes.
- Clarify acceptance criteria with the Quality / Test Lead and release impacts with the Operations / Release Owner.

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently and remain accountable for overall project coordination.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication
- Surface issues and route decisions to the appropriate owner

### Goals
- Deliver projects on time and within agreed scope
- Minimize unplanned work and unresolved escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

### Interactions and Handoffs
- Coordinate scope, milestones, and delivery risks with the Product Manager.
- Work with Developers and the Technical Lead to understand estimates, dependencies, and technical risks.
- Engage a Project Coordinator for tracking support while retaining accountability for delivery coordination.
- Escalate unresolved business, resource, or scope decisions to the Executive Sponsor / Business Owner; coordinate release timing with the Operations / Release Owner.

---

## Executive Sponsor / Business Owner

### Purpose
Sets strategic direction, secures organizational support, and resolves escalations that affect business outcomes, scope, or investment.

### Responsibilities and Authority
- Establish or endorse strategic goals and expected business outcomes.
- Secure sponsorship and help resolve organizational or resource constraints.
- Make or delegate major scope and investment decisions and resolve escalations beyond the delivery team's authority.

### Outputs and Interactions
- Provides strategic direction and decisions to the Product Manager and Project Manager.
- Aligns with the Product Manager on outcomes and priorities and receives delivery status and escalation information from the Project Manager.
- Consults the Technical Lead on significant feasibility or technical-risk trade-offs where relevant.

This responsibility may be held by a senior stakeholder rather than a dedicated project role. It does not replace the Product Manager's product decisions or the Project Manager's day-to-day delivery coordination.

---

## Project Coordinator / Delivery Coordinator

### Purpose
Supports the Project Manager with delivery administration and follow-up so that actions, decisions, dependencies, and status remain visible.

### Responsibilities and Outputs
- Maintain schedules, action items, decision logs, and meeting notes.
- Follow up on dependencies and collect status information.
- Prepare status-report inputs and keep project records current.

### Interactions and Authority
- Works with the Project Manager to identify and track follow-ups and prepare reporting.
- Coordinates with Developers, Product Managers, and other contributors to gather updates and clarify action ownership.
- Surfaces overdue actions and emerging blockers to the Project Manager; does not replace the Project Manager's accountability for overall coordination, delivery, or escalation.

This is a supporting responsibility that may be combined with the Project Manager role on smaller efforts.

---

## Technical Lead / Solution Architect

### Purpose
Guides the technical approach, architecture, and engineering trade-offs so that the solution is feasible, maintainable, and aligned with relevant technical constraints.

### Responsibilities and Outputs
- Guide architecture, design standards, and technical direction.
- Assess technical trade-offs, dependencies, and risks; contribute estimates and sequencing options.
- Provide design guidance and help resolve technical blockers.

### Interactions and Authority
- Partners with Developers on implementation choices, reviews, and technical quality.
- Works with the Product Manager and Project Manager on feasibility, estimates, technical risks, dependencies, and sequencing.
- Consults Security / Privacy Specialists and Operations / Release Owners when design or deployment has relevant security, privacy, or operational concerns.
- Recommends technical approaches; business scope and investment decisions remain with their designated owners.

The role may be held by a senior developer or shared among engineers when a dedicated lead is not needed.

---

## Quality / Test Lead

### Purpose
Defines the quality and validation approach, coordinates testing and defect triage, and makes readiness risks visible.

### Responsibilities and Outputs
- Define test strategy, validation responsibilities, and quality criteria.
- Coordinate testing, defect triage, and reporting of quality risks.
- Provide evidence and recommendations about whether agreed quality criteria have been met.

### Interactions and Authority
- Works with Developers on testability, defect prevention, and fixes.
- Partners with the Product Manager to clarify acceptance criteria and expected user outcomes.
- Shares readiness risks with the Project Manager and Operations / Release Owner to inform release planning.
- Escalates unresolved quality risks to the appropriate decision owner; does not independently change product scope or acceptance priorities.

Testing responsibilities may be shared with Developers or other team members on smaller projects; higher-risk work may warrant a dedicated lead.

---

## Operations / Release Owner

### Purpose
Plans deployment and operational readiness, including monitoring and rollback, so that releases can be delivered and supported safely.

### Responsibilities and Outputs
- Coordinate deployment plans, operational checks, monitoring, and rollback preparation.
- Review operational readiness and communicate deployment constraints or risks.
- Coordinate post-release verification and operational handoff as appropriate.

### Interactions and Authority
- Aligns release timing and communications with the Project Manager and Product Manager.
- Works with the Technical Lead and Developers on deployment, monitoring, and rollback details.
- Coordinates with the Quality / Test Lead on validation and readiness evidence.
- Raises operational risks to the Project Manager and relevant decision owners; release authorization follows the organization's established governance.

This responsibility can be shared by engineering or operations staff where a separate release role is unnecessary.

---

## Security / Privacy Specialist

### Purpose
Advises on security and privacy requirements, relevant risks, and controls, and escalates compliance concerns.

### Responsibilities and Outputs
- Clarify applicable security, privacy, and data-handling requirements.
- Review relevant designs, risks, and controls and recommend mitigations.
- Document concerns and escalate unresolved compliance or risk issues through appropriate governance.

### Interactions and Authority
- Works with the Product Manager to clarify requirements and with Developers and the Technical Lead to validate design and implementation.
- Coordinates with the Quality / Test Lead and Operations / Release Owner on relevant verification and operational controls.
- Shares material risks with the Project Manager and designated decision owners. Specialist advice informs decisions; formal acceptance of residual risk follows organizational policy.

Engage this role when the project's data, exposure, or regulatory context makes specialist review relevant; it need not be a dedicated position on every project.

---

## Customer / User Representative

### Purpose
Brings user needs, feedback, and context into discovery, prioritization, and acceptance so that delivery remains connected to intended outcomes.

### Responsibilities and Outputs
- Share user needs, pain points, and feedback from relevant customer or user groups.
- Participate in discovery, reviews, and validation where appropriate.
- Provide feedback on whether proposed solutions address user needs and expected outcomes.

### Interactions and Authority
- Partners with the Product Manager, who remains accountable for product vision and prioritization, to represent user outcomes.
- Provides feedback to Developers and the Technical Lead during reviews and validation.
- Helps the Project Manager understand user impacts relevant to delivery and communications.
- Contributes evidence and feedback to acceptance discussions; formal product acceptance is determined by the designated owner.

This responsibility may be performed by a customer, internal user, researcher, or designated advocate, depending on the project.

---

## Role Combinations and Lifecycle Participation

These are candidate responsibilities, not required separate job titles. One person may hold multiple roles, and specialist roles may be engaged only when the project's size, risk, and context warrant them. When roles are combined, make any potential conflicts of interest or decision boundaries explicit.

Typical participation includes:
- **Initiation:** Executive Sponsor / Business Owner provides strategic sponsorship; the Product Manager frames outcomes; the Project Manager establishes delivery coordination. User representatives may inform discovery.
- **Planning:** The Project Manager coordinates the plan; the Product Manager prioritizes scope; Developers and the Technical Lead contribute feasibility and estimates. The Project Coordinator may support tracking, while Quality, Security / Privacy, and Operations roles identify relevant plans and risks.
- **Execution:** Developers deliver and test work; the Product Manager clarifies product questions; the Project Manager manages coordination, dependencies, and reporting. Relevant specialists advise and track their areas.
- **Release:** The Operations / Release Owner coordinates operational readiness; Developers, the Technical Lead, and Quality / Test Lead contribute deployment and validation evidence. Security / Privacy Specialists review relevant controls, and the Product Manager coordinates product and user-facing readiness.
- **Retrospective:** The Project Manager facilitates review of delivery; the Product Manager considers outcome and user feedback; Developers and relevant contributors identify technical, quality, and process improvements.

### Decision and Escalation Guidance
- Product scope and priority decisions belong to the Product Manager within delegated authority; major business scope or investment decisions go to the Executive Sponsor / Business Owner or their delegate.
- The Project Manager owns delivery coordination and makes schedule, dependency, and escalation status visible; the appropriate accountable owner resolves decisions outside the Project Manager's authority.
- The Technical Lead guides technical recommendations, while the designated product or business owner decides trade-offs that change outcomes, scope, or investment.
- Quality, operations, security, and privacy specialists identify readiness concerns and recommend actions. Acceptance of residual risk and release authorization follow the organization's governance.
- Record significant decisions, their owners, and resulting actions in the project's agreed documentation so handoffs remain clear.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Tailor role participation to the project rather than treating every role as a mandatory job title.
