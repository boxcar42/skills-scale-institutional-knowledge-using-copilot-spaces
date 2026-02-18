# Role Responsibility Checklist

This document provides a comprehensive checklist for ensuring all critical project activities are assigned to appropriate roles, addressing gaps in accountability and clarifying escalation paths.

## Purpose
- Ensure no critical activities are left unassigned
- Clarify accountability for each project phase
- Define escalation paths for common scenarios
- Support onboarding of new team members

---

## Project Initiation Phase

| Activity | Primary Owner | Support Roles | Escalation Path |
|----------|---------------|---------------|-----------------|
| Define problem statement and business case | Product Manager | Business Analyst, Stakeholder Lead | Stakeholder Lead → Executive Sponsor |
| Identify project stakeholders | Stakeholder Lead | Project Manager | Project Manager → Product Manager |
| Create project charter | Project Manager | Product Manager, Business Analyst | Stakeholder Lead → Executive Sponsor |
| Establish success metrics | Product Manager | Business Analyst | Stakeholder Lead |
| Define high-level scope and timeline | Project Manager | Product Manager, Developers | Product Manager → Stakeholder Lead |
| Identify Subject Matter Experts needed | Project Manager | Business Analyst | Product Manager |
| Secure budget and resources | Project Manager | Stakeholder Lead | Stakeholder Lead → Executive Sponsor |

---

## Requirements Gathering Phase

| Activity | Primary Owner | Support Roles | Escalation Path |
|----------|---------------|---------------|-----------------|
| Conduct stakeholder interviews | Business Analyst | Stakeholder Lead | Product Manager |
| Document functional requirements | Business Analyst | Product Manager, SME | Project Manager |
| Define acceptance criteria | Product Manager | Business Analyst, QA Lead | Stakeholder Lead |
| Create user stories and use cases | Business Analyst | Product Manager, Developers | Product Manager |
| Validate domain-specific requirements | Subject Matter Expert (SME) | Business Analyst | Product Manager |
| Obtain requirement sign-off | Stakeholder Lead | Business Analyst, Product Manager | Executive Sponsor |
| Maintain requirements traceability | Business Analyst | Project Manager | Product Manager |

---

## Planning Phase

| Activity | Primary Owner | Support Roles | Escalation Path |
|----------|---------------|---------------|-----------------|
| Break down work into tasks | Developers | Project Manager, Product Manager | Project Manager |
| Estimate effort and timeline | Developers | Project Manager, SME | Product Manager |
| Create project schedule | Project Manager | Developers, Release Coordinator | Stakeholder Lead |
| Define test strategy | QA Lead | Developers, Business Analyst | Project Manager |
| Identify dependencies and risks | Project Manager | All team members | Product Manager → Stakeholder Lead |
| Plan release schedule | Release Coordinator | Project Manager, Product Manager | Stakeholder Lead |
| Allocate resources | Project Manager | Stakeholder Lead | Stakeholder Lead → Executive Sponsor |

---

## Execution Phase

| Activity | Primary Owner | Support Roles | Escalation Path |
|----------|---------------|---------------|-----------------|
| Implement features | Developers | SME | Project Manager |
| Conduct code reviews | Developers | SME | Tech Lead |
| Write and maintain tests | Developers | QA Lead | Tech Lead |
| Execute test cases | QA Lead | Developers | Project Manager |
| Track progress and update status | Project Manager | All team members | Stakeholder Lead |
| Manage scope changes | Product Manager | Project Manager, Business Analyst | Stakeholder Lead |
| Resolve blockers | Project Manager | Relevant role owners | Product Manager → Stakeholder Lead |
| Validate deliverables against requirements | Business Analyst | QA Lead, Product Manager | Product Manager |
| Manage technical risks | Developers / SME | Project Manager | Product Manager |
| Communicate progress to stakeholders | Stakeholder Lead | Project Manager | Executive Sponsor |

---

## Release Phase

| Activity | Primary Owner | Support Roles | Escalation Path |
|----------|---------------|---------------|-----------------|
| Prepare release documentation | Release Coordinator | Developers, Business Analyst | Project Manager |
| Coordinate User Acceptance Testing (UAT) | Business Analyst | QA Lead, Stakeholder Lead | Product Manager |
| Validate release readiness | Release Coordinator | QA Lead, Project Manager | Product Manager |
| Conduct go/no-go meeting | Release Coordinator | Project Manager, QA Lead, Product Manager | Stakeholder Lead |
| Execute deployment | Release Coordinator | Developers | Project Manager |
| Monitor post-deployment | Developers | QA Lead, Release Coordinator | Project Manager |
| Communicate release to stakeholders | Stakeholder Lead | Release Coordinator | Product Manager |
| Create release notes | Release Coordinator | Product Manager, Business Analyst | Product Manager |

---

## Closure & Retrospective Phase

| Activity | Primary Owner | Support Roles | Escalation Path |
|----------|---------------|---------------|-----------------|
| Conduct retrospective meeting | Project Manager | All team members | Product Manager |
| Document lessons learned | Project Manager | All team members | Stakeholder Lead |
| Archive project documentation | Project Manager | Business Analyst | N/A |
| Celebrate successes | Project Manager | All team members | N/A |
| Identify process improvements | Project Manager | All team members | Product Manager |
| Update knowledge base | Business Analyst | SME, Developers | Project Manager |
| Transition to maintenance/support | Release Coordinator | Developers, SME | Project Manager |

