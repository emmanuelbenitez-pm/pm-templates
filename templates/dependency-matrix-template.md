# Dependency Matrix Template

## 📋 Document Information

| Field | Details |
|-------|---------|
| **Project Name** | [Enter project name] |
| **Project Manager** | [Name] |
| **Date Created** | [MM/DD/YYYY] |
| **Last Updated** | [MM/DD/YYYY] |
| **Version** | [1.0] |
| **Review Frequency** | [Weekly/Bi-weekly] |

---

## 🎯 What is a Dependency Matrix?

A Dependency Matrix tracks relationships between work items, teams, deliverables, or external dependencies where one element depends on another to complete successfully. It helps identify bottlenecks, critical paths, and coordination needs.

### Why Dependencies Matter

**Benefits:**
- ✅ **Identify Bottlenecks** - See what's blocking progress
- ✅ **Coordinate Teams** - Know who needs what from whom
- ✅ **Manage Risk** - Dependencies = risks to schedule
- ✅ **Plan Sequencing** - Understand order of work
- ✅ **Avoid Delays** - Proactive management prevents surprises
- ✅ **Enable Parallel Work** - Identify what can be done simultaneously

**Without Dependency Tracking:**
- ❌ Surprise blockers discovered too late
- ❌ Teams working out of sequence
- ❌ Missed handoffs between teams
- ❌ Integration issues at the end
- ❌ Schedule delays cascade uncontrollably

---

## 📊 Dependency Types

### Common Dependency Categories

#### 1. **Finish-to-Start (FS)** - Most Common
Task B cannot start until Task A finishes

**Example:**
> Requirements (Task A) must finish before Design (Task B) starts

**Notation:** A → B

---

#### 2. **Start-to-Start (SS)**
Task B cannot start until Task A starts

**Example:**
> Frontend development (B) can start when Backend development (A) starts

**Notation:** A ⇉ B

---

#### 3. **Finish-to-Finish (FF)**
Task B cannot finish until Task A finishes

**Example:**
> Testing (B) cannot finish until Development (A) finishes

**Notation:** A ⇛ B

---

#### 4. **Start-to-Finish (SF)** - Rare
Task B cannot finish until Task A starts

**Example:**
> Old system shutdown (B) can't finish until new system goes live (A) starts

**Notation:** A ⥬ B

---

### Dependency Origin

| Type | Description | Example | Management Approach |
|------|-------------|---------|---------------------|
| **Internal** | Within project team control | Team A needs output from Team B | Coordinate internally |
| **External** | Outside project control | Vendor delivery, regulatory approval | Formal tracking, escalation |
| **Mandatory** | Inherent in work nature | Must code before testing | Accept and plan around |
| **Discretionary** | Process/preference based | Code review before merge | Can be challenged/optimized |

---

## 🗂️ Dependency Matrix

### Master Dependency Log

| Dep ID | From (Predecessor) | To (Successor) | Type | Owner | Status | Target Date | Risk Level | Notes |
|--------|-------------------|----------------|------|-------|--------|-------------|------------|-------|
| DEP-001 | Requirements Doc | System Design | FS | [Name] | 🟢 Complete | [MM/DD] | Low | On track |
| DEP-002 | API Development | Frontend Dev | SS | [Name] | 🟡 In Progress | [MM/DD] | Medium | API slightly delayed |
| DEP-003 | Vendor API Access | Integration | FS | [Name] | 🔴 Blocked | [MM/DD] | High | Vendor approval pending |
| DEP-004 | Database Schema | Backend Dev | FS | [Name] | 🟢 Complete | [MM/DD] | Low | Done |
| DEP-005 | Security Review | Production Deploy | FS | [Name] | 🟡 At Risk | [MM/DD] | High | Security team overloaded |

**Status Legend:**
- 🟢 **Complete** - Dependency satisfied
- 🟡 **In Progress / At Risk** - Working but may delay
- 🔴 **Blocked** - Cannot proceed, critical
- ⚪ **Not Started** - Future dependency

**Risk Levels:**
- 🔴 **High** - Will cause >1 week delay if not resolved
- 🟡 **Medium** - Could cause 2-5 day delay
- 🟢 **Low** - Minimal schedule impact

---

## 📋 Detailed Dependency Tracking

### Dependency Entry Template

#### DEP-001: [Dependency Name]

