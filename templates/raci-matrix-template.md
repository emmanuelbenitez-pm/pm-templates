# RACI Matrix Template

## 📋 What is RACI?

A RACI matrix is a responsibility assignment chart that clarifies roles and responsibilities for project activities and deliverables.

### RACI Definitions

| Letter | Role | Description |
|--------|------|-------------|
| **R** | **Responsible** | Person(s) who do the work to complete the task. Multiple people can be Responsible. |
| **A** | **Accountable** | Person ultimately answerable for the task's completion and has Yes/No authority. Only ONE person should be Accountable. |
| **C** | **Consulted** | People whose opinions are sought; two-way communication. Subject matter experts. |
| **I** | **Informed** | People who are kept up-to-date on progress; one-way communication. |

### Golden Rules
- ✅ **Every task must have at least one R (Responsible)**
- ✅ **Every task must have exactly ONE A (Accountable)** - never more than one!
- ⚠️ **Avoid too many C's** - consulting everyone creates bottlenecks
- ⚠️ **Don't over-inform** - keep I's to need-to-know basis
- ✅ **One person can have multiple roles** - e.g., R and A for the same task

---

## 📊 RACI Matrix Template

### Project Information
- **Project Name:** [Enter project name]
- **Project Manager:** [Name]
- **Date Created:** [MM/DD/YYYY]
- **Last Updated:** [MM/DD/YYYY]
- **Version:** [1.0]

---

## 👥 Team Members / Stakeholders

| ID | Name | Role/Title | Abbreviation |
|----|------|------------|--------------|
| 1 | [Name] | Project Manager | PM |
| 2 | [Name] | Project Sponsor | PS |
| 3 | [Name] | Technical Lead | TL |
| 4 | [Name] | Business Analyst | BA |
| 5 | [Name] | Developer | DEV |
| 6 | [Name] | QA Lead | QA |
| 7 | [Name] | Business Owner | BO |
| 8 | [Name] | Operations Manager | OPS |
| 9 | [Name] | Security Lead | SEC |
| 10 | [Name] | Change Manager | CM |

---

## 📋 RACI Matrix by Phase

### Phase 1: Project Initiation

| Activity / Deliverable | PM | PS | TL | BA | DEV | QA | BO | OPS | SEC | CM |
|------------------------|----|----|----|----|-----|----|----|-----|-----|-----|
| Define project charter | R | A | C | C | I | I | C | I | I | I |
| Secure funding approval | C | A/R | I | I | I | I | C | I | I | I |
| Identify stakeholders | R/A | C | C | C | I | I | C | C | I | C |
| Create project plan | R/A | C | C | C | I | I | C | I | I | C |
| Establish governance | R/A | C | C | I | I | I | C | I | I | I |
| Kickoff meeting | R/A | R | R | R | I | I | R | I | I | I |

### Phase 2: Requirements & Design

| Activity / Deliverable | PM | PS | TL | BA | DEV | QA | BO | OPS | SEC | CM |
|------------------------|----|----|----|----|-----|----|----|-----|-----|-----|
| Gather requirements | C | I | C | R/A | I | I | C | C | I | I |
| Document requirements | C | I | C | R/A | I | C | C | I | I | I |
| Requirements approval | C | A | C | R | I | I | C | I | I | I |
| Design architecture | C | I | R/A | C | C | I | I | C | C | I |
| Security review | C | I | C | I | I | I | I | C | R/A | I |
| Design approval | A | C | R | C | I | I | C | I | C | I |
| Create test strategy | C | I | C | C | I | R/A | I | I | I | I |

### Phase 3: Development

| Activity / Deliverable | PM | PS | TL | BA | DEV | QA | BO | OPS | SEC | CM |
|------------------------|----|----|----|----|-----|----|----|-----|-----|-----|
| Sprint planning | R | I | R | C | R | C | I | I | I | I |
| Code development | C | I | C | I | R | I | I | I | I | I |
| Code review | I | I | R/A | I | R | I | I | I | C | I |
| Unit testing | I | I | C | I | R/A | C | I | I | I | I |
| Integration | C | I | R/A | C | R | I | I | C | I | I |
| Deploy to test env | C | I | C | I | R | I | I | R/A | I | I |

