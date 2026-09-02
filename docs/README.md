# OctoAcme Project Management Documentation

## Overview

This directory is the central entry point for OctoAcme's project management
processes. Use this README to understand the overall approach, then follow the
links below to the detailed guidance for each phase, role, and practice.

## OctoAcme Project Management Process Summary

OctoAcme uses a structured, phase-based lifecycle: **Initiation** validates the
business need, stakeholders, success measures, and go/no-go decision;
**Planning** turns the approved initiative into a prioritized backlog with
acceptance criteria, estimates, dependencies, milestones, and a Definition of
Done. During **Execution**, the team delivers small increments through the
project board and pull request workflow. **Release** uses pre-release
checklists, staging verification, smoke tests, and rollback plans. **Close &
Retrospective** captures outcomes, learnings, and follow-up actions after a
sprint, release, milestone, or incident.

Responsibilities are shared across the delivery team. Project Managers
coordinate schedules, risks, dependencies, and stakeholder communication.
Product Managers own the product vision, backlog priorities, success metrics,
and outcome decisions. Developers design and build maintainable solutions,
write tests, and participate in reviews, while QA/Testing validates acceptance
criteria and quality. Stakeholders provide input and approvals at the
appropriate decision points.

Teams maintain alignment through daily standups focused on progress, blockers,
and dependencies; weekly PM/Product and delivery syncs for status, risks, and
decisions; and monthly updates for stakeholders. Quality is built into the
workflow through unit and integration tests, CI test and lint validation,
security scanning, code review, and end-to-end smoke tests before release.

Risks are recorded with owners, impact, likelihood, mitigation, and status,
then reviewed and escalated from the team to the PM, Product Lead, or sponsor
as needed. Retrospectives use a blameless structure to identify what went well,
what could improve, and a small set of owned, time-bound actions. Those actions
are tracked in the backlog and reviewed in subsequent syncs so the process
continues to improve.

## Documents in `docs/`

- [Project management overview](octoacme-project-management-overview.md)
- [Project initiation](octoacme-project-initiation.md)
- [Project planning](octoacme-project-planning.md)
- [Execution and tracking](octoacme-execution-and-tracking.md)
- [Risks and communication](octoacme-risks-and-communication.md)
- [Release and deployment](octoacme-release-and-deployment.md)
- [Retrospective and continuous improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and personas](octoacme-roles-and-personas.md)
