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

## QA / Quality Assurance Specialist

### Role Summary
QA specialists ensure product quality by designing test strategies, executing tests, and validating acceptance criteria. They collaborate with developers and product managers to define Definition of Done and quality standards. QA is essential for maintaining the quality bar throughout the delivery lifecycle and ensuring features meet user expectations before release.

### Responsibilities
- Design and execute test plans (unit, integration, end-to-end)
- Validate acceptance criteria and Definition of Done
- Identify and document defects with clear reproduction steps
- Participate in release readiness reviews
- Contribute to security and performance testing in CI/CD
- Collaborate with developers on testability and test coverage
- Define quality standards and test automation strategies

### Goals
- Minimize defects reaching production
- Ensure features meet user expectations and acceptance criteria
- Support rapid iteration with reliable automated testing
- Reduce regression risk and cycle-time through effective test coverage

### Interaction with Other Roles
- **Developers**: Review acceptance criteria together, collaborate on test coverage and automation, identify edge cases
- **Product Managers**: Validate user workflows and acceptance criteria, report on quality metrics
- **Project Managers**: Provide QA status updates, escalate blockers, confirm release readiness

### Typical Communication
- Sprint planning and backlog refinement
- QA status updates in daily standups
- Test result reports and defect tracking
- Release readiness sign-off
- Quality metrics and test coverage reports

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders provide business context, approvals, and resource support. Sponsors are senior stakeholders who champion the project and escalate blockers to executive leadership. They represent business priorities and ensure projects deliver intended value to the organization.

### Responsibilities
- Approve project charter and success metrics
- Provide business requirements and acceptance criteria
- Support resource allocation and team protection
- Receive regular project status updates
- Escalate business-impacting risks and decisions
- Advocate for the project within the organization
- Validate business outcomes and ROI

### Goals
- Ensure project delivers intended business value
- Maintain alignment between project and business strategy
- Support team in removing organizational blockers
- Drive adoption and successful implementation of deliverables

### Interaction with Other Roles
- **Project Managers**: Receive status updates, review risks, approve decisions
- **Product Managers**: Provide business priorities and trade-off guidance
- **Developers & QA**: Provide business context for acceptance criteria
- **Executive Leadership**: Escalate critical blockers and decisions

### Typical Communication
- Project initiation and kickoff meetings
- Monthly stakeholder updates
- Escalation paths for critical decisions
- Release announcements and success metrics reporting
- Business case reviews and ROI tracking

---

## Security / Compliance Lead

### Role Summary
Security leads ensure projects meet security and compliance requirements. They review designs, participate in threat modeling, and validate security controls. Security is integrated throughout the project lifecycle, not just at release time, to reduce risk and ensure compliance with organizational and regulatory standards.

### Responsibilities
- Review designs and architecture for security risks
- Participate in threat modeling and risk assessment
- Define security testing and scanning requirements
- Validate security controls before release
- Support incident response and post-mortems
- Advise on secure coding practices and compliance requirements
- Monitor security scanning in CI/CD pipeline

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure compliance with regulatory and organizational standards
- Build security and compliance into the development process
- Enable rapid iteration without compromising security posture

### Interaction with Other Roles
- **Developers**: Review code for security issues, advise on secure practices, validate fixes
- **Project Managers**: Highlight security dependencies and risk mitigations
- **QA**: Define security test cases and validate controls
- **Stakeholders/Sponsors**: Report on compliance status and security risks

### Typical Communication
- Design reviews and architecture discussions
- CI/CD configuration and security scanning setup
- Pre-release security sign-off
- Incident escalation and response
- Security training and awareness updates
- Compliance reporting to leadership

---

## Scrum Master / Facilitator

### Role Summary
Facilitators (often called Scrum Masters in agile teams) remove blockers, coach teams on agile practices, and ensure ceremonies (standups, planning, retros) run effectively. They serve the team as a servant leader, supporting continuous improvement and helping the team self-organize.

### Responsibilities
- Facilitate daily standups, planning, and retrospectives
- Coach team on agile practices and continuous improvement
- Identify and escalate team-level blockers
- Maintain project board and sprint tracking
- Support psychological safety and team health
- Drive action item follow-up from retrospectives
- Help remove organizational impediments to delivery

### Goals
- Maximize team velocity and predictability
- Continuous improvement through retrospectives and action items
- Remove friction from the delivery process
- Foster a healthy, collaborative team environment

### Interaction with Other Roles
- **Project Managers**: Escalate blockers, coordinate with dependencies
- **Developers & QA**: Support team health and remove impediments
- **Product Managers**: Facilitate backlog refinement and priority discussions
- **All Roles**: Ensure inclusive communication and psychological safety

### Typical Communication
- Daily standups and sprint ceremonies
- Blockers tracking and escalation
- Retrospective facilitation and action item tracking
- Team coaching and continuous improvement guidance
- Cross-team coordination on dependencies

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When defining acceptance criteria and workflows, consider how all personas interact and depend on each other.
