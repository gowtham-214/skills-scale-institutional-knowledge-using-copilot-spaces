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

## Technical Lead (Tech Lead)

### Role Summary
Technical Leads guide architecture and implementation approaches so teams can deliver safely and efficiently. They connect day-to-day engineering execution with product and delivery goals.

### Responsibilities
- Lead technical design decisions and architecture alignment
- Define engineering standards for quality, testing, and maintainability
- Surface and mitigate technical risks early
- Support developers through design reviews and implementation guidance

### Goals
- Keep technical direction coherent across features and teams
- Reduce rework caused by unclear architecture decisions
- Balance delivery speed with long-term system health

### Typical Communication
- Design reviews and architecture discussions with Developers
- Trade-off conversations with Product Managers and Project Managers
- Risk escalation discussions with Engineering Manager when needed

### When to involve this role
- New capabilities require non-trivial architecture changes
- Teams are making platform, dependency, or integration decisions
- Delivery plans carry elevated technical risk or uncertainty

### Collaboration with existing roles
- Partners with Project Managers on technical risk and sequencing impacts
- Works with Product Managers to align scope with technical constraints
- Coaches Developers and supports QA/Testing with test strategy decisions
- Provides technical updates to Stakeholders and Sponsors for high-impact decisions

---

## Engineering Manager

### Role Summary
Engineering Managers own team health, capacity, and delivery sustainability. They ensure people, process, and staffing support predictable execution.

### Responsibilities
- Manage team capacity, staffing, and priority trade-offs
- Support career growth, coaching, and performance management
- Remove organizational blockers and resolve resource conflicts
- Partner on hiring and onboarding for delivery-critical roles

### Goals
- Maintain a sustainable team pace and delivery reliability
- Improve team effectiveness and retention
- Ensure capacity plans match roadmap commitments

### Typical Communication
- Weekly planning and staffing syncs with Project Managers
- Regular one-on-ones and team health reviews with Developers
- Escalation and resourcing updates with Sponsors and Stakeholders

### When to involve this role
- Delivery plans require major scope/capacity rebalancing
- Team-level blockers cannot be resolved within sprint ceremonies
- Organizational dependencies impact roadmap commitments

### Collaboration with existing roles
- Works with Project Managers and Product Managers on realistic planning
- Supports Technical Leads in sequencing technically complex work
- Aligns with QA/Testing leads on coverage capacity and release readiness
- Communicates staffing and risk impacts to Stakeholders and Sponsors

---

## Delivery Lead

### Role Summary
Delivery Leads coordinate sprint-level execution across functions to keep commitments on track. They provide operational clarity on dependencies, handoffs, and blockers.

### Responsibilities
- Orchestrate day-to-day delivery across engineering, product, and QA
- Track dependency status and unblock cross-team work
- Maintain delivery boards and milestone visibility
- Drive follow-through on action items from planning and retrospectives

### Goals
- Improve predictability and flow of committed work
- Reduce delays from unclear handoffs
- Keep delivery status transparent for all contributors

### Typical Communication
- Daily/weekly coordination with Developers and QA/Testing
- Milestone and dependency updates with Project Managers
- Cross-functional check-ins with Product Managers and Stakeholders

### When to involve this role
- Multiple teams or workstreams must converge on one release
- Handoffs between product, engineering, and QA are causing delays
- There is a need for tighter operational cadence during critical milestones

### Collaboration with existing roles
- Complements Project Manager planning with execution-level orchestration
- Partners with Product Managers to sequence scope for delivery feasibility
- Coordinates Developers and QA/Testing for clear handoffs
- Shares delivery risk updates with Stakeholders and Sponsors

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers ensure solutions are usable, accessible, and aligned with user needs. They reduce delivery risk by validating assumptions before and during implementation.

### Responsibilities
- Run user research and synthesize findings into actionable guidance
- Design interaction flows and UI artifacts for implementation
- Define usability acceptance considerations with Product Managers
- Validate implemented experiences through testing and feedback