### Phase 4: Testing

| Activity / Deliverable | PM | PS | TL | BA | DEV | QA | BO | OPS | SEC | CM |
|------------------------|----|----|----|----|-----|----|----|-----|-----|-----|
| Create test cases | C | I | C | C | I | R/A | C | I | I | I |
| Execute system testing | C | I | C | C | C | R/A | I | I | I | I |
| Bug triage | C | I | R | C | R | R/A | I | I | I | I |
| UAT coordination | R | I | C | R | C | C | A | C | I | C |
| UAT execution | C | I | I | C | I | C | R/A | C | I | C |
| UAT sign-off | C | A | I | C | I | I | R | I | I | I |
| Security testing | C | I | C | I | I | C | I | I | R/A | I |

### Phase 5: Deployment

| Activity / Deliverable | PM | PS | TL | BA | DEV | QA | BO | OPS | SEC | CM |
|------------------------|----|----|----|----|-----|----|----|-----|-----|-----|
| Deployment plan | R/A | C | R | I | C | I | C | R | C | C |
| Production readiness | C | I | R | I | C | C | C | R/A | C | I |
| Change approval (CAB) | R | A | C | I | I | I | C | C | C | I |
| Deploy to production | C | I | C | I | R | I | I | R/A | C | I |
| Smoke testing | C | I | C | I | C | R/A | I | R | I | I |
| Go/No-Go decision | C | A | R | C | I | C | R | C | C | C |
| Rollback plan execution | C | I | R | I | R | I | I | R/A | I | I |

### Phase 6: Training & Change Management

| Activity / Deliverable | PM | PS | TL | BA | DEV | QA | BO | OPS | SEC | CM |
|------------------------|----|----|----|----|-----|----|----|-----|-----|-----|
| Training materials | C | I | I | R | I | I | C | I | I | R/A |
| User training sessions | C | I | I | R | I | I | C | I | I | R/A |
| Communication plan | R | C | I | C | I | I | C | I | I | R/A |
| Stakeholder comms | R/A | R | I | C | I | I | C | I | I | R |

### Phase 7: Closure & Handoff

| Activity / Deliverable | PM | PS | TL | BA | DEV | QA | BO | OPS | SEC | CM |
|------------------------|----|----|----|----|-----|----|----|-----|-----|-----|
| Documentation handoff | R/A | I | C | C | C | I | I | R | I | I |
| Operations handoff | C | I | R | I | I | I | C | R/A | I | I |
| Support model | C | I | R | I | C | I | C | R/A | I | I |
| Lessons learned | R/A | C | R | R | R | R | C | C | C | C |
| Project closure report | R/A | C | C | C | I | I | C | I | I | I |
| Final sign-off | R | A | I | I | I | I | C | I | I | I |

---

## 📊 Alternative Format: By Deliverable Type

### Technical Deliverables

| Deliverable | PM | TL | DEV | QA | OPS | SEC |
|-------------|----|----|-----|----|----|-----|
| Architecture Design Document | C | R/A | C | I | C | C |
| API Specifications | I | R/A | R | C | I | I |
| Database Schema | I | R/A | R | I | C | C |
| Security Controls | C | C | C | I | C | R/A |
| Deployment Scripts | C | C | R | I | R/A | C |
| Monitoring Setup | C | C | C | I | R/A | I |

### Business Deliverables

| Deliverable | PM | PS | BO | BA | CM |
|-------------|----|----|----|----|-----|
| Business Requirements | C | I | C | R/A | I |
| Process Documentation | C | I | C | R/A | C |
| Training Materials | C | I | C | R | R/A |
| Communication Plan | R | C | C | C | R/A |
| Change Impact Assessment | C | I | C | C | R/A |

### Governance Deliverables

