# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It expands the core model to cover cross-functional work across planning, design, delivery, release, operations, and stakeholder communication.

---

## Core Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Expanded Roles for Cross-Functional Delivery

### Engineering Manager

#### Role Summary
Engineering Managers support the health of the engineering organization by managing team capacity, staffing, growth, and cross-team coordination.

#### Responsibilities
- Align staffing and capacity with roadmap priorities
- Support performance, coaching, and team health
- Coordinate dependencies across engineering teams
- Escalate resource or prioritization conflicts to Product Lead and PM
- Help identify and mitigate delivery risk from staffing gaps

#### Interactions
- Works with Project Managers to balance roadmap commitments with team capacity
- Partners with Technical Leads on staffing, implementation trade-offs, and technical risks
- Coordinates with Product Managers when scope, timeline, or staffing changes need to be rebalanced

#### Typical Engagement
- During planning, resourcing, and staffing reviews
- When team capacity or skill gaps affect delivery commitments
- During escalations that require cross-team prioritization

---

### Technical Lead (Tech Lead)

#### Role Summary
Technical Leads guide the technical direction of a project or component, facilitate design decisions, and maintain delivery quality.

#### Responsibilities
- Own technical design and architecture decisions for a feature or system area
- Review implementation quality, maintainability, and reliability
- Facilitate design and code review for complex work
- Coordinate technical dependencies and sequencing with product and delivery teams
- Define or validate technical risk mitigations and fallback plans

#### Interactions
- Works closely with Developers to shape feasible solutions
- Partners with Product Managers and UX designers to align scope with technical constraints
- Coordinates with QA Lead and Release Engineer for readiness and risk checks

#### Typical Engagement
- During technical design, solution shaping, and implementation reviews
- For architecture decisions, dependency management, and release readiness decisions

---

### UX / Product Designer

#### Role Summary
UX and Product Designers translate user needs into clear, testable interfaces and flows that improve usability and customer outcomes.

#### Responsibilities
- Conduct user research and synthesize customer feedback
- Design flows, interactions, and prototypes for product features
- Validate usability and accessibility with stakeholders or pilot users
- Partner with product and engineering on acceptance criteria and edge cases
- Ensure design decisions are documented for implementation and QA

#### Interactions
- Partners with Product Managers to shape user problem statements and success criteria
- Hands off designs and validation criteria to Developers and QA
- Helps clarify ambiguity and reduce rework during implementation

#### Typical Engagement
- Discovery, concept validation, feature design, and usability testing
- When requirements need clarity around user behavior or edge cases

---

### QA Lead / Test Lead

#### Role Summary
QA Leads define the quality strategy, coordinate validation efforts, and ensure releases meet acceptance and regression standards.

#### Responsibilities
- Define test strategy, coverage requirements, and release gates
- Coordinate manual and automated regression testing
- Validate feature behavior against acceptance criteria
- Track defects, quality trends, and blocker severity
- Communicate quality risks to PM and delivery stakeholders

#### Interactions
- Works with Developers to test new functionality and confirm fixes
- Coordinates with Release Engineer and Platform teams for release environment readiness
- Escalates quality risk or release-readiness issues to PM and Technical Lead

#### Typical Engagement
- Throughout implementation and before release
- When validating critical paths, regression risk, or customer-impacting defects

---

### Release Engineer / Platform Engineer

#### Role Summary
Release Engineers and Platform Engineers maintain deployment pipelines, environment health, and operational readiness for software delivery.

#### Responsibilities
- Own release automation, deployment pipelines, and rollback processes
- Maintain staging and production environment stability
- Validate deployment health and post-deploy checks
- Document recovery steps and readiness conditions
- Partner with teams to reduce release risk and deployment friction

#### Interactions
- Coordinates with PM and Tech Lead on deployment windows and release readiness
- Works with Observability / On-call owners during production incidents or rollback activity
- Supports QA and Developers with environment readiness and smoke-test execution

#### Typical Engagement
- Before a release, during rollouts, and during incident recovery
- When automation, environment drift, or rollback planning require active ownership

---

### Security Engineer (or Security Liaison)

#### Role Summary
Security Engineers help teams design and ship secure systems by evaluating risk, reviewing implementations, and supporting compliance requirements.

#### Responsibilities
- Review architecture and changes for security risks
- Support threat modeling, secure design, and dependency review
- Validate compliance and security checks before release
- Escalate urgent issues according to incident and response procedures
- Provide guidance on secure defaults and best practices

#### Interactions
- Advises Tech Lead and Developers on secure design decisions
- Coordinates with PM and Release Engineer to ensure security checks are complete before release
- Escalates security incidents to Security on-call and relevant stakeholders

#### Typical Engagement
- During design reviews, dependency updates, and pre-release security checks
- When a vulnerability, data exposure, or security incident is identified

---

### Data / Analytics Lead

#### Role Summary
Data and Analytics Leads define measurement strategy and ensure teams can validate whether a feature or initiative creates the intended value.

