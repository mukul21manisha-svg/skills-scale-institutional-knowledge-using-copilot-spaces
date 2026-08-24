# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management documentation suite. This directory contains the processes, templates, and guidance that enable OctoAcme teams to run projects consistently, transparently, and with measurable outcomes.

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning


## Process Documentation by Lifecycle Phase
=======
## OctoAcme Project Management Approach

OctoAcme operates a structured, lifecycle-based project management framework that emphasizes customer-first delivery, iterative development, and clear accountability. The approach spans five key phases: **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments with defined acceptance criteria), **Execution** (daily standups and sprint-based delivery with quality gates), **Release** (standardized deployment with rollback contingencies), and **Close & Retrospective** (capturing learnings for continuous improvement). This end-to-end model ensures that projects are grounded in measurable success metrics, maintain transparency across stakeholders, and reduce single-person dependency risk by documenting processes and decisions systematically.

The delivery model is built on **three core roles**: Project Managers coordinate schedules, risks, and communications; Product Managers define outcomes, prioritize backlogs, and measure impact; and Developers implement features while contributing to design, estimation, and risk mitigation. Cross-functional collaboration is formalized through a regular communication cadence—daily team standups, twice-weekly delivery syncs, weekly PM-PdM alignment, and monthly stakeholder updates—supported by a "single source of truth" approach using project boards (e.g., GitHub Projects) and centralized documentation. This structure ensures decisions are visible, dependencies are tracked, and escalation paths are clear.

Quality and risk management are woven into every phase. OctoAcme enforces small pull requests (≤400 lines), requires automated testing and linting in CI, mandates at least one approval before merge, and includes security scanning and manual QA before release. Risk registers are maintained throughout the project lifecycle, with identified risks assessed for impact and likelihood, and reviewed weekly. Blockers escalate through a defined three-level hierarchy (team triage → PM to Product Lead → sponsor escalation), ensuring that obstacles don't delay delivery unexpectedly. A pre-release checklist confirms acceptance criteria, CI status, smoke tests, and rollback plans before deployment.

Finally, OctoAcme institutionalizes learning through **retrospectives and continuous improvement**. After each sprint, release, or milestone, teams reflect on what went well and what could improve, converting insights into prioritized action items tracked with clear owners and due dates. This culture of psychological safety, measurement, and iterative refinement—combined with artifact versioning and integration with Copilot Spaces—enables rapid onboarding, consistent execution, and sustainable scaling of institutional knowledge across the organization.

## Process Documentation

OctoAcme projects follow a structured lifecycle. Here's where to find guidance at each stage:

### 1. Initiation Phase
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Define the initial steps to validate and authorize work, align stakeholders, and create a lightweight plan. Confirms business need, identifies stakeholders, and establishes success criteria before moving to detailed planning.

### 2. Planning Phase
- **[Project Planning](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog for delivery. Breaks work into shippable increments, identifies dependencies, defines acceptance criteria, and creates a release plan.

### 3. Execution Phase
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day execution and track progress toward project milestones. Establishes team rhythm, sprint workflows, quality standards, and blocker escalation procedures.

### 4. Release Phase
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize how OctoAcme releases features to production to reduce risk and improve observability. Includes pre-release requirements, deployment checklists, and rollback procedures.

### 5. Closure & Continuous Improvement
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements. Formalizes the process of reflecting on what went well, identifying improvements, and tracking action items.

## Cross-Cutting Guidance

These documents apply throughout the project lifecycle and provide essential context:

- **[Project Management Overview](octoacme-project-management-overview.md)** — Concise introduction to how OctoAcme runs projects, core roles, key artifacts, and the overall lifecycle framework
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — How to identify, manage, and communicate risks and dependencies; includes risk escalation paths and stakeholder communication templates
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed definitions of key roles and responsibilities, including Developers, Product Managers, and Project Managers

## Getting Started

### New to OctoAcme?
Start with **[Project Management Overview](octoacme-project-management-overview.md)** for a high-level introduction to how OctoAcme structures projects and defines roles.

### Starting a new project?
Follow the lifecycle in order:
1. **[Project Initiation Guide](octoacme-project-initiation.md)** — Validate the idea and get stakeholder buy-in
2. **[Project Planning](octoacme-project-planning.md)** — Create a detailed plan and backlog

### Need help during execution?
Refer to **[Execution & Tracking](octoacme-execution-and-tracking.md)** for guidance on team rhythm, workflows, quality standards, and risk escalation.

### Preparing a release?
Use **[Release & Deployment Guide](octoacme-release-and-deployment.md)** to understand pre-release requirements, deployment procedures, and rollback strategies.

### Wrapping up a project or seeking improvements?
See **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** to run an effective retrospective and convert learnings into action items.

### Dealing with risks or dependencies?
**[Risk Management & Communication](octoacme-risks-and-communication.md)** provides templates and guidance for maintaining a risk register, escalating blockers, and keeping stakeholders informed.

## Quick Reference

| Phase | Document | Key Deliverables |
|-------|----------|------------------|
| Initiation | [Project Initiation Guide](octoacme-project-initiation.md) | Project One-pager, Stakeholder list, High-level timeline |
| Planning | [Project Planning](octoacme-project-planning.md) | Prioritized backlog, Estimates, Release plan, Definition of Done |
| Execution | [Execution & Tracking](octoacme-execution-and-tracking.md) | Sprint backlog, Status updates, Risk register updates |
| Release | [Release & Deployment Guide](octoacme-release-and-deployment.md) | Release notes, Deployment verification, Rollback plan |
| Retrospective | [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Action items, Improvement backlog, Learnings documentation |

## Contributing to OctoAcme Documentation

To add content or updates to the OctoAcme process documentation, use the **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** issue template. This ensures all updates are tracked, reviewed, and aligned with existing processes.
