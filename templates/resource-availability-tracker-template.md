# Resource Availability Tracker Template

## 📋 Document Information

| Field | Details |
|-------|---------|
| **Project Name** | [Enter project name] |
| **Project Manager** | [Name] |
| **Reporting Period** | [Month/Quarter/Year] |
| **Last Updated** | [MM/DD/YYYY] |
| **Version** | [1.0] |

---

## 🎯 Purpose

Track team member availability including vacations, sick leave, training, holidays, and other absences to proactively manage resource capacity and prevent project delays.

### Why This Matters

**Benefits:**
- ✅ **Proactive Planning** - No surprise absences
- ✅ **Capacity Management** - Know actual available hours
- ✅ **Risk Mitigation** - Identify single points of failure
- ✅ **Fair Distribution** - Balance workload across team
- ✅ **Compliance** - Track PTO usage, labor regulations
- ✅ **Forecasting** - Accurate timeline predictions

**Without This Tracking:**
- ❌ Unexpected delays when people are unavailable
- ❌ Overcommitment based on theoretical capacity
- ❌ Burnout from not tracking actual availability
- ❌ Conflicts from overlapping absences
- ❌ Poor sprint planning

---

## 👥 Team Roster

### Core Team Members

| ID | Name | Role | Email | Manager | Allocation | Start Date | End Date |
|----|------|------|-------|---------|------------|------------|----------|
| R-01 | [Name] | [Role] | [Email] | [Manager] | 100% | [MM/DD/YYYY] | [MM/DD/YYYY or Ongoing] |
| R-02 | [Name] | [Role] | [Email] | [Manager] | 50% | [MM/DD/YYYY] | [MM/DD/YYYY or Ongoing] |
| R-03 | [Name] | [Role] | [Email] | [Manager] | 75% | [MM/DD/YYYY] | [MM/DD/YYYY or Ongoing] |

**Notes:**
- **Allocation %** = Percentage of time dedicated to this project
- 100% = Full-time on project
- 50% = Split between this and other projects
- Start/End dates track team member tenure on project

---

## 📅 Availability Calendar

### Month: [Month Year]

| Team Member | Week 1 | Week 2 | Week 3 | Week 4 | Total Days Off | Effective Days |
|-------------|--------|--------|--------|--------|----------------|----------------|
| [Name 1] | 🟢🟢🟢🟢🟢 | 🔴🔴🟢🟢🟢 | 🟢🟢🟢🟢🟢 | 🟢🟢🟢🟢🟡 | 3 | 17/20 |
| [Name 2] | 🟢🟢🟢🟢🟢 | 🟢🟢🟢🟢🟢 | 🟢🟢🟢🟢🟢 | 🟢🟢🟢🟢🟢 | 0 | 20/20 |
| [Name 3] | 🟢🟢🟢🟢🟢 | 🟢🟢🟢🟢🟢 | 🟡🟡🟡🟡🟡 | 🟢🟢🟢🟢🟢 | 5 | 15/20 |

**Legend:**
- 🟢 Available (Working day)
- 🔴 Vacation/PTO (Planned time off)
- 🟡 Training/Conference (Not on project work)
- 🟠 Sick Leave (Unplanned absence)
- ⚪ Public Holiday
- 🔵 Other Project (Shared resource working elsewhere)

**Summary:**
- Total Team Days Available: [X days]
- Total Team Days Off: [Y days]
- Team Capacity: [Z%]

---

## 📋 Detailed Absence Log

### Upcoming Absences (Next 30 Days)

| ID | Team Member | Type | Start Date | End Date | Duration | Status | Impact | Mitigation |
|----|-------------|------|------------|----------|----------|--------|--------|------------|
| A-001 | [Name] | Vacation | [MM/DD] | [MM/DD] | 5 days | ✅ Approved | Medium | [Name] covers |
| A-002 | [Name] | Conference | [MM/DD] | [MM/DD] | 3 days | ✅ Approved | Low | Async work |
| A-003 | [Name] | Medical | [MM/DD] | [MM/DD] | 2 days | 🟡 Pending | High | Delay tasks |

---

