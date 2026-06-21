# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

#### Key Interactions
- **Product Manager** – Clarify requirements, accept criteria, feature priority
- **Project Manager** – Sprint planning, blockers, capacity planning
- **QA** – Test cases, acceptance validation, bug triage
- **Release Engineer** – Build/deployment questions, CI/CD integration
- **Engineering Manager** – Technical approach, code review standards, career development

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Key Interactions
- **Developers** – Requirements, trade-off discussions, technical feasibility
- **Project Manager** – Timeline alignment, resource needs, milestone planning
- **UX Researcher** – User research findings, design validation, spec refinement
- **Data Analyst** – Success metrics, instrumentation requirements, impact analysis
- **Stakeholders** – Roadmap communication, priority decisions

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Key Interactions
- **Product Manager** – Scope changes, priority shifts, milestone alignment
- **Developers** – Capacity, blockers, velocity tracking
- **Engineering Manager** – Resource allocation, team availability
- **Delivery Lead** – Day-to-day execution coordination
- **Release Engineer** – Deployment scheduling, go-live coordination

---

## Extended Roles

### Delivery Lead

#### Role Summary
Delivery Leads coordinate day-to-day execution across teams, ensure sprint commitments are realistic, and manage cross-team dependencies. They operate as an execution partner to the Project Manager and often focus on tactical coordination.

#### Responsibilities
- Coordinate daily standup meetings and execution sync
- Identify and escalate blockers quickly
- Manage cross-team dependencies and handoffs
- Track sprint metrics (velocity, burndown)
- Facilitate sprint ceremonies (planning, retros, demos)
- Communicate daily status to stakeholders

#### Goals
- Maximize team throughput and reduce cycle time
- Identify and mitigate blockers early
- Ensure smooth handoffs between teams
- Maintain psychological safety and team morale

#### Typical Communication
- Daily standups and execution syncs
- Real-time Slack/chat updates on blockers
- Sprint metrics and progress dashboards
- Weekly sync with Project Manager and Product Manager

#### Key Interactions
- **Project Manager** – Tactical vs. strategic coordination, escalations
- **Developers** – Daily blockers, sprint capacity, technical concerns
- **QA** – Testing readiness, acceptance criteria validation
- **Engineering Manager** – Team capacity and availability
- **Product Manager** – Scope trade-offs when dependencies conflict

---

### Engineering Manager

#### Role Summary
Engineering Managers focus on team health, capacity planning, technical debt prioritization, and career development for engineers. They serve as the primary people leader for the development team.

#### Responsibilities
- Lead and mentor developers on technical and professional growth
- Manage team capacity planning and resource allocation
- Prioritize technical debt and refactoring work
- Conduct code review standards and architecture discussions
- Identify and remove systemic blockers
- Foster psychological safety and inclusive team culture

#### Goals
- Build a high-performing, healthy engineering team
- Reduce technical debt while maintaining feature velocity
- Develop strong talent and reduce team churn
- Enable sustainable pace and work-life balance

#### Typical Communication
- 1:1s with direct reports (weekly)
- Technical design reviews and architecture discussions
- Career development conversations
- Resourcing and capacity planning discussions with PM/Project Manager

#### Key Interactions
- **Developers** – Mentoring, career growth, workload management
- **Project Manager** – Resource needs, capacity constraints
- **Product Manager** – Trade-offs between features and tech debt
- **Release Engineer** – Build pipeline health, CI/CD improvements
- **Security Champion** – Security culture, code review standards

---

### UX Researcher / Designer

#### Role Summary
UX Researchers and Designers lead discovery research, validate designs with users, and provide design specifications and acceptance criteria for UX-related work. They ensure customer needs are understood and solutions are usable.

#### Responsibilities
- Conduct user research and validation studies
- Create prototypes and wireframes
- Define UX acceptance criteria and design specs
- Review implementations against design specifications
- Advocate for user needs in trade-off discussions
- Maintain design system and component library documentation

#### Goals
- Ensure products are intuitive and easy to use
- Validate that user needs drive feature prioritization
- Reduce rework due to design misalignment
- Build consistent, maintainable design systems

#### Typical Communication
- Research findings and user testing reports
- Design specs and interactive prototypes
- Design review sessions and feedback on implementations
- Weekly sync with Product Manager

