# OctoAcme Project Management Documentation

## Overview

This folder contains the complete **OctoAcme project management framework**, guiding teams through all phases of project delivery: from initial conception through retrospective and continuous improvement.

OctoAcme is built on five core principles:
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named PM and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Quick Navigation

Browse by project phase or role:

### Project Phases

| Phase | Document | Purpose |
|-------|----------|---------|
| **Initiation** | [Project Initiation Guide](./octoacme-project-initiation.md) | Define problem statement, stakeholders, and initial timeline |
| **Planning** | [Project Planning](./octoacme-project-planning.md) | Create actionable backlog, estimate scope, and identify dependencies |
| **Execution** | [Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day delivery, quality assurance, and progress tracking |
| **Release** | [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Standardize releases and manage deployment risk |
| **Retrospective** | [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and drive improvements |

### Cross-functional Guidance

| Topic | Document | For |
|-------|----------|-----|
| **Overview** | [Project Management Overview](./octoacme-project-management-overview.md) | High-level introduction to roles, principles, and lifecycle |
| **Risk & Communication** | [Risk Management & Communication](./octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies |
| **Roles & Personas** | [Roles and Personas](./octoacme-roles-and-personas.md) | Understand responsibilities by role (PM, PdM, Developers, QA) |

## OctoAcme Project Management Lifecycle

### 1. Initiation
**Goal**: Validate the business need and authorize planning work.

**Key Activities**:
- Confirm business need and measurable outcomes
- Identify stakeholders and champions
- Create a Project One-pager (Problem, Goal, Success Metrics)
- Make a go/no-go decision to proceed to planning

**Decision Gate**: Move to planning when success metrics are clear, stakeholders align on priority, and team availability is confirmed.

### 2. Planning
**Goal**: Turn an approved initiative into an actionable plan and backlog.

**Key Activities**:
- Hold a kickoff meeting with stakeholders and delivery team
- Create a prioritized backlog with acceptance criteria
- Estimate scope and define Definition of Done
- Identify dependencies and integration points
- Create a release plan and milestone map

**Deliverables**: Backlog, release timeline, risk register, test plan.

### 3. Execution & Tracking
**Goal**: Manage day-to-day execution and track progress toward milestones.

**Key Activities**:
- Daily standups (15 min) focused on progress, blockers, dependencies
- Weekly delivery sync to show progress and flag risks
- Use project board with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Execute small PRs (≤ 400 lines) with proper testing and reviews
- Track velocity, burndown, and key metrics

**Quality Standards**: Unit tests, integration tests, end-to-end smoke tests, security scanning, manual QA.

### 4. Release & Deployment
**Goal**: Standardize releases to reduce risk and improve observability.

**Key Activities**:
- Ensure all acceptance criteria are met and PRs merged
- Verify passing CI and security scans
- Draft release notes and document rollback plans
- Deploy to staging and run smoke tests
- Deploy to production via automated pipeline
- Verify post-deployment and announce to stakeholders

**Release Types**: Patch (hotfixes), Minor (incremental features), Major (significant changes).

### 5. Retrospective & Continuous Improvement
**Goal**: Capture learnings and convert them into actionable improvements.

**Key Activities**:
- Hold a retrospective after each sprint, release, or milestone (45–75 min)
- Discuss what went well, what could improve, and action items
- Track improvements in backlog with clear owners and timelines
- Review progress on action items in weekly PM sync

**Output**: Retrospective notes, prioritized action items, continuous improvement culture.

## Key Artifacts

Every project maintains these core artifacts:

- **Project Charter / One-pager** — Problem, goal, success metrics, stakeholders, timeline
- **Roadmap & Release Plan** — High-level timeline and milestones
- **Sprint/Iteration Backlog** — Prioritized work with acceptance criteria and estimates
- **Risk Register** — ID, description, impact, probability, owner, mitigation
- **Project Board** — Visual tracking of work status (GitHub Projects or similar)
- **Retrospective Notes** — Learnings and action items from completed phases

## Core Roles & Responsibilities

### Project Manager (PM)
- Coordinates delivery, schedules, risk, and communications
- Maintains project plans and risk registers
- Facilitates meetings and ensures documentation
- Escalates blockers and manages dependencies

### Product Manager (PdM)
- Defines outcomes and prioritizes backlog
- Owns success metrics and product direction
- Validates solutions through user research and data
- Collaborates with PM on trade-offs and scope

### Developers
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Help estimate work and identify technical risks

### QA/Testing
- Validate quality and acceptance criteria
- Execute test plans and identify defects
- Verify feature acceptance before release
- Support end-to-end smoke testing

## Communication Cadence

- **Daily**: Standups (15 min) with delivery team
- **Weekly**: PM + PdM sync to align on priorities and risks
- **Twice weekly**: Standups for delivery team (or as agreed)
- **Monthly**: Stakeholder updates and progress reports
- **Ad-hoc**: Escalations as needed for critical blockers

## Getting Started

**New to OctoAcme?** Start here:
1. Read the [Project Management Overview](./octoacme-project-management-overview.md) for a concise introduction
2. Follow the guides for your current project phase (Initiation → Planning → Execution → Release → Retrospective)
3. Reference [Roles and Personas](./octoacme-roles-and-personas.md) to understand your responsibilities
4. Consult [Risk Management & Communication](./octoacme-risks-and-communication.md) for guidance on escalations and stakeholder updates

**Starting a new project?** Follow this workflow:
1. **Week 1**: Complete [Project Initiation Guide](./octoacme-project-initiation.md)
2. **Week 2**: Execute [Project Planning](./octoacme-project-planning.md)
3. **Ongoing**: Follow [Execution & Tracking](./octoacme-execution-and-tracking.md) cadence
4. **At Release**: Execute [Release & Deployment Guide](./octoacme-release-and-deployment.md)
5. **At Completion**: Run [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

## Process Improvement

Found a gap or improvement opportunity in these docs? Open an issue using the [Process Doc Update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to suggest updates.

Our goal is to keep these docs live, relevant, and useful for all teams using the OctoAcme framework.

---

**Last Updated**: 2026-07-01  
**Framework Owner**: OctoAcme Project Management Office
