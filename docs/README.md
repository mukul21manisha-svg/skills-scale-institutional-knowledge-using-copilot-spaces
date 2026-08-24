# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management documentation suite. This directory contains the processes, templates, and guidance that enable OctoAcme teams to run projects consistently, transparently, and with measurable outcomes.

## Overview

OctoAcme operates on these core principles:
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## OctoAcme Project Management Approach

OctoAcme operates a structured, lifecycle-based project management framework that emphasizes customer-first delivery, iterative development, and clear accountability. The approach spans five key phases: **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments with defined acceptance criteria), **Execution** (daily standups and sprint-based delivery with quality gates), **Release** (standardized deployment with rollback contingencies), and **Close & Retrospective** (capturing learnings for continuous improvement). This end-to-end model ensures that projects are grounded in measurable success metrics, maintain transparency across stakeholders, and reduce single-person dependency risk by documenting processes and decisions systematically.

The delivery model is built on **three core roles**: Project Managers coordinate schedules, risks, and communications; Product Managers define outcomes, prioritize backlogs, and measure impact; and Developers implement features while contributing to design, estimation, and risk mitigation. Cross-functional collaboration is formalized through a regular communication cadence—daily team standups, twice-weekly delivery syncs, weekly PM-PdM alignment, and monthly stakeholder updates—supported by a "single source of truth" approach using project boards (e.g., GitHub Projects) and centralized documentation. This structure ensures decisions are visible, dependencies are tracked, and escalation paths are clear.

Quality and risk management are woven into every phase. OctoAcme enforces small pull requests (≤400 lines), requires automated testing and linting in CI, mandates at least one approval before merge, and includes security scanning and manual QA before release. Risk registers are maintained throughout the project lifecycle, with identified risks assessed for impact and likelihood, and reviewed weekly. Blockers escalate through a defined three-level hierarchy (team triage → PM to Product Lead → sponsor escalation), ensuring that obstacles don't delay delivery unexpectedly. A pre-release checklist confirms acceptance criteria, CI status, smoke tests, and rollback plans before deployment.

Finally, OctoAcme institutionalizes learning through **retrospectives and continuous improvement**. After each sprint, release, or milestone, teams reflect on what went well and what could improve, converting insights into prioritized action items tracked with clear owners and due dates. This culture of psychological safety, measurement, and iterative refinement—combined with artifact versioning and integration with Copilot Spaces—enables rapid onboarding, consistent execution, and sustainable scaling of institutional knowledge across the organization.

## Process Documentation

OctoAcme projects follow a structured lifecycle. Here's where to find guidance at each stage:

### 1. Initiation Phase
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Define the initial steps to validate and authorize work, align stakeholders, and create a lightweight plan

### 2. Planning Phase
- **[Project Planning](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog for delivery

### 3. Execution Phase
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day execution and track progress toward project milestones

### 4. Release Phase
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize how OctoAcme releases features to production

### 5. Closure & Continuous Improvement
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements

## Cross-Cutting Guidance

These documents apply throughout the project lifecycle:

- **[Project Management Overview](octoacme-project-management-overview.md)** — Concise introduction to how OctoAcme runs projects, key roles, and artifacts
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — How to identify, manage, and communicate risks and dependencies
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Definitions of key roles and responsibilities (Developers, Product Managers, Project Managers)

## Getting Started

1. **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md)
2. **Starting a new project?** Follow [Project Initiation Guide](octoacme-project-initiation.md) → [Project Planning](octoacme-project-planning.md)
3. **Need help during execution?** Refer to [Execution & Tracking](octoacme-execution-and-tracking.md)
4. **Preparing a release?** Use [Release & Deployment Guide](octoacme-release-and-deployment.md)
5. **Wrapping up or seeking improvements?** See [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## Quick Reference

| Phase | Key Document | Purpose |
|-------|--------------|---------|
| **Initiation** | [Project Initiation Guide](octoacme-project-initiation.md) | Validate need, align stakeholders, decide go/no-go |
| **Planning** | [Project Planning](octoacme-project-planning.md) | Break work into shippable increments, manage dependencies |
| **Execution** | [Execution & Tracking](octoacme-execution-and-tracking.md) | Daily standups, sprint rituals, track progress |
| **Release** | [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardized deployment, rollback contingencies |
| **Retrospective** | [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings, drive improvements |

## Key Artifacts & Templates

Throughout the project lifecycle, you'll use or create:
- **Project Charter / One-pager** — High-level problem, goal, success metrics
- **Roadmap and Release Plan** — Milestone timeline and phased delivery
- **Sprint/Iteration Backlog** — Prioritized work with acceptance criteria
- **Risk Register** — Tracked risks with mitigation plans
- **Retrospective Notes & Action Items** — Team learnings and improvements

---

**For more information or to contribute updates to these process docs, create an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.**
