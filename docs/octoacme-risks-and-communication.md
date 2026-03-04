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

**Role Ownership for Risks:**
- Technical risks → **Technical Lead**
- Quality/testing risks → **QA Lead**
- Requirements/scope risks → **Business Analyst** in partnership with **Product Manager**
- UX/usability risks → **UX Designer**
- Schedule/resource risks → **Project Manager**
- Process/agility risks → **Scrum Master**

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

> **Changelog:** Risk ownership updated to assign specific risk categories to new roles (Technical Lead, QA Lead, Business Analyst, UX Designer, Scrum Master) for clearer accountability. See [issue #4](https://github.com/richardwike/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4).
