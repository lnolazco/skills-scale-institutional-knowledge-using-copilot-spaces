# OctoAcme Project Management Documentation

Welcome to OctoAcme's project management documentation. This README serves as your single entry point to understand how we run projects, from initial ideas through successful delivery and continuous improvement.

## Purpose

OctoAcme's project management processes provide a concise, shareable framework that enables new teammates to quickly understand our approach, roles, and key artifacts. These processes apply to all cross-functional projects that deliver product features, services, or integrations.

## Guiding Principles

Our project management approach is built on five core principles:

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments to enable faster feedback
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning at all levels

## Project Lifecycle

OctoAcme projects follow a structured five-phase lifecycle:

### 1. Initiation
Validate and authorize work, align stakeholders, and create a lightweight plan. This phase confirms business need, identifies stakeholders, defines success criteria, and produces a Project One-pager.

### 2. Planning
Turn approved initiatives into actionable plans and backlogs. Activities include kickoff meetings, backlog creation with acceptance criteria, scope estimation, defining Definition of Done, identifying dependencies, and creating release plans.

### 3. Execution
Manage day-to-day progress toward milestones through daily standups, weekly delivery syncs, and regular demos. Teams use project boards, follow PR workflows, maintain quality through testing, and escalate blockers as needed.

### 4. Release & Deployment
Standardize how features reach production to reduce risk and improve observability. This includes pre-release requirements, deployment checklists, post-deploy verifications, rollback plans, and stakeholder announcements.

### 5. Retrospective
Capture learnings and convert them into actionable improvements after each sprint, release, milestone, or incident. Focus on what went well, what could improve, and prioritize 2-3 action items.

## Key Roles and Personas

### Project Manager (PM)
Coordinates delivery activities, manages schedules, risks, and communications. Creates project plans, manages dependencies, facilitates meetings, and maintains documentation and status reporting.

### Product Manager (PdM)
Defines what should be built to deliver customer and business value. Owns the product vision, prioritizes the backlog, collaborates on trade-offs, and validates solutions through research and metrics.

### Developers
Design, build, test, and deliver software components. Implement features, write tests and documentation, participate in reviews, assist in planning, and identify technical risks.

### QA/Testing
Validate quality and acceptance criteria through unit tests, integration tests, end-to-end smoke tests, and manual testing when needed.

### Stakeholders
Provide inputs, approvals, and feedback. Participate in reviews and receive regular project updates.

### Supporting Roles (as needed)

#### Technical Writer
Maintains clear, accessible project documentation, coordinates release notes and user-facing materials. Reviews PRs for documentation completeness and works with developers, PMs, and support teams.

#### Scrum Master
Facilitates agile ceremonies (standups, sprint planning, reviews, retrospectives), coaches the team on agile principles, and helps resolve blockers.

#### UX Designer
Designs user experiences, creates wireframes and prototypes, and advocates for customer needs throughout the product lifecycle. Collaborates with Product Managers and Developers.

#### Business Analyst
Elicits requirements, translates business goals into technical solutions, and documents acceptance criteria. Bridges stakeholders, Product Managers, and Developers.

#### Support Lead / Customer Advocate
Represents user feedback, escalates critical support issues, and contributes insights to product development. Provides customer perspective to PMs and Developers.

## Key Workflows and Communication

### Communication Cadence
- **Daily standups** (15 min): Focus on progress, blockers, and dependencies (facilitated by Scrum Master when available)
- **Weekly PM + PdM sync**: Coordinate delivery and product alignment
- **Twice-weekly delivery team standups**: As agreed by the team
- **Monthly stakeholder updates**: Keep all parties informed
- **Sprint demos/reviews**: At the end of each sprint or milestone
- **Ad-hoc escalations**: As needed for critical issues
- **Documentation reviews**: Regular syncs with Technical Writer
- **Customer feedback sessions**: With Support Lead to inform priorities

### Status Reporting
Weekly status template includes:
- Progress this week
- Next steps
- Risks & blockers
- Asks/decisions needed

### Escalation Path
- **Level 1**: Team-level triage in daily standup
- **Level 2**: PM escalates to Product Lead and dependent teams
- **Level 3**: Sponsor-level escalation for business-impacting issues
- **Security incidents**: Follow security incident runbook and notify Security on-call

### Risk Management
Maintain a Risk Register with:
- ID, Description, Impact, Likelihood, Owner, Mitigation plan, Status
- Review risks at weekly syncs and update throughout project lifecycle

## Quality Assurance Practices

### Testing Standards
- **Unit tests** for new logic
- **Integration tests** where applicable
- **End-to-end smoke tests** for critical flows before release
- **Security scanning** in CI
- **Manual QA** for feature acceptance when needed

### Code Review Process
- Small PRs (≤400 lines when possible)
- Include issue link and acceptance criteria in PR description
- Run automated tests and linting in CI before requesting review
- Require at least one approval before merging (or team-defined policy)
- Technical Writer reviews for documentation completeness
- UX Designer reviews UI/UX changes for design consistency

### Release Criteria
All releases must meet:
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted (coordinated by Technical Writer)
- Rollback/mitigation plan documented
- Smoke tests prepared
- Documentation updated and published
- Support team briefed on changes