### Goals
- Increase user adoption and task success rates
- Reduce rework caused by usability gaps
- Improve outcome quality for customer-facing features

### Typical Communication
- Discovery and design review sessions with Product Managers
- Design handoff sessions with Developers and QA/Testing
- Insight sharing with Project Managers and Stakeholders

### When to involve this role
- Teams are introducing new user journeys or major interface changes
- Requirements include high usability or accessibility expectations
- Product decisions depend on user behavior evidence

### Collaboration with existing roles
- Works with Product Managers to shape requirements and success criteria
- Partners with Developers on design feasibility and implementation intent
- Aligns with QA/Testing on usability validation scenarios
- Provides user-impact context to Stakeholders and Sponsors

---

## Site Reliability Engineer (SRE) / Production Engineer

### Role Summary
SREs and Production Engineers focus on runtime reliability, scalability, and incident readiness. They help teams ship features that meet availability and operational expectations.

### Responsibilities
- Define and track service-level objectives and reliability indicators
- Improve observability, alerting, and operational runbooks
- Support incident response and post-incident follow-up actions
- Advise on architecture and delivery decisions that affect operability

### Goals
- Improve service availability and recovery outcomes
- Detect and resolve production issues faster
- Reduce operational risk during releases

### Typical Communication
- Reliability planning with Developers and Technical Leads
- Release risk coordination with Release Engineers and Project Managers
- Incident and postmortem updates with Stakeholders and Sponsors

### When to involve this role
- Features significantly change scale, latency, or system criticality
- Teams plan high-risk production changes or migrations
- Recurring incidents indicate reliability debt

### Collaboration with existing roles
- Partners with Developers and Technical Leads on resilient implementation
- Coordinates with Release Engineers on rollout and rollback readiness
- Works with Project Managers on risk communication and mitigation plans
- Supports QA/Testing with production-like validation requirements

---

## Security Lead

### Role Summary
Security Leads ensure delivery plans and implementations account for security and compliance expectations. They reduce risk by embedding secure-by-default practices across the lifecycle.

### Responsibilities
- Lead threat modeling and security design reviews
- Define and track remediation priorities for security findings
- Guide secure coding and dependency risk practices
- Support incident triage and security-related escalations

### Goals
- Prevent high-impact vulnerabilities in delivered features
- Shorten time-to-remediate for identified risks
- Increase confidence in compliance and audit readiness

### Typical Communication
- Security review checkpoints with Developers and Technical Leads
- Risk and remediation alignment with Project Managers
- High-severity updates with Stakeholders and Sponsors

### When to involve this role
- Features process sensitive data or introduce new trust boundaries
- External integrations change authentication or authorization posture
- Security findings affect release readiness or customer risk

### Collaboration with existing roles
- Works with Product Managers to align requirements with security needs
- Partners with Developers and QA/Testing on verification and remediation
- Coordinates with Project Managers on timelines for security gates
- Briefs Stakeholders and Sponsors on high-impact risk decisions

---

## Release Engineer

### Role Summary
Release Engineers manage release mechanics and automation so deployments are repeatable and low-risk. They provide structure for preparing, validating, and rolling out changes.

### Responsibilities
- Maintain and improve CI/CD pipelines and release automation
- Define release readiness checks and deployment runbooks
- Coordinate rollout windows, rollback plans, and post-release validation
- Track release process issues and drive improvements

### Goals
- Increase release frequency with stable quality
- Decrease release failures and rollback duration
- Improve confidence in deployment predictability

### Typical Communication
- Release readiness reviews with Project Managers and QA/Testing
- Pipeline and deployment coordination with Developers and SREs
- Release status communication to Stakeholders and Sponsors

### When to involve this role
- Teams prepare production releases with multiple dependencies
- Delivery requires phased rollout, feature flags, or rollback safeguards
- Pipeline instability is affecting delivery timelines

