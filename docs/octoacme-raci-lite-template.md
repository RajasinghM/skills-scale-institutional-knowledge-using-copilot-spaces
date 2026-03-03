# OctoAcme — RACI-Lite / Ownership Matrix Template

## Purpose
This template helps teams clarify who is Responsible, Accountable, Consulted, and Informed for key activities across the project lifecycle. Use this to reduce ambiguity and ensure smooth handoffs.

## When to Use
- During project planning to establish clear ownership
- When confusion arises about who owns a particular activity
- When onboarding new team members
- During retrospectives to identify ownership gaps

---

## RACI Definitions

- **R - Responsible**: Does the work to complete the task
- **A - Accountable**: Ultimately answerable for completion and quality (only one A per activity)
- **C - Consulted**: Provides input or expertise (two-way communication)
- **I - Informed**: Kept up-to-date on progress (one-way communication)

**Guidelines:**
- Each activity should have exactly **one A** (Accountable person)
- An activity can have multiple **R** (Responsible) contributors
- Limit **C** (Consulted) to those who truly need to provide input
- Use **I** (Informed) for stakeholders who need awareness but not involvement

---

## RACI Matrix Template

Copy and customize this table for your project. Replace role columns with actual team member names or specific role titles as needed.

| Activity | Developer | Product Manager | Project Manager | QA Lead | Business Analyst | Technical Writer | Scrum Master | UX Designer |
|----------|-----------|-----------------|-----------------|---------|------------------|------------------|--------------|-------------|
| **Initiation Phase** | | | | | | | | |
| Define problem statement | C | R | C | - | R | - | - | C |
| Approve project charter | I | A | R | - | C | - | - | - |
| Select team & roles | C | C | A | - | - | - | C | - |
| Create project one-pager | I | R | A | - | C | - | - | I |
| **Planning Phase** | | | | | | | | |
| Draft backlog & user stories | C | R | C | I | R | - | C | C |
| Estimate scope | R | C | C | I | C | - | C | - |
| Define Definition of Done | R | C | A | R | C | - | C | - |
| Create test plan / QA approach | C | I | C | A | C | - | - | - |
| Design wireframes/prototypes | C | C | I | - | C | - | - | A |
| Plan documentation strategy | I | C | C | - | - | A | - | - |
| **Execution Phase** | | | | | | | | |
| Implement features | A | I | I | I | - | - | - | C |
| Write unit/integration tests | A | - | - | C | - | - | - | - |
| Code review | R | - | I | - | - | - | - | - |
| Conduct QA testing | C | I | I | A | C | - | - | - |
| Triage and fix bugs | A | C | C | R | - | - | - | - |
| Update technical documentation | R | I | I | - | - | A | - | - |
| Facilitate daily standup | R | R | R | R | R | R | A | R |
| Track progress & risks | C | C | A | C | - | - | C | - |
| **Release Phase** | | | | | | | | |
| Draft release notes | C | R | C | - | - | A | - | - |
| Approve release readiness | I | C | C | A | - | - | - | - |
| Deploy to production | A | I | C | I | - | - | - | - |
| Smoke test post-deploy | R | I | C | A | - | - | - | - |
| Announce release | I | R | C | - | - | R | - | - |
| **Ongoing** | | | | | | | | |
| Maintain product backlog | C | A | C | - | R | - | C | C |
| Facilitate retrospectives | R | R | R | R | R | R | A | R |
| Escalate blockers | R | C | A | R | - | - | C | - |
| Monitor production metrics | R | C | I | C | - | - | - | - |

---

## Customization Instructions

1. **Copy this table** into your project repository or wiki
2. **Replace generic roles** with actual names or specific titles (e.g., "Alex Chen (Dev Lead)")
3. **Add project-specific activities** that are unique to your context
4. **Remove or combine roles** that don't apply to your project
5. **Review and validate** with the team during kickoff or planning
6. **Update as needed** when roles change or new activities emerge

---

## Tips for Effective Use

- **Start simple** — Focus on high-impact activities first; don't try to map every small task
- **Review regularly** — Update the matrix when team members change or scope evolves
- **Use in onboarding** — Share this matrix with new team members to clarify expectations
- **Reference in meetings** — When questions arise about ownership, refer to this matrix
- **Combine with handoffs checklist** — Use alongside [Roles & Handoffs Checklist](octoacme-roles-and-handoffs-checklist.md) for comprehensive clarity

---

**Related Documents:**
- [OctoAcme Roles and Personas](octoacme-roles-and-personas.md)
- [OctoAcme Roles & Handoffs Checklist](octoacme-roles-and-handoffs-checklist.md)
- [OctoAcme Project Planning](octoacme-project-planning.md)