### Continuous Improvement
- Run retrospectives after each sprint, release, milestone, or incident
- Track 2-3 prioritized action items with owners and due dates
- Review outstanding actions in weekly PM syncs
- Measure impact of improvements and celebrate successes
- Scrum Master facilitates retrospectives and tracks action items

## Key Artifacts

Throughout the project lifecycle, teams maintain:

- **Project Charter/One-pager**: Problem statement, goals, success metrics, stakeholders
- **Roadmap and Release Plan**: Timeline, milestones, and delivery schedule
- **Sprint/Iteration Backlog**: Prioritized work items with acceptance criteria
- **Acceptance Criteria & Definition of Done**: Clear completion standards
- **Risk Register**: Identified risks with mitigation plans
- **Retrospective Notes**: Learnings and action items for continuous improvement

## Complete Process Documentation

For detailed guidance on each phase and topic, refer to these comprehensive process documents:

### Core Process Guides
- **[Project Management Overview](octoacme-project-management-overview.md)** - High-level introduction to OctoAcme's project management approach
- **[Project Initiation](octoacme-project-initiation.md)** - How to validate and authorize new work
- **[Project Planning](octoacme-project-planning.md)** - Turn initiatives into actionable plans and backlogs
- **[Execution and Tracking](octoacme-execution-and-tracking.md)** - Day-to-day execution and progress tracking
- **[Release and Deployment](octoacme-release-and-deployment.md)** - Standardized release processes and deployment checklists

### Supporting Guides
- **[Risks and Communication](octoacme-risks-and-communication.md)** - Risk management and stakeholder communication strategies
- **[Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** - Capture learnings and drive improvements
- **[Roles and Personas](octoacme-roles-and-personas.md)** - Detailed role definitions and responsibilities

## Getting Started

### For New Team Members
1. Read this README to understand the overall approach
2. Review the [Project Management Overview](octoacme-project-management-overview.md) for core concepts
3. Familiarize yourself with your [role and responsibilities](octoacme-roles-and-personas.md)
4. Explore phase-specific guides as you engage in projects

### For Project Managers
1. Use the [Project Initiation](octoacme-project-initiation.md) guide to kick off new projects
2. Follow the [Project Planning](octoacme-project-planning.md) process to create actionable plans
3. Reference [Execution and Tracking](octoacme-execution-and-tracking.md) for day-to-day management
4. Apply [Risks and Communication](octoacme-risks-and-communication.md) strategies throughout

### For Product Managers
1. Define problem statements and success metrics during [Initiation](octoacme-project-initiation.md)
2. Collaborate on backlog prioritization in [Planning](octoacme-project-planning.md)
3. Validate acceptance criteria during [Execution](octoacme-execution-and-tracking.md)
4. Measure outcomes and drive improvements through [Retrospectives](octoacme-retrospective-and-continuous-improvement.md)

### For Development Teams
1. Understand quality standards in [Execution and Tracking](octoacme-execution-and-tracking.md)
2. Follow PR workflows and testing requirements
3. Participate in planning, demos, and retrospectives
4. Review [Release and Deployment](octoacme-release-and-deployment.md) procedures

### For Technical Writers
1. Review [Roles and Personas](octoacme-roles-and-personas.md) to understand documentation responsibilities
2. Coordinate release notes during [Release and Deployment](octoacme-release-and-deployment.md)
3. Maintain documentation standards throughout [Execution](octoacme-execution-and-tracking.md)
4. Participate in PR reviews for documentation completeness

### For Scrum Masters
1. Facilitate agile ceremonies as outlined in [Execution and Tracking](octoacme-execution-and-tracking.md)
2. Lead [Retrospectives](octoacme-retrospective-and-continuous-improvement.md) for continuous improvement
3. Support [Planning](octoacme-project-planning.md) activities and sprint ceremonies
4. Help remove blockers and coach team on agile practices

### For UX Designers
1. Contribute design specifications during [Planning](octoacme-project-planning.md)
2. Review UI/UX changes in [Execution](octoacme-execution-and-tracking.md) PR workflow
3. Validate user experience in demos and reviews
4. Collaborate with Product Managers on user needs

### For Business Analysts
1. Document requirements during [Project Initiation](octoacme-project-initiation.md)
2. Clarify acceptance criteria in [Planning](octoacme-project-planning.md)
3. Bridge stakeholders and technical teams throughout [Execution](octoacme-execution-and-tracking.md)
4. Validate solutions against business needs

### For Support Leads
1. Provide customer insights during [Initiation](octoacme-project-initiation.md) and [Planning](octoacme-project-planning.md)
2. Contribute feedback in demos and [Retrospectives](octoacme-retrospective-and-continuous-improvement.md)
3. Escalate critical customer issues as outlined in [Risks and Communication](octoacme-risks-and-communication.md)
4. Brief support team during [Release and Deployment](octoacme-release-and-deployment.md)

## Using These Docs with Copilot Spaces

To leverage these process documents as context for GitHub Copilot:
- Keep the Project Charter updated in the project repository
- Add process-specific docs into `.copilot/` directory to make them available as knowledge sources for Copilot Spaces
- Reference these docs when asking Copilot for project management guidance and best practices

---

*For questions or suggestions about these processes, please reach out to the Project Management team.*
