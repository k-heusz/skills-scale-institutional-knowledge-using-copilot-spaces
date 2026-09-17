# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

Role assignments may be combined or shared by one person depending on project size and complexity, but each responsibility should still have a clear accountable owner.

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

## Project Sponsor / Executive Sponsor

### Role Summary
Project Sponsors provide strategic sponsorship, organizational alignment, and escalation support. They help ensure the project remains funded, supported, and tied to business outcomes.

### Responsibilities
- Confirm the project charter, scope intent, and expected business value
- Resolve major escalations, priority conflicts, and cross-organizational blockers
- Approve significant scope, funding, or timeline changes when needed
- Support adoption, visibility, and executive alignment

### Decision Boundaries
- Own go/no-go decisions for major milestones when escalation is required
- Delegate day-to-day delivery decisions to the Project Manager and delivery team

### Typical Interactions
- Project Manager: reviews status, risks, dependencies, and escalations
- Product Manager: aligns on outcomes, priorities, and trade-offs
- Developers: receives high-level implementation updates for major risks or decisions
- QA/Testing: reviews release readiness and quality concerns when escalation is needed
- Stakeholders: reinforces alignment, sponsorship, and major decisions

---

## UX/Product Designer or User Researcher

### Role Summary
UX/Product Designers and User Researchers represent user needs during discovery, design, and validation. They help the team translate problems into usable workflows and clear acceptance criteria.

### Responsibilities
- Conduct or synthesize user research and usability feedback
- Create workflows, wireframes, prototypes, or journey maps as needed
- Define usability considerations and support acceptance criteria refinement
- Identify user risks, accessibility concerns, and open questions early

### Goals
- Improve usability, clarity, and customer adoption
- Reduce rework by validating assumptions before and during delivery

### Typical Interactions
- Project Manager: coordinates research timing, dependencies, and decision checkpoints
- Product Manager: aligns on problem definition, target users, and success criteria
- Developers: collaborates on feasibility, implementation details, and user flows
- QA/Testing: clarifies expected behavior, usability checks, and edge cases
- Stakeholders: shares research findings and design rationale for alignment

---

## Technical Lead / Architect

### Role Summary
Technical Leads and Architects guide technical direction across the project. They help the team make sound design decisions, manage technical risk, and maintain non-functional quality.

### Responsibilities
- Define or review architecture, integrations, and technical design choices
- Identify technical risks, dependencies, and non-functional requirements
- Guide implementation approaches, standards, and trade-off discussions
- Support estimation, sequencing, and mitigation planning for complex work

### Decision Boundaries
- Own technical recommendations and architecture guardrails
- Escalate business-priority trade-offs to the Product Manager and Project Manager

### Typical Interactions
- Project Manager: aligns on dependencies, estimates, technical risks, and sequencing
- Product Manager: discusses trade-offs between scope, value, and technical constraints
- Developers: provides implementation guidance, design reviews, and mentorship
- QA/Testing: improves testability, quality strategy, and environment assumptions
- Stakeholders: explains technical implications, constraints, and major design decisions

---

## DevOps/SRE or Release Manager

### Role Summary
DevOps/SRE roles and Release Managers coordinate deployment readiness, environments, observability, and release execution. They help reduce operational risk from build through production.

### Responsibilities
- Maintain release readiness across environments, pipelines, and access needs
- Coordinate deployment plans, rollback steps, and operational checks
- Monitor observability, incident signals, and post-release stability
- Surface operational risks that affect timelines or release confidence

### Goals
- Deliver predictable, low-risk releases
- Improve reliability, recovery readiness, and operational visibility

### Typical Interactions
- Project Manager: coordinates release timing, dependencies, communications, and cutover plans
- Product Manager: aligns on release scope, launch readiness, and customer impact
- Developers: supports CI/CD, environment needs, instrumentation, and deployment practices
- QA/Testing: confirms test environments, smoke tests, and release verification steps
- Stakeholders: communicates release readiness, operational constraints, and support expectations

---

## Security/Privacy Lead

### Role Summary
Security/Privacy Leads identify security, privacy, and compliance needs that affect the project. They help the team address risks early and make informed release decisions.

### Responsibilities
- Identify applicable security, privacy, and data-handling requirements
- Coordinate risk reviews, threat assessments, or compliance checkpoints
- Advise on secure design, access controls, and incident readiness
- Track remediation needs that affect scope, sequencing, or release readiness

### Decision Boundaries
- Own security and privacy recommendations and required control guidance
- Escalate unresolved material risks before release or data exposure changes

### Typical Interactions
- Project Manager: plans review timing, tracks remediation work, and escalates material risks
- Product Manager: clarifies data use, policy implications, and acceptable trade-offs
- Developers: reviews secure implementation patterns, controls, and remediation actions
- QA/Testing: aligns on security validation, privacy checks, and release criteria
- Stakeholders: communicates material risks, obligations, and approval needs

---

## Data/Analytics Lead

### Role Summary
Data/Analytics Leads define how the team measures outcomes, quality, and adoption. They help connect delivery work to meaningful evidence after release.

### Responsibilities
- Define key metrics, instrumentation needs, and reporting expectations
- Review event tracking, data quality, and dashboard requirements
- Support experiment design, baseline analysis, and post-release measurement
- Highlight gaps that limit decision-making or outcome evaluation

### Goals
- Improve confidence in product and project decisions through evidence
- Ensure post-release reporting supports iteration and accountability

### Typical Interactions
- Project Manager: aligns on reporting cadence, dependency tracking, and milestone metrics
- Product Manager: defines success measures, hypotheses, and outcome evaluation
- Developers: coordinates instrumentation, event definitions, and data quality needs
- QA/Testing: validates tracked events, data integrity, and reporting assumptions
- Stakeholders: shares impact reporting, insights, and decision-support metrics

---

## Customer Support / Operations Representative

### Role Summary
Customer Support and Operations Representatives bring production, support, and customer-readiness needs into the project. They help the team prepare for launch and learn from real-world usage.

### Responsibilities
- Represent support workflows, training needs, and operational constraints
- Prepare support teams with release notes, known issues, and escalation paths
- Surface recurring customer pain points and production learnings
- Help assess launch readiness from an operational and support perspective

### Goals
- Reduce customer friction during rollout and post-release support
- Improve feedback loops between production operations and the delivery team

### Typical Interactions
- Project Manager: coordinates launch readiness tasks, communications, and support dependencies
- Product Manager: shares customer feedback, operational insights, and rollout concerns
- Developers: escalates production issues, support trends, and documentation gaps
- QA/Testing: contributes support scenarios, known risk areas, and validation feedback
- Stakeholders: communicates support readiness, customer impact, and operational observations

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
