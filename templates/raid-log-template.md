# RAID Log Template
## (Risks, Assumptions, Issues, Dependencies)

## 📋 Document Information

| Field | Details |
|-------|---------|
| **Project Name** | [Enter project name] |
| **Project Manager** | [Name] |
| **Date Created** | [MM/DD/YYYY] |
| **Last Updated** | [MM/DD/YYYY] |
| **Review Frequency** | [Weekly/Bi-weekly] |
| **Version** | [1.0] |

---

## 🎯 What is a RAID Log?

A RAID Log is a consolidated project management tool that tracks four critical elements:
- **R**isks - Potential future problems
- **A**ssumptions - Things we're taking as true
- **I**ssues - Current problems that have occurred
- **D**ependencies - Things we rely on

### Why Use a RAID Log?

**Benefits:**
- ✅ **Single Source of Truth** - All concerns in one place
- ✅ **Holistic View** - See connections between items
- ✅ **Efficient Reviews** - Review all four elements together
- ✅ **Better Risk Management** - Track full lifecycle (assumption → risk → issue)
- ✅ **Proactive Management** - Identify patterns and trends
- ✅ **Clear Ownership** - Every item has an owner

**When to Use:**
- Weekly project reviews
- Status meetings
- Steering committee presentations
- Risk review sessions
- Change control meetings

---

## 📊 RAID Summary Dashboard

### Quick Status Overview

| Category | Total | Critical/High | Medium | Low | Trend |
|----------|-------|---------------|--------|-----|-------|
| **🔴 Risks** | 12 | 3 | 6 | 3 | → |
| **📝 Assumptions** | 8 | 2 | 4 | 2 | ↘️ |
| **⚠️ Issues** | 5 | 1 | 3 | 1 | ↗️ |
| **🔗 Dependencies** | 15 | 4 | 7 | 4 | → |
| **TOTAL** | **40** | **10** | **20** | **10** | → |

**Legend:**
- ↗️ Increasing (needs attention)
- → Stable
- ↘️ Decreasing (improving)

**Overall RAID Health:** 🟡 Medium (10 high/critical items require attention)

---

### Heat Map
```
Risk Probability vs Impact Matrix:

High Prob │ [R3]     [R1, R7]  [R2] 
          │
Med Prob  │ [R5]     [R4, R8]  [R6]
          │
Low Prob  │ [R9,R10] [R11]     [R12]
          └─────────────────────────
            Low        Medium    High
                    Impact
```

---

## 🔴 RISKS (Potential Future Problems)

### Active Risks

#### RISK-001: Vendor Delivery Delay 🔴 CRITICAL

| Field | Details |
|-------|---------|
| **Risk ID** | RISK-001 |
| **Category** | External / Vendor |
| **Status** | 🔴 Open |
| **Date Identified** | [MM/DD/YYYY] |
| **Identified By** | [Name] |
| **Owner** | [Name] |
| **Probability** | High (70%) |
| **Impact** | High (>2 weeks delay) |
| **Risk Score** | 🔴 9 (High × High) |
| **Proximity** | 2 weeks |

**Description:**
Key vendor (AWS) may not deliver production environment setup by required date due to their resource constraints.

**Trigger Events:**
- Vendor misses checkpoint on [MM/DD]
- Vendor requests deadline extension
- Vendor communication becomes sparse

**Impact if Occurs:**
- Project delayed by 2-4 weeks
- Go-live date missed
- Budget overrun ($50K for extended team costs)
- Stakeholder confidence impacted

**Probability Assessment:**
- Vendor has missed 1 of 3 previous milestones
- Vendor expressed concerns about timeline
- Vendor assigned junior resources
- Similar projects with vendor had delays

**Mitigation Strategy (Reduce Probability):**
- ✅ Weekly status calls with vendor (every Monday)
- ✅ Escalation to vendor account manager
- ✅ Daily check-ins during critical phase
- ⏳ Consider adding vendor resources (their cost)

**Contingency Plan (Reduce Impact if Occurs):**
- Backup vendor identified (Azure) - 1 week to switch
- Parallel path: Start development on dev environment
- Resequence work to delay vendor dependency
- Executive escalation to vendor VP

**Current Mitigation Progress:**
- Weekly calls established ✅
- Escalation meeting scheduled for [MM/DD]
- Backup vendor quoted ($60K)

**Cost of Mitigation:** $5K (weekly calls, escalation time)  
**Cost of Contingency:** $60K (switch to backup vendor)  
**Cost if Risk Occurs:** $100K (delay costs + team overtime)