#### Responsibilities
- Define telemetry, KPI tracking, and experiment instrumentation plans
- Validate whether product goals are being met through observed data
- Partner with Product and Engineering on metrics definitions and dashboards
- Support launch monitoring and post-release analysis
- Document assumptions and data gaps that affect decision-making

#### Interactions
- Provides metrics to Product Managers and PMs to inform prioritization and launch decisions
- Works with Developers to ensure instrumentation is in place before release
- Helps identify whether a feature needs adjustment based on evidence

#### Typical Engagement
- During planning, launch readiness, and post-release measurement reviews
- When feature success depends on user behavior, conversion, or operational signals

---

### Support / Customer Success Liaison

#### Role Summary
Support and Customer Success representatives surface customer pain points, monitor impact, and help teams prioritize fixes and communication.

#### Responsibilities
- Gather and triage customer issues and requests
- Communicate issue trends and operational impact to delivery teams
- Help validate whether fixes meet customer or user needs
- Support customer-facing communication when a bug or change affects adoption
- Contribute to release and incident feedback loops

#### Interactions
- Signals bugs, customer escalations, and patterns to PM and Product Manager
- Participates in validation for high-impact releases or hotfixes
- Helps coordinate user communications during incident recovery or rollout concerns

#### Typical Engagement
- When customer-reported issues or operational problems need triage
- During pre-release validation for critical customer impact areas

---

### Observability / On-call Owner

#### Role Summary
Observability and On-call owners maintain monitoring, alerting, and operational triage for the services or workflows in scope.

#### Responsibilities
- Own runbooks, alerts, and response processes for production health
- Monitor service health, incidents, and trends
- Diagnose service degradation or reliability concerns
- Coordinate escalation and communication during outages
- Capture follow-up work from incidents and operational reviews

#### Interactions
- Works with Release Engineer and DevOps teams during deployments and incident response
- Provides incident summaries to PM and Product Lead
- Supports Technical Lead and Developers by clarifying production behavior and risk

#### Typical Engagement
- During on-call rotations, production incidents, and reliability reviews
- When changes impact latency, error rate, or operational stability

---

## Role Matrix

| Activity | Primary role(s) | Secondary / supporting roles |
| --- | --- | --- |
| Problem framing and outcomes | Product Manager, PM | Data / Analytics Lead, Stakeholders |
| Experience design | UX / Product Designer | Product Manager, Developers, QA Lead |
| Technical design and architecture | Technical Lead | Engineering Manager, Developers, Security Engineer |
| Planning and dependency alignment | PM, Engineering Manager | Technical Lead, Product Manager, QA Lead |
| Implementation | Developers | Technical Lead, UX / Product Designer, Security Engineer |
| Quality validation | QA Lead | Developers, Technical Lead, Release Engineer |
| Release planning and launch | Release Engineer / Platform Engineer | PM, Technical Lead, QA Lead, Support / Customer Success |
| Production monitoring | Observability / On-call Owner | Release Engineer, Support / Customer Success, Security Engineer |
| Incident response | Observability / On-call Owner, PM | Technical Lead, Security Engineer, Support / Customer Success |
| Measurement and improvement | Data / Analytics Lead | Product Manager, PM, Developers |

---

## Handoff and Escalation Guidance

- Technical Lead owns feature readiness; Release Engineer owns pipeline readiness. When both are required for a release, the Technical Lead confirms business and technical readiness while the Release Engineer confirms deployment health and rollback procedures.
- Product Manager owns prioritization and desired outcomes; Engineering Manager owns staffing and execution constraints. When scope and capacity conflict, the PM and Engineering Manager escalate decisions with Product Lead and Sponsor as needed.
- QA Lead owns quality sign-off; Developers own implementation quality and fixes. Defects that affect release quality should be routed through the QA Lead and Tech Lead for triage and resolution.
- Support / Customer Success Liaison surfaces user or customer impact; PM owns communication planning and cross-team coordination. Operational issues should be summarized quickly so decision owners can respond without rework.
- Security Engineer is a consultation and escalation partner, not a replacement for product or engineering ownership. Security risk decisions should be documented with clear owners and required remediation timing.

---

## Common Coordination Templates

### Release Readiness Sign-off
- Feature and technical readiness confirmed by Tech Lead
- Test and regression status confirmed by QA Lead
- Pipeline and rollback readiness confirmed by Release Engineer
- Stakeholder communications coordinated by PM
- Release owner recorded in project board or release notes

### Incident Summary Template
- Incident summary:
- Service or feature impacted:
- Detection time and owner:
- Mitigation started:
- Current status:
- Customer / user impact:
- Follow-up action items and owners:

### Analytics Sign-off
- Success metric defined by Product Manager
- Instrumentation reviewed by Data / Analytics Lead
- Validation owner assigned for launch week or post-release review
- Decision thresholds and fallback plan documented before rollout

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When a project includes multiple teams or stakeholders, match the persona set to the workstream rather than requiring every role on every project.
- Clear ownership, escalation path, and handoff expectations reduce ambiguity and speed up decision-making.

