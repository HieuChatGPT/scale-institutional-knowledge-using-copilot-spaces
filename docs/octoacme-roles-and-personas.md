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

## Additional Personas

---

## Delivery Coordinator

### Role Summary
Delivery Coordinators operationalize project plans and maintain day-to-day schedules. They coordinate cross-team activities, track action items, and keep project dashboards current to ensure smooth execution.

### Responsibilities
- Maintain the project schedule and timeline
- Coordinate cross-team meetings and track outcomes
- Consolidate action items and follow up on completion
- Keep project dashboards and status tracking tools up to date
- Identify scheduling conflicts and resource constraints

### Goals
- Ensure efficient day-to-day project execution
- Minimize delays caused by coordination gaps
- Maintain real-time visibility into project health

### Interactions with Existing Roles
- **Works closely with Project Manager/Program Lead** to operationalize plans and provide real-time execution support
- **Coordinates with Release Coordinator** before cutover windows to align scheduling
- **Partners with Developers and Engineering Leads** on sprint logistics and dependency management
- **Reports blockers to Project Manager** for escalation and resolution

### Typical Communication
- Daily standups and status updates
- Shared calendars and project dashboards
- Action item tracking and closure confirmation

---

## Stakeholder Liaison

### Role Summary
Stakeholder Liaisons act as the primary point of contact between the project team and external stakeholders, business owners, and executives. They surface requirements, communicate decisions, and coordinate stakeholder reviews.

### Responsibilities
- Serve as the primary point of contact for stakeholder communication
- Surface stakeholder requirements, feedback, and business constraints
- Communicate project status and decisions to stakeholders
- Coordinate stakeholder reviews and approval gates
- Escalate scope or priority changes to the Program Lead

### Goals
- Ensure stakeholder alignment and satisfaction
- Reduce miscommunication and scope creep
- Enable timely business decisions

### Interactions with Existing Roles
- **Partners with Product Manager** to prioritize stakeholder-driven requirements
- **Escalates scope or priority changes to Program Lead** for impact assessment
- **Works with Communications Owner** to prepare stakeholder-facing updates and announcements
- **Coordinates with Release Coordinator** on stakeholder notification for releases
- **Reports stakeholder concerns** to Project Manager for risk escalation

### Typical Communication
- Stakeholder briefings and status reports
- Requirement solicitation sessions
- Executive-level updates and decision logs

---

## Release Coordinator

### Role Summary
Release Coordinators own the end-to-end release process, including runbooks, staging and production checklists, release window scheduling, and rollback planning. They coordinate cross-team readiness and gate releases on completion criteria.

### Responsibilities
- Own and maintain release runbooks and playbooks
- Develop and execute staging and production checklists
- Schedule release windows and coordinate team availability
- Develop and test rollback and mitigation plans
- Conduct cross-team release readiness reviews
- Gate releases on completion of all acceptance criteria

### Goals
- Execute reliable, low-risk releases
- Minimize time-to-resolution during production incidents
- Ensure consistent release processes across teams

### Interactions with Existing Roles
- **Coordinates with Engineering Leads** on code freeze dates and deployment readiness
- **Works with QA Representative** to confirm quality gates before release
- **Collaborates with Change Manager** on production change approval and risk assessment
- **Partners with Delivery Coordinator** on release window logistics
- **Notifies Stakeholder Liaison** of release timings for external communication
- **Works with Documentation Steward** to update runbooks post-release

### Typical Communication
- Release planning meetings and readiness reviews
- Runbook updates and change logs
- Release-day command center coordination
- Post-release retrospectives and incident reports

---

## QA Representative / Test Lead

### Role Summary
QA Representatives own acceptance criteria definition, test planning, and quality gate decisions. They consolidate test results, identify defects, and authorize releases based on quality metrics.

### Responsibilities
- Define acceptance criteria and test coverage expectations
- Own test plans and test case development
- Consolidate QA results and identify gaps
- Gate releases on quality metrics and defect thresholds
- Track and escalate critical defects
- Partner with Developers on test automation and coverage

### Goals
- Ensure features meet acceptance criteria before release
- Reduce production defects through comprehensive testing
- Enable rapid, quality-focused development cycles

### Interactions with Existing Roles
- **Works with Developers** on unit testing and test automation
- **Coordinates with Engineering Leads** on test strategy and coverage targets
- **Partners with Release Coordinator** to sign off on releases and confirm quality gates
- **Reports major defects to Risk Owner / Program Lead** for escalation
- **Collaborates with Product Manager** on acceptance criteria validation

### Typical Communication
- Test plan reviews and coverage discussions
- Defect reports and severity assessments
- Quality metrics dashboards
- Release readiness sign-offs

---

## Change Manager