**Last Review:** [MM/DD/YYYY]  
**Next Review:** [MM/DD/YYYY]  
**Trend:** → Stable (monitoring closely)

---

#### RISK-002: Key Resource Departure 🔴 HIGH

| Field | Details |
|-------|---------|
| **Risk ID** | RISK-002 |
| **Category** | Internal / Resource |
| **Status** | 🔴 Open |
| **Probability** | Medium (40%) |
| **Impact** | High (loss of critical knowledge) |
| **Risk Score** | 🔴 8 (Medium × High) |
| **Owner** | [PM] |

**Description:**
Lead architect (John Doe) has been approached by competitor. If he leaves, project loses critical technical knowledge and decision-making capability.

**Impact:**
- 3-4 week delay to find replacement
- Knowledge transfer time (2 weeks minimum)
- Design decisions may need re-evaluation
- Team morale impact

**Mitigation:**
- Cross-training: Backend lead shadowing architect
- Document all architectural decisions (ADRs)
- Retention conversation with HR
- Knowledge transfer sessions (2/week)

**Contingency:**
- Promote backend lead to interim architect
- Contract with external architect consultant
- Delay non-critical features

**Status:** Cross-training 50% complete, ADRs 80% documented

---

#### RISK-003: Scope Creep 🟡 MEDIUM

[Similar structure]

---

### Risk Categories

| Category | Count | Critical/High | Example |
|----------|-------|---------------|---------|
| Technical | 4 | 2 | Technology choice doesn't scale |
| Resource | 3 | 2 | Key person leaves |
| External | 2 | 1 | Vendor delay |
| Schedule | 2 | 0 | Integration takes longer |
| Budget | 1 | 0 | Currency fluctuation |

---

### Closed Risks (Occurred or Retired)

| Risk ID | Description | Date Closed | Outcome |
|---------|-------------|-------------|---------|
| RISK-004 | Security audit delay | [MM/DD] | ✅ Mitigated - audit completed early |
| RISK-005 | Database license cost | [MM/DD] | ✅ Retired - negotiated better pricing |
| RISK-006 | Testing environment | [MM/DD] | ❌ Occurred - became ISSUE-003 |

---

## 📝 ASSUMPTIONS (Things We're Taking as True)

### Active Assumptions

#### ASMP-001: User Adoption Rate 🟡 MEDIUM IMPACT

| Field | Details |
|-------|---------|
| **Assumption ID** | ASMP-001 |
| **Category** | Business |
| **Status** | 🟡 Active (unvalidated) |
| **Date Recorded** | [MM/DD/YYYY] |
| **Owner** | [Product Owner] |
| **Impact if Wrong** | High |
| **Validation Status** | Not yet validated |
| **Validation Date** | [MM/DD/YYYY] |

**Assumption:**
"80% of users will adopt the new system within 3 months of launch."

**Why We're Assuming This:**
- User survey showed 85% positive interest
- Similar rollout achieved 75% adoption
- Strong executive sponsorship

**Impact if Wrong:**
- Lower ROI than projected
- Business case doesn't materialize
- Training costs higher (need more sessions)
- Budget pressure for Year 2

**How We'll Validate:**
- Post-launch adoption tracking (weekly)
- User feedback surveys (monthly)
- Usage analytics dashboard

**What We'll Do if Wrong:**
- Enhanced change management program
- Executive-led adoption campaign  
- Additional training sessions
- Gamification/incentives for adoption

**Probability of Being Correct:** Medium (60%)

**Related Risks:** RISK-007 (Low adoption leads to project failure)

**Validation Plan:**
- Week 1: 20% target
- Month 1: 50% target
- Month 3: 80% target (validate assumption)

---

#### ASMP-002: Technical Capability 🟠 HIGH IMPACT

**Assumption:**
"Current infrastructure can handle 3x traffic increase without significant upgrades."

**Why Assumed:**
- Vendor claims scalability
- Preliminary testing showed capacity
- Architecture designed for scale

**Impact if Wrong:**
- Need infrastructure upgrades ($100K)
- Performance issues post-launch
- User dissatisfaction
- Possible production outages

**Validation:**
- Load testing at 3x volume (Week 15)
- Infrastructure review by vendor (Week 16)
- Production trial with subset of users (Week 17)

**Status:** 🟡 Not yet validated (testing planned)

---

#### ASMP-003: Budget Stability 🟢 LOW IMPACT

[Similar structure]

---

### Assumption Categories

