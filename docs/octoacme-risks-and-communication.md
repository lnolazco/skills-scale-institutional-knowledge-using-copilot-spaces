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
- Technical Writer maintains and publishes formal communication materials
- Support Lead channels customer feedback to appropriate stakeholders
- Business Analyst facilitates requirements clarification with stakeholders

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:
- Customer feedback summary (from Support Lead):

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled (facilitated by Scrum Master when available)
- Customer impact assessment (Support Lead)

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
- For customer-critical issues, Support Lead escalates directly to PM and Product Lead
- For requirements clarity, Business Analyst coordinates with PM and stakeholders
- For design decisions, UX Designer escalates to Product Manager for prioritization
