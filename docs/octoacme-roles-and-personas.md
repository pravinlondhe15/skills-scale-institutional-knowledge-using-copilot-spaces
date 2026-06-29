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

## QA Engineer

### Role Summary
QA Engineers validate that delivered software meets acceptance criteria, quality standards, and non-functional requirements (performance, security, accessibility). They are embedded in the delivery cycle, not a separate gate at the end.

### Responsibilities
- Define and maintain test plans and test cases aligned to acceptance criteria
- Perform exploratory, regression, and smoke testing
- Automate test coverage for high-risk and high-frequency flows
- Identify, document, and track defects through resolution
- Validate releases against the Definition of Done
- Collaborate with Developers on test strategies during planning

### Goals
- Catch defects as early as possible in the delivery cycle
- Increase confidence in releases with verified acceptance
- Reduce escaped defects in production

### Typical Communication
- Sprint planning: review acceptance criteria and test scope
- PR reviews: validate test coverage alongside code
- Release checks: confirm QA sign-off before deployment
- Bug reports with reproducible steps and severity ratings

### Interaction with Other Roles
- **Developers**: Pair on test strategy; developers write unit tests, QA focuses on integration and acceptance layers
- **Product Managers**: Clarify acceptance criteria and edge cases before work begins
- **Project Managers**: Flag quality risks and estimated re-work in risk register

---

## Technical Lead / Architect

### Role Summary
The Technical Lead provides architectural direction, sets engineering standards, and ensures that technical decisions align with long-term maintainability, scalability, and security objectives.

### Responsibilities
- Define and document technical architecture for new initiatives
- Establish and enforce coding standards, patterns, and security practices
- Conduct architecture and design reviews for significant changes
- Identify and reduce technical debt as part of planning cycles
- Mentor developers on design principles and best practices
- Evaluate third-party tools, libraries, and platforms

### Goals
- Maintain a system that is extensible, operable, and secure
- Reduce the cost of future changes through intentional design
- Enable team members to make confident, well-informed technical decisions

### Typical Communication
- Architecture Decision Records (ADRs) for significant choices
- Design review sessions before complex feature work begins
- Pull request reviews for architectural concerns
- Technical risk contributions to the project risk register

### Interaction with Other Roles
- **Developers**: Provide technical guidance, review high-risk code, unblock architectural blockers
- **Product Managers**: Translate business requirements into feasible technical approaches and surface trade-offs
- **Project Managers**: Flag technical risk and estimate impact of technical debt on delivery

---

## DevOps / Platform Engineer

### Role Summary
DevOps and Platform Engineers design, build, and maintain the CI/CD pipelines, infrastructure, and operational tooling that enable teams to ship reliably and recover quickly.

### Responsibilities
- Build and maintain CI/CD pipelines for automated build, test, and deployment
- Manage cloud infrastructure and environment configuration (as-code)
- Monitor system health, performance, and reliability; respond to incidents
- Enable developer productivity through tooling, environments, and automation
- Enforce security baselines and compliance controls in the delivery pipeline
- Define and support rollback and disaster recovery procedures

### Goals
- Enable fast, safe, and consistent deployments
- Reduce mean time to recovery (MTTR) through observability and runbooks
- Shield developers from infrastructure complexity while maintaining operational control

### Typical Communication
- Infrastructure change proposals and runbooks in version control
- On-call escalations and incident retrospectives
- Release coordination with Project Managers and QA for deployment windows
- Platform capability updates shared with developers in standups or wikis

### Interaction with Other Roles
- **Developers**: Provide self-service tooling and unblock CI/CD issues
- **Technical Lead**: Align on infrastructure and security architecture
- **Project Managers**: Coordinate scheduled maintenance, deployment windows, and incident timelines
- **QA Engineers**: Ensure test environments match production configurations

---

## Security Engineer

### Role Summary
Security Engineers embed security requirements into the design, build, and release process. They identify vulnerabilities, assess risk, and ensure that the team meets compliance and security obligations.

### Responsibilities
- Perform threat modeling and security design reviews for new features
- Run and triage automated security scans (SAST, DAST, dependency checks) in CI
- Conduct periodic penetration testing and vulnerability assessments
- Define security acceptance criteria for features handling sensitive data
- Maintain a security risk backlog and coordinate remediation
- Provide security guidance and training to the broader team

### Goals
- Prevent vulnerabilities from reaching production
- Reduce mean time to remediate (MTTR) for security findings
- Maintain compliance with relevant security frameworks and regulatory requirements

### Typical Communication
- Security review sign-off as part of the Definition of Done for high-risk features
- Vulnerability reports and remediation tracking in the risk register
- Incident response coordination with DevOps and management
- Regular security briefings for the team

### Interaction with Other Roles
- **Technical Lead**: Align on security architecture and design patterns
- **Developers**: Review code with security implications; provide secure coding guidance
- **DevOps Engineers**: Maintain pipeline scanning tools and enforce controls
- **Project Managers**: Communicate security risk and estimated remediation effort in project planning

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When reviewing process docs, consider whether each persona has sufficient coverage of their responsibilities and interaction patterns.

