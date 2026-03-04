# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

> **Changelog:** Expanded with additional personas (Scrum Master, Technical Lead, UX Designer, Business Analyst, QA Lead) to close process ownership and accountability gaps. See [issue #4](https://github.com/richardwike/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4) for full context.

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

### Interactions with Other Roles
- Works with **Technical Lead** for design guidance and code review escalations
- Works with **QA Lead** to ensure acceptance criteria and test coverage are met
- Works with **UX Designer** to validate implementation feasibility and UI details

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

### Interactions with Other Roles
- Works with **Business Analyst** to translate stakeholder needs into well-defined requirements
- Works with **UX Designer** to ensure solutions are user-centered
- Works with **Technical Lead** on technical trade-offs and feasibility

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

### Interactions with Other Roles
- Partners with **Scrum Master** to enforce process discipline and remove blockers
- Coordinates with **Technical Lead** for technical risk management
- Works with **QA Lead** to define acceptance criteria and quality gates
- Relies on **Business Analyst** to ensure business objectives are captured in plans

---

## Scrum Master

### Role Summary
The Scrum Master facilitates agile ceremonies, coaches the team on agile practices, and removes impediments that block delivery. They act as a servant leader, protecting the team's focus and continuous improvement cadence.

### Responsibilities
- Facilitate sprint ceremonies: planning, daily standups, reviews, and retrospectives
- Identify and remove impediments blocking the team
- Coach team members on agile/scrum principles and practices
- Shield the team from unplanned interruptions during a sprint
- Track and report on team velocity and sprint health

### Goals
- Enable a high-performing, self-organizing team
- Drive continuous improvement through retrospective action items
- Maintain a sustainable pace and healthy team dynamics

### Typical Communication
- Daily standup facilitation
- Sprint planning and retrospective facilitation
- Impediment log updates shared with Project Manager

### Interactions with Other Roles
- Works closely with **Project Manager** to enforce process discipline and escalate blockers
- Collaborates with **Product Manager** to maintain a healthy, prioritized backlog
- Supports **Developers** in following agile best practices and managing their workload

---

## Technical Lead

### Role Summary
The Technical Lead owns technical architecture decisions, supports developers through design and code reviews, and serves as the primary escalation point for engineering blockers. They bridge the gap between business requirements and technical execution.

### Responsibilities
- Define and maintain the technical architecture and standards
- Lead design reviews and ensure code quality through code reviews
- Identify and mitigate technical risks before and during delivery
- Mentor developers and help unblock technical challenges
- Evaluate feasibility of proposed features or approaches

### Goals
- Deliver a scalable, maintainable, and secure codebase
- Reduce technical debt while enabling feature velocity
- Ensure engineering decisions align with product and business goals

### Typical Communication
- Architecture Decision Records (ADRs) and design docs
- Code review comments and pair-programming sessions
- Technical risk updates in weekly project syncs

### Interactions with Other Roles
- Partners with **Product Manager** and **Project Manager** for technical risk management
- Guides **Developers** on design patterns, code quality, and escalations
- Works with **UX Designer** to assess feasibility of UX proposals
- Aligns with **QA Lead** on test strategy and quality standards

---

## UX Designer

### Role Summary
The UX Designer is responsible for user experience design, prototyping, and usability testing. They translate product requirements into user-centered solutions that are both functional and intuitive.

### Responsibilities
- Conduct user research and synthesize findings into design insights
- Create wireframes, prototypes, and high-fidelity designs
- Run usability tests and incorporate feedback iteratively
- Maintain a design system or style guide for consistency
- Collaborate with developers on implementation to preserve design intent

### Goals
- Deliver accessible, delightful, and usable interfaces
- Reduce friction in user flows and improve task completion rates
- Ensure designs are technically feasible and align with product goals

### Typical Communication
- Design reviews and prototype walkthroughs
- Usability test reports and design specifications
- Async feedback via design tools (e.g., Figma comments)

### Interactions with Other Roles
- Works closely with **Product Manager** to translate requirements into user-centered designs
- Collaborates with **Developers** for implementation feasibility and design handoff
- Coordinates with **Business Analyst** to incorporate user needs within business constraints
- Shares usability findings with **QA Lead** to inform acceptance testing

---

## Business Analyst

### Role Summary
The Business Analyst bridges stakeholder requirements and the development team's understanding. They elicit, document, and validate requirements to ensure business objectives are clearly reflected in delivered solutions.

### Responsibilities
- Elicit requirements from stakeholders through interviews, workshops, and analysis
- Document functional and non-functional requirements in a clear, testable format
- Validate that implemented solutions meet the stated business objectives
- Maintain traceability between business needs and delivered features
- Support backlog refinement by clarifying acceptance criteria

### Goals
- Ensure delivered solutions address the right business problems
- Reduce rework by catching ambiguities early in the process
- Foster shared understanding between business and technical teams

### Typical Communication
- Requirements documents, user stories, and process flow diagrams
- Stakeholder workshops and requirements review sessions
- Backlog refinement meetings with Product Manager and Developers

### Interactions with Other Roles
- Partners with **Product Manager** and **Project Manager** to align requirements with roadmap priorities
- Works with **Developers** to clarify requirements and acceptance criteria during development
- Collaborates with **QA Lead** to ensure test cases cover all business requirements
- Supports **UX Designer** by providing business context for design decisions

---

## QA Lead

### Role Summary
The QA Lead oversees the testing strategy, test case development, and quality gates throughout the project lifecycle. They ensure that releases meet acceptance criteria and that defects are triaged and resolved efficiently.

### Responsibilities
- Define and maintain the overall test strategy (unit, integration, end-to-end, regression)
- Develop and manage test plans and test case libraries
- Coordinate quality gates and sign-off criteria for releases
- Lead defect triage and track defect resolution
- Advocate for quality practices across the team

### Goals
- Prevent defects from reaching production
- Build a test suite that provides fast, reliable feedback
- Ensure all acceptance criteria are validated before release

### Typical Communication
- Test plans and test case documentation
- Defect reports and triage meeting facilitation
- Quality status updates in sprint reviews and release sign-offs

### Interactions with Other Roles
- Collaborates with **Developers** to define acceptance criteria and review unit/integration tests
- Works with **Project Manager** to communicate quality risks and release readiness
- Partners with **Business Analyst** to ensure test cases trace back to business requirements
- Coordinates with **Technical Lead** on test architecture and CI/CD quality gates
- Reviews usability findings from **UX Designer** to incorporate in acceptance testing

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When onboarding a new team member, refer to the [Onboarding Checklist](octoacme-onboarding-checklist.md) for role-specific guidance.

