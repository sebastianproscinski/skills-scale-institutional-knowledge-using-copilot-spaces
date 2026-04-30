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

## UX Designer

### Role Summary
UX Designers create user-centered workflows, wireframes, and interface designs that translate product requirements into intuitive experiences. They advocate for the end user throughout the delivery lifecycle.

### Responsibilities
- Design user flows, wireframes, and high-fidelity mockups
- Conduct usability testing and synthesize findings into actionable recommendations
- Maintain a design system and ensure visual consistency across features
- Collaborate on acceptance criteria to include usability and accessibility standards
- Participate in sprint reviews to validate that implemented features meet design intent

### Goals
- Deliver experiences that are intuitive, accessible, and aligned with user needs
- Reduce rework caused by late-stage usability issues
- Bridge the gap between business requirements and technical implementation through clear design artifacts

### Typical Communication
- Design reviews and handoff sessions with Developers
- Usability findings and iteration notes shared with Product Managers
- Sprint demos to gather team and stakeholder feedback on prototypes

### Interaction Points
- **Developers**: Provide annotated designs and design tokens; review implemented UI for fidelity; answer implementation questions during development.
- **Product Managers**: Collaborate on problem framing, user research, and acceptance criteria; validate designs against product goals.
- **Project Managers**: Communicate design milestone readiness; flag design-driven scope or timeline risks early.

---

## Business Analyst

### Role Summary
Business Analysts bridge business needs and technical solutions by translating stakeholder requirements into clear, structured documentation that guides delivery teams.

### Responsibilities
- Elicit, document, and validate business and functional requirements
- Create use cases, user stories, and process flow diagrams
- Facilitate requirements workshops with stakeholders and delivery teams
- Perform gap analysis between current-state and target-state processes
- Support acceptance testing by clarifying requirements and verifying outcomes

### Goals
- Eliminate ambiguity in requirements before development begins
- Reduce the number of mid-sprint requirement changes
- Ensure traceability from business objectives to delivered features

### Typical Communication
- Requirements documents, user story briefs, and process diagrams shared with Product Managers and Developers
- Stakeholder interview summaries and workshop outputs
- Questions and clarification requests surfaced in sprint planning and backlog grooming

### Interaction Points
- **Developers**: Provide detailed requirements and answer clarifying questions during implementation; participate in demos to confirm business intent is met.
- **Product Managers**: Collaborate on backlog refinement and feature scope; validate requirements against product vision and success metrics.
- **Project Managers**: Flag requirement risks or dependencies that affect timelines; contribute to risk register entries related to scope ambiguity.

---

## QA Automation Engineer

### Role Summary
QA Automation Engineers design, build, and maintain automated test suites that validate product quality at speed and scale. They embed quality practices throughout the delivery pipeline.

### Responsibilities
- Design and implement automated test frameworks (unit, integration, end-to-end)
- Maintain test coverage metrics and report quality trends to the team
- Collaborate with Developers on testability and CI pipeline integration
- Define and uphold test entry/exit criteria aligned with the Definition of Done
- Investigate and triage flaky tests; escalate critical defects with clear reproduction steps

### Goals
- Increase release confidence by maximizing repeatable, automated test coverage
- Reduce manual regression overhead and shorten feedback loops
- Surface quality issues as early as possible in the development cycle

### Typical Communication
- Test plans and coverage reports shared with Product Managers and Project Managers
- Defect reports and regression summaries in sprint reviews
- CI/CD pipeline status updates and quality gate alerts for Developers

### Interaction Points
- **Developers**: Partner on test design and code-level testability; review PRs for test coverage; pair on reproducing and fixing defects.
- **Product Managers**: Align on acceptance criteria and Definition of Done; surface quality signals that may affect release decisions.
- **Project Managers**: Report test status and quality risks; provide input for release readiness assessments.

---

## DevOps Engineer

### Role Summary
DevOps Engineers design, operate, and optimize the infrastructure, CI/CD pipelines, and platform tooling that enable fast, reliable software delivery and operations.