| Category | Count | High Impact | Status |
|----------|-------|-------------|--------|
| Business | 3 | 1 | 2 validated, 1 pending |
| Technical | 2 | 1 | 1 validated, 1 pending |
| Resource | 2 | 0 | Both validated |
| Schedule | 1 | 0 | Validated |

---

### Validated Assumptions

| Asmp ID | Assumption | Date Validated | Result |
|---------|------------|----------------|--------|
| ASMP-004 | Team availability | [MM/DD] | ✅ Confirmed - team fully allocated |
| ASMP-005 | API compatibility | [MM/DD] | ✅ Confirmed - integration tested |

---

### Invalidated Assumptions (Became Risks)

| Asmp ID | Assumption | Date Invalidated | Became |
|---------|------------|------------------|--------|
| ASMP-006 | Timeline feasibility | [MM/DD] | RISK-008 (Schedule risk) |

---

## ⚠️ ISSUES (Current Problems)

### Active Issues

#### ISSUE-001: Production Environment Not Ready 🔴 CRITICAL

| Field | Details |
|-------|---------|
| **Issue ID** | ISSUE-001 |
| **Category** | External / Infrastructure |
| **Severity** | 🔴 Critical |
| **Status** | 🟡 In Progress |
| **Date Opened** | [MM/DD/YYYY] |
| **Date Due** | [MM/DD/YYYY] (3 days) |
| **Reported By** | [DevOps Lead] |
| **Owner** | [Vendor PM] |
| **Age** | 5 days |
| **Impact** | Go-live at risk |

**Description:**
Production environment setup delayed. Vendor missed milestone by 1 week. Environment needed for final testing in 3 days.

**Business Impact:**
- Go-live date at risk (7 days delay if not resolved)
- Final UAT cannot proceed
- Training on production environment blocked
- Stakeholder confidence eroding

