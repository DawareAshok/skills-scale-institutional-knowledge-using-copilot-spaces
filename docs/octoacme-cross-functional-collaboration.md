# OctoAcme — Cross-Functional Collaboration Guide

## Purpose
Provide a structured approach for managing dependencies, communication, and accountability across multiple roles and teams in OctoAcme projects.

## When to Use
Use this guide when:
- Planning work that involves multiple roles (e.g., Design, Development, Data, Security)
- Managing dependencies between teams or workstreams
- Escalating blockers or decisions that require input from multiple stakeholders
- Conducting retrospectives and identifying collaboration gaps

## Core Principles
- **Early visibility**: Surface dependencies and blockers in planning, not execution
- **Clear ownership**: Every deliverable and decision has a named owner
- **Psychological safety**: Encourage feedback and learning from all roles
- **Transparent communication**: Use shared docs, dashboards, and project boards
- **Respectful escalation**: Escalate blockers quickly; avoid silos

## Cross-Functional Planning Checklist

### Pre-kickoff (48 hours before)
- [ ] Identify all roles involved (use Role Interaction Matrix in `octoacme-roles-and-personas.md`)
- [ ] List key dependencies and integration points
- [ ] Identify potential risks (technical, UX, security, compliance, data)
- [ ] Prepare draft success metrics and acceptance criteria
- [ ] Schedule kickoff meeting with all stakeholders

### Kickoff Meeting Agenda (60 min)
- [ ] **Problem & Goals** (10 min) – Product Manager presents vision and success metrics
- [ ] **Technical & Design Approach** (15 min) – UX and Engineering leads discuss approach
- [ ] **Dependencies & Risks** (15 min) – Project Manager walks through blockers and cross-team needs
- [ ] **Roles & Responsibilities** (10 min) – Clarify who owns what (RACI optional)
- [ ] **Success Criteria & Acceptance** (10 min) – Align on Definition of Done

### During Execution
- [ ] **Daily coordination** (15 min standup) – Delivery Lead runs daily sync focusing on blockers
- [ ] **Async updates** – Use shared project board and status doc (updated at end of day)
- [ ] **Weekly role syncs** – Subject-matter experts (Security, UX, Data) sync on their domain
- [ ] **Blocker escalation** – Any blocker blocking > 1 day escalates to Project Manager
- [ ] **Dependency tracking** – Project Manager updates dependency map in risk register weekly

### Pre-Release Coordination
- [ ] **Readiness review** (1 week before) – All roles confirm readiness
  - QA: Testing complete, known issues documented
  - Release Eng: Deployment runbook complete, rollback plan ready
  - Support Liaison: KB updated, support team trained
  - Security Champion: Security scans complete, vulnerabilities resolved
  - Compliance Officer: Compliance checklist signed off
- [ ] **Deployment dry-run** (2 days before) – Release Engineer runs on staging
- [ ] **Go-live coordination** (day of) – Release Eng, Support, and PM on call

### Post-Release Retrospective
- [ ] **Schedule retro** within 3 business days of release
- [ ] **Invite all roles** who participated in planning or execution
- [ ] **Review cross-functional interactions** – What worked well? What could improve?
- [ ] **Capture action items** with owners and due dates
- [ ] **Share learnings** with broader team for continuous improvement

## Role Responsibilities in Cross-Functional Work

### Product Manager
- Owns success metrics and acceptance criteria
- Facilitates trade-off discussions when dependencies conflict
- Provides regular priority and scope updates
- Escalates customer/business risks to stakeholders

### Project Manager
- Owns timeline, milestones, and risk register
- Identifies and tracks cross-team dependencies
- Escalates blockers to appropriate leaders
- Coordinates communication to stakeholders

### Delivery Lead
- Manages daily execution and standup discipline
- Identifies blockers in real-time and flags for escalation
- Ensures sprint commitments are realistic given dependencies
- Keeps project board and status docs current

### Engineering Manager
- Confirms team capacity and availability
- Advocates for technical debt and refactoring needs
- Ensures code review standards are maintained
- Escalates technical risks early

