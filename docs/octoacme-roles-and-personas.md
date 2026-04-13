# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Each persona includes their key responsibilities, goals, typical communication patterns, and how they interact with other roles.

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

### Interactions
- **With Product Managers:** Clarify requirements, discuss trade-offs, participate in acceptance criteria refinement
- **With Project Managers:** Provide estimates, flag blockers, report progress in standups
- **With QA/Testing:** Collaborate on test scenarios, fix defects, participate in code reviews
- **With UX Designers:** Discuss implementation feasibility, provide technical constraints, iterate on user flows
- **With Security Champions:** Incorporate security reviews, address vulnerabilities, follow secure coding practices

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Own product strategy and competitive positioning

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

### Interactions
- **With Project Managers:** Align on timelines, risks, and resource needs; provide priority guidance
- **With Developers:** Review technical proposals, discuss feasibility, define acceptance criteria
- **With Stakeholders:** Present roadmap, gather feedback, communicate business rationale
- **With UX Designers:** Collaborate on user research, validate designs against user needs
- **With Business Analysts:** Define requirements, validate market fit, measure impact
- **With Customer Support Liaisons:** Incorporate customer feedback, plan support readiness

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
- Track velocity, burndown, and key metrics

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

### Interactions
- **With Product Managers:** Align on scope, prioritization, and timeline; escalate blockers
- **With Developers:** Facilitate planning, manage dependencies, escalate blockers
- **With Stakeholders:** Provide status updates, communicate risks, seek approvals
- **With QA/Testing:** Coordinate testing schedules, track quality metrics
- **With Business Analysts:** Validate requirements, manage scope changes
- **With Security Champions:** Flag security-related risks, coordinate security reviews in timeline

---

## QA / Testing

### Role Summary
QA and Testing professionals ensure that delivered features meet acceptance criteria, maintain quality standards, and provide confidence in product releases.

### Responsibilities
- Create and maintain test plans and test cases
- Execute manual and automated testing across feature acceptance and regression scenarios
- Report and triage defects with clear reproducible steps
- Collaborate with developers on test strategy and coverage
- Validate that Definition of Done includes adequate test coverage
- Coordinate smoke tests and release validation activities
- Track quality metrics and test coverage

### Goals
- Ensure features meet acceptance criteria before release
- Reduce production incidents through comprehensive testing
- Provide clear visibility into product quality status

### Typical Communication
- Test plans and test case documentation
- Defect reports and quality metrics dashboards
- Coordination in planning, execution, and release ceremonies

### Interactions
- **With Developers:** Review acceptance criteria, collaborate on test scenarios, participate in code reviews
- **With Product Managers:** Clarify acceptance criteria, validate feature completeness
- **With Project Managers:** Report quality status, coordinate testing schedules, escalate blockers
- **With UX Designers:** Validate user workflows, test usability scenarios
- **With Stakeholders:** Present quality status and release readiness
- **With Security Champions:** Coordinate security testing and penetration testing

---

## UX Designers

### Role Summary
UX Designers champion the user experience throughout the project lifecycle. They conduct research, create prototypes, and collaborate with the team to ensure features are usable and meet user needs.

### Responsibilities
- Conduct user research and competitive analysis
- Create user flows, wireframes, and high-fidelity prototypes
- Validate design solutions with users and stakeholders
- Define interaction patterns and design systems
- Collaborate with developers on implementation feasibility
- Advocate for usability and accessibility standards
- Participate in feature acceptance and QA review

### Goals
- Deliver intuitive, accessible user experiences
- Reduce usability issues and support burden
- Align product features with user needs and expectations

### Typical Communication
- Design specs and prototypes (Figma, wireframes, etc.)
- Design review meetings and feedback sessions
- Accessibility and usability guidelines

### Interactions
- **With Product Managers:** Validate user needs, discuss design trade-offs, incorporate user research into roadmap
- **With Developers:** Discuss implementation constraints, review code for design system compliance, iterate on UI
- **With QA/Testing:** Define usability test scenarios, validate design implementation
- **With Project Managers:** Provide design timeline estimates, flag design-related risks
- **With Stakeholders:** Present design direction, gather stakeholder feedback
- **With Customer Support Liaisons:** Provide customer usability feedback, validate documentation approaches

---

## Business Analysts

### Role Summary
Business Analysts bridge the gap between business stakeholders and the delivery team. They gather, analyze, and clarify requirements to ensure shared understanding of what needs to be built.

