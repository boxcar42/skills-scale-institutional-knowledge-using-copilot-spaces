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

### Interactions with Other Roles
- **Product Manager**: Clarifies feature requirements and acceptance criteria
- **Project Manager**: Provides estimates, reports progress, highlights blockers
- **QA Lead**: Collaborates on testing strategy and defect resolution
- **Business Analyst**: Requests requirement clarification during implementation
- **Release Coordinator**: Coordinates code freeze and deployment activities
- **Subject Matter Expert (SME)**: Consults on domain-specific technical decisions

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

### Interactions with Other Roles
- **Developers**: Defines features and acceptance criteria, reviews implementation
- **Project Manager**: Aligns on roadmap and priorities, manages scope changes
- **QA Lead**: Validates quality standards and acceptance criteria
- **Business Analyst**: Collaborates on requirement definition and prioritization
- **Stakeholder Lead**: Gathers stakeholder feedback, aligns on business priorities
- **Release Coordinator**: Plans release contents and timing
- **Subject Matter Expert (SME)**: Consults on domain-specific feature decisions

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

### Interactions with Other Roles
- **Product Manager**: Aligns on scope, priorities, and schedule
- **Developers**: Manages timelines, removes blockers, coordinates work
- **QA Lead**: Tracks testing progress, manages quality risks
- **Business Analyst**: Ensures requirements are documented and clear
- **Stakeholder Lead**: Provides status updates, escalates issues
- **Release Coordinator**: Aligns project milestones with release schedule
- **Subject Matter Expert (SME)**: Identifies domain-related risks and dependencies

---

## QA Lead

### Role Summary
QA Leads ensure product quality by defining test strategies, coordinating testing activities, and verifying that deliverables meet acceptance criteria and quality standards before release.

### Responsibilities
- Define and maintain test strategy and quality standards
- Review acceptance criteria and ensure testability
- Coordinate testing activities across the team
- Identify and track quality risks and defects
- Validate release readiness and sign off on deployments

### Goals
- Maintain high product quality and reliability
- Catch defects early in the development cycle
- Reduce production incidents and customer-reported issues

### Typical Communication
- Daily coordination with Developers on feature testing
- Sprint planning to review test coverage needs
- Release readiness reviews with Project Manager and Release Coordinator
- Defect triage meetings with Product Manager and Developers

### Interactions with Other Roles
- **Developers**: Collaborates on test cases, reports defects, validates fixes
- **Product Manager**: Reviews acceptance criteria, prioritizes quality improvements
- **Project Manager**: Reports testing status, highlights quality risks
- **Release Coordinator**: Confirms testing completion, validates release readiness
- **Subject Matter Expert (SME)**: Validates domain-specific test scenarios

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and technical teams by gathering, clarifying, and documenting requirements. They ensure that deliverables align with business needs and objectives.

### Responsibilities
- Elicit and document business requirements from stakeholders
- Translate business needs into clear, actionable user stories
- Create process flows, wireframes, and functional specifications
- Facilitate requirement workshops and validation sessions
- Maintain traceability between requirements and deliverables
- Support User Acceptance Testing (UAT) planning and execution

### Goals
- Ensure complete and accurate requirement documentation
- Reduce rework by clarifying requirements early
- Improve stakeholder satisfaction through effective communication

### Typical Communication
- Requirement gathering sessions with Stakeholder Lead and business users
- Backlog refinement meetings with Product Manager and Project Manager
- Clarification discussions with Developers during implementation
- UAT coordination with QA Lead and stakeholders

### Interactions with Other Roles
- **Product Manager**: Collaborates on prioritization, validates business value of features
- **Project Manager**: Provides requirement documentation, supports scope management
- **Developers**: Clarifies requirements, answers questions during implementation
- **QA Lead**: Defines acceptance criteria, supports test case development
- **Stakeholder Lead**: Gathers business needs, validates requirements
- **Subject Matter Expert (SME)**: Validates domain-specific requirements and processes

---

## Release Coordinator

