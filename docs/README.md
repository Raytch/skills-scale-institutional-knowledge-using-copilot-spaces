# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management knowledge base. This directory contains comprehensive guides for running projects at OctoAcme, from initial concept through retrospective and continuous improvement.

## Quick Start

New to OctoAcme projects? Start here:
1. Read [Project Management Overview](./octoacme-project-management-overview.md) for principles and roles
2. Navigate to the relevant phase based on your current project stage (see **Project Lifecycle** below)
3. Reference specific docs as needed

## Our Approach

OctoAcme follows a structured, iterative project management approach grounded in five core principles:

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments to reduce risk and gather feedback early
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Manager (PdM) to ensure accountability
- **Data-informed decisions**: Measure impact and iterate based on evidence, not assumptions
- **Psychological safety**: Encourage feedback, learning, and experimentation without fear of blame

### Project Management Philosophy

OctoAcme's approach to project management emphasizes:

- **Lightweight structure**: Avoid heavy processes; use just enough documentation to stay aligned
- **Cross-functional collaboration**: Product, engineering, QA, and stakeholders work together from day one
- **Transparent communication**: Regular updates and escalation paths ensure no surprises
- **Continuous improvement**: Every project cycle includes retrospectives to drive incremental process improvements
- **Risk management**: Proactive identification and mitigation of blockers and dependencies
- **Quality standards**: Consistent testing, code review, and acceptance criteria validation

This framework enables teams to deliver reliable, maintainable solutions that meet customer needs while maintaining team velocity and morale.

## Core Roles

- **Project Manager**: Coordinates delivery, manages schedules, owns risks and communications, and ensures project transparency
- **Product Manager**: Defines outcomes, prioritizes the backlog, measures success, and validates solutions
- **Developers**: Design and build features, write tests, collaborate on design and code reviews, and identify technical risks
- **QA/Testing**: Validate quality against acceptance criteria and identify edge cases
- **Stakeholders**: Provide inputs, approvals, and business context

*For detailed role descriptions and communication patterns, see [Roles & Personas](./octoacme-roles-and-personas.md)*

## Project Lifecycle

Every OctoAcme project follows these phases:

### 1. [Initiation](./octoacme-project-initiation.md)
Validate business need, align stakeholders, and create a lightweight project one-pager to make a go/no-go decision.

**Key Deliverables**: Project One-pager, Stakeholder list, Initial risk list, Timeline and milestones

### 2. [Planning](./octoacme-project-planning.md)
Break work into shippable increments, define acceptance criteria, identify dependencies, and create a release plan.

**Key Deliverables**: Prioritized backlog, Definition of Done, Release timeline, Risk register

### 3. [Execution & Tracking](./octoacme-execution-and-tracking.md)
Build, test, review, and iterate with daily standups, weekly syncs, and regular demos to stakeholders.

**Key Deliverables**: Sprint backlog, Pull requests, Test results, Risk updates, Demo outcomes

### 4. [Release & Deployment](./octoacme-release-and-deployment.md)
Deploy to production with pre-release checks, smoke tests, and rollback plans to minimize risk.

**Key Deliverables**: Release notes, Deployment checklist, Post-deploy verification, Announcement

### 5. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
Capture learnings, identify improvements, and track action items to make the next cycle more efficient.

**Key Deliverables**: Retrospective notes, Action items with owners and due dates, Process improvements

## Complete Documentation Index

### Foundational
- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) — Core principles, roles, key artifacts, and high-level lifecycle
- [OctoAcme Roles & Personas](./octoacme-roles-and-personas.md) — Detailed responsibilities, goals, and communication patterns for each role

### By Project Phase
- [OctoAcme Project Initiation Guide](./octoacme-project-initiation.md) — Problem validation, stakeholder alignment, go/no-go decision gates
- [OctoAcme Project Planning](./octoacme-project-planning.md) — Backlog creation, estimation, Definition of Done, risk and dependency identification
- [OctoAcme Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day workflows, team rhythm, quality standards, blocker escalation
- [OctoAcme Release & Deployment Guide](./octoacme-release-and-deployment.md) — Release types, pre-release requirements, deployment checklist, rollback procedures
- [OctoAcme Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Retrospective structure, tracking improvements, action item management

### Cross-cutting
- [OctoAcme Risk Management & Communication](./octoacme-risks-and-communication.md) — Risk register maintenance, escalation paths, stakeholder communication templates, incident response

## Communication Cadence

**Daily**
- Team standups (15 min) — progress, blockers, dependencies

**Weekly**
- PM + PdM sync — alignment and decision-making
- Delivery team sync — progress updates and risk review
- Risk register review — identify and mitigate emerging risks

**Bi-weekly or Sprint-end**
- Demo / Review — showcase progress to stakeholders

**Monthly**
- Stakeholder updates — high-level status and upcoming milestones

**As needed**
- Ad-hoc escalations — blocker resolution and urgent decisions

## Key Artifacts You'll Work With

- **Project Charter / One-pager** — Problem statement, goals, success metrics, stakeholders, timeline
- **Risk Register** — Tracked risks with impact, probability, mitigation plans, and owners
- **Project Board** (e.g., GitHub Projects) — Visual workflow with columns: Backlog, Ready, In Progress, In Review, QA, Done
- **Backlog with Acceptance Criteria** — Prioritized work items with clear success criteria
- **Release Plan and Milestone Map** — Timeline of features and milestones
- **Retrospective notes and action items** — Learnings and improvements with owners and due dates
- **Release Notes** — What changed, migration steps, known issues

## Getting Started as a New Team Member

1. **Read the Overview** — Start with [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) to understand our approach
2. **Understand Your Role** — Review [Roles & Personas](./octoacme-roles-and-personas.md) to understand responsibilities and communication patterns
3. **Find Your Project Stage** — Navigate to the relevant lifecycle phase above
4. **Reference the Specific Guides** — Dive into detailed process docs as needed
5. **Ask Questions** — Reach out to your Project Manager or Product Lead if something isn't clear

## Questions or Feedback?

Refer to the relevant phase documentation above. If you can't find what you need or want to contribute an improvement:
- Reach out to your Project Manager or Product Lead
- Open an issue in the repository to suggest updates or clarifications
- See the issue template for [adding content to process docs](./.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
