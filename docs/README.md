# OctoAcme Project Management Docs — Overview & Index

Welcome to the OctoAcme project management documentation! This README provides a summary of the project management processes we use at OctoAcme and offers quick links to all major process docs.

## Project Management Processes Summary

### Overview & Core Principles

OctoAcme follows a structured, iterative project management approach that emphasizes customer value, clear ownership, and data-informed decision-making. The framework spans five lifecycle phases: **Initiation** (validating business need and aligning stakeholders), **Planning** (breaking work into shippable increments), **Execution** (build, test, review), **Release** (deploy and verify), and **Close & Retrospective** (capture learnings). At the heart of this process are three core roles—**Project Manager** (coordinates delivery and risk), **Product Manager** (defines outcomes and priorities), and **Development Team** (implements and validates)—each with clearly defined responsibilities that ensure transparent ownership and accountability throughout the project lifecycle.

### Workflows & Execution Practices

OctoAcme operates with a disciplined rhythm: daily standups (15 minutes, focused on progress and blockers), weekly delivery syncs to track progress and flag risks, and demos at sprint/milestone end. Work is managed on a **project board** using columns (Backlog → Ready → In Progress → In Review → QA → Done) and follows a **Pull Request workflow** emphasizing small PRs (≤400 lines), clear acceptance criteria, automated CI testing, and at least one approval before merge. **Risk and dependency management** are central to execution—teams maintain a Risk Register (tracking ID, description, impact, likelihood, owner, and mitigation), identify cross-team dependencies during planning, and escalate blockers through three levels: team triage, PM escalation to Product Lead, and sponsor-level escalation for business-impacting issues. This structured approach ensures visibility, reduces surprises, and enables proactive problem-solving.

### Quality Assurance & Communication

Quality is embedded throughout the delivery process via **unit tests for new logic**, **integration tests where applicable**, **end-to-end smoke tests** before release, **security scanning in CI**, and **manual QA for feature acceptance when needed**. OctoAcme measures success through **velocity, burndown, and key dashboards** (errors, latency, usage) aligned to the Project One-pager success metrics. Communication is consistent and role-tailored: weekly syncs between PM and Product Manager, twice-weekly standups for delivery teams, monthly stakeholder updates, and ad-hoc escalations as needed. Each project maintains a **single source of truth** (project README or charter) for status, and teams share weekly status updates summarizing progress, next steps, risks, and decisions needed. This emphasis on transparency, measurement, and psychological safety creates a culture where teams learn from retrospectives, act on feedback, and continuously improve their delivery practices.

## Key Principles

- **Customer-first**: We focus on solutions that deliver value and excellent usability to our customers.
- **Iterative delivery**: Features and improvements are shipped in small, testable increments.
- **Clear ownership**: Each project has a named Project Manager and Product Lead, with roles and responsibilities defined for all stakeholders.
- **Data-informed decisions**: We measure impact, use evidence in planning, and iterate based on feedback and metrics.
- **Transparency & Communication**: Processes are clearly documented, with regular updates and standing cadences for delivery, review, and improvement.
- **Continuous improvement**: Retrospectives drive process and practice evolution for greater effectiveness.

## Process Document Links

### Core Processes
- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) — Introduction to OctoAcme's approach, roles, and key artifacts
- [OctoAcme Project Initiation Guide](./octoacme-project-initiation.md) — Initial steps to validate and authorize work, align stakeholders
- [OctoAcme Project Planning](./octoacme-project-planning.md) — Turn approved initiatives into actionable plans and backlog
- [OctoAcme Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day execution, team rhythm, and progress tracking
- [OctoAcme Risk Management & Communication](./octoacme-risks-and-communication.md) — Identifying, managing, and communicating risks and dependencies
- [OctoAcme Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardized approach to releasing features to production
- [OctoAcme Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings and driving improvements
- [OctoAcme Roles and Personas](./octoacme-roles-and-personas.md) — Definitions of typical roles and responsibilities

## Quick Start

**For new team members:**
1. Start with [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) to understand our core approach
2. Review [OctoAcme Roles and Personas](./octoacme-roles-and-personas.md) to understand team responsibilities
3. Dive into specific processes based on your current project phase

**For project kickoff:**
1. Follow [OctoAcme Project Initiation Guide](./octoacme-project-initiation.md)
2. Move into [OctoAcme Project Planning](./octoacme-project-planning.md)
3. Reference [OctoAcme Risk Management & Communication](./octoacme-risks-and-communication.md) for identifying dependencies

**For ongoing execution:**
- Refer to [OctoAcme Execution & Tracking](./octoacme-execution-and-tracking.md) for daily standups and team rhythm
- Use [OctoAcme Risk Management & Communication](./octoacme-risks-and-communication.md) for escalations and status updates
- Reference [OctoAcme Release & Deployment Guide](./octoacme-release-and-deployment.md) when preparing for release

**For retrospectives and improvement:**
- Follow [OctoAcme Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) for capturing learnings
