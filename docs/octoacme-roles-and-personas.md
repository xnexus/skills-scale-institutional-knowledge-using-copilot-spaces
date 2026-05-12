# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It covers both core delivery roles and cross-functional roles that appear across planning, execution, risk management, release, and continuous improvement workflows.

See also: [Role-to-Process Matrix](./octoacme-role-process-matrix.md) for a quick view of which roles are active at each lifecycle stage.

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
- **Technical Lead**: receives technical direction, design guidance, and code review feedback
- **Project Manager**: provides status updates, flags blockers, and participates in risk identification
- **Product Manager**: clarifies acceptance criteria and scope trade-offs
- **QA/Testing**: hands off completed work for validation; addresses defects
- **Security / Compliance Lead**: incorporates security feedback from code reviews and scans

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

### Interactions
- **Project Manager**: aligns on scope, timeline, and priority changes; co-owns the project one-pager
- **UX / Product Designer**: collaborates on user journeys, prototypes, and acceptance criteria
- **Stakeholder / Sponsor**: presents roadmap, collects input, and surfaces prioritization decisions
- **Technical Lead**: discusses feasibility and implementation trade-offs
- **Developers**: provides requirements and validates delivered work against success metrics

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

### Interactions
- **Product Manager**: weekly sync on scope, priority, and milestone readiness
- **Technical Lead**: discusses technical risks, dependencies, and delivery estimates
- **Engineering Manager**: partners on team capacity, staffing risks, and escalations
- **Security / Compliance Lead**: involves in risk register updates and release readiness checks
- **Stakeholder / Sponsor**: provides status updates and escalates blockers requiring approval

---

## QA / Testing

### Role Summary
QA and testing roles validate that delivered work meets acceptance criteria, quality standards, and regression requirements before release. They are the last structured checkpoint between implementation and production.

### Responsibilities
- Define and execute test plans for features and releases
- Validate acceptance criteria against delivered work
- Identify, document, and track defects to resolution
- Perform regression testing after fixes or deployments
- Contribute to the Definition of Done criteria

### Goals
- Prevent regressions and undiscovered defects from reaching production
- Provide clear, fast feedback on feature readiness
- Raise quality bar through consistent standards and automation

### Typical Communication
- Test results and defect reports shared with the delivery team
- QA sign-off status included in release readiness reviews
- Participation in sprint demos and release checklists

### Interactions
- **Developers**: reviews work-in-progress, communicates defects, verifies fixes
- **Project Manager**: communicates testing progress, signals when milestones are at risk
- **Product Manager**: clarifies acceptance criteria and edge cases
- **Technical Lead**: escalates complex technical defects or environment issues
- **Support / Operations Lead**: shares known issues and production defect trends to inform test coverage

---

## Technical Lead

### Role Summary
The Technical Lead owns technical direction, architecture decisions, and implementation trade-offs for a project or team. They translate product and business goals into a clear, executable technical approach and are the primary escalation point for technical risk.

### Responsibilities
- Define and communicate technical architecture and design decisions
- Review code and ensure quality, consistency, and maintainability standards are met
- Identify and manage technical risks and dependencies
- Guide developers on implementation approach, patterns, and best practices
- Participate in planning to ensure estimates and scope are technically grounded
- Assess technical feasibility of new requirements and surface trade-offs

### Goals
- Deliver a technically sound, maintainable solution within project constraints
- Minimize technical debt introduced during delivery
- Ensure the team has a shared understanding of the technical approach

### Typical Communication
- Technical design docs and architecture decision records (ADRs)
- Code review comments and pull request feedback
- Engineering syncs and technical discussions during planning and estimation

### Interactions
- **Developers**: provides technical direction, design patterns, and code review feedback; escalation point for technical blockers
- **Project Manager**: communicates technical risks, dependencies, and impact on timeline
- **Product Manager**: advises on feasibility, cost, and trade-offs of requirements
- **Engineering Manager**: coordinates on team capacity, staffing gaps, and technical hiring needs
- **Security / Compliance Lead**: collaborates on secure design patterns and addresses findings from security reviews

---

## Engineering Manager

### Role Summary
The Engineering Manager supports team health, delivery capacity, and career development for the engineering team. They act as a bridge between individual contributors and organizational leadership, and partner with Project Managers on resourcing and escalation.

### Responsibilities
- Manage team staffing, capacity planning, and resource allocation across projects
- Support developer growth through coaching, feedback, and performance conversations
- Remove organizational blockers and escalate systemic issues affecting delivery
- Facilitate healthy team dynamics and a psychologically safe working environment
- Partner with Technical Leads on execution readiness and engineering quality

### Goals
- Maintain a healthy, high-performing team capable of sustained delivery
- Ensure projects are appropriately staffed and engineers are unblocked
- Balance short-term delivery needs with long-term team investment

### Typical Communication
- One-on-ones with direct reports
- Staffing and capacity discussions with Project Managers
- Cross-team coordination and escalation for systemic blockers

### Interactions
- **Project Manager**: aligns on team capacity, flags staffing risks, and participates in escalation for delivery-impacting issues
- **Technical Lead**: partners on execution readiness, code quality standards, and technical hiring
- **Developers**: provides coaching, career feedback, and organizational support
- **Stakeholder / Sponsor**: may be involved in escalations affecting team structure or delivery commitments
- **Product Manager**: provides input on team capacity when scope trade-offs are being evaluated

