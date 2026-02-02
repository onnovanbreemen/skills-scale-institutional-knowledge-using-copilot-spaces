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

## Business Analysts

### Role Summary
Business Analysts elicit requirements, document business needs, and bridge the gap between stakeholder goals and technical scope. They ensure requirements are clear, complete, and actionable for development teams.

### Responsibilities
- Gather and document business requirements from stakeholders
- Translate business needs into functional specifications
- Create process flows, use cases, and requirement documents
- Validate that delivered features meet business objectives
- Facilitate requirements workshops and discovery sessions

### Goals
- Ensure alignment between business needs and technical solutions
- Minimize rework through clear, complete requirements
- Enable effective decision-making with accurate analysis

### Typical Communication
- Requirements workshops with stakeholders and Product Managers
- Clarification sessions with Developers during sprint planning
- Documentation updates and requirement traceability matrices

### Interactions with Other Roles
- **Product Managers**: Collaborates during initiation and planning to define features and priorities
- **Project Managers**: Works together to ensure requirements are scheduled and tracked
- **Developers**: Clarifies requirements and acceptance criteria throughout implementation
- **QA Engineers**: Provides detailed requirements for test case creation
- **UX Designers**: Aligns on user needs and experience requirements

---

## UX Designers

### Role Summary
UX Designers create user flows, wireframes, and prototypes to ensure products are usable, accessible, and delightful. They advocate for the end user throughout the product development lifecycle.

### Responsibilities
- Design user interfaces, wireframes, and interactive prototypes
- Conduct user research and usability testing
- Ensure accessibility standards are met (WCAG, ARIA)
- Create design systems and component libraries
- Validate designs with users and stakeholders

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and improve satisfaction metrics
- Maintain design consistency across products

### Typical Communication
- Design reviews and critique sessions
- User research findings and persona documentation
- Design specifications and handoff materials

### Interactions with Other Roles
- **Product Managers**: Partners on feature specifications and user requirements
- **Business Analysts**: Aligns on user needs and workflow requirements
- **Developers**: Collaborates during implementation for design fidelity
- **QA Engineers**: Reviews acceptance criteria and validates user experience
- **Support Lead**: Gathers feedback on user pain points and usability issues

---

## QA Engineers

### Role Summary
QA Engineers ensure product quality through comprehensive testing strategies. They author test plans, execute tests, validate acceptance criteria, and track defects to ensure reliable releases.

### Responsibilities
- Develop test plans, test cases, and testing scripts
- Execute manual and automated tests across features
- Validate acceptance criteria and functional requirements
- Track, document, and verify defect resolution
- Perform regression testing before releases

### Goals
- Prevent defects from reaching production
- Maintain high test coverage and quality standards
- Reduce post-release incidents and customer-reported bugs

### Typical Communication
- Daily test status updates and defect reports
- Test plan reviews with team leads
- Bug triage meetings and quality metrics dashboards

### Interactions with Other Roles
- **Developers**: Partners for test coverage planning and defect resolution
- **Project Managers**: Coordinates QA cycles and schedule testing milestones
- **Release Managers**: Provides pre-release testing and go/no-go recommendations
- **UX Designers**: Validates user experience against design specifications
- **Support Lead**: Shares insights on production issues and testing gaps

---

## Release Managers

### Role Summary
Release Managers oversee deployment activities, coordinate release processes, and manage incident response. They ensure smooth, reliable releases with minimal disruption to users.

### Responsibilities
- Plan and coordinate release schedules and activities
- Manage deployment processes and release checklists
- Coordinate rollback procedures when needed
- Monitor release health and incident response
- Maintain release documentation and runbooks

### Goals
- Achieve zero-downtime deployments
- Minimize release-related incidents
- Ensure predictable, repeatable release processes

### Typical Communication
- Release readiness meetings and go/no-go decisions
- Deployment status updates and incident alerts
- Post-release reports and metrics reviews

### Interactions with Other Roles
- **Developers**: Verifies code readiness and deployment requirements
- **QA Engineers**: Confirms testing completion and quality sign-off
- **Project Managers**: Aligns release schedules with project timelines
- **Support Lead**: Coordinates incident response and user communications
- **Product Managers**: Updates on release status and feature availability

---

## Support Leads

### Role Summary
Support Leads coordinate incident response, manage customer support communications, and gather post-release feedback. They ensure customer issues are resolved quickly and insights are fed back into product development.

### Responsibilities
- Manage support ticket queues and escalations
- Coordinate incident response with engineering teams
- Gather and analyze customer feedback and pain points
- Document known issues and workarounds
- Provide insights for product improvements

### Goals
- Minimize customer downtime and resolve issues quickly
- Improve first-response and resolution times
- Surface actionable product improvement opportunities

### Typical Communication
- Daily support metrics and escalation updates
- Incident post-mortems and root cause analysis
- Customer feedback summaries and feature requests

### Interactions with Other Roles
- **QA Engineers**: Shares production issues to improve test coverage
- **Release Managers**: Coordinates during incidents and rollbacks
- **Product Managers**: Provides customer insights and improvement suggestions
- **Developers**: Escalates critical bugs and collaborates on fixes
- **Project Managers**: Reports on support impact and capacity planning

---

## Cross-Role Collaboration and Handoffs

### Requirements Phase
**Business Analyst → UX Designer → Product Manager**
- Business Analyst documents requirements and user needs
- UX Designer creates wireframes and user flows based on requirements
- Product Manager validates alignment with product vision and priorities

### Planning Phase
**Product Manager → Project Manager → Development Team**
- Product Manager prioritizes backlog and defines acceptance criteria
- Project Manager creates sprint plans and assigns resources
- Developers estimate effort and identify technical dependencies

### Development Phase
**Developer → QA Engineer → UX Designer**
- Developer implements features and submits for review
- QA Engineer validates functionality against acceptance criteria
- UX Designer reviews implementation for design fidelity

### Release Phase
**QA Engineer → Release Manager → Support Lead**
- QA Engineer provides testing sign-off and known issues
- Release Manager executes deployment and monitors release health
- Support Lead prepares for customer inquiries and monitors incidents

### Continuous Improvement
**Support Lead → Product Manager → Business Analyst**
- Support Lead shares customer feedback and pain points
- Product Manager prioritizes improvements based on impact
- Business Analyst documents enhancement requirements

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

