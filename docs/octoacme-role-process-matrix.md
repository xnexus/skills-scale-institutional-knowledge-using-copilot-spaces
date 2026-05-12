# OctoAcme — Role-to-Process Matrix

A quick-reference table showing which roles are typically active or involved at each stage of the OctoAcme project lifecycle. Use this to clarify ownership, set up the right meetings, and confirm who needs to be consulted or informed during each phase.

**Key:** **O** = Owner / Lead, **C** = Contributor / Active, **I** = Informed / Consulted

---

| Role | Initiation | Planning | Execution | Risk & Comms | Release | Retrospective |
|---|:---:|:---:|:---:|:---:|:---:|:---:|
| Project Manager | **O** | **O** | **O** | **O** | **C** | **O** |
| Product Manager | **O** | **O** | **C** | **C** | **C** | **C** |
| Technical Lead | **C** | **O** | **O** | **C** | **C** | **C** |
| Engineering Manager | **C** | **C** | **C** | **C** | I | **C** |
| Developers | I | **C** | **O** | **C** | **C** | **C** |
| UX / Product Designer | **C** | **O** | **C** | I | I | **C** |
| QA / Testing | I | **C** | **C** | **C** | **O** | **C** |
| Security / Compliance Lead | **C** | **C** | **C** | **C** | **C** | I |
| Support / Operations Lead | I | **C** | I | **C** | **O** | **C** |
| Stakeholder / Sponsor | **O** | **C** | I | I | **C** | I |

---

## Stage Summaries

### Initiation
Project Managers and Product Managers co-own initiation — defining the problem statement, aligning stakeholders, and making the go/no-go decision. Technical Leads and Security / Compliance Leads contribute to early feasibility and risk identification. Sponsors provide final approval to proceed.

### Planning
Project Managers own the plan; Technical Leads and Product Managers drive scope definition and backlog creation. UX / Product Designers finalize interaction flows and acceptance criteria. Engineering Managers input on team capacity. QA and Support / Operations Leads define their test and readiness requirements early.

### Execution
Developers lead day-to-day delivery. Technical Leads provide direction and review. Project Managers track progress and manage risks. Product Managers validate work against goals. QA and Security participate in quality and security checkpoints throughout.

### Risk & Communication
Project Managers own the risk register and stakeholder communication. Technical Leads, Security / Compliance Leads, and Support / Operations Leads contribute risk identification and mitigation input. Developers flag technical blockers. Escalation paths: Team → PM → Product Lead → Sponsor.

### Release
QA and Support / Operations Leads own release readiness verification. Project Managers coordinate the deployment checklist and window. Security / Compliance Leads sign off on security-sensitive changes. Stakeholders and Product Managers are informed of release timing and announcements.

### Retrospective
Project Managers facilitate the retrospective. All delivery team members (Developers, QA, UX, Technical Lead, Engineering Manager) actively contribute. Product Managers and Support / Operations Leads bring external feedback. Action items are tracked in the project backlog with clear owners and due dates.

---

## Escalation Quick Reference

| Situation | First Contact | Escalate To |
|---|---|---|
| Technical blocker or design dispute | Technical Lead | Engineering Manager → PM |
| Scope or priority conflict | Product Manager | Stakeholder / Sponsor |
| Staffing or capacity risk | Engineering Manager | PM → Sponsor |
| Security finding or compliance gap | Security / Compliance Lead | PM → Sponsor |
| Production incident | Support / Operations Lead | PM → on-call escalation |
| Cross-team dependency delay | PM | Product Lead → Sponsor |

---

*See [OctoAcme Personas](./octoacme-roles-and-personas.md) for full role definitions, responsibilities, and interaction patterns.*
