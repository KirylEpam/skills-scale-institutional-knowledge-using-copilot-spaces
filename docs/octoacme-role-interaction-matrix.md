# OctoAcme Role Interaction Matrix

## Purpose
Provide a quick reference for which roles interact, when, and on what topics. Helps new team members understand the web of relationships and dependencies.

## Phase-Based Interaction Map

### Initiation Phase
| Role | Involvement | Key Activities |
|------|------------|-----------------|
| **Product Manager** | Lead | Define problem, success metrics, vision |
| **Project Manager** | Lead | Create timeline, identify stakeholders |
| **Business Analyst** | Support | Clarify business case and requirements |
| **Stakeholders** | Lead | Provide input, approve charter |
| **Developers** | Advisory | Early technical feasibility input |
| **Security Champion** | Support | Security implications and requirements |

**Key Touchpoint**: Project One-pager approval meeting

---

### Planning Phase
| Role | Involvement | Key Activities |
|------|------------|-----------------|
| **Product Manager** | Lead | Backlog prioritization, acceptance criteria |
| **Project Manager** | Lead | Timeline, dependencies, resource plan |
| **Business Analyst** | Lead | Requirements elicitation, specification |
| **Developers** | Lead | Estimation, design, technical approach |
| **UX Designer** | Lead | Design specs, user flows, wireframes |
| **Scrum Master** | Support | Backlog refinement, sprint planning setup |
| **QA Lead** | Support | Test planning, acceptance criteria review |
| **Customer Support** | Advisory | Customer feedback and use cases |
| **Security Champion** | Support | Security requirements and threat model |

**Key Touchpoint**: Kickoff meeting, Sprint 0 planning

---

### Execution Phase
| Role | Involvement | Key Activities |
|------|------------|-----------------|
| **Developers** | Lead | Code, testing, PR review |
| **Scrum Master** | Lead | Ceremonies, impediment removal, coaching |
| **UX Designer** | Support | Design feedback, design-dev handoff, QA |
| **QA Lead** | Support | Testing, acceptance validation |
| **Project Manager** | Oversight | Risk tracking, blocker escalation, status |
| **Product Manager** | Advisory | Backlog questions, definition changes |
| **Business Analyst** | Support | Requirement clarification, edge cases |
| **Customer Support** | Advisory | Customer impact of changes, UAT prep |
| **Security Champion** | Support | Code review, security issue escalation |

**Key Touchpoints**: Daily standup, sprint reviews, backlog refinement

---

### Release & Deployment Phase
| Role | Involvement | Key Activities |
|------|------------|-----------------|
| **Project Manager** | Lead | Release timeline, go/no-go decision |
| **Developers** | Lead | Final testing, deployment, rollback |
| **QA Lead** | Lead | Smoke testing, validation, sign-off |
| **Security Champion** | Support | Security check before deployment |
| **Product Manager** | Lead | Release notes, stakeholder communication |
| **Customer Support** | Support | User training, FAQ prep, support readiness |
| **UX Designer** | Support | UI verification in production |

**Key Touchpoint**: Release sign-off meeting

---

### Retrospective & Continuous Improvement Phase
| Role | Involvement | Key Activities |
|------|------------|-----------------|
| **Scrum Master** | Lead | Facilitate retrospective, track actions |
| **All Team Members** | Lead | Participate in retrospective |
| **Project Manager** | Support | Track action items, follow-up |
| **Product Manager** | Support | Product/process improvements |

**Key Touchpoint**: Sprint retrospective

---

## Communication Frequency by Role Pair

| Role 1 | Role 2 | Frequency | Topics |
|--------|--------|-----------|--------|
| **PM** | **PdM** | Weekly sync (1 hr) | Scope, priority, blockers, metrics |
| **PM** | **Project Manager** | As needed | Timeline, resource conflicts, escalations |
| **Developers** | **UX Designer** | During sprint | Design specs, implementation approach |
| **Developers** | **Security Champion** | PR review, design review | Code security, architecture security |
| **Product Manager** | **Stakeholders** | Weekly/monthly | Roadmap, progress, decisions |
| **Scrum Master** | **Developers** | Daily | Impediments, process coaching |
| **Project Manager** | **All Roles** | Weekly status | Progress, risks, escalations |
| **Customer Support** | **Product Manager** | Bi-weekly | Feedback, patterns, feature ideas |

---

## Dependency & Risk Points

### High-Risk Dependency Zones
1. **Developer ↔ Security Champion**: Security review delays can block releases.
   - **Mitigation**: Involve Security early in design phase.

2. **Developers ↔ UX Designer**: Design changes mid-sprint can derail velocity.
   - **Mitigation**: Freeze design before sprint start, queue feedback for next sprint.

3. **Product Manager ↔ Stakeholders**: Changing requirements cause scope creep.
   - **Mitigation**: Change control process; prioritize in next sprint.

4. **Business Analyst ↔ Developers**: Ambiguous requirements lead to rework.
   - **Mitigation**: Acceptance criteria refinement ceremony before sprint start.

5. **Project Manager ↔ Cross-Team Dependencies**: External team delays block progress.
   - **Mitigation**: Weekly dependency sync, escalate 2+ weeks early.

---

## Anti-Patterns to Avoid

❌ **Developers blocked by unknown requirements** → Involve Business Analyst in planning
❌ **Designer surprised by dev limitations** → Design review with tech lead before sprint
❌ **Security issues discovered at deployment** → Include Security Champion in design phase
❌ **Customer feedback ignored by product** → Regular Customer Support → Product Manager updates
❌ **Scope creep due to unclear goals** → Validate problem statement with Stakeholders in initiation
❌ **Retrospective actions never tracked** → Project Manager owns action item follow-up
❌ **Scrum Master without developer feedback** → Daily standup is sacred; don't skip
