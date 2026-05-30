# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management knowledge base. This folder contains comprehensive guides for running projects at OctoAcme, from initiation through retrospective.

## Quick Start

New to OctoAcme projects? Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand our approach, roles, and key artifacts.

## Overview of OctoAcme Project Management Processes

OctoAcme follows a structured, lifecycle-based project management approach designed to deliver customer value through iterative execution and clear governance. The methodology spans five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. Each phase is supported by standardized artifacts—including a Project One-pager, prioritized backlog with acceptance criteria, risk registers, and release notes—that serve as a single source of truth for stakeholders. Projects are guided by clear principles emphasizing customer-first delivery, iterative increments, data-informed decisions, and psychological safety. This structured approach ensures alignment across teams and reduces ambiguity about what success looks like from the outset.

OctoAcme defines clear ownership and collaboration across three primary personas: **Project Managers** coordinate delivery activities, manage schedules and risks, and facilitate stakeholder communication; **Product Managers** define what should be built, prioritize the backlog, and measure outcomes; and **Developers** implement features, write tests, participate in reviews, and help identify technical risks. Communication happens through a consistent rhythm of daily standups (15 minutes, focused on progress and blockers), weekly PM-PdM syncs, twice-weekly team standups, and monthly stakeholder updates. Risk escalation follows a structured three-level path: team-level triage in standups, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues. This distributed ownership model ensures accountability while maintaining transparency.

Execution and quality are maintained through disciplined workflows and continuous monitoring. The team uses GitHub Projects with standard columns (Backlog, Ready, In Progress, In Review, QA, Done) to track progress, enforces small pull requests (≤400 lines when possible) with at least one approval before merge, and requires automated testing, linting, and security scanning in CI. Quality assurance spans unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, and manual QA for feature acceptance. Metrics such as velocity, burndown, and success indicators (errors, latency, usage) are tracked via dashboards to inform decision-making. Releases are standardized by type (patch, minor, major) and include pre-deployment checklists, smoke tests, and rollback plans to minimize production risk.

Finally, OctoAcme embeds learning and continuous improvement into every project through structured retrospectives held after each sprint, release, or milestone. Retrospectives follow a consistent format (what went well, what could improve, action items with owners and due dates), are timeboxed to 45–75 minutes, and prioritize 2–3 actionable improvements to avoid overload. Action items are tracked in the project backlog and reviewed in weekly PM syncs, ensuring accountability and measurable progress. This approach transforms project execution into a feedback loop that refines processes over time, reduces institutional knowledge silos, and accelerates onboarding for new team members.

## Documentation Structure

### Core Guides

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, roles, principles, and lifecycle
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps to validate, authorize, and plan new projects
- **[Project Planning](./octoacme-project-planning.md)** — Breaking work into actionable backlog items, estimation, and release planning
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Day-to-day execution, quality standards, and blocker escalation
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identifying, managing, and communicating risks and dependencies
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardized release processes and rollback procedures
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capturing learnings and driving iterative improvements

### Reference

- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Detailed definitions of Project Managers, Product Managers, and Developers

## How to Use These Docs

- **For Project Managers**: Use the full lifecycle guides to plan, track, and close projects
- **For Product Managers**: Focus on Initiation, Planning, and Release guides for roadmapping and success metrics
- **For Developers**: Reference Execution & Tracking for PR workflows, quality standards, and Definition of Done
- **For Stakeholders**: Review the Project Management Overview and Risk Management guides for visibility and escalation paths

## Contributing

Have feedback or want to propose updates to these processes? See `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` for the process to request documentation changes.

---

*Last updated: 2026-05-30*