| Field | Details |
|-------|---------|
| **Dependency ID** | DEP-001 |
| **From (Predecessor)** | [Work item / Team / Deliverable that must complete first] |
| **To (Successor)** | [Work item / Team / Deliverable that depends on predecessor] |
| **Dependency Type** | FS / SS / FF / SF |
| **Category** | Internal / External / Mandatory / Discretionary |
| **Description** | [Detailed explanation of the dependency] |

**Example:**
> Frontend team (successor) needs REST API specification (predecessor) completed before they can start building the UI data integration layer.

**Ownership:**
- **Predecessor Owner:** [Name - person delivering the output]
- **Successor Owner:** [Name - person waiting for the output]
- **Dependency Manager:** [Name - person coordinating handoff]

**Timing:**
- **Predecessor Target Date:** [MM/DD/YYYY]
- **Successor Start Date:** [MM/DD/YYYY]
- **Lead Time Required:** [X days for handoff/review]
- **Latest Date (Critical Path):** [MM/DD/YYYY]

**Current Status:**
- **Status:** 🟢 Complete / 🟡 In Progress / 🔴 Blocked / ⚪ Not Started
- **Progress:** [X% complete]
- **Last Updated:** [MM/DD/YYYY]
- **Next Update:** [MM/DD/YYYY]

**Risk Assessment:**
- **Risk Level:** 🔴 High / 🟡 Medium / 🟢 Low
- **Probability of Delay:** High / Medium / Low
- **Impact if Delayed:** [X days delay to successor]
- **On Critical Path:** Yes / No

**Mitigation Plan:**
If this dependency is at risk:
- [Mitigation action 1]
- [Mitigation action 2]
- [Contingency plan]

**Communication:**
- **Last Sync Meeting:** [MM/DD/YYYY]
- **Next Sync Meeting:** [MM/DD/YYYY]
- **Escalation Path:** [Who to escalate to if blocked]

**Handoff Checklist:**
- [ ] Deliverable complete and tested
- [ ] Documentation provided
- [ ] Knowledge transfer session held
- [ ] Successor team has access
- [ ] Acceptance criteria met
- [ ] Formal handoff approved

**Status Log:**
| Date | Status | Update | Updated By |
|------|--------|--------|------------|
| [MM/DD] | ⚪ Not Started | Dependency identified | [Name] |
| [MM/DD] | 🟡 In Progress | Predecessor work started | [Name] |
| [MM/DD] | 🟢 Complete | Handoff complete, successor unblocked | [Name] |

---

## 📊 Dependency Visualization

### Cross-Team Dependency Map
```
TEAM A (Backend)              TEAM B (Frontend)           TEAM C (QA)
     │                              │                         │
     │  DEP-001: API Spec          │                         │
     ├─────────────────────────────>│                         │
     │                              │                         │
     │  DEP-002: API Endpoints     │                         │
     ├─────────────────────────────>│                         │
     │                              │                         │
     │                              │  DEP-005: UI Complete   │
     │                              ├─────────────────────────>│
     │                              │                         │
     │  DEP-006: Integration Help  │                         │
     ├─────────────────────────────────────────────────────────>│
     │                              │                         │
```

### Critical Path Dependencies
```
Start → Requirements → Design → Dev Backend → Dev Frontend → Testing → Deploy → End
        (2 weeks)     (3 wks)   (4 weeks)     (4 weeks)      (2 wks)   (1 wk)

Critical Dependencies:
  DEP-001: Requirements → Design (CRITICAL)
  DEP-003: Dev Backend → Dev Frontend (CRITICAL)
  DEP-007: Testing → Deploy (CRITICAL)
```

---

## 🔄 External Dependencies

### Vendor / Third-Party Dependencies

| Dep ID | Vendor/Partner | What We Need | Target Date | Status | Risk | Owner | Escalation Contact |
|--------|---------------|--------------|-------------|--------|------|-------|-------------------|
| EXT-001 | AWS | Production environment | [MM/DD] | 🟢 | Low | [Name] | [AWS Rep] |
| EXT-002 | Payment Vendor | API credentials | [MM/DD] | 🟡 | Medium | [Name] | [Vendor PM] |
| EXT-003 | Legal | Contract approval | [MM/DD] | 🔴 | High | [Name] | [General Counsel] |
| EXT-004 | IT Ops | Firewall rules | [MM/DD] | 🟡 | Medium | [Name] | [IT Director] |

