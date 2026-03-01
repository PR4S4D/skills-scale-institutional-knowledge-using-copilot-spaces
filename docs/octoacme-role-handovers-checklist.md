# OctoAcme Role Handovers Checklist

This checklist documents key collaboration touchpoints between personas across the OctoAcme project lifecycle. Use it to ensure clear handoffs, shared context, and accountability at each stage.

For full role definitions see [Roles and Personas](octoacme-roles-and-personas.md).

---

## 1. Project Initiation

| Touchpoint | From | To | Action |
|---|---|---|---|
| Stakeholder registry created | Stakeholder Engagement Specialist | Project Manager | Share initial stakeholder map and engagement plan |
| Initial risk identification | Risk Manager | Project Manager | Log risks in Risk Register with owners and initial mitigation notes |
| Comms plan drafted | Communications Lead | Project Manager | Agree on communication cadence, channels, and templates |
| Quality criteria defined | QA Coordinator | Product Manager | Align on Definition of Done and acceptance criteria before backlog is built |

---

## 2. Project Planning

| Touchpoint | From | To | Action |
|---|---|---|---|
| Backlog risk review | Risk Manager | Engineering Lead | Flag technical risks tied to scope; confirm mitigation owners |
| Stakeholder input on priorities | Stakeholder Engagement Specialist | Product Manager | Deliver synthesized stakeholder feedback to inform backlog ranking |
| Kickoff comms drafted | Communications Lead | Project Manager | Prepare and distribute kickoff announcement to all stakeholder groups |
| Release quality gates set | QA Coordinator | Release Coordinator | Define quality gate criteria (CI, security scans, test coverage) for each milestone |

---

## 3. Execution & Tracking

| Touchpoint | From | To | Action |
|---|---|---|---|
| Weekly risk status update | Risk Manager | Project Manager | Review Risk Register; escalate any new high-impact risks |
| Quality gate checkpoint | QA Coordinator | Developers | Review test coverage, defect rates, and Definition of Done compliance per sprint |
| Stakeholder feedback synthesis | Stakeholder Engagement Specialist | Product Manager | Deliver feedback summaries after demos or structured engagement sessions |
| Status communications | Communications Lead | All stakeholders | Distribute weekly status update using standard template |
| Blocker escalation | Project Manager | Sponsor / Product Lead | Escalate unresolved blockers per the escalation path defined in [Risk Management & Communication](octoacme-risks-and-communication.md) |

---

## 4. Release & Deployment

| Touchpoint | From | To | Action |
|---|---|---|---|
| Go/no-go quality sign-off | QA Coordinator | Release Coordinator | Confirm all quality gates are met before release approval |
| Release risk review | Risk Manager | Project Manager + Release Coordinator | Review release-blocking risks; confirm rollback plan is in place |
| Release announcement | Communications Lead | All stakeholders | Draft and distribute release notes and deployment announcement |
| Stakeholder readiness check | Stakeholder Engagement Specialist | Project Manager | Confirm key stakeholders are informed and prepared for the release impact |

---

## 5. Retrospective & Continuous Improvement

| Touchpoint | From | To | Action |
|---|---|---|---|
| Risk retrospective | Risk Manager | Project Manager | Summarize what risks materialized, how mitigation performed, and lessons learned |
| Quality retrospective | QA Coordinator | Project Manager + Developers | Review quality metrics and propose Definition of Done improvements |
| Stakeholder satisfaction review | Stakeholder Engagement Specialist | Product Manager + Project Manager | Share stakeholder satisfaction feedback and engagement gaps identified |
| Comms retrospective | Communications Lead | Project Manager | Assess communication effectiveness; recommend cadence or channel improvements |
| Action items tracked | Project Manager | All roles | Log retrospective action items in the project backlog and assign owners |

---

## Quick Reference: RACI Summary

| Activity | Project Manager | Risk Manager | Communications Lead | QA Coordinator | Stakeholder Engagement Specialist | Product Manager |
|---|---|---|---|---|---|---|
| Risk Register maintenance | A | R | I | I | I | I |
| Stakeholder communications | A | I | R | I | C | I |
| Quality gate sign-off | A | I | I | R | I | C |
| Stakeholder feedback synthesis | I | I | C | I | R | A |
| Project status reporting | R | C | R | I | I | I |
| Release go/no-go | A | C | C | C | I | I |

**Key:** R = Responsible, A = Accountable, C = Consulted, I = Informed
