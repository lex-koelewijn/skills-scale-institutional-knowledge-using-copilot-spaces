# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Personas describe accountability and collaboration needs; they do not require a separate person for every role. On smaller projects, one person may cover multiple personas when conflicts of interest and workload are managed explicitly.

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

### Accountability Boundaries
- Own implementation quality, technical estimates, and evidence that acceptance criteria are met.
- Escalate delivery, security, reliability, or dependency risks rather than silently accepting them.
- Do not unilaterally change product priorities, release scope, or stakeholder commitments.

### Key Deliverables
- Production code and automated tests
- Technical documentation and code review feedback
- Implementation estimates, risks, and operational notes

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

### Accountability Boundaries
- Own product outcomes, priority, scope decisions, and acceptance of delivered value.
- Make trade-offs visible to the Project Manager and delivery team.
- Do not override technical, security, or operational release gates without documented risk acceptance by the appropriate accountable owner.

### Key Deliverables
- Problem statement and success metrics
- Prioritized backlog with acceptance criteria
- Roadmap, release scope, and stakeholder decisions

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

### Accountability Boundaries
- Own delivery coordination, dependency tracking, risk reporting, and stakeholder communication.
- Escalate issues through the documented team, Product Lead, and sponsor paths.
- Do not make product-priority or technical-architecture decisions without the accountable Product Manager or Technical Lead.

### Key Deliverables
- Project plan, milestone map, and status updates
- Risk register, dependency log, and decision log
- Meeting cadence, escalation records, and release coordination plan

---

## Delivery Manager / Scrum Master

### Role Summary
The Delivery Manager or Scrum Master improves team flow and facilitates the delivery rhythm. This role is complementary to the Project Manager: it focuses on team working practices and impediment removal, while the Project Manager coordinates the broader project plan, risks, and stakeholders.

### Responsibilities
- Facilitate planning, standups, reviews, and retrospectives
- Maintain visibility of work in progress, blockers, and flow metrics
- Help the team keep backlog items ready and appropriately sized
- Remove or escalate impediments
- Reinforce agreed working agreements and the Definition of Done

### Goals
- Improve flow, predictability, and team focus
- Reduce avoidable blockers and work-in-progress overload
- Turn retrospective findings into owned improvements

### Typical Communication
- Daily delivery-team coordination
- Sprint or iteration planning and review facilitation
- Impediment updates with the Project Manager and Product Manager

### Accountability Boundaries
- Own the delivery process and visibility of impediments, not the team's technical or product decisions.
- The Project Manager remains accountable for project-level schedule, risk, and stakeholder commitments.
- The Product Manager remains accountable for priority and value decisions.

### Key Deliverables
- Ready backlog and iteration plan
- Blocker and flow-metric updates
- Retrospective actions with owners and due dates

### Interactions
- Partners with the Project Manager on schedule, risks, dependencies, and escalation.
- Works with the Product Manager on backlog readiness and prioritization trade-offs.
- Helps Developers and QA/Testing surface blockers without taking away their delivery ownership.
- Coordinates with the Technical Lead, Designer, and Release/Ops Lead when workflow issues affect design, implementation, or deployment readiness.

---

## UX/UI or Service Designer

### Role Summary
The UX/UI or Service Designer represents user needs and designs usable, accessible experiences and service flows. The role connects discovery and validation to implementation-ready requirements.

### Responsibilities
- Conduct discovery, user research, and usability validation
- Maintain user journeys, service blueprints, flows, and interface designs
- Identify accessibility and usability needs
- Contribute user-centered acceptance criteria
- Validate that delivered experiences address the intended problem

### Goals
- Improve usability, accessibility, and customer outcomes
- Reduce rework caused by unclear user needs or design decisions
- Make customer and stakeholder feedback actionable for the team

### Typical Communication
- Discovery workshops and design reviews
- Design artifacts linked to backlog items
- Usability findings shared with Product, Developers, QA/Testing, and stakeholders

### Accountability Boundaries
- Owns the quality and evidence of user experience recommendations and design artifacts.
- Advises on user needs but does not independently set product priority or technical implementation.
- Design exceptions and usability risks should be visible in acceptance criteria, decisions, or the risk register.

### Key Deliverables
- User journeys, flows, wireframes, or service blueprints
- Usability and accessibility findings
- Design specifications and user-centered acceptance criteria

### Interactions
- Collaborates with the Product Manager on problem statements, outcomes, and success metrics.
- Works with Developers and the Technical Lead on feasibility, design trade-offs, and implementation detail.
- Partners with QA/Testing to define usability and accessibility checks.
- Involves stakeholders in reviews and acceptance, while the Product Manager retains product acceptance accountability.

