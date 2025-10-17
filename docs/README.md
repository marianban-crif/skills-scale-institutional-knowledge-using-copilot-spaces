# OctoAcme Project Management Quick Start

Welcome to OctoAcme! This README provides a quick overview of how we manage projects. For detailed guidance, refer to the individual process documents linked throughout.

## Our Approach

OctoAcme uses a structured yet flexible project management framework designed to deliver customer value iteratively while maintaining clear ownership and transparency.

### Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

Every project follows these five key stages:

### 1. **Initiation** 
Define the problem, align stakeholders, and validate the business need.

- Create Project One-pager (problem, goal, success metrics)
- Identify stakeholders and champions
- Define success criteria and initial timeline
- Build initial risk list
- Decide go/no-go for planning

📖 [Detailed Initiation Guide](octoacme-project-initiation.md)

### 2. **Planning**
Turn the approved initiative into an actionable plan and backlog.

- Hold kickoff meeting with stakeholders and delivery team
- Create prioritized backlog with acceptance criteria
- Estimate scope (T-shirt sizing or story points)
- Define Definition of Done (DoD)
- Identify dependencies and integration points
- Create release plan and milestone map

📖 [Detailed Planning Guide](octoacme-project-planning.md)

### 3. **Execution & Tracking**
Manage day-to-day execution and track progress toward milestones.

- Daily standups (15 min) — progress, blockers, dependencies
- Weekly delivery sync — updates and flagged risks
- Demo/review at end of each sprint or milestone
- Use project board (Backlog → Ready → In Progress → In Review → QA → Done)
- Small PRs with automated tests and code reviews

📖 [Detailed Execution Guide](octoacme-execution-and-tracking.md)

### 4. **Release & Deployment**
Standardized approach to releasing features to production.

- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback/mitigation plan documented
- Smoke tests prepared and executed
- Post-deploy verifications

📖 [Detailed Release Guide](octoacme-release-and-deployment.md)

### 5. **Retrospective**
Capture learnings and convert them into actionable improvements.

- Review what went well and what could be improved
- Identify 2–3 top action items with owners and due dates
- Follow up on previous action items
- Measure impact of improvements

📖 [Detailed Retrospective Guide](octoacme-retrospective-and-continuous-improvement.md)

## Core Roles and Responsibilities

### Project Manager (PM)
Coordinates delivery, schedules, risks, and communications.

**Key responsibilities:**
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Product Manager (PdM)
Defines outcomes, prioritizes backlog, and measures success.

**Key responsibilities:**
- Define problem statements and success metrics
- Prioritize roadmap and backlog
- Collaborate on trade-offs
- Validate solutions through user research and metrics

### Developers
Implement features, collaborate on design and testability.

**Key responsibilities:**
- Implement features to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Help identify technical risks and propose mitigations

### QA/Testing
Validate quality and acceptance criteria.

**Key responsibilities:**
- Manual QA for feature acceptance when needed
- End-to-end smoke tests for critical flows
- Integration testing where applicable

### Stakeholders
Provide inputs and approvals.

📖 [Detailed Roles and Personas](octoacme-roles-and-personas.md)

## Key Artifacts and Templates

### Project Charter / One-pager
- Project name
- Problem statement
- Objective/Goal (SMART)
- Success metrics
- Primary stakeholders
- Suggested timeline/milestones
- Quick risks & dependencies
- Proposed team/roles

### Backlog Item Template
- Title
- Description
- Acceptance criteria
- Priority
- Estimate
- Owner
- Related docs/links

### Risk Register
Track risks with:
- ID, Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

### Release Notes Template
- Release name/number
- Date
- Summary
- Notable changes
- Migration steps (if any)
- Known issues

### Weekly Status Template
- Progress this week
- Next steps
- Risks & blockers
- Ask/decisions needed

📖 [More on Risk Management & Communication](octoacme-risks-and-communication.md)

## Communication Cadence

- **Daily standups**: Team-level, 15 minutes (or as agreed)
- **Weekly PM + PdM sync**: Alignment on priorities and blockers
- **Twice-weekly delivery team standups**: Progress updates
- **Monthly stakeholder updates**: High-level status and milestones
- **Sprint/milestone demos**: Show progress and gather feedback
- **Ad-hoc escalations**: As needed for critical issues

## Escalation Paths

- **Level 1**: Team-level triage in daily standup
- **Level 2**: PM escalates to Product Lead and dependent teams
- **Level 3**: Sponsor-level escalation for business-impacting issues
- **Security incidents**: Follow security incident runbook and notify Security on-call

## How to Use These Docs

1. **Keep the Project Charter updated** in the project repository
2. **Add process-specific docs** into `.copilot/` if you want Copilot Spaces to use them as context
3. **Use project boards** (e.g., GitHub Projects) to track work
4. **Reference detailed guides** for phase-specific best practices

## Getting Started

New to a project? Here's your checklist:

- [ ] Read the Project Charter/One-pager
- [ ] Review the current sprint/iteration backlog
- [ ] Attend the weekly delivery sync
- [ ] Join the team standups
- [ ] Familiarize yourself with the project board
- [ ] Review the Risk Register for known issues
- [ ] Read the Definition of Done (DoD) for the project

## Additional Resources

- [Project Management Overview](octoacme-project-management-overview.md) — High-level summary
- [Project Initiation](octoacme-project-initiation.md) — Starting a new project
- [Project Planning](octoacme-project-planning.md) — Creating actionable plans
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day management
- [Release & Deployment](octoacme-release-and-deployment.md) — Going to production
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Learning and improving
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Managing risks and stakeholders
- [Roles and Personas](octoacme-roles-and-personas.md) — Team roles and responsibilities

---

Questions? Reach out to your Project Manager or Product Lead!
