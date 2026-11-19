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

## Release Manager / Release Coordinator

### Role Summary
The Release Manager or Release Coordinator owns release readiness and coordinates deployment, verification, and rollback activities across teams.

### Responsibilities
- Coordinate deployment windows and release sequencing
- Confirm that acceptance criteria, CI, security checks, and smoke tests are complete
- Maintain rollback and mitigation plans
- Coordinate release announcements and operational handoffs

### Goals
- Deliver releases predictably and with minimal disruption
- Make release status, risks, and rollback decisions visible
- Improve repeatability and observability of deployments

### Decision Boundaries
The Release Manager coordinates release readiness and recommends go/no-go decisions, but severe production incidents follow the incident response and escalation procedures. Business-critical or cross-team exceptions should be confirmed with the Project Manager, Product Manager, and Sponsor as applicable.

### Interactions with Existing Roles
- Partners with **Developers** and **QA/Testing** to confirm technical readiness and acceptance.
- Coordinates with **Support/Operations** on documentation, on-call coverage, monitoring, and production handoff.
- Works with the **Project Manager** on timing, dependencies, risks, stakeholder communication, and escalation.
- Confirms scope and expected business impact with the **Product Manager**.
- Provides stakeholders with clear release status and known issues.

---

## Scrum Master / Delivery Facilitator

### Role Summary
The Scrum Master or Delivery Facilitator helps the delivery team maintain effective iterative practices, removes team-level impediments, and promotes continuous improvement.

### Responsibilities
- Facilitate planning, standups, reviews, retrospectives, and refinement where applicable
- Identify and escalate impediments that affect team flow
- Encourage clear backlog items, healthy delivery rhythms, and agreed working agreements
- Coach the team on continuous improvement and psychological safety

### Goals
- Improve predictability and sustainable delivery flow
- Reduce avoidable interruptions and unresolved team blockers
- Turn retrospective findings into measurable improvements

### Decision Boundaries
The Delivery Facilitator improves the team's process but does not replace the Product Manager's prioritization or the Project Manager's delivery coordination. Team-level impediments are escalated through the Project Manager or relevant leadership when cross-team action is required.

### Interactions with Existing Roles
- Supports **Developers** and **QA/Testing** in preparing clear, achievable increments.
- Coordinates with the **Project Manager** on risks, dependencies, and delivery commitments.
- Works with the **Product Manager** to keep backlog refinement and iteration goals connected to outcomes.
- Uses stakeholder feedback to improve ceremonies and communication without bypassing established priorities.

---

## UX / Design Lead

### Role Summary
The UX / Design Lead represents customer and usability needs in product decisions, translating user and business needs into coherent, accessible experiences.

### Responsibilities
- Conduct or coordinate user research and usability validation
- Define workflows, interaction patterns, prototypes, and design standards
- Clarify usability acceptance criteria and accessibility needs
- Identify experience risks and validate designs with evidence

### Goals
- Improve usability, accessibility, and customer value
- Reduce rework caused by unclear or unvalidated experience requirements
- Maintain a consistent experience across features

### Decision Boundaries
The UX / Design Lead owns user experience recommendations and design quality. Final scope and prioritization remain with the Product Manager, while implementation trade-offs are resolved with Developers and the Project Manager.

### Interactions with Existing Roles
- Partners with the **Product Manager** on problem framing, success metrics, and solution validation.
- Collaborates with **Developers** on feasibility, interaction implementation, and design review.
- Works with **QA/Testing** to turn usability and accessibility requirements into acceptance criteria.
- Shares findings and decisions with stakeholders and incorporates feedback where it supports the project goals.

---

## Security Lead

### Role Summary
The Security Lead provides security guidance, defines relevant controls, and helps the team identify and address security risks across the project lifecycle.

### Responsibilities
- Define applicable security requirements and threat-modeling needs
- Review high-risk designs and changes
- Coordinate security scans and remediation priorities
- Define security incident escalation and communication paths

