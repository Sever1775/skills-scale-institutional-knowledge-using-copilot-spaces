# OctoAcme Project Management Docs

This README provides a central index of OctoAcme's project management process documentation and a quick summary of how projects are run end to end.

---

## Project Management Process Summary

OctoAcme follows a structured, lifecycle-driven approach to project management organized across five phases: Initiation, Planning, Execution, Release, and Retrospective.

**Initiation** is where teams produce a lightweight Project One-pager capturing the problem statement, SMART objectives, success metrics, and stakeholder alignment before committing to full planning. A clear decision gate — confirmed success metrics, stakeholder agreement, and team availability — governs the move into planning.

**Planning** transforms an approved initiative into a prioritized, estimated backlog with a documented Definition of Done, a release milestone map, and a Risk Register. This ensures the team has shared clarity on scope, dependencies, and quality expectations before development begins.

**Execution & Tracking** is anchored in a consistent team rhythm: 15-minute daily standups, weekly delivery syncs to surface risks, and sprint-end demos for stakeholder visibility. Work flows through a structured GitHub Projects board, with small pull requests, mandatory CI checks, peer review, and a tiered blocker escalation path from team triage up through PM, Product Lead, and sponsor.

**Risk & Communication** is managed through a maintained Risk Register (ID, description, impact, likelihood, owner, mitigation, status), regular stakeholder status updates, and clearly defined escalation paths — from team-level to PM to Product Lead to Sponsor, with a separate track for security incidents.

**Release & Deployment** follows a standardized checklist covering staging validation, rollback planning, post-deploy verification, and stakeholder announcements. Releases are categorized as Patch, Minor, or Major, and every deployment includes a documented rollback and incident playbook.

**Retrospective & Continuous Improvement** closes the loop after every sprint, release, or incident. Timeboxed retrospectives (45–75 minutes) surface what went well, what could improve, and 2–3 prioritized action items with clear owners and due dates. These feed back into the backlog, creating a continuous improvement cycle.

OctoAcme's three core personas — **Project Manager** (delivery coordination, risk, communications), **Product Manager** (vision, backlog, outcomes), and **Developer** (implementation, testing, technical risk) — carry distinct responsibilities across the lifecycle, supported by regular cadences including weekly PM/PdM syncs, twice-weekly standups, and monthly stakeholder updates.

---

## Documentation Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Introduction to OctoAcme's approach, roles, artifacts, and lifecycle |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps to validate and authorize work, align stakeholders, and create a lightweight plan |
| [Project Planning](octoacme-project-planning.md) | Turn an approved initiative into an actionable plan and backlog |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Managing day-to-day execution and tracking progress toward milestones |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardized approach to releasing features to production |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert them into actionable improvements |
| [Roles & Personas](octoacme-roles-and-personas.md) | Typical roles and responsibilities used across OctoAcme projects |
