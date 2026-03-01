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
Project Managers coordinate delivery activities, manage schedules, dependencies, and overall project health. They enable the team to deliver on commitments efficiently and serve as the central coordination point across all functional roles.

### Responsibilities
- Create and maintain project plans, timelines, and milestones
- Own dependency tracking and resource constraint management
- Facilitate key meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Escalate unresolved issues to sponsors or leadership
- Delegate risk ownership to the Risk Manager and communication execution to the Communications Lead

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Decision logs and dependency tracking
- Coordination via project boards and meeting facilitation

---

## Risk Manager

### Role Summary
The Risk Manager proactively identifies, assesses, and monitors project risks throughout the project lifecycle. They maintain the Risk Register, coordinate mitigation actions, and escalate critical risks to the Project Manager.

### Responsibilities
- Maintain and update the Risk Register (ID, description, impact, likelihood, owner, mitigation, status)
- Facilitate risk identification sessions with team leads and stakeholders
- Define and track mitigation plans and contingency strategies
- Report risk status at weekly syncs and milestone reviews
- Escalate high-impact risks to the Project Manager promptly

### Goals
- Minimize the likelihood and impact of project risks
- Ensure risks are visible, owned, and actively mitigated
- Build a proactive risk culture across the project team

### Typical Communication
- Weekly risk status updates in project syncs
- Risk Register updates shared with the Project Manager and Engineering Lead
- Ad-hoc escalations for newly identified high-impact risks

### Interactions with Existing Roles
- **Project Manager**: Reports risk status; escalates risks that require schedule, scope, or resource decisions.
- **Engineering Lead / Developers**: Collects technical risk inputs; validates mitigation feasibility.
- **Communications Lead**: Coordinates messaging for stakeholder-facing risk updates.
- **Release Coordinator**: Aligns on release-blocking risks and go/no-go criteria.
- **Product Manager**: Surfaces risks that may affect backlog priorities or customer commitments.

---

## Communications Lead

### Role Summary
The Communications Lead designs and manages the project's communication strategy, ensuring timely, accurate, and consistent information flow to all team members and stakeholders throughout the project lifecycle.

### Responsibilities
- Develop and maintain the project communications plan
- Draft and distribute key project announcements, status updates, and milestone summaries
- Maintain a log of key decisions and communications artifacts
- Coordinate with the Project Manager on the cadence and content of stakeholder updates
- Ensure communication channels (e.g., channels, wikis, email) are current and accessible

### Goals
- Ensure every stakeholder receives the right information at the right time
- Reduce information gaps and miscommunication-driven delays
- Build and maintain trust through transparent, consistent updates

### Typical Communication
- Weekly project status newsletters or channel posts
- Milestone and release announcements
- Decision log updates and meeting summaries

### Interactions with Existing Roles
- **Project Manager**: Translates project status into stakeholder-ready communications; aligns on messaging priorities.
- **Risk Manager**: Crafts and distributes stakeholder-appropriate risk updates and escalation notices.
- **Stakeholder Engagement Specialist**: Coordinates the timing and channel selection for stakeholder touchpoints.
- **Product Manager**: Incorporates product roadmap updates and feature announcements into communications.
- **Release Coordinator**: Produces release notes and deployment announcements for end users and internal teams.

---

## Quality Assurance Coordinator

### Role Summary
The Quality Assurance Coordinator defines, maintains, and monitors quality standards across the project. They work with development and release teams to embed quality checkpoints throughout the delivery lifecycle rather than treating quality as a final gate.

### Responsibilities
- Develop and maintain quality control checklists, review criteria, and the Definition of Done
- Design and schedule QA review cycles in alignment with sprint and release milestones
- Track quality metrics (e.g., defect rates, test coverage, acceptance criteria pass rates)
- Facilitate quality retrospective reviews and communicate findings to the team
- Escalate quality blockers to the Project Manager before they impact release timelines

### Goals
- Ensure all deliverables meet defined acceptance criteria and quality standards
- Shift quality left by integrating checks early in the development cycle
- Continuously improve quality practices based on retrospective learnings

### Typical Communication
- QA status updates in sprint reviews and weekly delivery syncs
- Quality checklists and review reports shared with developers and the Release Coordinator
- Escalation notices when quality gates are at risk

### Interactions with Existing Roles
- **Developers**: Collaborates on test coverage requirements, review criteria, and defect triage.
- **Release Coordinator**: Ensures quality gates (CI passing, security scans, smoke tests) are met before deployment.
- **Project Manager**: Escalates quality blockers that may affect milestones or scope.
- **Product Manager**: Aligns quality criteria with acceptance criteria and customer expectations.
- **Engineering Lead**: Partners on technical quality standards, code review policies, and test infrastructure.

---

## Stakeholder Engagement Specialist

### Role Summary
The Stakeholder Engagement Specialist ensures that stakeholder interests, needs, and feedback are actively gathered, synthesized, and integrated throughout the project lifecycle. They bridge the gap between the project team and its broader stakeholder community.

### Responsibilities
- Map and maintain the stakeholder registry, including communication preferences and engagement levels
- Design structured feedback loops (surveys, interviews, demos, advisory reviews)
- Synthesize stakeholder input and present actionable summaries to the Project Manager and Product Manager
- Represent stakeholder perspectives in planning, retrospectives, and scope discussions
- Monitor stakeholder satisfaction and flag engagement risks early

### Goals
- Ensure stakeholder voices are heard and reflected in project decisions
- Build strong stakeholder relationships that support project adoption and success
- Reduce rework caused by misaligned stakeholder expectations

### Typical Communication
- Stakeholder registry and engagement plan maintained throughout the project
- Feedback summaries shared after each structured engagement activity
- Escalation to the Project Manager when stakeholder alignment is at risk

### Interactions with Existing Roles
- **Product Manager**: Channels stakeholder feedback into backlog prioritization and feature scoping.
- **Project Manager**: Surfaces engagement risks and alignment gaps that may affect project outcomes.
- **Communications Lead**: Coordinates timing and targeting of stakeholder communications and update cycles.
- **Risk Manager**: Flags stakeholder-driven risks (e.g., resistance, misaligned expectations) for the Risk Register.
- **Developers**: Facilitates demos and feedback sessions that inform acceptance criteria and iteration priorities.

---

## Example: Risk Escalation Scenario

This scenario illustrates how the new personas collaborate during a typical risk escalation flow:

1. **Risk Manager** identifies a critical third-party API dependency risk during sprint planning and logs it in the Risk Register.
2. **Risk Manager** notifies the **Engineering Lead** to assess technical feasibility of the mitigation (fallback implementation).
3. **Risk Manager** escalates to the **Project Manager** with a recommended mitigation plan and timeline impact.
4. **Communications Lead** drafts a stakeholder-ready risk update, reviewed by the **Project Manager**, and distributes it via the project status channel.
5. **Stakeholder Engagement Specialist** gathers stakeholder feedback on the proposed mitigation approach during the next advisory check-in.
6. **Quality Assurance Coordinator** updates the release quality gate checklist to include validation of the fallback path before deployment.
7. **Project Manager** reviews the updated Risk Register and confirms the go/no-go criteria with the **Release Coordinator**.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [Role Handovers Checklist](octoacme-role-handovers-checklist.md) for key collaboration touchpoints between personas across the project lifecycle.