---

## UX / Product Designer

### Role Summary
UX and Product Designers define the user experience, interaction patterns, and visual design of product features. They ensure that solutions are usable, accessible, and aligned with customer needs before and during implementation.

### Responsibilities
- Conduct user research and synthesize findings into design requirements
- Create wireframes, prototypes, and high-fidelity designs for review
- Define interaction flows, usability requirements, and accessibility standards
- Collaborate with Product Managers to translate user needs into acceptance criteria
- Iterate on designs based on usability testing and developer feedback

### Goals
- Deliver intuitive, accessible, and high-quality user experiences
- Reduce implementation rework by clarifying design intent early
- Ensure design decisions are informed by real user data and validated assumptions

### Typical Communication
- Design reviews and prototype walkthroughs with the delivery team
- Design specs and annotated mockups shared with Developers
- Participation in sprint planning and kickoffs to present design context

### Interactions
- **Product Manager**: partners on defining user problems, requirements, and success criteria
- **Developers**: provides design specifications, answers implementation questions, and reviews UI output for fidelity
- **QA / Testing**: reviews test cases for usability and accessibility coverage
- **Stakeholder / Sponsor**: presents designs for feedback during review milestones
- **Technical Lead**: aligns on feasibility of interaction patterns and design system constraints

---

## Security / Compliance Lead

### Role Summary
The Security / Compliance Lead advises on security controls, compliance requirements, and risk posture across the project lifecycle. They are a key contributor to risk identification and release readiness, and the primary escalation point for security incidents.

### Responsibilities
- Review security-sensitive changes, designs, and configurations
- Assess compliance requirements (e.g., data privacy, regulatory obligations) and advise the team
- Participate in risk register reviews to identify and assess security-related risks
- Validate that CI security scans are configured and findings are triaged appropriately
- Contribute to release readiness sign-off for security-sensitive changes
- Support incident response for security-related issues

### Goals
- Prevent security vulnerabilities and compliance gaps from reaching production
- Make security guidance practical and actionable for delivery teams
- Ensure the team has clear escalation paths for security incidents

### Typical Communication
- Security review findings shared with developers and Technical Leads
- Participation in risk register reviews and escalation discussions with Project Managers
- Release readiness input on security scan results and known vulnerabilities

### Interactions
- **Developers**: provides secure coding guidance, reviews implementations, and communicates scan findings
- **Technical Lead**: collaborates on secure architecture decisions and remediation plans
- **Project Manager**: flags security risks and contributes to the risk register; involved in escalation for security blockers
- **Support / Operations Lead**: partners on production security monitoring and incident response
- **Stakeholder / Sponsor**: may be involved in escalations involving compliance obligations or data risk

---

## Support / Operations Lead

### Role Summary
The Support / Operations Lead represents production readiness, operational health, and customer support perspectives. They ensure that teams ship changes that can be monitored, supported, and rolled back safely, and that production feedback flows back into future planning.

### Responsibilities
- Advise on observability requirements (logging, alerting, dashboards) for new features
- Participate in release readiness reviews to assess production impact and rollback plans
- Monitor production health after deployments and coordinate incident response
- Surface recurring support issues and production defect trends to inform planning
- Ensure support documentation and runbooks are updated before release

### Goals
- Prevent production incidents caused by insufficient operational readiness
- Shorten mean time to resolution (MTTR) through better observability and runbooks
- Create a feedback loop from production and support into the development cycle

### Typical Communication
- Participation in release readiness and deployment checklist reviews
- Incident updates and post-incident retrospective notes
- Production trend summaries shared with Project Managers and Product Managers

### Interactions
- **Project Manager**: communicates production readiness risks; participates in risk register for operations-impacting changes
- **Developers**: advises on observability requirements; coordinates on production incidents
- **QA / Testing**: shares known production issues and defect trends to inform regression coverage
- **Security / Compliance Lead**: partners on security incident response and post-incident reviews
- **Stakeholder / Sponsor**: provides visibility into production health and customer impact during incidents

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors represent business, customer, or organizational interests in a project. They provide strategic input, approve key decisions, and are the final escalation point for scope, priority, and resource trade-offs.

### Responsibilities
- Approve project initiation (go/no-go) and major scope changes
- Provide input on business priorities, customer needs, and organizational constraints
- Participate in milestone reviews and release announcements
- Make decisions when escalated trade-offs exceed the authority of the delivery team
- Ensure resources and organizational support are available for the project

### Goals
- Confirm that projects deliver measurable business and customer value
- Make timely decisions to keep delivery unblocked
- Maintain visibility into progress, risks, and outcomes without requiring deep day-to-day involvement

### Typical Communication
- Monthly status updates and milestone reports from the Project Manager
- Escalation notifications when blockers require sponsor-level decisions
- Participation in project kickoffs, major milestone reviews, and release announcements

### Interactions
- **Project Manager**: primary point of contact for status, escalations, and decision requests
- **Product Manager**: reviews roadmap, validates business priorities, and provides input on scope trade-offs
- **Engineering Manager**: may be involved in escalations affecting team structure or delivery commitments
- **Security / Compliance Lead**: may be involved in escalations with compliance or data risk implications
- **Support / Operations Lead**: receives visibility into production incidents and customer impact

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The [Role-to-Process Matrix](./octoacme-role-process-matrix.md) provides a quick reference for which roles are active at each lifecycle stage.

