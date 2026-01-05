# Issues Log Template

## 📋 Document Information

| Field | Details |
|-------|---------|
| **Project Name** | [Enter project name] |
| **Project Manager** | [Name] |
| **Date Created** | [MM/DD/YYYY] |
| **Last Updated** | [MM/DD/YYYY] |
| **Version** | [1.0] |

---

## 🎯 What is an Issues Log?

An Issues Log tracks problems that have **already occurred** and require resolution. Unlike risks (which are potential future problems), issues are current obstacles impacting the project **right now**.

### Issue vs Risk

| Aspect | Risk | Issue |
|--------|------|-------|
| **Timing** | Future (might happen) | Present (has happened) |
| **Status** | Uncertain | Certain |
| **Action** | Mitigation/Prevention | Resolution/Fix |
| **Example** | "Vendor might miss deadline" | "Vendor missed deadline" |

---

## 📊 Issue Severity Levels

### Severity Definitions

| Level | Impact | Response Time | Escalation |
|-------|--------|---------------|------------|
| 🔴 **CRITICAL** | Project cannot proceed | Immediate (within hours) | Executive |
| 🟠 **HIGH** | Major impact on timeline/budget | Within 24 hours | Sponsor |
| 🟡 **MEDIUM** | Noticeable impact, workaround exists | Within 3 days | PM discretion |
| 🟢 **LOW** | Minor inconvenience, no real impact | Within 1 week | Team level |

---

## 📋 Active Issues

### 🔴 CRITICAL ISSUES

#### ISSUE-001: [Issue Title]
| Field | Details |
|-------|---------|
| **Issue ID** | ISSUE-001 |
| **Date Identified** | [MM/DD/YYYY] |
| **Category** | Technical / Resource / Schedule / Budget / Quality / External |
| **Severity** | 🔴 Critical |
| **Status** | 🔴 Open / 🟡 In Progress / 🟢 Resolved / ⚫ Closed |
| **Identified By** | [Name] |
| **Assigned To** | [Name - person responsible for resolution] |
| **Target Resolution** | [MM/DD/YYYY] |

**Description:**
[Detailed description of what happened and current situation]

**Impact:**
- **Schedule:** [e.g., 2 week delay to milestone]
- **Budget:** [e.g., $50K additional cost]
- **Scope:** [e.g., Feature X cannot be delivered]
- **Quality:** [e.g., Performance degraded by 40%]
- **Team:** [e.g., Team blocked, cannot proceed]

**Root Cause:**
[Why did this happen? What was the underlying cause?]

**Resolution Plan:**
1. [Action step 1]
2. [Action step 2]
3. [Action step 3]

**Dependencies:**
[What needs to happen first? Who/what are we waiting on?]

**Escalation Path:**
- Level 1: [Project Manager]
- Level 2: [Sponsor]
- Level 3: [Executive]

**Action Items:**
- [ ] [Action 1] - Owner: [Name] - Due: [MM/DD] - Status: [Not Started/In Progress/Complete]
- [ ] [Action 2] - Owner: [Name] - Due: [MM/DD] - Status: [Not Started/In Progress/Complete]

**Status Updates:**
| Date | Update | Updated By |
|------|--------|------------|
| [MM/DD] | [Status update, progress, blockers] | [Name] |
| [MM/DD] | [Status update, progress, blockers] | [Name] |

---

### 🟠 HIGH PRIORITY ISSUES

#### ISSUE-002: [Issue Title]
| Field | Details |
|-------|---------|
| **Issue ID** | ISSUE-002 |
| **Date Identified** | [MM/DD/YYYY] |
| **Category** | [Category] |
| **Severity** | 🟠 High |
| **Status** | [Open/In Progress/Resolved] |
| **Assigned To** | [Name] |
| **Target Resolution** | [MM/DD/YYYY] |

**Description:**
[What happened]

**Impact:**
[How it affects project]