---

## Technical Lead / Architect

### Role Summary
The Technical Lead or Architect guides technical direction and makes cross-cutting engineering risks visible. The role supports Developers without replacing their implementation ownership.

### Responsibilities
- Guide technical direction and document significant decisions
- Identify architectural risks, dependencies, and integration points
- Support estimation and sequencing of technical work
- Define maintainability, reliability, observability, and performance expectations
- Review designs and help resolve complex technical issues

### Goals
- Enable sustainable delivery and reduce avoidable technical risk
- Keep architecture aligned with product outcomes and operational needs
- Make important technical trade-offs explicit and reversible where possible

### Typical Communication
- Technical design documents and decision records
- Architecture and code reviews
- Risk and dependency discussions with Product, Project, Security, and Operations

### Accountability Boundaries
- Owns technical direction and architectural decision quality within the agreed scope.
- Developers own implementation details and code quality within that direction.
- Does not decide product priority or accept unresolved security and operational risks without the relevant accountable owner.

### Key Deliverables
- Technical design and architecture decision records
- Technical risk, dependency, and migration plans
- Non-functional requirements and readiness recommendations

### Interactions
- Works with Developers on design, implementation, and reviews.
- Partners with the Product Manager and Project Manager on technical trade-offs, sequencing, and impact on milestones.
- Coordinates with Security/Privacy on controls and with Release/Ops on reliability and operational readiness.
- Works with QA/Testing to make non-functional and integration risks testable.

---

## Security and Privacy Partner

### Role Summary
The Security and Privacy Partner identifies security, privacy, and compliance risks early and helps the team select proportionate controls. This role may be a dedicated specialist or a consulted function for smaller initiatives.

### Responsibilities
- Assess data handling, access, threat, privacy, and compliance risks
- Advise on controls, threat modeling, secure design, and privacy-by-design practices
- Define required security and privacy validation
- Review findings and confirm mitigation or documented risk acceptance before release
- Escalate material risks through the security incident or project escalation path

### Goals
- Prevent avoidable security and privacy incidents
- Integrate controls early enough to avoid late delivery surprises
- Make residual risk and ownership explicit

### Typical Communication
- Design and threat-model reviews
- Security findings in the risk register or issue tracker
- Release-readiness decisions and incident communications

### Accountability Boundaries
- Owns the quality of security and privacy advice and the clarity of identified risks.
- The designated business or product owner remains accountable for accepting residual business risk where policy permits.
- Critical security incidents follow the security incident runbook and are not handled only through normal project status reporting.

### Key Deliverables
- Security and privacy assessment or threat model
- Required controls and validation plan
- Security findings, mitigations, and release recommendation

### Interactions
- Works with the Technical Lead on architecture, data flows, and controls.
- Works with Developers and QA/Testing on secure implementation and validation.
- Coordinates with the Project Manager on risk status, escalation, and release gates.
- Advises the Product Manager and stakeholders on customer, regulatory, and business impact.

---

## Data / Analytics or Measurement Lead

### Role Summary
The Data, Analytics, or Measurement Lead turns intended outcomes into observable measures and verifies data quality. The role connects Product success metrics to implementation instrumentation and post-release learning.

### Responsibilities
- Define measurement plans, baselines, and target outcomes
- Specify instrumentation, event definitions, and data ownership
- Validate data quality and metric interpretation
- Report whether delivered changes achieved their intended outcomes
- Identify limitations, biases, or uncertainty in the evidence

### Goals
- Support evidence-based prioritization and iteration
- Prevent decisions based on incomplete or misleading data
- Shorten the feedback loop between release and learning

### Typical Communication
- Metric definitions in the one-pager or feature documentation
- Instrumentation requirements with Developers and QA/Testing
- Outcome reporting in reviews, stakeholder updates, and retrospectives

### Accountability Boundaries
- Owns measurement definitions, data-quality checks, and interpretation of evidence.
- The Product Manager owns outcome and priority decisions informed by the evidence.
- Does not treat instrumentation as complete until the data is validated in the intended environment.

### Key Deliverables
- Measurement and instrumentation plan
- Metric definitions, baselines, and dashboards
- Post-release outcome analysis and recommendations

### Interactions
- Works with the Product Manager on success metrics and decision thresholds.
- Works with Developers on instrumentation and with QA/Testing on data validation.
- Provides the Project Manager with status signals for reporting and retrospectives.
- Collaborates with UX/UI or Service Design on qualitative and quantitative evidence.

---

## Release / Operations or Site Reliability Lead

