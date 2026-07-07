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

## QA/Testing Lead

### Role Summary
QA/Testing Leads ensure product quality through comprehensive testing strategies, test automation, and acceptance validation. They work closely with developers and product teams to validate that features meet acceptance criteria and quality standards.

### Responsibilities
- Design and execute test plans aligned with acceptance criteria
- Implement and maintain test automation frameworks
- Conduct manual QA for features requiring human validation
- Identify and document bugs with reproducible steps and severity levels
- Validate quality gates before release and sign off on deployment readiness
- Collaborate with developers on testability and test coverage

### Goals
- Catch defects early to reduce production issues
- Enable confidence in release quality
- Support fast feedback loops during development
- Build quality into the development process rather than testing at the end

### Typical Communication
- Sprint planning and backlog refinement discussions (defining test acceptance criteria)
- Daily standup updates on test coverage and blocking issues
- QA sign-off in PR reviews and release checklists
- Post-incident reviews to identify testing gaps

### Interaction with Other Roles
- **With Developers**: Collaborate during sprint planning to clarify testability requirements; participate in PR reviews
- **With Product Managers**: Validate acceptance criteria are testable; ensure test coverage aligns with feature priorities
- **With Project Managers**: Provide quality metrics and risk assessments for release readiness decisions

---

## Product Lead

### Role Summary
Product Leads act as senior product strategists who align product initiatives with business goals, mentor Product Managers, and govern product decisions. They provide oversight, escalation, and strategic guidance across the product portfolio.

### Responsibilities
- Review and approve project one-pagers and success metrics
- Escalate product/business risks identified by PMs to leadership
- Approve major roadmap decisions and trade-offs
- Mentor PMs on strategy, stakeholder management, and data-driven decision-making
- Act as tie-breaker on prioritization disputes between competing initiatives
- Ensure portfolio-level alignment and avoid conflicting roadmap commitments

### Goals
- Ensure product initiatives deliver measurable business value
- Maintain strategic alignment across the product portfolio
- Build PM capability and scale the product organization
- Unblock cross-functional decisions quickly

### Typical Communication
- Weekly PM/PdM syncs with oversight and guidance
- Monthly roadmap reviews and strategic planning sessions
- Escalation point for critical decisions or risks
- Quarterly business reviews with leadership

### Interaction with Other Roles
- **With Product Managers**: Mentor, approve major decisions, provide strategic context
- **With Project Managers**: Escalation point for business/product risks; align on prioritization disputes
- **With Sponsors/Stakeholders**: Represent product strategy; communicate product outcomes

---

## Stakeholder/Sponsor

### Role Summary
Sponsors provide business context, approvals, and organizational support for projects. They represent customer or business interests and act as advocates for the initiative within the organization.

### Responsibilities
- Provide business requirements and success criteria
- Approve project charters and funding
- Remove organizational blockers and secure necessary resources
- Participate in project kickoff and key milestone reviews
- Communicate project outcomes and value to leadership
- Validate that delivered outcomes meet business expectations

### Goals
- Ensure projects align with business strategy
- Unblock dependencies outside the immediate delivery team
- Drive adoption and stakeholder buy-in for initiatives
- Maximize return on investment from project delivery

### Typical Communication
- Project initiation and approval meetings
- Monthly stakeholder status updates
- Milestone reviews and demo participation
- Ad-hoc escalation when needed for resource or organizational blockers

### Interaction with Other Roles
- **With Project Managers**: Provide direction, approvals, and organizational support
- **With Product Managers**: Align on business success metrics and strategic fit
- **With Product Lead**: Communicate strategic outcomes and resource needs

---

## Security/Compliance Officer

### Role Summary
Security and Compliance Officers ensure that projects meet security, privacy, and regulatory requirements throughout the project lifecycle. They act as advisors and gatekeepers to prevent security incidents and maintain organizational compliance.

### Responsibilities
- Review security implications during project planning and design phases
- Conduct or coordinate security reviews and threat assessments before release
- Ensure compliance scanning is integrated into CI/CD pipelines
- Advise on encryption, authentication, authorization, and data handling best practices
- Participate in incident response and post-mortems to identify systemic improvements
- Stay current on regulatory requirements and emerging security threats

### Goals
- Prevent security incidents and data breaches
- Ensure regulatory compliance and reduce legal risk
- Build security practices into the development workflow (shift-left approach)
- Enable secure and compliant delivery without blocking velocity

### Typical Communication
- Design review sessions for high-risk features (authentication, payment, data handling)
- Security scanning gate in deployment checklist and pre-release validation
- Incident communication and escalation
- Periodic security training and updates for engineering teams

### Interaction with Other Roles
- **With Developers**: Advise on secure coding practices; review code during PRs for security
- **With Project Managers**: Escalate security risks and compliance gaps; participate in release readiness decisions
- **With Product Managers**: Advise on security trade-offs and feature implications

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove process impediments, and coach teams on agile best practices. They act as process guardians and enablers of team productivity and continuous improvement.

### Responsibilities
- Facilitate daily standups, sprint planning, sprint reviews, and retrospectives
- Track sprint velocity, burndown, and team health metrics
- Remove blockers and impediments to progress
- Coach team on agile best practices and continuous improvement
- Maintain the backlog grooming cadence and work with Product Manager on prioritization
- Foster psychological safety and encourage open, honest communication

### Goals
- Maximize team productivity and flow
- Foster psychological safety and a culture of continuous improvement
- Reduce cycle time and improve predictability of delivery
- Unblock teams and remove organizational friction

### Typical Communication
- Daily standups and sprint ceremonies (facilitation)
- Weekly velocity and health check-ins with team leads
- Retrospective action item tracking and follow-up
- Backlog refinement sessions (coordination)
- Escalations of systemic blockers to Project Manager and leadership

### Interaction with Other Roles
- **With Project Managers**: Escalate process blockers; provide velocity and team health data
- **With Developers**: Coach on agile practices; facilitate collaboration and remove impediments
- **With Product Managers**: Support backlog prioritization and grooming; facilitate stakeholder collaboration

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When managing a project, ensure all roles are assigned or explicitly scoped out to avoid gaps in accountability.