### Collaboration with existing roles
- Partners with Project Managers on release plans and go/no-go checkpoints
- Works with Developers and QA/Testing for build and validation readiness
- Coordinates with SREs on production rollout and monitoring expectations
- Shares release outcomes and incident learnings with Stakeholders and Sponsors

---

## Data Analyst / Analytics Engineer

### Role Summary
Data Analysts and Analytics Engineers enable evidence-based delivery decisions. They define, instrument, and analyze metrics to validate whether shipped work achieves intended outcomes.

### Responsibilities
- Define success metrics and measurement plans with Product Managers
- Specify and validate instrumentation requirements with Developers
- Build analysis views and reports for delivery and product outcomes
- Identify data quality issues that impact decision-making confidence

### Goals
- Improve signal quality for prioritization and iteration decisions
- Validate product and delivery outcomes quickly after release
- Reduce ambiguity in performance and adoption reporting

### Typical Communication
- Metrics planning with Product Managers and Project Managers
- Instrumentation handoff sessions with Developers
- Outcome reporting to Stakeholders and Sponsors

### When to involve this role
- Features rely on KPI movement or behavior-based validation
- Teams need experiment or launch measurement plans
- Existing telemetry is insufficient for decision-making

### Collaboration with existing roles
- Works with Product Managers to define value and success indicators
- Partners with Developers on event tracking implementation
- Aligns with Project Managers on reporting cadence and milestones
- Supports Stakeholders and Sponsors with decision-ready insights

---

## Business Analyst / Domain SME

### Role Summary
Business Analysts and Domain SMEs translate domain context into clear, actionable requirements. They help teams avoid misinterpretation of business rules, workflows, and constraints.

### Responsibilities
- Clarify business processes, rules, and edge cases
- Refine requirements into testable acceptance criteria
- Validate delivered behavior against domain expectations
- Surface compliance, policy, or operational constraints early

### Goals
- Improve requirement quality and reduce rework
- Minimize defects caused by domain misunderstandings
- Accelerate team decisions where business context is critical

### Typical Communication
- Backlog refinement sessions with Product Managers and Project Managers
- Requirement clarification with Developers and QA/Testing
- Domain impact discussions with Stakeholders and Sponsors

### When to involve this role
- Work involves complex business logic, policy, or regulatory nuance
- Teams encounter repeated requirement ambiguity during implementation
- Acceptance disputes occur because expected behavior is unclear

### Collaboration with existing roles
- Supports Product Managers with requirement precision and prioritization
- Works with Developers and QA/Testing to clarify edge cases
- Partners with Project Managers on scope clarity and change impact
- Aligns Stakeholders and Sponsors on domain trade-offs

---

## Customer Success / Support Liaison

### Role Summary
Customer Success and Support Liaisons represent real customer impact in delivery decisions. They connect implementation work to support trends, adoption outcomes, and user pain points.

### Responsibilities
- Provide customer pain points, support signals, and adoption context
- Help prioritize fixes and improvements based on user impact
- Coordinate reproduction details and escalation quality for defects
- Share post-release feedback and operational learnings

### Goals
- Reduce customer-facing incidents and unresolved pain points
- Improve prioritization based on real-world impact
- Strengthen feedback loops between delivery teams and users

### Typical Communication
- Issue triage and impact reviews with Project Managers and Product Managers
- Reproduction and validation collaboration with Developers and QA/Testing
- Customer-impact summaries for Stakeholders and Sponsors

### When to involve this role
- Support volume or severity indicates urgent customer-impacting issues
- Teams need direct customer context for prioritization decisions
- Post-release feedback must inform rapid iteration

### Collaboration with existing roles
- Works with Product Managers on customer-informed prioritization
- Partners with Project Managers on escalation handling and communication
- Coordinates with Developers and QA/Testing to improve issue reproduction
- Helps Stakeholders and Sponsors understand customer outcomes

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
