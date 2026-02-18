# OctoAcme — Cross-Functional Kickoff Checklist

## Purpose
Ensure that all key roles are engaged, critical decisions are made, and ownership is clear before executing a project. Use this checklist during the project kickoff meeting and planning phase.

## When to Use
- After project initiation is approved (one-pager completed)
- Before detailed sprint planning begins
- At the start of any significant new feature or project

---

## Pre-Kickoff Preparation

### Project Context
- [ ] **Project one-pager** completed and shared with all attendees
  - See: [Project Initiation Guide](octoacme-project-initiation.md)
- [ ] **Success metrics** clearly defined
- [ ] **Timeline and key milestones** identified
- [ ] **Initial stakeholder list** confirmed

### Meeting Logistics
- [ ] Kickoff meeting scheduled (suggest 1-2 hours depending on scope)
- [ ] All key roles invited and confirmed:
  - [ ] Project Manager
  - [ ] Product Manager
  - [ ] Developer(s) / Engineering Lead
  - [ ] QA Engineer / Tester
  - [ ] UX/UI Designer (if applicable)
  - [ ] Technical Lead / Architect
  - [ ] Business Analyst (if applicable)
  - [ ] Support / Customer Success Lead (if applicable)
  - [ ] Key stakeholders and sponsors
- [ ] Pre-read materials shared 24-48 hours before kickoff

---

## During Kickoff: Key Discussions & Decisions

### 1. Alignment & Context
- [ ] **Problem statement** reviewed and agreed
- [ ] **Success metrics** confirmed by all roles
- [ ] **Customer impact** and use cases understood
- [ ] **Business objectives** clarified

### 2. Roles & Responsibilities
- [ ] **Project Manager** identified and confirmed
- [ ] **Product Manager / Product Lead** confirmed
- [ ] **Engineering Lead / Technical Lead** assigned
- [ ] **QA/Test Lead** assigned
- [ ] **Design Lead** assigned (if applicable)
- [ ] **Business Analyst** assigned (if applicable)
- [ ] **Support/CS liaison** identified for customer feedback
- [ ] Refer to [RACI Matrix](octoacme-roles-raci.md) for detailed activity ownership

### 3. Scope & Planning Approach
- [ ] **Scope boundaries** agreed (what's in and what's out)
- [ ] **Definition of Done (DoD)** defined or reviewed
  - See: [Project Planning Guide](octoacme-project-planning.md)
- [ ] **Release strategy** discussed (phased, big bang, feature flags, etc.)
- [ ] **Testing approach** outlined (unit, integration, E2E, manual QA)
- [ ] **Dependencies** identified (cross-team, external, technical)

### 4. Communication & Cadence
- [ ] **Standup schedule** agreed (frequency, format, duration)
- [ ] **Weekly sync** between PM and PdM confirmed
- [ ] **Demo/review cadence** established (end of sprint, milestone-based, etc.)
- [ ] **Stakeholder update frequency** agreed (weekly, bi-weekly, monthly)
- [ ] **Communication channels** confirmed (Slack, email, project board, etc.)

### 5. Risk & Escalation
- [ ] **Top 3-5 initial risks** identified
  - See: [Risks and Communication Guide](octoacme-risks-and-communication.md)
- [ ] **Risk owners** assigned for each identified risk
- [ ] **Escalation path** clarified (team → PM → sponsor)
- [ ] **Blocker resolution process** agreed

### 6. Tools & Artifacts
- [ ] **Project board** created (GitHub Projects, Jira, etc.)
  - Columns: Backlog, Ready, In Progress, In Review, QA, Done
- [ ] **Repository / workspace** set up
- [ ] **CI/CD pipeline** identified or configured
- [ ] **Documentation location** agreed (repo `/docs`, `.copilot/`, wiki, etc.)

### 7. Backlog & Planning
- [ ] **Initial backlog** reviewed (epics, features, or stories)
- [ ] **Prioritization approach** confirmed (MoSCoW, value/effort, etc.)
- [ ] **Estimation method** agreed (story points, T-shirt sizing, hours)
- [ ] **Sprint/iteration length** decided (1 week, 2 weeks, etc.)

---

## Post-Kickoff Actions

### Immediate Follow-Ups (within 24 hours)
- [ ] **Kickoff notes** documented and shared with all attendees
- [ ] **Action items** captured with owners and due dates
- [ ] **Risk register** created or updated
- [ ] **Project board** populated with initial backlog items
- [ ] **Recurring meetings** sent (standups, syncs, reviews)

### First Sprint / Iteration Setup
- [ ] **Sprint planning** completed (pull prioritized, ready items into sprint)
- [ ] **Acceptance criteria** confirmed for sprint items
- [ ] **Test plan** drafted by QA
- [ ] **Design specs** available for items requiring UI work
- [ ] **Technical design** or spike completed for complex items

### Continuous Practices
- [ ] **Daily standups** running
- [ ] **Risk register** reviewed weekly
- [ ] **Progress tracking** maintained on project board
- [ ] **Retrospective** scheduled at end of sprint/milestone
  - See: [Retrospective Guide](octoacme-retrospective-and-continuous-improvement.md)

---

## Common Pitfalls to Avoid
- ❌ Starting execution without clear Definition of Done
- ❌ Missing key roles in kickoff (especially QA, UX, or Technical Lead)
- ❌ Not identifying dependencies early
- ❌ Skipping communication cadence agreements
- ❌ Forgetting to assign risk owners
- ❌ Unclear escalation paths

---

## Related Documents
- [OctoAcme Project Initiation Guide](octoacme-project-initiation.md)
- [OctoAcme Project Planning](octoacme-project-planning.md)
- [OctoAcme Roles and Personas](octoacme-roles-and-personas.md)
- [OctoAcme Roles RACI Matrix](octoacme-roles-raci.md)
- [OctoAcme Execution and Tracking](octoacme-execution-and-tracking.md)
- [OctoAcme Risks and Communication](octoacme-risks-and-communication.md)
- [OctoAcme Retrospective Guide](octoacme-retrospective-and-continuous-improvement.md)

---

## Quick Reference: Kickoff Agenda Template

```
OctoAcme Project Kickoff — [Project Name]
Duration: 90 minutes

1. Introductions & Roles (5 min)
2. Project Overview & Context (10 min)
   - Problem statement, goals, success metrics
3. Scope & Approach (15 min)
   - What's in/out, DoD, release strategy
4. Team Structure & Responsibilities (10 min)
   - Refer to RACI matrix
5. Communication & Cadence (10 min)
   - Standups, syncs, demos, status updates
6. Risks & Dependencies (15 min)
   - Top risks, owners, escalation path
7. Tools & Backlog Review (15 min)
   - Project board, repo, initial backlog
8. Next Steps & Action Items (10 min)
   - Sprint planning, follow-ups, owners
9. Q&A (remaining time)
```