### Goals
- Reduce security vulnerabilities and exposure
- Integrate security checks into normal delivery workflows
- Improve the team's ability to detect and respond to security risks

### Decision Boundaries
The Security Lead provides security requirements and may block or escalate changes that do not meet required controls. Emergency security incidents follow the organization’s security incident runbook and are escalated to the appropriate Security on-call and Sponsor or leadership channels.

### Interactions with Existing Roles
- Advises **Developers** on secure design, coding, and remediation.
- Works with **QA/Testing** to include security tests and validation in the quality plan.
- Coordinates release risk and controls with the **Release Manager** and **Project Manager**.
- Supports the **Product Manager** in understanding security trade-offs and prioritizing work.
- Coordinates significant security findings with stakeholders and Security on-call personnel.

---

## Data / Analytics Representative

### Role Summary
The Data / Analytics Representative defines how project outcomes are measured and ensures teams can interpret product and operational evidence consistently.

### Responsibilities
- Define measurement plans and instrumentation requirements
- Validate dashboards, experiments, and reporting assumptions
- Analyze usage, quality, and outcome data
- Communicate findings and data limitations to delivery and stakeholder groups

### Goals
- Enable evidence-based prioritization and validation
- Ensure success metrics and dashboards are reliable
- Detect delivery and product risks early

### Decision Boundaries
The Data / Analytics Representative owns measurement validity and analytical recommendations. The Product Manager decides how validated evidence affects priorities, while the Project Manager coordinates actions arising from delivery metrics.

### Interactions with Existing Roles
- Partners with the **Product Manager** to select and validate success metrics.
- Provides **Developers** with instrumentation and data-quality requirements.
- Works with **QA/Testing** to validate test and reporting data.
- Shares trends and experiment results with the **Project Manager**, stakeholders, and delivery team.

---

## Business Analyst / Requirements Lead

### Role Summary
The Business Analyst or Requirements Lead transforms stakeholder needs into clear, traceable, testable requirements and resolves ambiguities before implementation.

### Responsibilities
- Gather and organize stakeholder needs
- Document process flows, requirements, constraints, and assumptions
- Maintain traceability from requirements to acceptance criteria and tests
- Facilitate requirement clarification and change impact discussions

### Goals
- Improve requirement completeness and clarity
- Reduce late-stage ambiguity and rework
- Maintain alignment between stakeholder needs and delivery increments

### Decision Boundaries
The Requirements Lead owns requirement analysis and documentation but does not independently approve scope or priority. The Product Manager owns product prioritization, while significant requirement changes follow the Project Manager’s change and risk processes.

### Interactions with Existing Roles
- Collaborates with the **Product Manager** and stakeholders to clarify outcomes and priorities.
- Converts approved needs into actionable detail for **Developers** and **QA/Testing**.
- Raises requirement dependencies and conflicts to the **Project Manager** for planning and escalation.
- Partners with the UX / Design Lead when requirements include customer experience or workflow changes.

---

## Support / Operations Representative

### Role Summary
The Support / Operations Representative represents operational readiness and customer support needs throughout delivery and release.

### Responsibilities
- Validate support procedures, troubleshooting guides, and escalation paths
- Review monitoring, logging, alerting, and operational readiness
- Prepare support teams for new features or known issues
- Feed production observations and customer issues into backlog prioritization

### Goals
- Reduce operational surprises and support friction
- Improve observability and response readiness
- Accelerate learning from production and support feedback

### Decision Boundaries
The Support / Operations Representative can require operational readiness actions for support-critical changes and escalate unresolved production risks. Final release and scope decisions remain with the appropriate Product, Project, and Release leadership roles.

### Interactions with Existing Roles
- Works with **Developers** and the **Release Manager** on observability, runbooks, and release verification.
- Coordinates quality and known-issue communication with **QA/Testing**.
- Provides operational feedback and production priorities to the **Product Manager**.
- Keeps the **Project Manager** and stakeholders informed of operational risks and support impacts.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
