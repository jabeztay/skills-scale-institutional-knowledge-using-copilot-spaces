# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Role Ownership

Clear role ownership ensures accountability throughout the release process:

- **Release Manager**: Coordinates overall release process, manages deployment execution, and ensures rollback procedures are ready
- **QA Lead**: Provides testing sign-off, validates smoke tests on staging, and confirms quality gates are met
- **Technical Writer**: Ensures release notes and documentation are complete and published with the release
- **Project Manager**: Aligns release timeline with project milestones and communicates status to stakeholders
- **Developers**: Prepare code for release, assist with deployment verification, and support incident response if needed

For detailed checklists per role, see [OctoAcme Role Checklists](octoacme-role-checklists.md).

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