**Root Cause:**
- Vendor resource assigned to emergency for another client
- Underestimated complexity of our network requirements
- Communication breakdown (vendor didn't escalate early)

**Steps Taken:**
1. [MM/DD] Escalated to vendor account manager ✅
2. [MM/DD] Daily status calls established ✅
3. [MM/DD] Vendor added 2nd resource ✅
4. [MM/DD] Working weekend to catch up 🟡 In Progress

**Current Status:**
Environment 80% complete. On track to finish by [MM/DD] (2 days late).

**Resolution Plan:**
- Vendor completes by [MM/DD]
- Our team validates immediately
- Compress UAT by 2 days (manageable)
- Parallel final testing and training

**Workaround:**
- Continue testing in staging environment
- Delay some production-specific tests

**Escalation:**
- Level 1: Vendor PM (current)
- If not resolved by [MM/DD]: Escalate to vendor VP
- If not resolved by [MM/DD]: Escalate to our CTO + sponsor

**Financial Impact:**
- Delay cost: $10K (team idle time)
- Recovery cost: $5K (weekend work)

**Lessons Learned (when closed):**
[To be filled upon resolution]

---

#### ISSUE-002: Test Data Quality 🟠 HIGH

| Field | Details |
|-------|---------|
| **Issue ID** | ISSUE-002 |
| **Severity** | 🟠 High |
| **Status** | 🟡 In Progress |
| **Age** | 8 days |
| **Owner** | [BA] |

**Description:**
Test data doesn't represent production scenarios. QA finding issues that should have been caught earlier.

**Impact:**
- Low confidence in test results
- Bugs escaping to UAT
- Extended testing cycle (+1 week)

**Resolution:**
- BA creating production-like dataset
- Expected completion: [MM/DD]
- Retest affected areas

**Status:** 60% complete

---

#### ISSUE-003: Integration Performance 🟡 MEDIUM

[Similar structure]

---

### Issue Aging Report

| Severity | 0-3 days | 4-7 days | 8-14 days | 15+ days | Total |
|----------|----------|----------|-----------|----------|-------|
| Critical | 0 | 1 | 0 | 0 | 1 |
| High | 1 | 0 | 1 | 0 | 2 |
| Medium | 1 | 0 | 1 | 0 | 2 |
| **Total** | **2** | **1** | **2** | **0** | **5** |

**Aging Threshold:** Issues >14 days require executive escalation

---

### Closed Issues

| Issue ID | Description | Date Closed | Resolution Time | Outcome |
|----------|-------------|-------------|-----------------|---------|
| ISSUE-004 | API timeout | [MM/DD] | 3 days | ✅ Fixed - increased timeout |
| ISSUE-005 | Login bug | [MM/DD] | 1 day | ✅ Fixed - code error |

---

### Issue to Risk Conversion

Some issues, if not resolved, become risks for future sprints:

| Issue ID | Description | Could Become Risk |
|----------|-------------|-------------------|
| ISSUE-001 | Prod environment | RISK-009 (If pattern continues) |
| ISSUE-002 | Test data quality | RISK-010 (Data quality in production) |

---

## 🔗 DEPENDENCIES (Things We Rely On)

### Active Dependencies

#### DEP-001: Vendor API Access 🔴 CRITICAL

| Field | Details |
|-------|---------|
| **Dependency ID** | DEP-001 |
| **Type** | External / Vendor |
| **Category** | FS (Finish-to-Start) |
| **Status** | 🔴 Blocked |
| **Date Identified** | [MM/DD/YYYY] |
| **Owner** | [Architect] |
| **From (Predecessor)** | Vendor API credentials |
| **To (Successor)** | Payment integration development |
| **Target Date** | [MM/DD/YYYY] |
| **Actual/Forecast Date** | [MM/DD/YYYY] (+1 week late) |
| **Impact** | High (blocks payment feature) |

**Description:**
We need production API credentials from payment vendor to complete payment integration. Vendor approval process taking longer than expected.

**Impact of Delay:**
- Payment feature delayed by 1 week
- Cannot test end-to-end checkout flow
- Go-live at risk if not resolved soon
- May need to descope payment feature

**Why Blocked:**
- Vendor security review taking 3 weeks (expected 1 week)
- Additional paperwork requested by vendor legal
- Vendor assigned junior resource to our request

**Actions Taken:**
- [MM/DD] Submitted application ✅
- [MM/DD] Followed up with vendor ✅
- [MM/DD] Escalated to vendor account manager ✅
- [MM/DD] Executive call scheduled 🟡 Pending

**Mitigation:**
- Use vendor sandbox API for development (limited functionality)
- Parallel development of other features
- Plan to compress testing if credentials arrive late

**Contingency:**
- Defer payment feature to Phase 2 if not received by [MM/DD]
- Use alternative payment provider (takes 2 weeks to setup)

**Communication:**
- Daily check-in with vendor
- Weekly update to stakeholders
- Escalation path documented

**Dependency Manager:** [Architect]  
**Next Check:** [MM/DD/YYYY]

---

#### DEP-002: UAT User Availability 🟡 AT RISK

| Field | Details |
|-------|---------|
| **Dependency ID** | DEP-002 |
| **Type** | Internal / Resource |
| **Status** | 🟡 At Risk |
| **From** | Business users (20 people) |
| **To** | UAT Testing |
| **Target Date** | [MM/DD/YYYY] |
| **Impact** | Medium |

**Description:**
Need 20 business users for UAT testing. Some users have competing priorities and limited availability.

**Actions:**
- Secured executive sponsor email requesting participation
- Created flexible UAT schedule (3 time slots)
- Offering training credit for participation

**Status:** 15/20 users confirmed, 5 pending

---

#### DEP-003: Database Schema Finalization 🟢 ON TRACK

[Similar structure]

---

### Dependency Map
```
External Dependencies:
Vendor API (DEP-001) ──────► Payment Integration ──────► Checkout Flow
         │                          │                          │
         └──[BLOCKED]               └──[WAITING]              └──[BLOCKED]

Internal Dependencies:
Requirements ──► Design ──► Development ──► Testing ──► Deployment
   [DONE]       [DONE]     [IN PROGRESS]   [WAITING]   [WAITING]

Cross-Team Dependencies:
Backend Team ──────► API Complete ──────► Frontend Team
   [80%]                                      [WAITING]
```

---

### Dependency Categories

| Category | Total | Critical | Blocked | At Risk | On Track |
|----------|-------|----------|---------|---------|----------|
| External | 6 | 2 | 1 | 2 | 3 |
| Internal | 5 | 1 | 0 | 1 | 4 |
| Cross-Team | 4 | 1 | 0 | 2 | 2 |
| **Total** | **15** | **4** | **1** | **5** | **9** |

---

### Resolved Dependencies

| Dep ID | Description | Date Resolved | Resolution |
|--------|-------------|---------------|------------|
| DEP-004 | Legal approval | [MM/DD] | ✅ Approved on schedule |
| DEP-005 | Hardware delivery | [MM/DD] | ✅ Delivered 2 days early |

---

## 📊 RAID Analysis & Trends

### Weekly RAID Trends
```
RAID Items Over Time:
Week 1:  Risks: 8  | Assumptions: 10 | Issues: 2  | Dependencies: 12
Week 2:  Risks: 10 | Assumptions: 9  | Issues: 4  | Dependencies: 14
Week 3:  Risks: 11 | Assumptions: 9  | Issues: 3  | Dependencies: 15
Week 4:  Risks: 12 | Assumptions: 8  | Issues: 5  | Dependencies: 15  ← Current
```

**Analysis:**
- Risks increasing (8→12): New risks identified, proactive
- Assumptions decreasing (10→8): Good - validating assumptions
- Issues fluctuating (2→5): Within normal range
- Dependencies stable (12→15): Expected as project progresses

---

### RAID Interconnections

**Examples of RAID Item Relationships:**

**Assumption → Risk → Issue Chain:**
```
ASMP-006 (Timeline feasible)
    ↓ [Invalidated]
RISK-008 (Schedule at risk)
    ↓ [If occurs]
ISSUE-XXX (Project delayed)
```

**Dependency → Risk:**
```
DEP-001 (Vendor API blocked)
    ↓ [If continues]
RISK-011 (Payment feature at risk)
```

**Issue → Risk:**
```
ISSUE-002 (Test data quality)
    ↓ [Pattern continues]
RISK-010 (Production data quality issues)
```

---

### Critical Path Impact

**RAID Items Affecting Critical Path:**
- 🔴 RISK-001 (Vendor delay) - On critical path
- 🔴 ISSUE-001 (Prod environment) - On critical path
- 🔴 DEP-001 (Vendor API) - On critical path
- 🟡 DEP-002 (UAT users) - Near critical path

**Total critical path items:** 4 (HIGH PRIORITY)

---

## 🎯 RAID Review Meeting

### Weekly RAID Review Agenda

**Frequency:** Every Monday, 1:00 PM  
**Duration:** 60 minutes  
**Attendees:** PM, Tech Lead, Business Owner, Key Stakeholders

**Agenda:**

**1. Review Critical Items (20 min)**
- All RED items (critical/high)
- Any items on critical path
- Items approaching deadline
- Escalation decisions

**2. New Items (10 min)**
- New risks identified
- New assumptions documented
- New issues logged
- New dependencies added

**3. Status Updates (15 min)**
- Progress on mitigation plans
- Dependency status checks
- Issue resolution progress
- Assumption validation updates

**4. Trends & Patterns (10 min)**
- RAID trend analysis
- Interconnections identified
- Early warning signals

**5. Action Items (5 min)**
- Assign owners
- Set deadlines
- Confirm next steps

---

### RAID Review Checklist

**Before Meeting:**
- [ ] Update all RAID items
- [ ] Identify items for discussion
- [ ] Prepare status updates
- [ ] Review previous action items

**During Meeting:**
- [ ] Review all critical/high items
- [ ] Update statuses
- [ ] Assign action items
- [ ] Document decisions

**After Meeting:**
- [ ] Send meeting notes
- [ ] Update RAID log
- [ ] Follow up on action items
- [ ] Schedule next review

---

## 💡 Best Practices

### RAID Management Do's ✅

1. **Review Weekly** - Don't let RAID log go stale
2. **Be Proactive** - Identify items early
3. **Assign Owners** - Every item needs an owner
4. **Track Trends** - Look for patterns
5. **Connect Items** - Show relationships between RAID elements
6. **Validate Assumptions** - Don't let them stay "assumed" forever
7. **Close Items** - Document outcomes when resolved
8. **Escalate Promptly** - Don't wait too long

### RAID Management Don'ts ❌

1. **Don't Ignore** - Empty RAID log = not managing
2. **Don't Duplicate** - Use other detailed logs (Risk Register, Issues Log)
3. **Don't Over-Detail** - Keep it high-level, link to details
4. **Don't Let Items Age** - Stale items lose relevance
5. **Don't Skip Reviews** - Consistency matters
6. **Don't Forget Assumptions** - Most forgotten element
7. **Don't Confuse Risk and Issue** - Risk = future, Issue = current
8. **Don't Orphan Items** - Always have an owner

---

## 📎 Related Templates

- [Risk Register](./risk-register-template.md) - Detailed risk management
- [Issues Log](./issues-log-template.md) - Detailed issue tracking
- [Dependency Matrix](./dependency-matrix-template.md) - Detailed dependency management
- [Weekly Status Report](./weekly-status-report-template.md) - Include RAID summary

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