**External Dependency Management:**

**For Each External Dependency:**
1. **Identify Early** - As soon as possible in planning
2. **Document Formally** - Get commitment in writing
3. **Establish SLA** - Response time, delivery date
4. **Assign Owner** - One person accountable
5. **Weekly Check-ins** - Don't assume, verify
6. **Escalation Path** - Know who to call if blocked
7. **Plan B** - Always have contingency

---

### Regulatory / Compliance Dependencies

| Dep ID | Requirement | Agency/Authority | Expected Date | Actual Date | Status | Risk |
|--------|-------------|------------------|---------------|-------------|--------|------|
| REG-001 | GDPR approval | EU Data Authority | [MM/DD] | [MM/DD] | 🟡 | Medium |
| REG-002 | Security audit | Internal Security | [MM/DD] | - | 🔴 | High |
| REG-003 | Privacy review | Legal | [MM/DD] | [MM/DD] | 🟢 | Low |

---

## 📅 Dependency Management Process

### Weekly Dependency Review

**Meeting:** Dependency Sync  
**Frequency:** Weekly (or daily for critical dependencies)  
**Duration:** 30 minutes  
**Attendees:** Dependency owners, Team leads, PM  

**Agenda:**
1. **Review Red Dependencies** (10 min)
   - Status update
   - Blockers
   - Mitigation actions
   - Escalation decisions

2. **Review Yellow Dependencies** (10 min)
   - Progress update
   - Risks emerging
   - Support needed

3. **Upcoming Dependencies** (5 min)
   - Dependencies due in next 2 weeks
   - Readiness check

4. **New Dependencies** (5 min)
   - Newly identified
   - Assignment

**Output:**
- Updated dependency matrix
- Action items assigned
- Escalations identified

---

### Dependency Handoff Process

**Step 1: Notification (T-2 weeks)**
- Predecessor notifies successor: "We're 2 weeks away"
- Confirm readiness to receive
- Schedule handoff meeting

**Step 2: Pre-Handoff Review (T-1 week)**
- Predecessor: Self-review against acceptance criteria
- Successor: Prepare questions
- Review documentation

**Step 3: Handoff Meeting (T-0)**
- Walkthrough of deliverable
- Q&A session
- Knowledge transfer
- Access provisioning

**Step 4: Acceptance (T+2 days)**
- Successor validates deliverable
- Raise any issues immediately
- Formal acceptance or rejection

**Step 5: Closure (T+1 week)**
- Dependency marked complete
- Lessons learned captured
- Update dependency matrix

---

## ⚠️ Dependency Risk Management

### Risk Assessment

**For Each Dependency, Evaluate:**

| Risk Factor | Low | Medium | High |
|-------------|-----|--------|------|
| **Criticality** | Not on critical path | Near critical path | On critical path |
| **Complexity** | Simple handoff | Moderate coordination | Complex integration |
| **Uncertainty** | Clear requirements | Some ambiguity | Requirements unclear |
| **External** | Internal team | Cross-department | External vendor |
| **Track Record** | Proven reliable | Some delays | History of issues |

**Risk Score:** Low = 1 point, Medium = 2 points, High = 3 points

- **Total 3-5:** 🟢 Low risk
- **Total 6-10:** 🟡 Medium risk  
- **Total 11-15:** 🔴 High risk

---

### Mitigation Strategies

#### For External Dependencies (High Risk)

**Strategy 1: Early Engagement**
- Engage vendor 3x earlier than needed
- Build in 50% time buffer
- Weekly status checks

**Strategy 2: Parallel Path**
- Start work assuming dependency will be ready
- Use mock data/stubs
- Ready to integrate when real dependency arrives

**Strategy 3: Alternative Sources**
- Identify backup vendors
- Have Plan B ready
- Negotiate exit clauses

---

#### For Internal Dependencies

**Strategy 1: Embed Resources**
- Temporarily assign person to other team
- Work together on dependency
- Ensure alignment

**Strategy 2: Swarm**
- Multiple people work on blocker
- Accelerate delivery
- Remove other work temporarily

**Strategy 3: Resequence**
- Change order of work
- Do something else while waiting
- Avoid idle time

---

## 📊 Dependency Metrics

### Key Metrics

