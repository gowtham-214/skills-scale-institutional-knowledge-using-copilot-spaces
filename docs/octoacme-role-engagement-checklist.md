# OctoAcme — Role Engagement Checklist

## Purpose
Use this checklist to quickly decide which personas should be actively involved for a piece of work, and where ownership is primary vs. shared. This complements the detailed guidance in [Roles and personas](./octoacme-roles-and-personas.md).

## How to use
1. Start in planning and identify the personas required by scope, risk, and complexity.
2. Mark one role as **Primary Owner** per decision or artifact.
3. Mark other roles as **Contributors** when they provide required input or approvals.
4. Confirm handoffs are explicit in backlog items, sprint plans, or release checklists.

## Engagement triggers
- **Technical complexity or architecture risk:** involve Technical Lead and Engineering Manager.
- **Cross-team delivery dependencies:** involve Delivery Lead and Project Manager.
- **User-facing workflow changes:** involve UX Researcher / Designer.
- **Reliability, scale, or production risk:** involve SRE / Production Engineer.
- **Security/privacy/compliance sensitivity:** involve Security Lead.
- **Production release with operational risk:** involve Release Engineer.
- **Metric-driven launch validation:** involve Data Analyst / Analytics Engineer.
- **Complex business logic or policy constraints:** involve Business Analyst / Domain SME.
- **Customer-impacting incident patterns or escalations:** involve Customer Success / Support Liaison.

## Lightweight responsibility matrix (by lifecycle phase)
| Lifecycle phase | Primary owner(s) | Key contributors |
| --- | --- | --- |
| Initiation | Product Manager, Project Manager | Business Analyst / Domain SME, Customer Success / Support Liaison, Engineering Manager |
| Planning | Project Manager, Product Manager | Technical Lead, Delivery Lead, UX Researcher / Designer, QA/Testing, Business Analyst / Domain SME |
| Execution | Developers, Delivery Lead | Technical Lead, Project Manager, QA/Testing, UX Researcher / Designer, Security Lead |
| Release readiness | Release Engineer, Project Manager | SRE / Production Engineer, QA/Testing, Technical Lead, Security Lead |
| Post-release validation | Product Manager, Data Analyst / Analytics Engineer | Customer Success / Support Liaison, Project Manager, Developers, SRE / Production Engineer |
| Retrospective and improvement | Project Manager, Engineering Manager | Delivery Lead, Product Manager, Technical Lead, Stakeholders |

## Handoff checklist
- [ ] Scope handoff: Product Manager + Business Analyst / Domain SME to Developers and QA/Testing
- [ ] Design handoff: UX Researcher / Designer to Developers and QA/Testing (with acceptance expectations)
- [ ] Technical handoff: Technical Lead to implementation owners (architecture notes, constraints, risks)
- [ ] Release handoff: Delivery Lead + Project Manager to Release Engineer and SRE (window, rollback, comms)
- [ ] Security handoff: Security Lead remediation guidance included in backlog and release criteria
- [ ] Measurement handoff: Data Analyst instrumentation plan linked to acceptance and post-release review
- [ ] Support handoff: Customer Success / Support Liaison escalation paths and triage expectations documented
