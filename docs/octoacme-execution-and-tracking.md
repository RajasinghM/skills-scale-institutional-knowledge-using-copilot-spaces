# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
  - **QA Column**: Represents items undergoing quality validation. The QA Lead (if assigned) owns and coordinates this stage, ensuring acceptance criteria are validated through appropriate testing (manual, automated, or both). If no QA Lead is assigned, Developers and Product Manager share responsibility for validating acceptance criteria before moving items to Done.
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

## Documentation Updates During Execution

Documentation should be kept current as features are developed and changes are made. Clear ownership ensures documentation doesn't fall behind.

**Ownership models** (choose based on your [Roles & Handoffs Checklist](octoacme-roles-and-handoffs-checklist.md)):
- **Technical Writer assigned**: Technical Writer is the primary owner, working with Developers to document features, APIs, and configuration changes. Developers provide technical details and review for accuracy.
- **Shared responsibility**: Developers own inline code documentation and README updates. Product Manager or Project Manager owns user-facing guides and process docs.

**Best practices:**
- Include documentation tasks in Definition of Done
- Update docs in the same PR as code changes when feasible
- Tag documentation updates in PR descriptions for visibility
- Review documentation during sprint demos to catch gaps
- Refer to [OctoAcme Roles and Personas](octoacme-roles-and-personas.md) for detailed Technical Writer responsibilities

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
