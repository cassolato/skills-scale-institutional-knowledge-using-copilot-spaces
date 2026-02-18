# OctoAcme Roles RACI Matrix

## Purpose
This document provides a RACI (Responsible, Accountable, Consulted, Informed) matrix to clarify ownership and involvement across key project lifecycle activities and artifacts at OctoAcme.

## RACI Key
- **R - Responsible**: Does the work to complete the task
- **A - Accountable**: Ultimately answerable for completion and has approval authority (only one A per item)
- **C - Consulted**: Provides input and is consulted before decisions or actions
- **I - Informed**: Kept informed of progress or decisions

## Role Abbreviations
- **PM**: Project Manager
- **PdM**: Product Manager
- **Dev**: Developers
- **QA**: QA Engineer / Tester
- **UX**: UX/UI Designer
- **TL**: Technical Lead / Architect
- **BA**: Business Analyst
- **CS**: Support / Customer Success Lead

---

## Lifecycle Activities RACI

| Activity | PM | PdM | Dev | QA | UX | TL | BA | CS |
|----------|----|----|-----|----|----|----|----|-----|
| **Initiation Phase** |
| Define problem statement | C | A | I | I | C | C | R | C |
| Identify stakeholders | R | A | I | I | I | C | C | I |
| Create project one-pager | R | A | C | I | C | C | C | C |
| Approve project initiation | C | A | I | I | I | I | I | I |
| **Planning Phase** |
| Facilitate kickoff meeting | A | R | R | R | R | R | R | I |
| Create prioritized backlog | C | A | C | C | C | C | R | C |
| Define acceptance criteria | C | A | R | C | C | C | R | I |
| Estimate scope and effort | R | C | A | C | C | A | C | I |
| Define Definition of Done | R | A | R | A | C | A | C | I |
| Identify dependencies & risks | A | C | R | C | C | R | C | I |
| Create release plan | A | R | C | C | C | C | C | I |
| **Execution Phase** |
| Implement features | I | I | A | I | C | R | C | I |
| Design UI/UX | C | C | C | I | A | C | C | I |
| Code review | I | I | R | I | I | A | I | I |
| Write tests | I | I | A | R | I | C | I | I |
| Execute test plans | I | I | C | A | I | C | I | I |
| Manage daily standups | A | C | R | R | R | R | R | I |
| Track progress & risks | A | C | I | I | I | I | I | I |
| Bug triage & resolution | C | C | A | R | I | R | I | I |
| **Release Phase** |
| Validate release readiness | R | A | C | R | I | C | I | C |
| Execute deployment | I | I | A | C | I | R | I | I |
| Verify production deployment | C | C | R | A | I | C | I | C |
| Create release notes | R | C | C | I | I | I | I | C |
| Customer communication | C | C | I | I | I | I | I | A |
| **Retrospective Phase** |
| Facilitate retrospective | A | R | R | R | R | R | R | R |
| Document learnings | R | C | C | C | C | C | C | C |
| Create action items | A | C | C | C | C | C | C | C |

---

## Key Artifacts RACI

| Artifact | PM | PdM | Dev | QA | UX | TL | BA | CS |
|----------|----|----|-----|----|----|----|----|-----|
| **Project One-pager** | R | A | I | I | C | C | C | C |
| **Product Roadmap** | C | A | I | I | C | C | C | C |
| **Sprint/Iteration Backlog** | C | A | R | C | C | C | R | I |
| **User Stories / Requirements** | C | A | C | C | C | C | R | C |
| **Definition of Done (DoD)** | R | A | R | A | C | A | C | I |
| **Risk Register** | A | C | R | R | C | R | C | C |
| **Technical Design Docs** | I | C | R | C | C | A | C | I |
| **Design Specifications** | C | C | C | C | A | C | C | I |
| **Test Plans** | I | C | C | A | I | C | I | I |
| **Release Notes** | R | C | C | I | I | I | I | C |
| **Retrospective Notes** | R | C | C | C | C | C | C | C |
| **Customer Feedback Reports** | I | R | I | I | I | I | I | A |

---

## How to Use This Matrix

1. **Before starting an activity or creating an artifact**: Check the matrix to understand who needs to be involved
2. **When planning meetings**: Invite those marked as R, A, or C; inform those marked as I
3. **When decisions are needed**: Ensure the Accountable (A) person makes or approves the final decision
4. **When conflicts arise**: Refer to the Accountable role for resolution
5. **Adapt as needed**: This matrix represents typical assignments; adjust for specific project contexts and team structures

---

## Related Documents
- [OctoAcme Roles and Personas](octoacme-roles-and-personas.md) - Detailed role descriptions
- [OctoAcme Project Management Overview](octoacme-project-management-overview.md) - High-level process overview
- [OctoAcme Kickoff Checklist](octoacme-kickoff-checklist.md) - Cross-functional kickoff guidance