### Role Summary
Release Coordinators oversee the end-to-end release process, including planning, scheduling, coordination, and communication. They ensure that releases are executed smoothly with minimal disruption.

### Responsibilities
- Create and maintain release schedules and deployment plans
- Coordinate release activities across development, QA, and operations teams
- Track release readiness and manage go/no-go decisions
- Facilitate release retrospectives to improve processes
- Maintain release documentation and runbooks
- Communicate release status and timelines to stakeholders
- Manage release-related risks and issues

### Goals
- Deliver releases on schedule with high quality
- Minimize production incidents and rollbacks
- Improve release process efficiency and predictability

### Typical Communication
- Release planning meetings with Project Manager and Product Manager
- Daily release status updates during release windows
- Go/no-go meetings with QA Lead, Developers, and stakeholders
- Post-release retrospectives with all delivery team members

### Interactions with Other Roles
- **Project Manager**: Aligns release schedule with project timelines and milestones
- **Developers**: Coordinates code freeze, deployment activities, and hotfix processes
- **QA Lead**: Validates testing completion and release readiness criteria
- **Product Manager**: Confirms feature completeness and communicates release contents
- **Stakeholder Lead**: Provides release notifications and manages stakeholder expectations
- **Business Analyst**: Reviews release documentation for business impact

---

## Subject Matter Expert (SME)

### Role Summary
Subject Matter Experts provide specialized domain knowledge to guide technical decisions, validate requirements, and ensure solutions meet industry standards and business domain needs.

### Responsibilities
- Provide domain expertise on specific business areas or technologies
- Review and validate requirements for accuracy and completeness
- Assess technical approaches for domain appropriateness
- Support problem-solving for complex domain-specific issues
- Provide training and knowledge transfer to team members
- Review documentation for technical and domain accuracy

### Goals
- Ensure solutions align with domain best practices
- Reduce technical debt through informed architectural decisions
- Improve team knowledge and self-sufficiency in the domain

### Typical Communication
- Ad-hoc consultations with Developers and Business Analysts
- Design review sessions for technical approaches
- Knowledge sharing sessions and documentation reviews
- Escalation support for complex domain issues

### Interactions with Other Roles
- **Business Analyst**: Validates requirements and provides domain context
- **Developers**: Advises on implementation approaches and technical decisions
- **QA Lead**: Reviews test scenarios for domain coverage
- **Product Manager**: Provides domain insights for feature prioritization
- **Project Manager**: Identifies domain-related risks and dependencies
- **Stakeholder Lead**: Ensures solutions meet business domain expectations

---

## Stakeholder Lead

### Role Summary
Stakeholder Leads act as the primary liaison between the project team and key stakeholders (clients, executives, or business units). They ensure stakeholder needs are understood, communicated, and addressed throughout the project lifecycle.

### Responsibilities
- Identify and manage stakeholder relationships
- Communicate project progress, risks, and decisions to stakeholders
- Gather stakeholder feedback and business requirements
- Facilitate stakeholder meetings and presentations
- Manage stakeholder expectations and resolve conflicts
- Escalate critical issues to appropriate decision-makers
- Ensure stakeholder sign-off on key deliverables

### Goals
- Maintain strong stakeholder engagement and satisfaction
- Ensure alignment between project outcomes and business priorities
- Facilitate timely decision-making and issue resolution

### Typical Communication
- Weekly stakeholder updates and status reports
- Monthly steering committee meetings or executive briefings
- Ad-hoc escalations for critical decisions or issues
- Stakeholder feedback sessions and requirement validation

### Interactions with Other Roles
- **Product Manager**: Aligns on product vision and prioritization based on stakeholder needs
- **Project Manager**: Collaborates on status reporting, risk management, and escalations
- **Business Analyst**: Provides access to stakeholders for requirement gathering
- **Release Coordinator**: Communicates release schedules and impacts to stakeholders
- **Subject Matter Expert (SME)**: Engages SME for stakeholder technical discussions
- **QA Lead**: Coordinates UAT with business stakeholders
- **Developers**: Facilitates stakeholder demos and feedback sessions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

