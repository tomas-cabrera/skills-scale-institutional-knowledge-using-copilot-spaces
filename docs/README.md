# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation. This summary will help you understand how OctoAcme initiates, plans, executes, tracks, releases, and continually improves all its cross-functional projects. Linked documents cover team roles, communication, risk, and more.

## Docs Overview

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

## OctoAcme Project Management Process Summary

OctoAcme follows a comprehensive, lifecycle-based project management approach grounded in five core principles: **customer-first prioritization**, **iterative delivery**, **clear ownership**, **data-informed decisions**, and **psychological safety**. The organization structures all cross-functional projects through a well-defined five-stage lifecycle: **Initiation** (problem validation and stakeholder alignment), **Planning** (scope definition and backlog creation), **Execution** (build and test cycles), **Release** (controlled deployment to production), and **Close & Retrospective** (learning capture and continuous improvement). At each stage, lightweight but deliberate artifacts—from the Project One-pager through Risk Registers to Release Notes—serve as single sources of truth, ensuring transparency and traceability across the organization.

### Organizational Structure & Roles

The organizational structure emphasizes clear role separation and accountability. **Project Managers** coordinate delivery activities, manage schedules, risks, and communications; **Product Managers** define outcomes, prioritize the backlog, and measure success; **Developers** implement features while maintaining quality standards through code review and testing; and **QA/Testing teams** validate acceptance criteria and quality gates. This multi-disciplinary model is supported by a regular communication cadence including daily standups (15 minutes focused on blockers), weekly syncs between PM and Product Lead, twice-weekly delivery team standups, and monthly stakeholder updates. Escalation follows a three-level structure: team-level triage in standups, PM escalation to Product Lead and dependent teams, and sponsor-level involvement for business-impacting issues.

### Quality Assurance & Delivery Workflow

Quality and testing are woven throughout execution rather than treated as an afterthought. OctoAcme requires unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows before release, security scanning in CI pipelines, and manual QA for feature acceptance when needed. The delivery workflow uses GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done), enforces pull requests with inclusion links, acceptance criteria, automated CI testing and linting, and requires at least one approval before merging. Progress is tracked through velocity and burndown metrics, with dashboards monitoring key signals such as errors, latency, and usage. When issues arise, a blameless retrospective process captures learnings and converts them into prioritized action items, embedding continuous improvement into the team's regular cadence.

## Quick Links

- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md)
- **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md)
- **Planning a project?** Use the [Project Planning](./octoacme-project-planning.md) guide
- **Managing day-to-day work?** See [Execution & Tracking](./octoacme-execution-and-tracking.md)
- **Ready to release?** Review the [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- **Learning from delivery?** Check out [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