### Developers
- Proactively raise technical concerns and risks
- Collaborate on design and spec refinement
- Participate in cross-functional code reviews
- Help estimate impact of dependencies and trade-offs

### UX Researcher / Designer
- Provides design specs and acceptance criteria
- Reviews implementations against design specifications
- Conducts usability testing and provides feedback
- Advocates for user needs in priority discussions

### Release Engineer
- Owns deployment readiness and CI/CD health
- Creates rollback plans and runbooks
- Coordinates go-live logistics
- Monitors post-deployment health

### Data Analyst
- Defines success metrics with Product Manager
- Provides instrumentation requirements to Developers
- Builds dashboards for monitoring and reporting
- Analyzes impact and provides recommendations

### Support Liaison
- Escalates critical customer issues quickly
- Provides feedback on product usability and reliability
- Updates KB and trains support team pre-release
- Monitors post-release customer impact

### Security Champion
- Threat models during design phase
- Reviews code and architecture for security concerns
- Coordinates security scans and remediation
- Escalates security risks to leadership

### Compliance Officer
- Reviews features for regulatory compliance
- Advises on data handling and privacy requirements
- Maintains compliance documentation
- Escalates compliance risks to legal and leadership

## Dependency Mapping Template

Use this template in the project risk register:

```
Dependency ID: PROJ-D001
Description: [E.g., "Waiting on API design from Platform team"]
Dependent Team(s): [E.g., "Backend + QA"]
Provider Team(s): [E.g., "Platform"]
Planned Completion: [Date]
Risk Level: High / Medium / Low
Mitigation: [E.g., "Weekly sync with Platform lead; design review by date X"]
Owner: [PM name]
Status: Active / Mitigated / Resolved
```

## Escalation Paths for Cross-Functional Issues

### Level 1: Team Resolution (< 1 day)
- Raise in daily standup
- Owners coordinate directly
- Delivery Lead or Project Manager facilitates if needed

### Level 2: Leadership Escalation (1–2 days)
- Escalate to Project Manager and relevant Engineering/Product Managers
- Schedule focused sync to resolve
- Document decision and rationale

### Level 3: Sponsor Escalation (> 2 days)
- Project Manager and Product Lead escalate to Project Sponsor
- Present trade-offs and recommendation
- Sponsor makes final decision
- Document and communicate decision to team

## Communication Templates

### Weekly Cross-Functional Status

**To:** [All roles]
**Subject:** [Project Name] – Weekly Status (Week of XX/XX)

**Accomplishments This Week:**
- [Key milestone or deliverable]
- [Key milestone or deliverable]

**Planned for Next Week:**
- [Planned work]
- [Planned work]

**Active Dependencies & Risks:**
| Dependency | Owner | Status | Mitigation |
|------------|-------|--------|------------|
| [Description] | [Name] | [Active] | [Plan] |

**Asks for Next Week:**
- [Decision or input needed from X role]
- [Approval from Y]

**Metrics (if applicable):**
- [Completion %]
- [Key KPI]

---

### Blocker Escalation Template

**Blocker ID:** [PROJ-B001]
**Description:** [Concise description of what is blocked]
**Impact:** [What work is waiting / which teams affected]
**Root Cause:** [Why is it blocked]
**Owner:** [Who needs to unblock]
**Proposed Mitigation:** [Suggested path forward]
**Timeline to Resolve:** [By when]
**Escalation Level:** [Level 1 / 2 / 3]

---

## Best Practices

1. **Over-communicate, not under-communicate** – Especially across roles and teams
2. **Use a shared single source of truth** – Project board, status doc, risk register
3. **Make decisions visible** – Document decisions and rationale so all understand context
4. **Celebrate wins together** – Recognition should span all roles that contributed
5. **Learn from failures** – Retrospectives should be blameless and focus on process improvement
6. **Respect domain expertise** – Trust UX on design, Security on threat modeling, Data on metrics, etc.
7. **Escalate early, resolve quickly** – Don't let blockers fester; surface immediately
8. **Invest in relationships** – 1:1 chats between roles build trust and speed decision-making