### Absence Entry Template

#### Absence ID: A-[###]

| Field | Details |
|-------|---------|
| **Team Member** | [Name, Role] |
| **Absence Type** | Vacation / Sick Leave / Training / Conference / Personal / Maternity/Paternity / Jury Duty / Bereavement / Other |
| **Start Date** | [MM/DD/YYYY] |
| **End Date** | [MM/DD/YYYY] |
| **Total Days** | [X working days] |
| **Request Date** | [MM/DD/YYYY] |
| **Status** | 🟡 Requested / ✅ Approved / ❌ Denied / 🔄 Modified / ⚫ Cancelled |
| **Approved By** | [Manager Name] |
| **Approval Date** | [MM/DD/YYYY] |

**Reason/Notes:**
[Brief explanation if relevant - not required for PTO]

**Work Impact:**
- **Tasks Affected:** [List of tasks/stories]
- **Criticality:** 🔴 Critical / 🟠 High / 🟡 Medium / 🟢 Low
- **Dependencies:** [Who/what depends on this person]

**Coverage Plan:**
- **Primary Backup:** [Name]
- **Secondary Backup:** [Name if needed]
- **Handoff Completed:** ✅ Yes / 🟡 In Progress / ❌ No / N/A
- **Knowledge Transfer:** [Document link or N/A]

**Approval Conditions:**
[Any conditions for approval, e.g., "Must complete X before leaving"]

---

## 📊 Absence Type Breakdown

### Vacation/PTO

#### [Team Member Name]
| Field | Details |
|-------|---------|
| **Annual Allocation** | [X days per year] |
| **Used YTD** | [Y days] |
| **Remaining** | [Z days] |
| **Planned/Approved** | [A days] |
| **Available to Use** | [Z - A days] |

**Upcoming Vacations:**
- [MM/DD - MM/DD]: [X days]
- [MM/DD - MM/DD]: [X days]

**Vacation Policy Notes:**
- Blackout dates: [e.g., Week of product launch]
- Advance notice required: [e.g., 2 weeks for >5 days]
- Maximum consecutive days: [e.g., 15 days]

---

### Sick Leave

| Team Member | Total Sick Days YTD | Recent Absences | Pattern Noticed | Action Needed |
|-------------|---------------------|-----------------|-----------------|---------------|
| [Name] | 3 days | [MM/DD (1), MM/DD (2)] | None | None |
| [Name] | 8 days | [MM/DD (3), MM/DD (5)] | Frequent | HR follow-up |

**Sick Leave Policy:**
- Notice required: As soon as possible
- Documentation required: After 3 consecutive days
- Reporting: Notify manager and PM

---

### Training & Development

| Training | Dates | Duration | Attendees | Impact | Business Value |
|----------|-------|----------|-----------|--------|----------------|
| AWS Certification | [MM/DD - MM/DD] | 5 days | [Name, Name] | Medium | High - needed for project |
| Agile Workshop | [MM/DD] | 1 day | [Full team] | High | Medium - team building |
| Conference | [MM/DD - MM/DD] | 3 days | [Name] | Low | High - industry knowledge |

---

### Public Holidays

#### [Year] Holiday Calendar

| Date | Holiday | Day of Week | Impact |
|------|---------|-------------|--------|
| [MM/DD] | [Holiday Name] | [Monday] | Team unavailable |
| [MM/DD] | [Holiday Name] | [Friday] | Team unavailable |
| [MM/DD] | [Holiday Name] | [Monday] | Team unavailable |

**Regional Variations:**
- US Team: [List US holidays]
- Mexico Team: [List Mexico holidays]
- India Team: [List India holidays]

**Cross-Regional Planning:**
- Ensure handoffs before holidays
- Plan sprints around major holidays
- No deployments on holiday weeks

---

### Extended Leave

#### Maternity/Paternity Leave

| Team Member | Type | Start Date | Expected Return | Duration | Coverage |
|-------------|------|------------|-----------------|----------|----------|
| [Name] | Maternity | [MM/DD] | [MM/DD] | 12 weeks | [Name] |
| [Name] | Paternity | [MM/DD] | [MM/DD] | 2 weeks | Team coverage |