| Metric | Target | Current | Status |
|--------|--------|---------|--------|
| **Total Active Dependencies** | - | [#] | - |
| **Critical Path Dependencies** | - | [#] | - |
| **Blocked Dependencies** | 0 | [#] | 🟢🟡🔴 |
| **At-Risk Dependencies** | <10% | [#] ([%]) | 🟢🟡🔴 |
| **Average Dependency Age** | <2 weeks | [X days] | 🟢🟡🔴 |
| **On-Time Handoff Rate** | >90% | [X%] | 🟢🟡🔴 |
| **External Dependency Delays** | 0 | [#] | 🟢🟡🔴 |

---

### Dependency Trends
```
Week 1:  Total: 25  |  🔴 3  |  🟡 8  |  🟢 14
Week 2:  Total: 28  |  🔴 5  |  🟡 10 |  🟢 13  ← Worsening
Week 3:  Total: 30  |  🔴 2  |  🟡 12 |  🟢 16  ← Improving
Week 4:  Total: 27  |  🔴 1  |  🟡 8  |  🟢 18  ← Better
```

**Trend Analysis:**
- Increasing red = Escalate immediately
- Stable yellow = Normal, monitor
- Increasing green = Good progress

---

## 💡 Best Practices

### Dependency Management Do's ✅

1. **Identify Early** - During planning, not execution
2. **Document Everything** - Verbal agreements aren't enough
3. **Assign Clear Owners** - One throat to choke
4. **Communicate Proactively** - Don't assume, verify
5. **Build in Buffers** - External deps need 50%+ buffer
6. **Review Weekly** - Dependencies change, stay current
7. **Escalate Fast** - Don't wait, act immediately
8. **Have Plan B** - Always have contingency

### Dependency Management Don'ts ❌

1. **Don't Ignore External Deps** - They're highest risk
2. **Don't Assume Alignment** - Confirm explicitly
3. **Don't Wait Until Blocked** - Be proactive
4. **Don't Over-Depend** - Minimize dependencies where possible
5. **Don't Skip Documentation** - Future you will thank you
6. **Don't Forget to Close** - Mark complete when done
7. **Don't Accept Vague Commitments** - Get specific dates
8. **Don't Let Dependencies Age** - Old deps are risky deps

---

## 🔔 Escalation Protocol

### When to Escalate

**Escalate to Project Manager:**
- Dependency blocked >3 days
- Predecessor missing target by >1 week
- Communication breakdown between teams

**Escalate to Sponsor:**
- Cross-functional alignment needed
- Resource prioritization conflict
- Budget implications

**Escalate to Executive:**
- Vendor relationship issue
- Major schedule impact (>1 month)
- Strategic decision required

---

### Escalation Template
```
TO: [Escalation Contact]
SUBJECT: [URGENT] Dependency Blocker: [Brief Description]

DEPENDENCY: [DEP-ID] [Dependency Name]

SITUATION:
- Predecessor: [What] owned by [Who]
- Expected: [Date]
- Current Status: [Blocked/Delayed]
- Impact: [X days delay to successor]

ROOT CAUSE:
[Why is this blocked?]

ATTEMPTS TO RESOLVE:
- [Action 1] - Result: [No success]
- [Action 2] - Result: [No success]

ESCALATION REQUEST:
[Specific action needed from escalation contact]

DECISION NEEDED BY: [Date]

Critical Path Impact: YES / NO
```

---

## 📋 Dependency Types by Project Phase

### Planning Phase Dependencies
- Stakeholder approvals
- Budget allocation
- Resource availability
- Vendor selection
- Technology decisions

### Design Phase Dependencies
- Requirements completion
- Architecture decisions
- Security review
- UI/UX approval
- Technical spike results

### Development Phase Dependencies
- API specifications
- Database schema
- Development environment
- Code libraries
- Integration endpoints

### Testing Phase Dependencies
- Development completion
- Test environment
- Test data
- UAT participants
- Defect fixes

### Deployment Phase Dependencies
- Testing sign-off
- Production environment
- Change approval
- Training completion
- Documentation

---

## 📎 Related Templates

- [Risk Register](./risk-register-template.md) - Dependencies are risks
- [RACI Matrix](./raci-matrix-template.md) - Dependency ownership
- [Weekly Status Report](./weekly-status-report-template.md) - Report dependency status
- [Issues Log](./issues-log-template.md) - Track blocked dependencies

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
