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

## Business Analysts

### Role Summary
Business Analysts bridge the gap between stakeholder needs and the development team. They translate business requirements into clear, actionable specifications that guide product and engineering decisions.

### Responsibilities
- Elicit, document, and validate business and functional requirements
- Facilitate requirements workshops with stakeholders and product teams
- Produce user stories, process flows, and acceptance criteria
- Analyze gaps between current and desired business processes
- Support UAT by aligning test cases with business requirements

### Goals
- Ensure that delivered solutions address genuine business problems
- Reduce rework caused by ambiguous or missing requirements
- Maintain a shared understanding of scope across stakeholders and the delivery team

### Typical Communication
- Requirements review sessions with Product Managers and Developers
- Process flow diagrams and business requirements documents (BRDs)
- Participation in sprint reviews to verify delivered functionality matches intent

### Interactions
- Works closely with **Product Managers** to refine backlog items and success metrics
- Provides **Developers** with detailed acceptance criteria and use-case context
- Coordinates with **QA Specialists** to ensure test cases cover all business scenarios
- See [Project Planning](octoacme-project-planning.md) for how requirements feed into sprint planning

---

## UX/UI Designers

### Role Summary
UX/UI Designers own the user experience and interface design, ensuring that product features are intuitive, accessible, and aligned with customer needs and brand standards.

### Responsibilities
- Conduct user research, usability testing, and competitive analysis
- Create wireframes, prototypes, and high-fidelity mockups
- Define and maintain the design system and UI component library
- Collaborate with Product Managers on feature discovery and prioritization
- Review implemented UI against design specifications and provide feedback

### Goals
- Deliver experiences that are usable, accessible, and delightful
- Reduce usability issues discovered late in the delivery cycle
- Maintain design consistency across the product surface area

### Typical Communication
- Design critiques and prototype review sessions
- Annotated mockups and design handoff documentation (e.g., Figma links)
- Participation in sprint planning and backlog refinement

### Interactions
- Partners with **Product Managers** to translate user needs into design solutions
- Collaborates with **Developers** during implementation to ensure design fidelity
- Shares usability findings with **Business Analysts** to refine requirements
- See [Project Initiation Guide](octoacme-project-initiation.md) for how design discovery fits into project kick-off

---

## DevOps Engineers

### Role Summary
DevOps Engineers manage infrastructure, CI/CD pipelines, and deployment processes. They enable reliable, repeatable, and fast delivery of software to production environments.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and automation tooling
- Manage cloud or on-premises infrastructure using infrastructure-as-code
- Monitor system health, performance, and security posture
- Define and enforce deployment gates, rollback procedures, and change controls
- Collaborate with Developers to resolve environment and build issues

### Goals
- Maximize deployment frequency while minimizing failure rate and recovery time
- Reduce manual toil through automation
- Ensure environments are secure, stable, and reproducible

### Typical Communication
- Deployment run-books and infrastructure documentation
- Incident reports and post-mortems
- Participation in release planning and change-advisory discussions

### Interactions
- Works with **Developers** to integrate automated testing and quality gates into pipelines
- Coordinates with **Project Managers** on release schedules and deployment windows
- Partners with **QA Specialists** to provision stable test environments
- See [Release & Deployment Guide](octoacme-release-and-deployment.md) for deployment workflow details

---

## Quality Assurance Specialists

### Role Summary
Quality Assurance Specialists ensure that delivered features meet acceptance criteria, functional requirements, and quality standards before release. They advocate for quality throughout the project lifecycle.

### Responsibilities
- Define test strategies, test plans, and test cases based on acceptance criteria
- Execute functional, regression, integration, and exploratory testing
- Log, triage, and track defects through to resolution
- Participate in sprint planning to assess testability of requirements
- Collaborate on automation frameworks to improve test coverage and speed

### Goals
- Prevent defects from reaching production
- Shorten feedback loops between development and quality validation
- Maintain a clear and up-to-date picture of product quality

### Typical Communication
- Test plans and results shared with Project and Product Managers
- Bug reports with reproduction steps, severity, and priority
- Participation in sprint reviews and release go/no-go decisions

### Interactions
- Aligns with **Business Analysts** to ensure test cases reflect business intent
- Works with **Developers** to reproduce and resolve defects quickly
- Coordinates with **DevOps Engineers** on test environment stability and pipeline integration
- See [Execution & Tracking](octoacme-execution-and-tracking.md) for how QA gates fit into sprint delivery

---

## Customer Support Leads

### Role Summary
Customer Support Leads collect and channel feedback from end users back to the product and project teams, ensuring that real-world issues and user pain points inform ongoing development priorities.

### Responsibilities
- Triage incoming support requests and identify recurring themes or critical bugs
- Escalate high-impact issues to Product Managers and Project Managers
- Maintain a feedback loop between end users and the delivery team
- Contribute to release communications, FAQs, and user-facing documentation
- Participate in release reviews to prepare support teams for new functionality

### Goals
- Minimize user-facing disruption and unresolved issues
- Ensure the delivery team has visibility into real-world product usage and pain points
- Reduce time-to-resolution for critical customer issues

### Typical Communication
- Weekly support trend reports shared with Product and Project Managers
- Escalation tickets linked to backlog items for prioritization
- Pre-release briefings and post-release monitoring reports

### Interactions
- Provides **Product Managers** with qualitative and quantitative feedback to inform prioritization
- Coordinates with **Project Managers** on escalation paths and communication plans
- Works with **QA Specialists** to reproduce user-reported issues
- See [Risk Management & Communication](octoacme-risks-and-communication.md) for escalation procedures

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