### Role Summary
Change Managers assess and approve production changes to minimize risk. They ensure Change Advisory Board (CAB) processes are followed, confirm rollback plans, and validate mitigation strategies before deployment.

### Responsibilities
- Assess production changes for risk and impact
- Ensure CAB processes and approval gates are followed
- Confirm rollback and mitigation steps are documented and tested
- Authorize or defer production changes
- Coordinate with Release Coordinator on high-risk releases
- Document change decisions and outcomes

### Goals
- Minimize unplanned production incidents
- Ensure rollback readiness for all production changes
- Maintain change governance and compliance

### Interactions with Existing Roles
- **Works with Release Coordinator and Program Lead** on high-risk change assessment
- **Coordinates with Engineering Leads** on technical feasibility of rollback plans
- **Partners with QA Representative** to confirm testing completeness
- **Notifies Documentation Steward** of approved changes requiring post-deployment updates
- **Reports change decisions** to Project Manager for audit and compliance

### Typical Communication
- Change Advisory Board meetings
- Change risk assessments and approval forms
- Rollback plan validation and testing
- Change logs and decision records

---

## Documentation Steward

### Role Summary
Documentation Stewards ensure process and runbook documentation remains current and accessible. They own documentation review cycles, manage publication in the docs folder, and coordinate knowledge transfer.

### Responsibilities
- Ensure process and runbook documentation is current and accurate
- Own documentation review cycles and update scheduling
- Manage documentation publishing in the docs/ folder
- Coordinate knowledge transfer between team members
- Identify gaps in documentation and propose improvements
- Maintain documentation standards and formatting

### Goals
- Keep institutional knowledge accessible and up to date
- Reduce onboarding time through quality documentation
- Enable consistent process execution across team members

### Interactions with Existing Roles
- **Collaborates with Delivery Coordinator and Release Coordinator** to update runbooks and process docs
- **Partners with Onboarding Mentor** for knowledge transfer and onboarding checklist updates
- **Works with Project Manager** on process improvement documentation
- **Coordinates with Change Manager** on post-deployment documentation updates
- **Supports all roles** by maintaining their role-specific documentation and checklists

### Typical Communication
- Documentation review meetings
- Knowledge transfer sessions
- Docs folder updates and publishing
- Feedback collection on documentation gaps

---

## Onboarding Mentor

### Role Summary
Onboarding Mentors curate onboarding checklists and provide mentorship for new team members and first-time role holders. They run role-specific onboarding sessions and identify onboarding gaps to address.

### Responsibilities
- Curate onboarding checklists for new contributors to project processes
- Provide mentorship for first-time role holders
- Run role-specific onboarding sessions and walk-throughs
- Identify gaps and friction in the onboarding experience
- Recommend improvements to onboarding processes
- Validate onboarding completion and readiness

### Goals
- Accelerate time-to-productivity for new team members
- Reduce single-person dependency by scaling knowledge
- Improve consistency in how roles are executed

### Interactions with Existing Roles
- **Works with Documentation Steward** to keep onboarding checklists current
- **Partners with Project Manager** to understand role-specific requirements
- **Mentors team members** across all roles on process execution
- **Reports onboarding gaps to Program Lead** for process improvement
- **Collaborates with all personas** on their role-specific onboarding content

### Typical Communication
- Onboarding checklist development and updates
- One-on-one mentoring sessions
- Role-specific training and walk-throughs
- Feedback collection and gap identification

---

## RACI Matrix for Cross-Critical Activities

The following table shows role responsibilities for critical project activities:

| Activity | Responsible | Accountable | Consulted | Informed |
|----------|-------------|------------|-----------|----------|
| **Release Coordination** | Release Coordinator | Program Lead | Engineering Lead, QA Representative, Change Manager | Stakeholder Liaison, Documentation Steward, Delivery Coordinator |
| **Risk Escalation** | Project Manager | Program Lead | Risk Owner (if defined), Change Manager | Stakeholder Liaison, Team Lead |
| **Acceptance Criteria Definition** | QA Representative | Product Manager | Developers, Engineering Lead | Project Manager |
| **Production Change Approval** | Change Manager | Program Lead | Release Coordinator, Engineering Lead | QA Representative, Documentation Steward |
| **Stakeholder Communication** | Stakeholder Liaison | Program Lead | Product Manager, Project Manager | All team members |
| **Documentation Updates** | Documentation Steward | Program Lead | All roles contributing content | All team members |
| **Onboarding New Members** | Onboarding Mentor | Program Lead | Documentation Steward, Role-specific Lead | All team members |
| **Schedule and Execution** | Delivery Coordinator | Project Manager | Release Coordinator, Engineering Lead | All team members |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Leverage the RACI matrix to understand decision rights and consultation requirements for cross-functional activities.
- Use the interaction descriptions to simulate handoffs and dependencies between personas.
