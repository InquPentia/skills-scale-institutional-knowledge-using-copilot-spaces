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

## QA / Testing Lead

### Role Summary
QA / Testing Leads define quality strategy, test plans, and release readiness for features and increments. They ensure delivery quality is measurable, verifiable, and aligned with the product definition of done.

### Responsibilities
- Define test strategy, test plans, and release quality gates
- Create and maintain automated and manual test coverage
- Validate features against acceptance criteria and quality standards
- Identify, document, and triage defects with clear reproduction steps
- Collaborate with Developers on testability and regression risk
- Sign off on release readiness with Product and Project stakeholders

### Goals
- Reduce defect escape to production
- Improve confidence in release quality and customer experience
- Maintain a repeatable, transparent QA process

### Typical Communication
- Daily QA updates in standups and review meetings
- Test summaries and defect reports in PR reviews and release checkpoints
- Quality-risk escalations with Project Managers and Product Managers

### Interaction with existing roles
- With Developers: partners on testability, defect triage, and regression prevention
- With Product Managers: validates that acceptance criteria are met and user value is protected
- With Project Managers: reports quality risks, readiness status, and release blockers

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide architecture direction, technical standards, and design guidance so the team can deliver maintainable, scalable, and secure solutions.

### Responsibilities
- Review technical design and architecture decisions
- Identify technical risks, trade-offs, and mitigation strategies
- Mentor Developers and guide code quality and system design
- Ensure architecture aligns with product goals and operational constraints
- Coordinate integration decisions across services, platforms, and dependencies

### Goals
- Deliver technically sound, maintainable systems
- Reduce rework and avoid avoidable technical debt
- Support sustainable delivery at scale

### Typical Communication
- Design reviews and architecture decision records
- Technical dependency updates in planning and implementation meetings
- Guidance during code review and incident response

### Interaction with existing roles
- With Developers: provides architecture guidance, code review support, and technical mentorship
- With Product Managers: translates product priorities into technical trade-offs and delivery feasibility
- With Project Managers: helps scope complexity, assess delivery risk, and plan dependencies

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters or Agile Coaches facilitate team health, ceremony effectiveness, and continuous improvement so delivery remains focused, predictable, and collaborative.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Remove or escalate blockers that slow delivery
- Coach the team on agile practices and collaboration habits
- Help improve flow, visibility, and team accountability
- Support healthy team dynamics and continuous improvement work

### Goals
- Improve team efficiency and delivery predictability
- Reduce friction in the delivery process
- Strengthen a learning-oriented, psychologically safe working culture

### Typical Communication
- Team ceremonies and retrospectives
- Active blocker tracking and coaching conversations
- Alignment discussions with Project Managers and Product Leads

### Interaction with existing roles
- With Developers: supports delivery rhythm, collaboration, and process improvement
- With Product Managers: helps align delivery priorities with team capacity and flow
- With Project Managers: coordinates execution visibility, impediments, and planning discipline

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, funding, strategic direction, and decision-making authority. They ensure the project stays aligned with business priorities and organizational goals.

### Responsibilities
- Define business outcomes, success criteria, and strategic priorities
- Approve milestones, budget commitments, and major changes
- Provide executive sponsorship and decision support when risks arise
- Align cross-functional work with broader organizational objectives
- Escalate decisions that require leadership support or resource trade-offs

### Goals
- Ensure the project delivers measurable business value
- Maintain strategic alignment and resource support
- Support timely decisions that unblock progress

### Typical Communication
- Monthly or milestone-based status reviews
- Decision forums, steering updates, and executive briefings
- Escalation of cross-team dependency or risk issues

### Interaction with existing roles
- With Product Managers: aligns product strategy and business outcomes
- With Project Managers: reviews progress, milestones, and escalations
- With Developers and delivery teams: provides clarity on priorities and trade-offs without micro-managing execution

---

## Security / Compliance Officer

### Role Summary
Security and Compliance Officers ensure that work meets regulatory, privacy, and security requirements throughout the project lifecycle.

### Responsibilities
- Define and validate security and compliance requirements for features and releases
- Review designs, workflows, and implementation choices for risk exposure
- Ensure security controls are in place for data handling, access, and deployment
- Support remediation planning for vulnerabilities and compliance gaps
- Coordinate with incident response and governance processes when needed

### Goals
- Reduce security and compliance risk
- Embed safe practices into delivery without slowing value creation unnecessarily
- Maintain trust and regulatory readiness

### Typical Communication
- Security reviews, compliance checkpoints, and risk discussions
- Release sign-off requirements and governance updates
- Escalations for critical security or policy concerns

### Interaction with existing roles
- With Developers: reviews secure implementation patterns and validates controls
- With Product Managers: ensures business requirements include risk and compliance considerations
- With Project Managers and Sponsors: communicates policy risk, remediation timing, and broader impacts

---

## DevOps / Infrastructure Engineer

### Role Summary
DevOps / Infrastructure Engineers support system reliability, automation, and operational readiness so the team can deploy and support features safely and repeatedly.

### Responsibilities
- Maintain CI/CD pipelines, environment configuration, and deployment automation
- Manage infrastructure provisioning, scaling, and monitoring practices
- Support reliability, observability, and post-deployment verification
- Collaborate with teams to reduce deployment risk and recovery time
- Help troubleshoot production issues and support operational continuity

### Goals
- Enable fast, safe, repeatable delivery
- Improve system reliability and observability
- Reduce deployment and operational risk

### Typical Communication
- Deployment readiness reviews and pipeline status updates
- Production incident coordination and recovery follow-up
- Infrastructure and reliability planning with delivery and PM stakeholders

### Interaction with existing roles
- With Developers: supports build, deploy, and environment readiness for feature delivery
- With Project Managers: provides deployment risk assessments and release timing guidance
- With Security / Compliance: helps maintain secure infrastructure standards and operational controls

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- This expanded set helps teams clarify ownership, communication paths, and decision-making across the full project lifecycle.