#### Key Interactions
- **Product Manager** – User research findings, priority inputs, spec refinement
- **Developers** – Design spec clarity, implementation questions, usability feedback
- **QA** – Usability testing, acceptance criteria validation
- **Stakeholders** – User research insights, design decisions
- **Data Analyst** – Usability metrics, user behavior analysis

---

### Release Engineer

#### Role Summary
Release Engineers maintain CI/CD pipelines, manage release automation, and own rollback and deployment runbooks. They ensure reliable, repeatable releases with minimal downtime.

#### Responsibilities
- Design, build, and maintain CI/CD pipelines
- Automate build, test, and deployment processes
- Create and maintain deployment and rollback runbooks
- Coordinate release windows and deployment communication
- Monitor post-deployment health and triage issues
- Implement security scanning and compliance checks in CI/CD

#### Goals
- Enable fast, frequent, reliable releases
- Reduce deployment risk and mean time to recovery (MTTR)
- Automate repetitive deployment tasks
- Maintain high visibility into release and post-deployment health

#### Typical Communication
- Release coordination meetings and deploy notifications
- CI/CD pipeline status and health metrics
- Deployment runbooks and post-deploy verification checklists
- Incident response during failed deployments

#### Key Interactions
- **Developers** – Build/test integration, CI/CD troubleshooting
- **Project Manager** – Release scheduling and go-live coordination
- **QA** – Test environment setup, smoke test automation
- **Security Champion** – Security scanning, compliance automation
- **Support Liaison** – Post-deploy verification, incident communication

---

### Data Analyst / Data Engineer

#### Role Summary
Data Analysts and Data Engineers define success metrics, build dashboards, validate data quality, and instrument events needed to measure outcomes. They enable data-driven decision-making.

#### Responsibilities
- Define success metrics and KPIs aligned with business goals
- Build dashboards and reporting tools
- Validate data quality and accuracy
- Instrument features with tracking events
- Analyze feature impact and provide recommendations
- Document data schema and metric definitions

#### Goals
- Enable data-driven prioritization and trade-off decisions
- Provide real-time visibility into product health and impact
- Ensure data accuracy and trust in metrics
- Support continuous improvement through experimentation

#### Typical Communication
- Metric definitions and dashboard links
- Weekly data summaries and impact reports
- Instrumentation requirements during planning
- Analysis and recommendations for optimization

#### Key Interactions
- **Product Manager** – Metric definitions, success criteria, impact analysis
- **Developers** – Instrumentation requirements, data accuracy questions
- **Data Platform team** – Data infrastructure, pipeline reliability
- **UX Researcher** – User behavior analytics, usability metrics
- **Stakeholders** – Executive dashboards, outcome reporting

---

### Support Liaison / Customer Support Lead

#### Role Summary
Support Liaisons and Customer Support Leads triage customer-reported issues, communicate status to stakeholders, and maintain knowledge base updates. They are the voice of the customer and bridge product/engineering with support.

#### Responsibilities
- Triage and prioritize customer-reported issues
- Communicate issue status and workarounds to customers
- Escalate critical bugs and incidents to engineering
- Collect customer feedback and feature requests
- Maintain and update knowledge base and FAQ
- Participate in go-live support and post-release monitoring

#### Goals
- Reduce customer impact and time-to-resolution for issues
- Identify patterns in customer issues for product improvement
- Reduce support ticket volume through documentation
- Improve customer satisfaction and retention

#### Typical Communication
- Issue escalation to engineering with reproduction steps
- Customer status updates and workarounds
- Root cause analysis summaries
- Feature request aggregation and trending

#### Key Interactions
- **Developers** – Issue triage, bug reproduction, root cause analysis
- **Release Engineer** – Rollback decisions, deployment impact
- **Product Manager** – Feature requests, customer feedback patterns
- **Project Manager** – Priority escalations, incident communication
- **QA** – Test case validation for reported issues

---

### Security Champion

#### Role Summary
Security Champions advocate security best practices within the team, perform threat modeling, and coordinate security scans. They embed security thinking into day-to-day development.

#### Responsibilities
- Advocate and educate on security best practices
- Perform threat modeling during design phase
- Review PRs for security concerns
- Coordinate and review security scans and penetration testing
- Triage security vulnerabilities and coordinate fixes
- Maintain security runbooks and incident procedures

#### Goals
- Build security-aware engineering culture
- Prevent security vulnerabilities in code and design
- Ensure compliance with security standards and policies
- Reduce security incident frequency and severity

