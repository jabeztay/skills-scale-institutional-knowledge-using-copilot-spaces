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

## Release Manager

### Role Summary
Release Managers coordinate the end-to-end release process, ensuring that code moves safely and reliably from development to production. They manage release schedules, communicate deployment plans, and ensure rollback procedures are in place.

### Responsibilities
- Plan and coordinate release schedules across teams
- Manage release branches and version control for deployments
- Oversee deployment pipeline execution and monitor for issues
- Coordinate rollback procedures when necessary
- Ensure release notes and deployment documentation are complete
- Communicate release status to stakeholders

### Goals
- Minimize deployment risk and downtime
- Ensure smooth, predictable release cadence
- Maintain clear audit trail of what was released when

### Typical Communication
- Release status updates and deployment schedules
- Go/no-go decisions before production deployments
- Post-deployment reports and incident coordination
- Release notes and changelog communications

### Interaction Points
- **With Project Managers**: Align on release timelines and milestone readiness
- **With Product Managers**: Confirm feature completeness and priorities for releases
- **With Developers**: Coordinate code freeze dates, branch management, and deployment verification
- **With QA Lead**: Validate testing sign-off before releases
- **With Technical Writers**: Ensure documentation is ready for release

### Success Criteria
- Zero unplanned rollbacks in production
- Release notes published on time for every release
- Deployment process completed within planned maintenance windows

---

## QA Lead

### Role Summary
QA Leads define the testing strategy, coordinate quality assurance activities, and ensure features meet acceptance criteria before release. They balance thoroughness with delivery velocity.

### Responsibilities
- Define test plans and testing strategy for features and releases
- Coordinate manual and automated testing efforts
- Identify and track defects through resolution
- Sign off on feature readiness and release quality
- Maintain test environments and test data
- Collaborate with developers on test automation

### Goals
- Prevent critical defects from reaching production
- Maintain high test coverage and quality standards
- Enable rapid, confident releases through effective testing

### Typical Communication
- Test status reports and defect summaries
- Quality gates and sign-off approvals
- Test plan reviews with PM and engineering
- Bug triage meetings

### Interaction Points
- **With Developers**: Review test coverage, reproduce defects, collaborate on test automation
- **With Product Managers**: Clarify acceptance criteria and edge cases
- **With Project Managers**: Report testing progress and blockers
- **With Release Manager**: Provide quality sign-off for releases
- **With UX Designer**: Validate user flows and interaction patterns

### Success Criteria
- All critical user flows covered by automated tests
- Zero critical defects in production deployments
- Test execution completed before release deadlines

---

## UX Designer

### Role Summary
UX Designers create user-centered designs that solve customer problems and align with product strategy. They conduct user research, create wireframes and prototypes, and collaborate with developers to implement designs effectively.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define interaction patterns and visual design standards
- Collaborate with developers on design implementation
- Validate implemented features match design intent
- Maintain design system and component library

### Goals
- Create intuitive, accessible user experiences
- Validate designs solve real user problems
- Ensure consistent design implementation across products

### Typical Communication
- Design reviews and critique sessions
- Usability testing reports and findings
- Handoff documentation for developers
- Design specs and component documentation

### Interaction Points
- **With Product Managers**: Align on user needs, feature priorities, and success metrics
- **With Developers**: Collaborate on design feasibility, implementation details, and refinements
- **With QA Lead**: Review acceptance criteria and validate user flows in testing
- **With Project Managers**: Provide design estimates and flag design dependencies

### Success Criteria
- User satisfaction scores meet or exceed targets
- Design implementation matches specifications
- Design system reduces implementation time for new features

---

## Technical Writer

### Role Summary
Technical Writers create clear, accurate documentation that helps users and developers succeed with the product. They ensure documentation is up-to-date, accessible, and aligned with product capabilities.

### Responsibilities
- Write and maintain user guides, API documentation, and tutorials
- Collaborate with developers on technical accuracy
- Update documentation for new features and releases
- Maintain documentation site and information architecture
- Gather feedback on documentation quality and gaps
- Create release notes and migration guides

### Goals
- Enable users to self-serve through clear documentation
- Reduce support burden through comprehensive guides
- Maintain documentation quality and consistency

### Typical Communication
- Documentation reviews with engineering and product teams
- Release notes and changelog updates
- Documentation feedback and improvement suggestions
- Information architecture proposals

### Interaction Points
- **With Developers**: Gather technical details and validate accuracy
- **With Product Managers**: Understand feature value propositions and user workflows
- **With Release Manager**: Coordinate documentation updates with releases
- **With Project Managers**: Track documentation deliverables and timelines

### Success Criteria
- Documentation published before or at feature release
- Reduction in support tickets for well-documented features
- Positive user feedback on documentation quality

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

