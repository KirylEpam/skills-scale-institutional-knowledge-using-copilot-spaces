# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

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
- For security incidents, follow the security incident runbook and notify Security on-call

## Role-Specific Escalation Paths

Different roles have different escalation chains based on issue type:

### Technical/Delivery Blockers
Escalation Path: Developer → Scrum Master → Project Manager → CTO/Tech Lead

**Example Scenarios:**
- Code dependency blocked by another team
- Infrastructure/environment unavailable
- Third-party API or service failure
- Build or CI pipeline down

**Owner**: Project Manager (coordinate resolution)

### Product/Requirement Issues
Escalation Path: Business Analyst → Product Manager → Product Director → Chief Product Officer

**Example Scenarios:**
- Conflicting requirements from stakeholders
- Scope creep or priority dispute
- Market/customer feedback contradicts roadmap
- Strategic alignment question

**Owner**: Product Manager (make prioritization decision)

### Security Issues
Escalation Path: Security Champion → Project Manager + Security Lead → CISO (if critical)

**Example Scenarios:**
- Vulnerability discovered in code or dependency
- Suspicious infrastructure activity
- Data breach or unauthorized access
- Non-compliance with security policy

**Owner**: Security Champion + Project Manager (coordinate remediation)

### UX/Usability Issues
Escalation Path: UX Designer → Product Manager → Product Director

**Example Scenarios:**
- Design feasibility concern discovered during dev
- Usability issue in user testing
- Accessibility gap
- Design system inconsistency

**Owner**: UX Designer + Product Manager (make design decision)

### Customer-Impacting Issues
Escalation Path: Customer Support → Project Manager → Product Manager → VP Customer Success

**Example Scenarios:**
- Critical bug affecting customer operations
- Performance degradation impacting users
- Data loss or integrity issue
- Feature not meeting customer expectations

**Owner**: Project Manager + Product Manager (communicate & resolve)

---

**General Rule**: If unsure about escalation path, the Project Manager is the default coordinator. They triage severity and involve appropriate leadership.