**Transition Plan:**
- 4 weeks before: Knowledge transfer begins
- 2 weeks before: Handoff complete
- During leave: [Name] assumes responsibilities
- Return: 2-week ramp-up period

#### Medical/Disability Leave

| Team Member | Start Date | Expected Return | Status | Coverage Plan |
|-------------|------------|-----------------|--------|---------------|
| [Name] | [MM/DD] | [TBD] | Ongoing | Backfill contractor hired |

---

## 📊 Capacity Planning

### Weekly Capacity Summary

| Week Of | Total Capacity | Available Hours | Planned Absences | Actual Hours | Variance |
|---------|----------------|-----------------|------------------|--------------|----------|
| [MM/DD] | 400 hours | 380 hours | 20 hours (1 person vacation) | 375 hours | -5 hours |
| [MM/DD] | 400 hours | 360 hours | 40 hours (2 people out) | 365 hours | +5 hours |
| [MM/DD] | 400 hours | 400 hours | 0 hours | 390 hours | -10 hours |

**Calculation:**
- Total Capacity = Team Size × Hours/Week × Allocation%
- Available Hours = Total Capacity - Planned Absences
- Variance = Actual - Available (positive = overtime, negative = underutilized)

---

### Sprint Capacity Planning

#### Sprint [#]: [Start Date - End Date]

| Team Member | Allocation | Total Hours | Planned Absence | Available Hours | Committed Work |
|-------------|------------|-------------|-----------------|-----------------|----------------|
| [Name] | 100% | 80 hours | 16 hours (vacation) | 64 hours | 60 hours |
| [Name] | 50% | 40 hours | 0 hours | 40 hours | 38 hours |
| [Name] | 100% | 80 hours | 8 hours (training) | 72 hours | 70 hours |
| **TOTAL** | | **200 hours** | **24 hours** | **176 hours** | **168 hours** |

**Sprint Notes:**
- Capacity: 176 hours available
- Committed: 168 hours (95% capacity) ✅ Good
- Buffer: 8 hours for unknowns
- Velocity estimate: [X story points]

---

## ⚠️ Conflict Resolution

### Overlapping Absences

| Dates | Team Members Out | Roles Affected | Risk Level | Resolution |
|-------|------------------|----------------|------------|------------|
| [MM/DD - MM/DD] | [Name], [Name] | 2 Backend Devs | 🔴 High | [Name] delays vacation 1 week |
| [MM/DD - MM/DD] | [Name], [Name] | QA, BA | 🟡 Medium | Acceptable, different functions |

**Conflict Prevention Rules:**
- Maximum 1 person per critical role absent simultaneously
- No more than 30% of team out at once
- Advance notice required for conflict resolution

---

### Single Point of Failure (SPOF) Analysis

| Role/Skill | Primary Person | Backup | Cross-Training Status | Risk |
|------------|----------------|--------|-----------------------|------|
| DevOps | [Name] | None | 🔴 Not started | 🔴 High |
| Database | [Name] | [Name] | 🟡 In progress | 🟡 Medium |
| Frontend | [Name] | [Name], [Name] | 🟢 Complete | 🟢 Low |

**SPOF Mitigation Plan:**
- 🔴 High Risk: Immediate cross-training needed
- 🟡 Medium Risk: Cross-training in progress
- 🟢 Low Risk: Multiple people capable

---

## 📈 Analytics & Reporting

### Absence Trends

#### Monthly Absence Rate
```
Jan 2026: ████████ (8%)
Feb 2026: ██████ (6%)
Mar 2026: ████████████ (12%) ⚠️ High
Apr 2026: ██████ (6%)
```

**Target:** <10% absence rate per month

#### Absence by Type (YTD)
- Vacation/PTO: 65% (expected)
- Sick Leave: 20% (acceptable)
- Training: 10% (good investment)
- Other: 5%

#### Peak Absence Periods
- December: 15% (holiday season) ⚠️
- July-August: 12% (summer vacations) ⚠️
- March: 3% (low)