#### Typical Communication
- Security threat models and design reviews
- Security scan results and remediation guidance
- Incident response during security events
- Team security training and awareness

#### Key Interactions
- **Developers** – Code review, security guidance, vulnerability fixes
- **Engineering Manager** – Security culture, code review standards
- **Release Engineer** – Security scanning automation, compliance checks
- **Security on-call** – Incident response, vulnerability disclosure
- **Product Manager** – Security requirement clarification

---

### Compliance / Privacy Owner

#### Role Summary
Compliance and Privacy Owners ensure features comply with regulatory requirements (e.g., GDPR, HIPAA), maintain records for audits, and advise on data handling. They are the organizational safeguard for regulatory alignment.

#### Responsibilities
- Ensure features comply with applicable regulations and policies
- Maintain documentation for audit and compliance reviews
- Advise on data privacy and handling requirements
- Review data flows and storage practices
- Coordinate with legal and security on compliance issues
- Maintain compliance checklists and runbooks

#### Goals
- Prevent compliance violations and regulatory fines
- Enable confident, compliant product development
- Maintain audit readiness and regulatory relationships
- Reduce compliance risk throughout the organization

#### Typical Communication
- Compliance requirement documentation and guidance
- Data flow diagrams and privacy impact assessments
- Audit readiness checklists and documentation
- Incident notification and post-incident reviews

#### Key Interactions
- **Product Manager** – Compliance requirement clarification
- **Developers** – Data handling best practices, implementation guidance
- **Data Engineer** – Data retention, privacy automation
- **Legal team** – Regulatory interpretation, contract review
- **Security Champion** – Data protection, incident response

---

## Role Interaction Matrix

The following matrix summarizes key interaction patterns and dependencies:

| Role | Primary Collaborators | Frequency | Key Touchpoints |
|------|----------------------|-----------|------------------|
| Developer | Developers, QA, PM, Engineering Manager | Daily | PRs, standups, code review |
| Product Manager | PM, Developers, UX, Data Analyst | Weekly | Planning, spec refinement, metrics |
| Project Manager | Developers, PM, Delivery Lead, Release Eng | Daily/Weekly | Status, blockers, risk register |
| Delivery Lead | Developers, QA, PM, Project Manager | Daily | Standups, sprint tracking, blockers |
| Engineering Manager | Developers, PM, Release Eng, Security | Weekly | 1:1s, tech debt, resourcing |
| UX Researcher | PM, Developers, QA, Data Analyst | Weekly | Research findings, design specs, usability |
| Release Engineer | Developers, QA, PM, Security Champion | Per Release | CI/CD, deployment, security scans |
| Data Analyst | PM, Developers, UX, Stakeholders | Weekly | Metrics, instrumentation, reports |
| Support Liaison | Developers, Release Eng, PM, QA | Daily/Weekly | Bug triage, issue escalation, feedback |
| Security Champion | Developers, Release Eng, Engineering Mgr | Weekly | Code review, threat modeling, scans |
| Compliance Officer | Product, Developers, Data Eng, Legal | Weekly/Monthly | Requirements, data handling, audits |

---

## How These Personas Are Used

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the **Role Interaction Matrix** when identifying stakeholders for project planning and escalation paths.
- Use the **Key Interactions** section in each persona to understand who to loop in for specific decisions or concerns.

---

## Cross-Functional Collaboration Best Practices

### Before Starting a Feature
1. **Confirm stakeholders** – Use the Role Interaction Matrix to identify who needs to be involved
2. **Document interfaces** – Clarify handoff points and acceptance criteria across roles
3. **Align on metrics** – Work with Data Analyst to define success criteria early
4. **Assess risks** – Loop in Security Champion for threat modeling and Compliance Officer for regulatory needs

### During Execution
1. **Maintain transparency** – Use shared project board, status docs, and dashboards
2. **Escalate early** – Blockers and dependencies should be surfaced in daily standups
3. **Review across roles** – Code reviews should include technical and domain expertise (security, UX, performance)
4. **Iterate with feedback** – UX, QA, and Support Liaison feedback should inform refinements

### At Release
1. **Coordinate pre-release** – Release Engineer, QA, and Support Liaison should validate readiness
2. **Communicate externally** – Product Manager and Support Liaison should brief customers
3. **Monitor post-release** – Data Analyst, Release Engineer, and Support should monitor health
4. **Capture learnings** – Include all roles in retrospective to identify process improvements
