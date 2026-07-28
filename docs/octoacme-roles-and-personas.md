# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Operational & Specialist Roles

To reduce ambiguity and improve handoffs across planning, execution, release, and incident workflows, add the following operational and specialist personas. For each persona we define a short Role summary, Responsibilities, and Interactions with existing roles.

### Release Manager

Role summary: Coordinates and owns the release process for features and fixes.

Responsibilities:
- Create and maintain the release checklist
- Schedule deployment windows and coordinate stakeholders
- Verify pre-release gating (CI, smoke tests, backups)
- Coordinate rollback and mitigation plans
- Communicate release status and post-release verification

Interactions:
- PM / PdM: approves release timing and stakeholder communications
- Developers: ensures build readiness and addresses release blockers
- QA: validates release acceptance criteria and sign-off
- Platform/DevOps: executes or automates deployments
- Support/On-call: prepares monitoring and incident handoff

---

### Security Engineer

Role summary: Ensures security considerations are integrated into planning, code, and releases.

Responsibilities:
- Conduct security reviews and threat modeling for features
- Run vulnerability scanning and static analysis
- Recommend mitigations and track security issues
- Support incident response for security events

Interactions:
- Developers: advise on secure design and code fixes
- PM / PdM: contribute to risk assessment and prioritization
- Platform/DevOps: ensure secure configurations and secrets management
- Sponsor/Product Lead: escalate high-impact security decisions

---

### Data Analyst / Metrics Owner

Role summary: Defines success metrics and provides data-driven insights.

Responsibilities:
- Define success metrics and dashboards
- Validate telemetry and metric instrumentation
- Analyze feature outcomes and produce reports
- Support A/B testing and experimentation analysis

Interactions:
- Product Manager: define and validate success criteria
- Developers: collaborate to implement instrumentation
- PM: provide reporting for status updates and retrospectives

---

### Support Liaison / Customer Success Representative

Role summary: Represents customer-facing concerns and channels feedback into the delivery process.

Responsibilities:
- Triage incoming customer issues and surface priorities
- Provide early feedback from customers and support teams
- Prepare customer communications for releases and incidents
- Assist in reproducing and prioritizing customer-impacting bugs

Interactions:
- PM / PdM: align on customer messaging and priorities
- Developers: provide context and steps to reproduce issues
- Release Manager: coordinate customer-facing release notes and timing

---

### Platform / DevOps Engineer

Role summary: Owns platform reliability, CI/CD pipelines, and deployment automation.

Responsibilities:
- Maintain and improve CI/CD pipelines
- Ensure platform reliability, observability, and infra-as-code
- Support deployments, rollouts, and rollback strategies
- Optimize build and release automation

Interactions:
- Developers: support build and runtime environments
- Release Manager: execute or validate deployment plans
- Security Engineer: implement secure platform configurations

---

### QA Lead / Test Architect

Role summary: Defines and enforces testing strategy to ensure release quality.

Responsibilities:
- Define test strategy and coverage goals
- Maintain automated test suites and test environments
- Coordinate manual acceptance testing and QA sign-off
- Ensure testability is considered during design

Interactions:
- Developers: collaborate on testability and fixing test failures
- Release Manager: confirm QA sign-off before release
- PM / PdM: ensure acceptance criteria are verifiable

---

### Accessibility Specialist (if applicable)

Role summary: Ensures products meet accessibility standards and inclusion goals.

Responsibilities:
- Review designs and implementations for accessibility
- Define accessibility acceptance criteria and test cases
- Recommend remediation and verify fixes

Interactions:
- Product and UX teams: contribute accessibility requirements
- Developers: provide remediation guidance and verification
- QA: include accessibility checks in testing

---

## Suggested placement
Append this section to the existing "Personas" doc under a new heading titled "Additional Operational & Specialist Roles". Each entry should include Role summary, Responsibilities, and Interactions.

## Related
- Related issue: #4
