# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documents and serves as a single-entry index for contributors and new team members. The docs capture our lifecycle, roles, workflows, and ready-to-use templates to help teams start, plan, execute, release, and continuously improve projects.

## Brief overview

OctoAcme runs a lightweight, iterative project management approach focused on clear ownership and measurable outcomes. Work begins with Initiation (one-pager and decision gate), moves into Planning (prioritized backlog, estimates, and release mapping), continues through Execution (small PRs, daily standups, CI checks, and demos), and finishes with Release (staging verification, rollback plan) and Retrospective (action items fed back into the backlog). Each stage has minimum deliverables and checklists stored in this repo so process artifacts remain discoverable and versioned.

## Workflows & quality

Teams use a standard project board (Backlog → Ready → In Progress → In Review → QA → Done) and a pull-request driven workflow emphasizing small, reviewable changes, CI-based tests and security scans, and at least one approval before merging. QA is layered: unit tests, integration tests, and smoke/end-to-end checks for critical flows, plus manual QA where needed. Releases follow a checklist with staging verification, rollback playbook, and post-deploy validation.

## Roles & communication

Roles are explicit: Product Managers define goals and success metrics, Project Managers coordinate delivery and risks, Developers implement and test, QA validates acceptance, and Stakeholders receive scheduled updates. Communication cadence includes daily standups, weekly delivery/PM syncs, sprint demos, and monthly stakeholder reports. Risk registers, incident templates, and escalation paths are provided to keep communication consistent and timely.

## Links to documents

- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Risks & Communication](docs/octoacme-risks-and-communication.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)

## Notes

- Keep this README short — link to the canonical docs above for details.
- Add this README to onboarding materials and project boards for easier discoverability.
