# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner (assigned to appropriate role)
- Mitigation plan
- Status

### Role-Specific Risk Ownership
- **Security Lead**: Security vulnerabilities, compliance risks, data privacy issues
- **Technical Writer**: Documentation gaps, unclear user guidance
- **UX Designer**: Usability risks, accessibility compliance issues
- **Developers**: Technical debt, performance issues, integration risks
- **Product Manager**: Market risks, stakeholder misalignment, scope creep
- **Project Manager**: Timeline risks, resource constraints, dependency blockers
- **Customer Support**: Customer satisfaction risks, support capacity issues
- **Scrum Master**: Team velocity risks, process bottlenecks

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

### Communication Matrix by Role
- **Product Manager**: Roadmap updates, feature announcements, stakeholder briefings
- **Project Manager**: Status reports, milestone tracking, risk escalations
- **Scrum Master**: Sprint reports, team velocity, impediment status
- **Developers**: Technical updates, PR reviews, implementation details
- **UX Designer**: Design decisions, research findings, usability test results
- **Security Lead**: Security advisories, compliance status, incident notifications
- **Technical Writer**: Documentation release notes, style guide updates
- **Customer Support**: Support metrics, customer feedback, known issues

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security Lead on-call
- For UX/accessibility issues impacting launch, escalate to UX Designer and Product Manager
- For customer-impacting bugs, notify Customer Support Representative and coordinate communication
- For documentation gaps blocking release, escalate to Technical Writer and Project Manager
- For process impediments, Scrum Master escalates to Project Manager and leadership