### Role Summary
The Release, Operations, or Site Reliability Lead ensures that a change can be deployed, observed, supported, and rolled back safely. The role connects delivery work to the release and incident playbooks.

### Responsibilities
- Define operational readiness and deployment requirements
- Coordinate environment, configuration, monitoring, alerting, and rollback planning
- Lead or support deployment, smoke testing, and post-deploy verification
- Ensure incident response and support handoff information is complete
- Review reliability, capacity, and observability risks before release

### Goals
- Reduce deployment and operational risk
- Make failures detectable and recoverable
- Ensure stakeholders and support teams know what changed and how to respond

### Typical Communication
- Release readiness reviews and deployment plans
- Runbooks, dashboards, and incident channels
- Post-release verification and incident follow-up

### Accountability Boundaries
- Owns operational readiness recommendations and deployment execution within the agreed process.
- Developers and the Technical Lead remain accountable for product and technical quality; QA/Testing remains accountable for validation evidence.
- A release may be delayed or escalated when required rollback, monitoring, or support conditions are not met.

### Key Deliverables
- Deployment, rollback, and smoke-test plan
- Monitoring, alerting, and operational runbook updates
- Post-deploy verification and support handoff

### Interactions
- Partners with Developers and the Technical Lead on reliability, observability, and deployment design.
- Works with QA/Testing on smoke tests and release validation.
- Coordinates with the Project Manager on release timing, risks, and communications.
- Works with the Product Manager and stakeholders on release impact, known issues, and support readiness.

---

## Lifecycle Collaboration and Accountability

The following matrix is a lightweight guide. `A` means the role is accountable for the outcome or decision, `R` means it leads or performs the work, `C` means it should be consulted, and `I` means it should be kept informed. A project may combine roles, but the accountability should remain explicit.

| Lifecycle stage | Primary accountability | Common contributors and consultees | Expected evidence or handoff |
|---|---|---|---|
| Initiation | Product Manager: problem, goal, success metrics; Project Manager: stakeholders, initial timeline, and risks | Designer, Technical Lead, Data/Analytics, Security/Privacy, Release/Ops | One-pager, stakeholder list, initial risks, outcome measures, go/no-go decision |
| Planning | Product Manager: prioritized scope; Project Manager: plan and dependencies; Technical Lead: technical approach | Delivery Manager, Developers, Designer, QA/Testing, Security/Privacy, Data/Analytics, Release/Ops | Estimated backlog, acceptance criteria, Definition of Done, release plan, risk register, test approach |
| Execution and tracking | Developers: implementation; Delivery Manager: flow and impediments; Project Manager: coordination and reporting | Product Manager, Technical Lead, Designer, QA/Testing, Security/Privacy, Data/Analytics, Release/Ops | Reviewed PRs, test evidence, updated board, risk/dependency status, demos, decisions |
| Release and deployment | Release/Ops: operational readiness and deployment; Product Manager: release scope and stakeholder acceptance | Developers, Technical Lead, QA/Testing, Security/Privacy, Project Manager, Data/Analytics | Passing CI and scans, release notes, smoke tests, rollback plan, monitoring, post-deploy verification |
| Retrospective and continuous improvement | Project Manager: follow-up and visibility; Product Manager: outcome learning; Delivery Manager: team-process improvements | All relevant personas and stakeholders | Retrospective notes, outcome analysis, owned action items, updated risks and process documentation |

When responsibilities overlap, record the decision owner in the project charter, backlog, risk register, or release document. Use the documented escalation path when a blocker, dependency, security concern, or release risk cannot be resolved at team level.

---

## Role Assignment and Accountability Checklist

Use this checklist during initiation or kickoff. Select only the roles needed for the initiative and record combined responsibilities where one person covers multiple personas.

- [ ] Product Manager and Project Manager are named.
- [ ] Developer and QA/Testing ownership is clear.
- [ ] Delivery facilitation is assigned, even if combined with the Project Manager role.
- [ ] User experience and accessibility ownership is assigned when the change affects users or services.
- [ ] Technical direction and architecture decisions have an accountable owner.
- [ ] Security, privacy, and compliance needs have been assessed.
- [ ] Success metrics, instrumentation, and data-quality ownership are defined.
- [ ] Release, operations, monitoring, rollback, and support handoff ownership are defined.
- [ ] Combined roles and potential conflicts of interest are documented.
- [ ] Key deliverables, decision boundaries, and escalation paths are recorded in the project artifacts.
- [ ] Stakeholders know when they will be consulted, informed, or asked to approve a decision.

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Use the lifecycle matrix and checklist to identify missing ownership before planning or release.
