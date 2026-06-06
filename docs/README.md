# OctoAcme Project Management Docs

This README provides a centralized entry point and overview of OctoAcme's project management processes and links to our core process documentation.

## Summary of Project Management Processes

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The framework spans five distinct phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Closure & Retrospective**. During initiation, teams validate business need and align stakeholders around a lightweight Project One-pager that defines the problem, goals, and success metrics. Once approved, the planning phase breaks work into a prioritized, estimated backlog with clear acceptance criteria and dependencies mapped in a risk register. This structured foundation ensures alignment before development begins and reduces downstream surprises.

Execution and delivery are coordinated through a consistent team rhythm that includes daily standups (15 minutes), weekly delivery syncs, and end-of-sprint demos. Work flows through a project board with columns for Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests are kept small (≤400 lines when possible), include issue links and acceptance criteria, and require automated testing and at least one approval before merging. Quality assurance is embedded throughout: unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, and security scanning in CI. Risk management is continuous, with a formal escalation ladder (team-level → PM → Product Lead → Sponsor) ensuring blockers receive appropriate attention.

OctoAcme defines clear roles and responsibilities to prevent ambiguity and enable efficient collaboration. **Product Managers** define what should be built, prioritize the backlog, and measure outcomes through success metrics. **Project Managers** coordinate schedules, manage risks and dependencies, and maintain stakeholder communication through weekly status updates and risk registers. **Developers** implement features to acceptance criteria, write tests and documentation, and participate in design reviews and estimation. This separation of concerns—product vision, delivery coordination, and technical execution—creates accountability and clarity. Communication is structured through weekly PM-PdM syncs, twice-weekly standups, and monthly stakeholder updates, with a single source of truth (project README or release docs) for status.

Release and post-delivery processes are standardized to minimize risk and capture continuous improvement. Before production deployment, teams verify all acceptance criteria are met, CI and security scans pass, release notes are drafted, and smoke tests are prepared. Post-release, teams run verification checks and announce to stakeholders. Critically, every sprint or milestone concludes with a retrospective (45–75 minutes) where the team reflects on what went well, what could improve, and commits to 2–3 prioritized action items with clear owners and timelines. This cycle of learning and incremental improvement reinforces psychological safety and ensures the team evolves its processes based on real experience.

## Core Process Documents

- [Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, roles, and key artifacts
- [Project Initiation Guide](./octoacme-project-initiation.md) — Initial steps to validate and authorize work, align stakeholders, and create a lightweight plan
- [Project Planning](./octoacme-project-planning.md) — Turn an approved initiative into an actionable plan and backlog for delivery
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Guidance for managing day-to-day execution and tracking progress toward milestones
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardize how OctoAcme releases features to production
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements
- [Roles and Personas](./octoacme-roles-and-personas.md) — Define typical roles and responsibilities used in OctoAcme projects
