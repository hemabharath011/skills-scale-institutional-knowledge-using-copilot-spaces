# OctoAcme Project Management Docs

Welcome! This README provides an overview of the project management processes used by OctoAcme, with links to all detailed process documents below.

## OctoAcme Project Management – Key Principles

- **Customer-first:** Value and usability drive priorities.
- **Iterative delivery:** Small, testable increments with frequent review.
- **Clear ownership:** Named PM and Product Lead for each project.
- **Data-informed:** Metrics guide improvements and decisions.
- **Transparency:** Regular communication and documentation of roles, risks, and status.

OctoAcme processes cover initiation, planning, execution, release, continuous improvement, risk management, and core roles.

## Project Management Overview

OctoAcme operates on a structured, lifecycle-based project management approach grounded in clear roles, iterative delivery, and data-informed decision-making. The organization follows five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**.

### Lifecycle Phases

1. **Initiation:** Validate business needs through a lightweight Project One-pager that establishes the problem statement, success metrics, and stakeholder alignment before progressing to planning.

2. **Planning:** Break the approved initiative into shippable increments with prioritized backlogs, clear acceptance criteria, and identified dependencies to ensure projects are well-scoped before significant effort is invested.

3. **Execution:** Teams emphasize quality and measurable progress through rigorous workflows, GitHub Projects for workflow management, small PRs (≤400 lines), mandatory CI/CD checks, automated testing, and security scanning.

4. **Release:** Before deployment, teams ensure all acceptance criteria are met, CI/CD pipelines pass, security scans complete, and rollback plans are documented. Releases are categorized by type (Patch, Minor, Major).

5. **Close & Retrospective:** After each sprint, release, or milestone, teams conduct structured retrospectives to capture learnings, identify improvements, and assign action items with clear owners and due dates.

### Core Roles & Responsibilities

- **Project Managers:** Coordinate delivery timelines, risks, and communications. Create and maintain project plans, manage schedules, facilitate meetings, and ensure consistent documentation and status reporting.

- **Product Managers:** Define customer value, prioritize the backlog, establish success metrics, and measure outcomes through data-driven analysis.

- **Developers:** Implement features while maintaining quality standards through code reviews, testing, design collaboration, and risk identification.

### Communication Strategy

OctoAcme enforces a disciplined communication cadence:
- **Daily standups (15 min):** Focus on progress, blockers, and dependencies
- **Weekly delivery sync:** Show progress, updates, and flagged risks
- **Weekly PM & PdM alignment:** Coordination between Project and Product Managers
- **Monthly stakeholder updates:** Broader visibility into project status
- **Ad-hoc escalations:** For risks and critical issues

### Quality Assurance & Testing

Execution emphasizes comprehensive quality practices:
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI/CD pipeline
- Manual QA for feature acceptance when needed

### Risk Management

Risk management is ongoing and structured:
- **Identify:** During planning and ongoing execution
- **Assess:** Estimate impact and likelihood
- **Mitigate:** Reduce via actions and contingency plans
- **Monitor:** Review at weekly syncs and update status
- **Escalate:** Team-level triage → PM escalation → Sponsor-level escalation

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

---

For suggestions on updating process documentation, use the ["Add Content to Project Management Process Docs"](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.