### Responsibilities
- Build and maintain CI/CD pipelines, deployment automation, and infrastructure-as-code
- Monitor system health, set up observability tooling (logging, metrics, alerting), and coordinate incident response
- Manage environment provisioning for development, staging, and production
- Enforce security and compliance controls within the delivery pipeline
- Collaborate on release planning to ensure infrastructure readiness and rollback capability

### Goals
- Maximize deployment frequency while minimizing mean time to recovery (MTTR)
- Eliminate manual, error-prone release steps through automation
- Ensure stable, observable, and secure environments across the delivery lifecycle

### Typical Communication
- Pipeline status and environment health dashboards shared with Developers and Project Managers
- Incident reports, post-mortems, and runbooks
- Infrastructure change notifications and deployment release notes

### Interaction Points
- **Developers**: Define pipeline contracts and deployment standards; support local-dev and staging environment setup; review infrastructure-impacting code changes.
- **Product Managers**: Communicate infrastructure capacity, reliability constraints, and release window requirements that affect roadmap timing.
- **Project Managers**: Provide deployment readiness assessments; flag infrastructure risks in the risk register; coordinate release scheduling.

---

## Customer Support

### Role Summary
Customer Support acts as the voice of the customer within the delivery team, surfacing real-world feedback, documenting issues, and ensuring post-release experience meets user expectations.

### Responsibilities
- Collect, categorize, and escalate customer-reported bugs, questions, and feature requests
- Maintain a knowledge base of known issues, workarounds, and FAQs
- Participate in pre-release reviews to assess support readiness (runbooks, FAQs, training)
- Provide post-release feedback to Product and Project teams based on user impact data
- Represent user pain points in retrospectives and backlog grooming sessions

### Goals
- Reduce customer-facing defects by surfacing issues before and after release
- Minimize time-to-resolution for customer-reported problems
- Improve self-service resources so users can resolve common issues independently

### Typical Communication
- Weekly support ticket summaries and trend reports shared with Product Managers
- Bug escalations and user impact assessments sent to Project Managers and Developers
- Pre-release and post-release feedback sessions with the full delivery team

### Interaction Points
- **Developers**: Provide detailed reproduction steps for reported bugs; validate fixes address the original user issue; receive release notes for new features.
- **Product Managers**: Share user feedback and pain-point data to inform backlog prioritization; validate that new features address support-identified gaps.
- **Project Managers**: Flag high-impact customer issues that may require prioritization or escalation; contribute to post-release retrospective input.

---

## Data Analyst

### Role Summary
Data Analysts design metrics, build dashboards, and deliver insights that help the team understand product usage, measure outcomes, and make evidence-based decisions.

### Responsibilities
- Define key performance indicators (KPIs) and success metrics in collaboration with Product Managers
- Build and maintain dashboards and automated reports for product and business stakeholders
- Analyze experiment results (A/B tests, feature flags) and communicate findings clearly
- Identify trends and anomalies in product usage data and escalate actionable insights
- Ensure data quality, integrity, and documentation of analytical models

### Goals
- Enable data-driven decision-making at every stage of the delivery lifecycle
- Reduce time from data question to actionable insight
- Surface early signals of product success or failure to guide iteration

### Typical Communication
- Dashboard summaries and experiment results shared with Product Managers and Project Managers
- Ad-hoc analysis reports requested by stakeholders
- Data quality and instrumentation requirements coordinated with Developers

### Interaction Points
- **Developers**: Define event tracking and instrumentation requirements; validate that analytics integrations are implemented correctly; troubleshoot data pipeline issues.
- **Product Managers**: Collaborate on experiment design, success metrics, and interpretation of results; provide data to support roadmap and prioritization decisions.
- **Project Managers**: Contribute metrics on delivery health (cycle time, defect rates) and post-release outcome data for retrospectives and reporting.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For role handoff clarity and accountability templates, see [Cross-Functional Handoff Checklist](octoacme-cross-functional-handoff-checklist.md).

