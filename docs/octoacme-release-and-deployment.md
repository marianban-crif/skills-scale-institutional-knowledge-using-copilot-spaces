# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

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
- [ ] Deployment window scheduled (if needed) (Project Manager)
- [ ] Security scan results reviewed and approved (Security Lead)
- [ ] Documentation published or updated (Technical Writer)
- [ ] Support team trained on new features (Customer Support Representative)
- [ ] Customer-facing communications prepared (Product Manager + Customer Support)
- [ ] UX acceptance testing completed (UX Designer)
- [ ] Backup or snapshot (if applicable) (Developers)
- [ ] Deploy to staging and run smoke tests (Developers)
- [ ] Deploy to production (automated pipeline preferred) (Developers)
- [ ] Run post-deploy verifications (Developers + Scrum Master)
- [ ] Announce release to stakeholders and support (Project Manager + Product Manager)

## Role-Specific Release Responsibilities
- **Developers**: Execute deployment, monitor systems, handle rollbacks if needed
- **Security Lead**: Final security approval, monitors for security incidents post-release
- **Technical Writer**: Publishes release documentation and user guides
- **Customer Support**: Prepares to handle customer inquiries, updates knowledge base
- **UX Designer**: Validates user experience in production, monitors usability metrics
- **Product Manager**: Communicates release to stakeholders, tracks success metrics
- **Project Manager**: Coordinates release activities, manages communications
- **Scrum Master**: Facilitates release retrospective to capture lessons learned

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
