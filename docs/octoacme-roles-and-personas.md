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

### Interactions with Other Roles
- Collaborate with **QA/Testing Lead** on test coverage, testability improvements, and defect resolution
- Partner with **Technical Lead** on design decisions and architectural guidance
- Work with **Project Manager** on task estimation and scheduling
- Receive feature specifications from **Product Manager**
- Coordinate with **DevOps/Release Engineer** on deployment and infrastructure concerns

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

### Interactions with Other Roles
- Partner with **Project Manager** on scope, timelines, and resource planning
- Define acceptance criteria for **Developers** and **QA/Testing Lead**
- Align with **Stakeholders/Sponsors** on business priorities and resource allocation
- Consult **Technical Lead** on technical feasibility and trade-offs
- Measure success using metrics from **DevOps/Release Engineer** (observability and deployment data)

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

### Interactions with Other Roles
- Facilitate collaboration between **Product Manager** and **Developers**
- Coordinate with **Scrum Master/Agile Coach** on sprint ceremonies and team velocity
- Escalate risks and blockers to **Stakeholders/Sponsors**
- Track quality metrics and release readiness with **QA/Testing Lead** and **DevOps/Release Engineer**
- Partner with **Technical Lead** to identify technical dependencies and risks

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads define and execute test strategies to ensure features meet acceptance criteria and quality standards before release. They collaborate with developers and product managers to validate that solutions work as intended and identify defects early.

### Responsibilities
- Define test strategy and QA approach for features and releases
- Create and maintain test plans, test cases, and acceptance criteria validation
- Execute manual and automated testing, document defects, and track resolution
- Collaborate with developers on test coverage and testability improvements
- Validate acceptance criteria before marking work as "Done"
- Participate in release readiness reviews and smoke testing
- Report quality metrics and test progress to the team

### Goals
- Reduce defects reaching production
- Enable fast, confident releases through comprehensive testing
- Improve test coverage and automation over time
- Provide early feedback to developers on quality issues

### Typical Communication
- Sprint planning and review sessions
- Daily standups (reporting test status and blockers)
- Defect reports and resolution tracking
- Release readiness sign-off

### Interactions with Other Roles
- Work closely with **Developers** to design testable features and resolve defects
- Review acceptance criteria with **Product Manager** to ensure clarity
- Coordinate release validation with **DevOps/Release Engineer** for smoke testing
- Report quality status to **Project Manager** for risk and schedule planning
- Align on test strategy with **Technical Lead** for integration and architectural testing
- Participate in retrospectives with **Scrum Master/Agile Coach**

---

## Technical Lead / Architect

### Role Summary
Technical Leads define technical direction, review design decisions, and manage technical debt and dependencies. They guide the team on architectural choices and ensure solutions are maintainable, scalable, and aligned with long-term strategy.

### Responsibilities
- Define technical architecture and design patterns for features and systems
- Review design proposals and code from developers
- Identify and manage technical debt and dependencies
- Mentor developers on best practices and new technologies
- Collaborate on estimating technical complexity
- Ensure solutions align with long-term technical vision
- Identify integration points and cross-team technical dependencies

### Goals
- Maintain high code quality and architecture standards
- Reduce technical debt and complexity
- Enable rapid, sustainable feature delivery
- Build scalable, maintainable systems

### Typical Communication
- Technical design reviews and architecture discussions
- Code review sessions and guidance
- Technical spike investigations and recommendations
- Escalation of complex technical decisions to stakeholders

### Interactions with Other Roles
- Provide technical guidance to **Developers** on design and implementation
- Advise **Product Manager** on technical feasibility and trade-offs
- Work with **Project Manager** to identify technical risks and dependencies
- Partner with **QA/Testing Lead** on architectural and integration testing strategies
- Collaborate with **DevOps/Release Engineer** on deployment architecture and scalability
- Help **Scrum Master/Agile Coach** estimate technical work and manage sprint risks

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide executive oversight, approve resources, and escalate business-level decisions. They represent business interests, ensure alignment with organizational strategy, and remove organizational barriers to project success.

### Responsibilities
- Approve project scope, budget, and resource allocation
- Provide business context and strategic alignment
- Escalate business-level decisions and organizational blockers
- Review project status and milestone progress
- Communicate project outcomes to broader organizational leadership
- Ensure project aligns with organizational priorities and compliance requirements

### Goals
- Maximize business value and ROI from projects
- Ensure projects align with organizational strategy
- Remove organizational and resource barriers to success
- Maintain visibility and accountability

### Typical Communication
- Monthly or milestone-based status reviews
- Executive steering committee meetings
- Budget and resource approval decisions
- Escalation of organizational blockers and decisions

