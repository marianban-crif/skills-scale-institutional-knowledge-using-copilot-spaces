# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo (Developers + Project Manager)
- [ ] CI configured for tests, lint, and security scanning (Developers + Security Lead)
- [ ] Regular demos scheduled (Scrum Master)
- [ ] UX design reviews scheduled for implementation validation (UX Designer)
- [ ] Documentation updates tracked as part of Definition of Done (Technical Writer)
- [ ] Support team knowledge base articles drafted for new features (Customer Support Representative)
- [ ] Security reviews scheduled for security-sensitive features (Security Lead)
- [ ] Risk register updated weekly (Project Manager + Scrum Master)
- [ ] Sprint retrospectives conducted with action items (Scrum Master)

## Role-Specific Execution Responsibilities
- **Scrum Master**: Facilitates ceremonies, removes blockers, tracks team velocity
- **Developers**: Implements features, writes tests, reviews PRs, documents code
- **UX Designer**: Reviews implementations, conducts usability testing, iterates designs
- **Security Lead**: Reviews code for vulnerabilities, monitors security scans
- **Technical Writer**: Updates documentation concurrently with feature development
- **Customer Support**: Prepares support materials, tests customer-facing changes
- **Product Manager**: Validates acceptance criteria, adjusts priorities based on feedback
- **Project Manager**: Tracks milestones, manages dependencies, reports status