### Responsibilities
- Conduct stakeholder interviews and gather business requirements
- Translate business needs into actionable, specific requirements
- Create requirements documentation and traceability matrices
- Identify gaps, ambiguities, and conflicting requirements
- Support scope definition and change management
- Validate that delivered features meet business objectives
- Facilitate workshops and working sessions with stakeholders

### Goals
- Ensure clarity and alignment on project scope and requirements
- Reduce rework due to unclear or missed requirements
- Maximize business value delivered

### Typical Communication
- Requirements documentation and specifications
- Stakeholder meeting notes and clarifications
- Change request documentation and impact analysis

### Interactions
- **With Stakeholders:** Conduct interviews, clarify business needs, validate requirements
- **With Product Managers:** Translate business needs into product features, align on priorities
- **With Project Managers:** Support scope definition, manage change requests, track requirements
- **With Developers:** Clarify requirements, discuss feasibility, resolve ambiguities
- **With QA/Testing:** Define acceptance criteria, support test case development

---

## Security Champions

### Role Summary
Security Champions advocate for secure development practices across the project lifecycle. They review features for security risks, ensure compliance, and work with the broader security team to maintain product security.

### Responsibilities
- Review architectural designs and code for security vulnerabilities
- Ensure compliance with security standards and policies
- Advocate for secure coding practices and security training
- Coordinate security scanning and penetration testing
- Participate in threat modeling and risk assessment activities
- Help triage and resolve security findings
- Stay current on emerging security threats and best practices

### Goals
- Deliver secure products that protect customer data
- Minimize security vulnerabilities and compliance risks
- Build security into the development process (shift-left security)

### Typical Communication
- Security threat models and vulnerability reports
- Code review feedback on security concerns
- Security compliance and risk assessments

### Interactions
- **With Developers:** Provide security guidance, review code, help resolve vulnerabilities
- **With Project Managers:** Flag security-related risks, coordinate security reviews in timeline
- **With Product Managers:** Advise on privacy and security trade-offs, influence roadmap for security improvements
- **With QA/Testing:** Coordinate security testing and penetration testing
- **With Stakeholders:** Report security posture, communicate incident response plans

---

## Customer Support Liaisons

### Role Summary
Customer Support Liaisons represent the voice of customers and support teams within the project. They ensure that new features are supportable, help plan support readiness, and provide feedback on customer pain points.

### Responsibilities
- Gather and communicate common customer issues and feature requests
- Review new features for support readiness and documentation needs
- Create support documentation and FAQs
- Conduct support training for new features
- Validate that features include clear error messages and user guidance
- Track customer satisfaction and support metrics
- Facilitate communication between support teams and product/engineering

### Goals
- Ensure features are easy for customers to understand and use
- Reduce support burden and improve first-contact resolution
- Drive product improvements based on customer feedback

### Typical Communication
- Customer feedback summaries and support metrics
- Support readiness documentation and training materials
- Feedback on feature usability and documentation

### Interactions
- **With Product Managers:** Communicate customer feedback, validate feature alignment with user expectations
- **With Developers:** Review features for supportability, provide customer context
- **With QA/Testing:** Coordinate user acceptance testing, validate feature completeness
- **With Project Managers:** Flag support-related risks, coordinate support readiness activities
- **With UX Designers:** Provide customer usability feedback, validate documentation approaches

---

## Stakeholders / Sponsors

### Role Summary
Stakeholders and Sponsors provide business context, approve scope and budgets, and represent organizational interests in the project. They may include executive leadership, business unit heads, or key customers.

### Responsibilities
- Define business objectives and success criteria
- Approve project charters and budgets
- Provide strategic guidance and resolve conflicts
- Communicate project importance and status to broader organization
- Make go/no-go decisions at key milestones
- Remove organizational blockers
- Participate in acceptance and launch decisions

### Goals
- Ensure project delivers business value
- Maintain alignment across organizational priorities
- Manage risk and organizational impact

### Typical Communication
- Project charters and one-pagers
- Monthly stakeholder updates and status reports
- Decision logs and escalation communications

### Interactions
- **With Project Managers:** Review status, approve scope changes, escalate decisions
- **With Product Managers:** Align on strategic direction, approve roadmap and priorities
- **With Business Analysts:** Provide business context, validate requirements
- **With Development Team:** Occasionally review progress, participate in major milestone reviews
- **With QA/Testing:** Receive quality status and release readiness reports
- **With UX Designers:** Provide strategic feedback on design direction

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference these personas in project checklists and communication templates to ensure all necessary roles are involved at key decision points.
- When reviewing the other OctoAcme process documents, these personas help clarify who is responsible for each activity and how cross-functional teams interact.