### Interactions with Other Roles
- Receive recommendations and risk escalations from **Project Manager**
- Review business outcomes and success metrics from **Product Manager**
- Allocate resources and resolve organizational constraints affecting **Developers** and team
- Make final decisions on scope and priority trade-offs in consultation with **Product Manager** and **Project Manager**
- Approve release timing and business continuity plans from **DevOps/Release Engineer**
- Receive strategic guidance from **Technical Lead** on long-term technical investments

---

## Security Lead

### Role Summary
Security Leads own security requirements, threat assessment, and compliance validation in releases. They ensure features and deployments meet security standards and organizational compliance requirements.

### Responsibilities
- Define security requirements for features and releases
- Conduct threat assessments and security reviews
- Validate compliance with organizational and regulatory standards
- Collaborate on secure design practices and threat mitigation
- Conduct security testing and vulnerability scanning
- Approve security readiness before production deployment
- Track and manage security issues and patch management

### Goals
- Prevent security vulnerabilities and breaches
- Ensure compliance with organizational and regulatory requirements
- Build security awareness and practices across the team
- Enable rapid, secure releases

### Typical Communication
- Security requirements workshops with developers and product managers
- Security review findings and recommendations
- Incident response coordination (see Risk Management & Communication docs)
- Pre-release security sign-off

### Interactions with Other Roles
- Work with **Developers** and **Technical Lead** to design secure solutions and review code
- Review acceptance criteria with **Product Manager** for security requirements
- Collaborate with **QA/Testing Lead** on security testing and validation
- Provide security readiness assessment to **Project Manager** and **DevOps/Release Engineer**
- Approve security aspects of releases before **DevOps/Release Engineer** deploys to production
- Escalate security risks to **Project Manager** and **Stakeholder/Sponsor**

---

## DevOps / Release Engineer

### Role Summary
DevOps and Release Engineers manage deployment pipelines, infrastructure, and release automation. They enable fast, reliable deployments and maintain production systems, observability, and incident response capabilities.

### Responsibilities
- Design and maintain deployment pipelines and infrastructure
- Automate release processes and reduce manual steps
- Manage production environments and infrastructure scaling
- Implement monitoring, logging, and observability
- Manage rollback and incident response procedures
- Coordinate smoke testing and deployment validation
- Track deployment metrics and system health
- Document release procedures and runbooks

### Goals
- Enable fast, safe, reliable deployments to production
- Minimize manual work and human error in releases
- Maintain high system availability and performance
- Reduce mean time to recovery (MTTR) from incidents

### Typical Communication
- Release planning and coordination with Product Manager and Project Manager
- Deployment readiness reviews with QA/Testing Lead and Security Lead
- Post-deployment monitoring and incident notifications
- Retrospectives on deployments and incidents

### Interactions with Other Roles
- Coordinate deployment validation with **QA/Testing Lead** on smoke tests
- Receive security approval from **Security Lead** before deploying to production
- Provide infrastructure and scaling guidance to **Technical Lead** and **Developers**
- Coordinate release timing with **Product Manager** and **Project Manager**
- Monitor system health and provide observability data to measure **Product Manager** success metrics
- Participate in incident response with **Technical Lead**, **Developers**, and **Project Manager**

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate ceremonies, remove blockers, and coach the team on agile practices. They help teams maintain consistent velocity, reduce waste, and continuously improve their delivery capabilities.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove blockers and impediments to team progress
- Coach team members on agile practices and mindsets
- Track sprint velocity and burndown metrics
- Maintain sprint backlog and process discipline
- Help the team reflect and implement continuous improvements
- Foster psychological safety and encourage feedback

### Goals
- Maintain consistent team velocity and delivery rhythm
- Reduce cycle time and waste in the development process
- Build a high-performing, self-organizing team
- Continuously improve team practices and outcomes

### Typical Communication
- Daily standups (facilitating, not reporting)
- Sprint planning and estimation sessions
- Sprint reviews and retrospectives
- One-on-ones with team members on blockers and concerns

### Interactions with Other Roles
- Remove blockers from **Developers** and coordinate with other roles to resolve impediments
- Facilitate planning and estimation collaboration between **Product Manager**, **Developers**, and **Project Manager**
- Help **Technical Lead** share knowledge and mentor developers
- Coach **Project Manager** on agile ceremonies and metrics
- Work with **QA/Testing Lead** to incorporate quality metrics into sprint planning
- Facilitate **DevOps/Release Engineer** collaboration on deployment automation improvements
- Foster retrospective culture and capture action items for **Product Manager** and **Project Manager**

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- References to specific roles in other OctoAcme process documents should align with the responsibilities and interactions defined here.
