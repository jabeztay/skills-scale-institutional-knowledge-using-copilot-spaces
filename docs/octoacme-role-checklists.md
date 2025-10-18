# OctoAcme Role Checklists

This document provides actionable checklists for key project roles. These can be copy-pasted into project READMs or used during planning and execution phases.

---

## Release Manager Checklist

### Pre-Release Planning
- [ ] Confirm release date and scope with PM and Product Manager
- [ ] Create release branch and communicate branch name to team
- [ ] Review and finalize release notes with contributors
- [ ] Verify all planned features/fixes are merged to release branch
- [ ] Confirm rollback plan is documented and tested
- [ ] Schedule deployment window and notify stakeholders

### Release Execution
- [ ] Verify CI passes on release branch (tests, security scans, build)
- [ ] Deploy to staging environment
- [ ] Coordinate smoke testing on staging with QA Lead
- [ ] Obtain sign-off from QA Lead and PM
- [ ] Execute production deployment
- [ ] Run post-deployment verification tests
- [ ] Monitor error rates and key metrics for 30 minutes post-deploy

### Post-Release
- [ ] Publish release notes to stakeholders and customers
- [ ] Update version numbers and tags in repository
- [ ] Archive release documentation
- [ ] Conduct release retrospective (if major release)
- [ ] Close release milestone and update project board

---

## QA Lead Checklist

### Test Planning
- [ ] Review acceptance criteria with Product Manager and developers
- [ ] Define test scope (unit, integration, e2e, performance)
- [ ] Identify test data requirements and prepare test environments
- [ ] Create or update test cases for new features
- [ ] Assign testing responsibilities to team members

### Test Execution
- [ ] Run automated test suite and review results
- [ ] Execute manual test cases for new functionality
- [ ] Test edge cases and error scenarios
- [ ] Verify cross-browser/platform compatibility (if applicable)
- [ ] Test accessibility compliance
- [ ] Document any defects found and assign priority

### Release Sign-off
- [ ] Verify all critical defects are resolved
- [ ] Confirm test coverage meets team standards
- [ ] Run regression tests on release candidate
- [ ] Review smoke test results on staging
- [ ] Provide go/no-go recommendation to Release Manager
- [ ] Document known issues and workarounds

---

## UX Designer Checklist

### Discovery & Research
- [ ] Conduct user research to understand needs and pain points
- [ ] Review analytics and user feedback on existing features
- [ ] Create user personas and journey maps (if needed)
- [ ] Define design success criteria with Product Manager
- [ ] Identify design constraints and technical limitations

### Design & Prototyping
- [ ] Create wireframes for key user flows
- [ ] Design high-fidelity mockups aligned with design system
- [ ] Build interactive prototype for user testing
- [ ] Conduct usability testing and gather feedback
- [ ] Iterate designs based on feedback
- [ ] Document interaction patterns and component specifications

### Handoff & Implementation
- [ ] Prepare design handoff documentation for developers
- [ ] Review technical feasibility with engineering team
- [ ] Provide design assets and specifications
- [ ] Answer developer questions during implementation
- [ ] Review implemented UI against design specifications
- [ ] Collaborate with QA Lead on acceptance criteria for user flows

---

## Technical Writer Checklist

### Documentation Planning
- [ ] Review feature specifications and acceptance criteria
- [ ] Identify documentation needs (user guide, API docs, tutorials)
- [ ] Determine target audience and documentation format
- [ ] Establish documentation deadline aligned with release date
- [ ] Coordinate with developers for technical review availability

### Content Creation
- [ ] Draft documentation content based on specifications
- [ ] Include code examples, screenshots, or diagrams as needed
- [ ] Test all code examples and procedures for accuracy
- [ ] Review documentation with developers for technical accuracy
- [ ] Incorporate feedback and finalize content
- [ ] Ensure documentation follows style guide and standards

### Publication & Maintenance
- [ ] Publish documentation to documentation site
- [ ] Update navigation and search index
- [ ] Create or update release notes
- [ ] Notify stakeholders of new/updated documentation
- [ ] Monitor feedback and support tickets for documentation gaps
- [ ] Schedule periodic documentation review and updates

---

## Using These Checklists

- Copy relevant checklists into your project README or planning documents
- Customize checklists to match your team's specific processes
- Use checklists during sprint planning to ensure all activities are covered
- Reference checklists during retrospectives to identify process improvements
- Link to these checklists from other process docs for easy reference
