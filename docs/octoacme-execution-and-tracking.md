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
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly

## Cross-Functional Roles & Responsibilities

During execution, different roles contribute at specific touchpoints:

| Role | Daily Standup | Planning | Reviews | Risk Escalation |
|------|---------------|----------|---------|-----------------|
| **Developer** | Reports progress, flags blockers | Estimates work, discusses approach | Demo features, review feedback | Technical risks |
| **Scrum Master** | Facilitates, removes impediments | Helps shape backlog | Observes, captures improvements | Process blockers |
| **UX Designer** | May attend async updates | Refines acceptance criteria | Demos designs, gathers feedback | Usability gaps |
| **QA/Tester** | Reports test results | Reviews acceptance criteria | Validates features | Quality risks |
| **Business Analyst** | Ad-hoc as needed | Clarifies requirements, edge cases | Validates against requirements | Scope/requirement gaps |
| **Customer Support** | Escalates critical issues | Shares customer feedback | Participates in demos | Customer-impacting issues |
| **Security Champion** | Escalates security issues | Reviews security requirements | Reviews code/design for security | Security risks |
| **Project Manager** | Facilitates, tracks risks | Owns timeline, dependencies | Tracks progress vs. plan | Escalates blockers |
| **Product Manager** | Prioritization questions | Owns backlog, acceptance criteria | Participates, prioritizes feedback | Business/strategic issues |

**Guideline**: Invite roles based on their relevance to the sprint's work. Minimize ceremony bloat by having optional attendance for supporting roles.