| Deliverable | PM | PS | BO | TL |
|-------------|----|----|----|----|
| Status Reports | R/A | I | I | C |
| Risk Register | R/A | C | C | C |
| Budget Tracking | R/A | C | I | I |
| Change Requests | R/A | A | C | C |
| Steering Committee Materials | R/A | C | C | C |

---

## 🎯 Common RACI Patterns

### Decision Making
- **Strategic decisions:** Sponsor = A, PM = R, Others = C
- **Technical decisions:** Tech Lead = A, Architects = R, PM = C
- **Business decisions:** Business Owner = A, BA = R, PM = C

### Execution
- **Development:** Developers = R, Tech Lead = A, PM = I
- **Testing:** QA = R/A, Developers = C, PM = I
- **Deployment:** Ops = R/A, Developers = C, PM = C

### Communication
- **Executive updates:** PM = R/A, Sponsor = I
- **Team updates:** PM = R/A, Team = I
- **Stakeholder comms:** PM = R, Change Manager = A, Stakeholders = I

---

## ⚠️ Common RACI Mistakes to Avoid

### ❌ Too Many Accountable
**Wrong:**
| Task | PM | Sponsor |
|------|----|----|
| Budget approval | A | A |

**Right:**
| Task | PM | Sponsor |
|------|----|----|
| Budget approval | R | A |

### ❌ No Responsible
**Wrong:**
| Task | PM | Team |
|------|----|----|
| Code review | C | I |

**Right:**
| Task | PM | Team Lead | Dev |
|------|----|----|-----|
| Code review | I | A | R |

### ❌ Too Many Consulted
**Wrong:**
| Task | PM | Dev | QA | Ops | Sec | BA | BO | CM |
|------|----|----|----|----|-----|----|----|-----|
| Write code | C | R | C | C | C | C | C | C |

**Right:**
| Task | PM | Dev | QA | Tech Lead |
|------|----|----|----|----|
| Write code | I | R | I | A |

---

## 💡 Tips for Success

### Creating Your RACI
1. **Start with major deliverables** - don't get too granular initially
2. **Verify exactly ONE A per row** - this is non-negotiable
3. **Limit C's to 2-3 per task** - too many consultations = slow progress
4. **Review with stakeholders** - ensure everyone agrees on their role
5. **Update as project evolves** - RACI is a living document

### Using Your RACI
1. **Reference in meetings** - "Per RACI, John is Accountable for this decision"
2. **Resolve conflicts** - "RACI shows Sarah is Accountable, not Mike"
3. **Onboard new team members** - gives instant clarity on roles
4. **Escalate appropriately** - know who to go to for decisions
5. **Avoid scope creep** - if it's not in RACI, it's out of scope

### Red Flags
- 🚩 **Multiple A's** - creates confusion and delays
- 🚩 **No A** - work falls through the cracks
- 🚩 **Everyone is C** - paralysis by consensus
- 🚩 **RACI never updated** - becomes obsolete and ignored
- 🚩 **Too detailed** - managing at task level, not deliverable level

---

## 📝 Customization Guide

### For Agile/Scrum Projects
- Replace "phases" with "ceremonies" and "artifacts"
- Add roles: Scrum Master, Product Owner
- Focus on sprint-level deliverables

### For Small Projects
- Simplify to 10-15 key deliverables
- Combine similar phases
- Fewer stakeholders to track

### For Large Programs
- Create separate RACI per workstream
- Add program-level governance activities
- Include PMO and portfolio manager

---

## 📎 Related Templates
- [Project Charter](./project-charter-template.md)
- [Stakeholder Analysis](./stakeholder-analysis-template.md)
- [Communication Plan](./communication-plan-template.md)

---

## 📋 Change Log

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | [MM/DD/YYYY] | Emmanuel Benitez | Initial template |

---

**Template Version:** 1.0  
**Last Updated:** January 2026  
**Author:** Emmanuel Benitez  
**Source:** github.com/emmanuelbenitez-pm/pm-templates  
**License:** MIT
