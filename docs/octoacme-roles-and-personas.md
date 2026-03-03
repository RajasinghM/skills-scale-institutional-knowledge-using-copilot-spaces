# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

## How to Use This Document

Use this document to:
- **Select appropriate roles** for each project based on scope, complexity, and team structure
- **Clarify ownership and accountability** across different activities and deliverables
- **Facilitate handoffs** by understanding how roles interact with one another
- **Set expectations** for communication patterns and responsibilities

**Important notes:**
- Not all projects require all roles — tailor staffing to your project needs
- Some roles may be combined (e.g., PM and Scrum Master on smaller projects)
- Interactions described below help teams understand dependencies and handoff points
- Review this document during project initiation to assign clear ownership

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA Lead

### Role Summary
The QA Lead oversees the quality assurance strategy and coordinates testing activities. They ensure that testing is comprehensive, acceptance criteria are validated, and quality metrics are tracked throughout the project lifecycle.

### Responsibilities
- Define and maintain the overall QA approach and test plan
- Coordinate manual and automated testing activities
- Track and report on quality metrics and acceptance criteria validation
- Escalate critical bugs and quality risks to Project Manager and Product Manager
- Review and approve test coverage and test cases
- Facilitate test environment management and data preparation

### Goals
- Ensure high product quality and minimal production defects
- Reduce testing cycle time through automation and efficient processes
- Maintain clear visibility into quality status and risks

### Typical Communication
- Daily QA status updates in standups
- Weekly quality metrics reports to PM and Product Manager
- Bug triage meetings with Developers
- Test plan reviews with the delivery team

### Interactions with Other Roles
- **Developers**: Collaborates on test coverage, test automation frameworks, and bug investigation/resolution
- **Product Managers**: Validates acceptance criteria, clarifies requirements, and reports on feature readiness
- **Project Managers**: Reports quality status, testing progress, and risks; escalates blockers
- **Business Analyst**: Reviews requirements for testability and helps define test scenarios
- **Technical Writer**: Provides feedback on documentation accuracy through testing validation

---

## Business Analyst

### Role Summary
Business Analysts bridge business needs and technical solutions. They gather stakeholder requirements, translate them into actionable specifications, and ensure traceability throughout the project lifecycle.

### Responsibilities
- Gather and document business requirements from stakeholders
- Draft user stories, specifications, and process flows
- Facilitate requirements workshops and stakeholder interviews
- Ensure requirements traceability from conception to delivery
- Support acceptance testing by validating solutions against requirements
- Analyze gaps between current and desired state

### Goals
- Ensure clear, complete, and testable requirements
- Maximize alignment between business needs and technical solutions
- Reduce rework caused by unclear or missing requirements

### Typical Communication
- Requirements documents and user story specifications
- Stakeholder interview summaries and workshop facilitation
- Traceability matrices and requirements status reports
- Regular syncs with Product Manager and Project Manager

### Interactions with Other Roles
- **Product Managers**: Collaborates on product vision, prioritization, and user needs analysis
- **Project Managers**: Provides requirements clarity, tracks requirements status, and supports planning
- **Developers**: Clarifies acceptance criteria, answers implementation questions, and validates technical approaches
- **QA Lead**: Defines test scenarios based on requirements and validates test coverage
- **UX Designer**: Aligns on user flows and validates designs against business requirements

---

## Technical Writer

### Role Summary
Technical Writers create and maintain project documentation, release notes, and knowledge base content. They ensure that technical information is accurate, accessible, and up-to-date for various audiences.

### Responsibilities
- Write and maintain technical documentation (user guides, API docs, architecture docs)
- Create release notes and changelog entries for each release
- Edit and organize knowledge base content
- Document critical configuration changes and deployment procedures
- Collaborate with team to ensure documentation accuracy
- Maintain documentation standards and templates

### Goals
- Provide clear, accurate documentation that reduces support burden
- Keep documentation synchronized with product changes
- Make knowledge accessible and discoverable for all stakeholders

### Typical Communication
- Documentation review requests and feedback sessions
- Release notes drafts for stakeholder review
- Documentation status updates in sprint reviews
- Style guide and template recommendations

### Interactions with Other Roles
- **Developers**: Gathers technical details, reviews code comments, and validates technical accuracy
- **Product Managers**: Collaborates on feature documentation, user guides, and release announcements
- **Project Managers**: Tracks documentation milestones and coordinates documentation releases
- **QA Lead**: Validates documentation accuracy through testing scenarios
- **UX Designer**: Aligns on user-facing documentation and incorporates design elements

---

## Scrum Master

### Role Summary
The Scrum Master facilitates Agile ceremonies, coaches the team on Agile practices, and removes impediments to team productivity. They focus on process improvement and team effectiveness.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Coach team members on Agile principles and practices
- Remove blockers and impediments to team progress
- Track and follow up on action items from retrospectives
- Protect the team from external interruptions during sprints
- Foster a culture of continuous improvement

### Goals
- Maximize team velocity and predictability
- Reduce process friction and impediments
- Build a self-organizing, high-performing team

### Typical Communication
- Agile ceremony facilitation and meeting notes
- Retrospective action item tracking
- Blocker escalation and resolution coordination
- Team health and velocity metrics

### Interactions with Other Roles
- **Developers**: Removes impediments, facilitates collaboration, and coaches on Agile practices
- **Product Managers**: Helps refine backlog, facilitates sprint planning, and provides team capacity insights
- **Project Managers**: Coordinates on cross-team dependencies, escalates organizational blockers, and shares team metrics
- **QA Lead**: Facilitates QA participation in ceremonies and helps remove testing blockers
- **Business Analyst**: Ensures requirements are ready for sprint planning and clarifies acceptance criteria

---

## UX Designer

### Role Summary
UX Designers ensure that the user experience perspective is central to product development. They create designs, conduct usability testing, and advocate for end-user needs throughout the project lifecycle.

### Responsibilities
- Develop wireframes, mockups, and interactive prototypes
- Conduct user research and usability testing
- Create and maintain design systems and style guides
- Validate design decisions with users and stakeholders
- Advocate for accessibility and inclusive design
- Collaborate on design reviews and iterations

### Goals
- Create intuitive, accessible, and delightful user experiences
- Validate designs with real user feedback early and often
- Reduce development rework through early design validation

### Typical Communication
- Design review presentations and prototype demonstrations
- Usability testing reports and user feedback summaries
- Design specifications and component documentation
- Collaboration sessions with Product and Engineering

### Interactions with Other Roles
- **Product Managers**: Collaborates on product vision, user needs, and feature prioritization
- **Developers**: Works together on design feasibility, design system implementation, and design-to-code handoff
- **Business Analyst**: Validates user flows and requirements alignment with design solutions
- **QA Lead**: Coordinates on usability acceptance criteria and participates in UI/UX testing
- **Technical Writer**: Collaborates on user-facing documentation and design asset integration

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