**Lessons Learned:**
- Avoid critical milestones in Dec/Jul-Aug
- Plan buffer time during peak absence months
- Encourage PTO during low-activity periods

---

### Team Member Patterns

| Team Member | Absence Days YTD | Absence Rate | Pattern | Notes |
|-------------|------------------|--------------|---------|-------|
| [Name] | 12 days | 5% | Consistent | Planned vacations |
| [Name] | 28 days | 12% | High | Mostly medical - HR aware |
| [Name] | 5 days | 2% | Low | May have unused PTO risk |

---

## 📋 Processes & Policies

### Absence Request Process

**Step 1: Request Submission**
- Submit request to manager minimum [X days] in advance
- Use [system/form/email]
- Include dates, type, business justification if needed

**Step 2: Manager Review**
- Check team capacity
- Review project impact
- Identify conflicts
- Approve/deny/modify within [Y days]

**Step 3: PM Notification**
- Manager notifies PM of all approved absences
- PM updates resource tracker
- PM assesses project impact

**Step 4: Coverage Planning**
- Identify backup resources
- Complete knowledge transfer
- Update project schedule if needed

**Step 5: Team Communication**
- Announce absence to team [Z days] in advance
- Update shared calendars
- Set out-of-office messages

---

### Approval Guidelines

**Auto-Approve (Manager Discretion):**
- ✅ Vacation <5 days with >2 weeks notice
- ✅ Training/professional development
- ✅ Sick leave (obviously)

**PM Approval Required:**
- ⚠️ Vacation >5 consecutive days
- ⚠️ Absence during critical milestone week
- ⚠️ Multiple team members overlapping absence

**Sponsor Approval Required:**
- 🔴 Extended leave (>2 weeks)
- 🔴 Absence of key role with no backup

---

### Emergency Absence Protocol

**Unplanned Absence Notification:**
1. Team member notifies manager ASAP (call/text)
2. Manager notifies PM within 2 hours
3. PM assesses impact and activates coverage plan
4. Team notified via Slack/email

**Same-Day Coverage:**
- Backup person identified in advance
- Emergency contact list maintained
- Critical task documentation up-to-date

---

## 💡 Best Practices

### For Project Managers

**Do:**
- ✅ Update tracker weekly
- ✅ Review capacity before each sprint planning
- ✅ Flag conflicts early (2+ weeks ahead)
- ✅ Build 10-15% buffer for unplanned absences
- ✅ Cross-train team to eliminate SPOFs
- ✅ Respect work-life balance - don't deny reasonable requests

**Don't:**
- ❌ Wait until someone is out to realize impact
- ❌ Plan critical work when key people are out
- ❌ Create culture of not taking PTO
- ❌ Surprise stakeholders with absence impacts
- ❌ Forget to update tracker (leads to inaccurate planning)

---

### For Team Members

**Do:**
- ✅ Request time off well in advance
- ✅ Check team calendar for conflicts
- ✅ Complete handoff before leaving
- ✅ Set proper out-of-office messages
- ✅ Document your work (assume someone might need to cover)
- ✅ Take your PTO - burnout helps no one

**Don't:**
- ❌ Request time off during critical milestones (unless unavoidable)
- ❌ Leave without proper handoff
- ❌ Check work email/Slack during PTO (defeats the purpose)
- ❌ Save all PTO for end of year (use it throughout)

---

## 🔔 Notifications & Reminders

### Automated Reminders
- 2 weeks before absence: Reminder to complete handoff
- 3 days before absence: Confirm coverage plan in place
- Day of return: Welcome back, ramp-up plan

### Escalation Triggers
- 🚨 2+ people in same role out simultaneously
- 🚨 Critical role absence with no backup
- 🚨 Team capacity <70%
- 🚨 Unplanned absence during critical milestone

---

## 📎 Related Templates

- [RACI Matrix](./raci-matrix-template.md) - Identify backup owners
- [Weekly Status Report](./weekly-status-report-template.md) - Report capacity impacts
- [Risk Register](./risk-register-template.md) - Track resource-related risks
- [Issues Log](./issues-log-template.md) - Log absence-caused issues

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
