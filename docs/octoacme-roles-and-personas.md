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

### Interactions with other roles
- **With Technical Lead**: follows architectural guidance and design reviews
- **With QA/Testing Lead**: collaborates on test automation and acceptance criteria clarity
- **With Product Manager**: aligns on requirements and acceptance criteria
- **With Project Manager**: provides status updates and risk identification

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

### Interactions with other roles
- **With Technical Lead**: advises on technical feasibility and trade-offs
- **With QA/Testing Lead**: aligns on quality standards and acceptance criteria
- **With UX/Design Lead**: collaborates on user experience and feature definition
- **With Developers**: communicates requirements and acceptance criteria
- **With Project Manager**: works on scope and prioritization decisions

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

### Interactions with other roles
- **With Technical Lead**: flags technical risks and dependency impacts
- **With QA/Testing Lead**: reports quality status and readiness
- **With DevOps/Release Engineer**: coordinates deployment windows
- **With Product Manager**: aligns on scope and prioritization
- **With Business Stakeholder**: provides status updates and escalations

---

## Technical Lead / Solution Architect

### Role Summary
Technical Leads provide architectural guidance, design oversight, and technical strategy. They ensure solutions are scalable, maintainable, and aligned with long-term technical vision.

### Responsibilities
- Define technical approach and architecture for initiatives
- Review and approve design decisions and trade-offs
- Identify technical risks and propose mitigations
- Mentor developers and conduct technical design reviews
- Advise on technology selections and technical debt management

### Goals
- Ensure technical excellence and long-term maintainability
- Minimize technical debt and architectural rework
- Transfer knowledge and build team capability

### Typical Communication
- Design review meetings and architectural discussions
- Technical documentation and decision records
- Code review feedback and technical mentoring

### Interactions with other roles
- **With Developers**: reviews designs, provides technical guidance, approves architecture
- **With Product Manager**: advises on technical feasibility and trade-offs during prioritization
- **With Project Manager**: flags technical risks and dependency impacts
- **With DevOps/Release Engineer**: ensures deployability and operational considerations

---

## QA/Testing Lead

### Role Summary
QA and Testing Leads own quality standards, test strategy, and acceptance validation. They ensure features meet acceptance criteria and quality benchmarks before release.

### Responsibilities
- Define test strategy and acceptance criteria with Product Manager
- Create and maintain test plans and QA approach
- Validate acceptance criteria are met before release
- Report quality metrics and test coverage
- Identify and escalate quality risks

### Goals
- Ensure features meet quality and usability standards
- Reduce defects reaching production
- Provide confidence in release readiness

### Typical Communication
- Test plan and strategy documents
- Quality reports and metrics dashboards
- Test execution results and issue tracking

### Interactions with other roles
- **With Developers**: collaborates on test automation and acceptance criteria clarity
- **With Product Manager**: aligns on quality standards and acceptance criteria
- **With Project Manager**: reports quality status and risks
- **With DevOps/Release Engineer**: collaborates on smoke testing and staging validation

---

## DevOps / Release Engineer

### Role Summary
Release Engineers own deployment pipelines, infrastructure management, and release execution. They enable safe, reliable deployments and maintain operational excellence.

### Responsibilities
- Build and maintain deployment automation and CI/CD pipelines
- Manage staging and production infrastructure
- Execute releases and deployments following release checklist
- Monitor post-deployment health and respond to incidents
- Document and maintain runbooks for deployment and rollback

### Goals
- Enable fast, safe deployments with minimal risk
- Reduce manual work and human error in deployments
- Maintain high system availability and performance

### Typical Communication
- Deployment schedules and release notes
- Infrastructure and pipeline documentation
- Incident communication and post-mortems

### Interactions with other roles
- **With Developers**: ensures code quality gates and automated testing in CI
- **With QA Lead**: collaborates on smoke testing and staging validation
- **With Project Manager**: coordinates deployment windows and communicates release status
- **With Technical Lead**: ensures deployability and operational considerations

---

## UX/Design Lead

### Role Summary
UX and Design Leads define user experience standards, ensure design consistency, and advocate for user needs throughout development.

### Responsibilities
- Define user experience vision and design standards
- Create design specifications and prototypes
- Conduct usability research and user testing
- Review implementations for design compliance
- Advocate for user-centered approaches in product decisions

### Goals
- Deliver intuitive, accessible user experiences
- Maintain design consistency and brand alignment
- Minimize post-launch UX issues

### Typical Communication
- Design specifications and mockups
- Usability research findings and insights
- Design review meetings and feedback

### Interactions with other roles
- **With Product Manager**: collaborates on feature definition and user needs
- **With Developers**: provides design specifications and conducts reviews
- **With QA/Testing Lead**: ensures usability acceptance criteria are met
- **With Business Stakeholder**: presents design rationale and user research

---

## Business Stakeholder / Sponsor

### Role Summary
Business Stakeholders and Sponsors provide business context, strategic alignment, and approval authority. They ensure projects deliver business value and advance organizational goals.

### Responsibilities
- Define business objectives and success metrics
- Provide strategic context and business priorities
- Approve major decisions and resource allocation
- Validate business value realization
- Support cross-organizational alignment

### Goals
- Ensure projects deliver measurable business value
- Minimize business risk and maximize ROI
- Maintain strategic alignment with organizational goals

### Typical Communication
- Executive status reports and milestone reviews
- Decision approvals and business case validation
- Stakeholder communication and escalations

### Interactions with other roles
- **With Product Manager**: aligns on business priorities and success metrics
- **With Project Manager**: reviews status and provides approvals
- **With Technical Lead**: understands technical trade-offs and risks
- **With Support/Customer Success Manager**: validates customer impact and feedback

---

## Support / Customer Success Manager

### Role Summary
Support and Customer Success Managers represent post-release customer needs and feedback. They ensure products remain valuable and usable after launch.

### Responsibilities
- Collect and prioritize customer feedback
- Identify support patterns and product gaps
- Advocate for customer pain points in prioritization
- Provide customer context during product decisions
- Track customer health and satisfaction metrics

### Goals
- Maximize customer satisfaction and retention
- Identify improvement opportunities from customer insights
- Reduce support burden through product improvements

### Typical Communication
- Customer feedback and issue reports
- Support metrics and trends
- Customer success reviews and business reviews

### Interactions with other roles
- **With Product Manager**: provides customer feedback for prioritization
- **With Developers**: communicates customer needs and use cases
- **With Project Manager**: escalates critical customer issues
- **With Business Stakeholder**: reports on customer health and NPS

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to persona interactions to understand cross-functional dependencies and communication patterns in project delivery.