**Resolution Plan:**
[How we'll fix it]

**Action Items:**
- [ ] [Action 1] - Owner: [Name] - Due: [MM/DD]

---

### 🟡 MEDIUM PRIORITY ISSUES

#### ISSUE-003: [Issue Title]
[Similar structure, briefer format]

---

### 🟢 LOW PRIORITY ISSUES

#### ISSUE-004: [Issue Title]
[Similar structure, briefer format]

---

## ✅ RESOLVED ISSUES

### Recently Resolved

#### ~~ISSUE-XXX: [Issue Title]~~
| Field | Details |
|-------|---------|
| **Issue ID** | ISSUE-XXX |
| **Resolved Date** | [MM/DD/YYYY] |
| **Resolution Time** | [X days from identification to resolution] |
| **Severity** | [Original severity] |
| **Category** | [Category] |

**Final Resolution:**
[How it was resolved]

**Lessons Learned:**
[What we learned, how to prevent in future]

**Archived:** [MM/DD/YYYY]

---

## 📊 Issues Dashboard

### Issue Summary
| Status | Critical | High | Medium | Low | Total |
|--------|----------|------|--------|-----|-------|
| 🔴 Open | [#] | [#] | [#] | [#] | [#] |
| 🟡 In Progress | [#] | [#] | [#] | [#] | [#] |
| 🟢 Resolved This Week | [#] | [#] | [#] | [#] | [#] |
| **Total Active** | **[#]** | **[#]** | **[#]** | **[#]** | **[#]** |

### Issues by Category
| Category | Open | In Progress | Total Active |
|----------|------|-------------|--------------|
| Technical | [#] | [#] | [#] |
| Resource | [#] | [#] | [#] |
| Schedule | [#] | [#] | [#] |
| Budget | [#] | [#] | [#] |
| Quality | [#] | [#] | [#] |
| External | [#] | [#] | [#] |

### Aging Report
| Age | Critical | High | Medium | Low |
|-----|----------|------|--------|-----|
| 0-3 days | [#] | [#] | [#] | [#] |
| 4-7 days | [#] | [#] | [#] | [#] |
| 8-14 days | [#] | [#] | [#] | [#] |
| 15+ days 🚩 | [#] | [#] | [#] | [#] |

### Resolution Metrics
| Metric | This Week | Last Week | This Month |
|--------|-----------|-----------|------------|
| Issues Opened | [#] | [#] | [#] |
| Issues Resolved | [#] | [#] | [#] |
| Average Resolution Time | [X days] | [X days] | [X days] |
| Open Backlog | [#] | [#] | [#] |

---

## 🔄 Issue Workflow

### Issue Lifecycle
```
Identified → Logged → Assigned → In Progress → Resolved → Verified → Closed
     ↓          ↓          ↓           ↓            ↓          ↓         ↓
  Someone   Issue ID   Owner     Working on   Solution    Tested   Archived
  spots     created   assigned   resolution   deployed   working   (30 days)
  problem
```

### Status Definitions

| Status | Definition | Next Action |
|--------|------------|-------------|
| **Open** | Issue logged, not yet assigned | Assign owner, prioritize |
| **Assigned** | Owner identified, not started | Owner begins work |
| **In Progress** | Actively working on resolution | Continue to resolution |
| **Resolved** | Solution implemented | Verify solution works |
| **Verified** | Solution confirmed working | Close issue |
| **Closed** | Issue archived | Document lessons learned |

---

## 📋 Issue Categories

### Technical Issues
- Code defects/bugs
- System performance problems
- Integration failures
- Infrastructure issues
- Security vulnerabilities

### Resource Issues
- Team member unavailable
- Skills gap
- Conflicting priorities
- Insufficient resources
- Turnover

### Schedule Issues
- Milestone missed
- Dependency delay
- Underestimated effort
- Rework required
- Blocked work

### Budget Issues
- Cost overrun
- Unexpected expenses
- Vendor price increase
- Currency fluctuation
- Funding shortage

### Quality Issues
- Failed testing
- Requirements not met
- User acceptance problems
- Non-compliance
- Technical debt

### External Issues
- Vendor problems
- Third-party delays
- Regulatory changes
- Market changes
- Client/customer issues

---

## 🎯 Issue Management Process

### Daily Issue Review (15 min)

**Participants:** PM, Tech Lead, Key Owners

**Agenda:**
1. **Critical Issues** (5 min)
   - Status update
   - Blockers
   - Escalation needed?

2. **New Issues** (5 min)
   - Review newly identified
   - Assign severity
   - Assign owner
   - Initial response plan

3. **Resolution Progress** (5 min)
   - High priority issues status
   - Target dates at risk?
   - Help needed?

### Weekly Deep Dive (1 hour)

**Participants:** Full project team

**Agenda:**
1. Review all active issues (30 min)
2. Aging report analysis (10 min)
3. Pattern identification (10 min)
4. Process improvements (10 min)

---

## 💡 Best Practices

### Issue Identification

**Recognize Issues Early:**
- Daily standups surface blockers
- Testing reveals defects immediately
- Metrics/dashboards flag problems
- Team members empowered to raise issues
- Retrospectives identify patterns

**Good Issue Titles:**
- ✅ "Production database crashed, users unable to login"
- ✅ "Key developer John out sick, sprint at risk"
- ✅ "Client rejected UAT results, 3 weeks rework needed"

**Poor Issue Titles:**
- ❌ "Problem"
- ❌ "Issue with system"
- ❌ "Help needed"

### Issue Resolution

**Effective Resolution Plans:**
1. **Specific actions** - Not "fix the problem" but "restart service, restore from backup, test"
2. **Clear ownership** - One person accountable
3. **Realistic timelines** - Based on actual effort
4. **Dependencies identified** - Know what you're waiting for
5. **Escalation criteria** - When to escalate if blocked

**Resolution Approaches:**
- **Workaround:** Temporary fix to keep moving
- **Root Cause Fix:** Permanent solution
- **Rollback:** Undo change that caused issue
- **Escalation:** Get help from higher authority
- **Accept:** Document and live with it

---

## ⚠️ Red Flags

### Issue Management Problems

🚩 **Critical issue open > 24 hours** - Why hasn't it been resolved?

🚩 **Many issues aging > 2 weeks** - Not enough focus on resolution

🚩 **Same issues recurring** - Root cause not addressed

🚩 **Issues discovered late** - Testing/monitoring gaps

🚩 **No clear ownership** - Issues fall through cracks

🚩 **Issues hidden/downplayed** - Team afraid to raise problems

### When to Escalate

**Escalate to Sponsor when:**
- Critical issue blocking project > 24 hours
- Budget overrun required to resolve
- Scope change needed
- Executive decision required
- Multiple teams/vendors involved

**Escalate to Steering Committee when:**
- Multiple critical issues
- Project timeline at significant risk
- Major strategic implications
- Cross-functional alignment needed

---

## 🔄 Issue vs Risk Management

### When Risk Becomes Issue

**Risk:** "Vendor might miss deadline"  
**Trigger:** Deadline passes  
**Becomes Issue:** "Vendor missed deadline, 2 week delay"  

**Process:**
1. Close/archive risk as "Occurred"
2. Create new issue
3. Link risk ID to issue ID for traceability
4. Execute contingency plan from risk register

### Example Flow
```
RISK-005: Vendor delivery delay (Probability: High, Impact: High)
↓ (Trigger event occurs)
ISSUE-012: Vendor delivered 2 weeks late
↓ (Resolution)
Lessons Learned: Add buffer time for vendor deliveries
↓
Update Risk Register: Increase mitigation for future vendor risks
```

---

## 📊 Issue Reporting Templates

### Daily Standup Format

**Issues Update:**
- "ISSUE-003 is blocking Sprint story 42, need DBA help today"
- "ISSUE-007 resolved yesterday, deployment successful"
- "New issue: Test environment down, can't run automated tests"

### Weekly Status Report Section

**Open Issues:**
| ID | Title | Severity | Days Open | Owner | Status |
|----|-------|----------|-----------|-------|--------|
| 001 | [Title] | 🔴 Critical | 2 | [Name] | In Progress |
| 003 | [Title] | 🟠 High | 5 | [Name] | Assigned |

**Resolved This Week:**
- ISSUE-002: Database performance (Resolved: [Date])
- ISSUE-004: Missing requirements (Resolved: [Date])

---

## 📎 Related Templates

- [Risk Register](./risk-register-template.md) - Manage potential future problems
- [Decision Log](./decision-log-template.md) - Document how issues were decided
- [Weekly Status Report](./weekly-status-report-template.md) - Report issues to stakeholders
- [Lessons Learned](./lessons-learned-template.md) - Capture issue patterns

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