---

## Common Escalation Scenarios

### Technical Issues

| Scenario | Initial Contact | Escalation Path |
|----------|----------------|-----------------|
| Complex technical decision needed | Developer → SME | SME → Tech Lead → Product Manager |
| Architectural concern | Developer → SME | SME → Tech Lead → Stakeholder Lead |
| Technical blocker | Developer → Project Manager | Project Manager → Product Manager → Stakeholder Lead |
| Production incident | Developer → Release Coordinator | Release Coordinator → Project Manager → Stakeholder Lead |

### Business & Requirements Issues

| Scenario | Initial Contact | Escalation Path |
|----------|----------------|-----------------|
| Requirement ambiguity | Developer → Business Analyst | Business Analyst → Product Manager → Stakeholder Lead |
| Scope creep | Any team member → Project Manager | Project Manager → Product Manager → Stakeholder Lead |
| Conflicting stakeholder requirements | Business Analyst → Product Manager | Product Manager → Stakeholder Lead → Executive Sponsor |
| Missing business information | Business Analyst → Stakeholder Lead | Stakeholder Lead → Product Manager |

### Schedule & Resource Issues

| Scenario | Initial Contact | Escalation Path |
|----------|----------------|-----------------|
| Timeline at risk | Any team member → Project Manager | Project Manager → Product Manager → Stakeholder Lead |
| Resource constraint | Project Manager | Project Manager → Stakeholder Lead → Executive Sponsor |
| Release date conflict | Release Coordinator → Project Manager | Project Manager → Product Manager → Stakeholder Lead |
| Dependency blocking progress | Project Manager | Project Manager → Stakeholder Lead |

### Quality Issues

| Scenario | Initial Contact | Escalation Path |
|----------|----------------|-----------------|
| Quality standard not met | QA Lead → Project Manager | Project Manager → Product Manager → Stakeholder Lead |
| Critical defect found late | QA Lead → Release Coordinator | Release Coordinator → Project Manager → Stakeholder Lead |
| UAT failure | Business Analyst → Product Manager | Product Manager → Stakeholder Lead |
| Test coverage concerns | QA Lead → Project Manager | Project Manager → Product Manager |

---

## Role Accountability Matrix (RACI)

This matrix clarifies who is Responsible, Accountable, Consulted, and Informed for key project activities.

| Activity | Developer | Product Manager | Project Manager | QA Lead | Business Analyst | Release Coordinator | SME | Stakeholder Lead |
|----------|-----------|----------------|----------------|---------|------------------|---------------------|-----|------------------|
| Define requirements | C | A | C | C | R | I | C | I |
| Estimate work | R | C | A | C | I | I | C | I |
| Implement features | R | I | I | C | I | I | C | I |
| Test features | C | I | C | R/A | I | I | C | I |
| Release planning | C | C | C | C | I | R/A | I | C |
| Deploy to production | R | I | C | C | I | A | I | I |
| Stakeholder communication | I | C | C | I | I | I | I | R/A |
| Risk management | C | C | R/A | C | C | C | C | I |
| Retrospectives | C | C | R/A | C | C | C | C | I |

**Legend:**
- **R (Responsible)**: Does the work
- **A (Accountable)**: Ultimately answerable for completion
- **C (Consulted)**: Provides input and feedback
- **I (Informed)**: Kept in the loop

---

## Gap Coverage Checklist

Use this checklist to ensure all critical areas have clear ownership:

- [ ] **Stakeholder Management**: Is there a dedicated Stakeholder Lead for each project?
- [ ] **Requirements Documentation**: Is a Business Analyst assigned to document and maintain requirements?
- [ ] **Domain Expertise**: Have necessary Subject Matter Experts been identified and engaged?
- [ ] **Release Management**: Is a Release Coordinator assigned for each release?
- [ ] **Quality Assurance**: Is there a QA Lead responsible for test strategy and validation?
- [ ] **Technical Leadership**: Are technical decisions supported by appropriate SME consultation?
- [ ] **Risk Escalation**: Does every team member know who to escalate issues to?
- [ ] **Status Communication**: Is it clear who communicates what to whom and when?
- [ ] **UAT Coordination**: Is there clear ownership for coordinating User Acceptance Testing?
- [ ] **Post-Release Support**: Is there a clear handoff plan for maintenance and support?
- [ ] **Documentation**: Is someone responsible for maintaining project documentation throughout?
- [ ] **Process Improvement**: Are retrospective action items tracked and assigned?

---

## Best Practices for Role Clarity

1. **Document role assignments** in the project charter at project initiation
2. **Review the RACI matrix** during project kickoff with all team members
3. **Update role assignments** as project needs evolve
4. **Communicate changes** immediately to all affected parties
5. **Resolve conflicts** when multiple roles claim accountability for the same activity
6. **Fill gaps** immediately when unassigned activities are identified
7. **Escalate promptly** according to defined paths rather than waiting
8. **Review accountability** during retrospectives to identify improvements

---

## How to Use This Checklist

1. **At Project Start**: Review all checklists with the team to ensure coverage
2. **During Planning**: Assign primary and support roles for each activity
3. **During Execution**: Reference escalation paths when issues arise
4. **At Retrospective**: Identify gaps or confusion that occurred and update the checklist
5. **For Onboarding**: Use as a reference to help new team members understand responsibilities

