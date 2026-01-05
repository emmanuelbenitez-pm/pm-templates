# Budget Tracking Template

## 📋 Document Information

| Field | Details |
|-------|---------|
| **Project Name** | [Enter project name] |
| **Project Manager** | [Name] |
| **Budget Period** | [Fiscal Year / Quarter / Project Duration] |
| **Budget Owner** | [Name, Title] |
| **Last Updated** | [MM/DD/YYYY] |
| **Version** | [1.0] |

---

## 🎯 Budget Overview

### Executive Summary

| Metric | Amount | Status |
|--------|--------|--------|
| **Total Approved Budget** | $[X] | - |
| **Budget Spent to Date** | $[Y] | [%] |
| **Budget Remaining** | $[Z] | [%] |
| **Forecasted Total Cost** | $[A] | - |
| **Variance (Projected)** | $[+/- B] | 🟢🟡🔴 |

**Overall Status:** 🟢 On Budget / 🟡 At Risk / 🔴 Over Budget

**Key Highlights:**
- [Highlight 1: e.g., "15% under budget YTD"]
- [Highlight 2: e.g., "Infrastructure costs higher than planned"]
- [Highlight 3: e.g., "Forecasting 5% overrun by project end"]

---

## 💰 Budget Breakdown by Category

### Detailed Budget vs Actual

| Category | Approved Budget | Spent to Date | Committed | Remaining | Forecast Total | Variance | % Used | Status |
|----------|-----------------|---------------|-----------|-----------|----------------|----------|--------|--------|
| **Labor - Internal** | $250,000 | $150,000 | $50,000 | $50,000 | $250,000 | $0 | 60% | 🟢 |
| **Labor - External** | $100,000 | $80,000 | $15,000 | $5,000 | $105,000 | +$5,000 | 80% | 🟡 |
| **Software Licenses** | $50,000 | $45,000 | $0 | $5,000 | $48,000 | -$2,000 | 90% | 🟢 |
| **Hardware** | $75,000 | $60,000 | $10,000 | $5,000 | $72,000 | -$3,000 | 80% | 🟢 |
| **Cloud/Infrastructure** | $80,000 | $55,000 | $20,000 | $5,000 | $85,000 | +$5,000 | 69% | 🟡 |
| **Travel** | $25,000 | $8,000 | $5,000 | $12,000 | $20,000 | -$5,000 | 32% | 🟢 |
| **Training** | $30,000 | $15,000 | $10,000 | $5,000 | $28,000 | -$2,000 | 50% | 🟢 |
| **Contingency (10%)** | $61,000 | $0 | $0 | $61,000 | $15,000 | -$46,000 | 0% | 🟢 |
| **TOTAL** | **$671,000** | **$413,000** | **$110,000** | **$148,000** | **$623,000** | **-$48,000** | **62%** | **🟢** |

**Legend:**
- **Approved Budget:** Original allocated amount
- **Spent to Date:** Actually paid/invoiced
- **Committed:** Purchase orders issued, not yet paid
- **Remaining:** Available to spend
- **Forecast Total:** Expected final spend
- **Variance:** Forecast vs Approved (negative = under, positive = over)
- **% Used:** (Spent + Committed) / Approved

**Status Indicators:**
- 🟢 Green: On track, within 5% of pro-rata budget
- 🟡 Yellow: At risk, 5-10% variance or trending over
- 🔴 Red: Over budget or forecasting >10% overrun

---

## 📊 Monthly Spend Tracking

### Burn Rate Analysis

| Month | Planned Spend | Actual Spend | Cumulative Planned | Cumulative Actual | Variance | Burn Rate |
|-------|---------------|--------------|-------------------|-------------------|----------|-----------|
| Jan 2026 | $50,000 | $45,000 | $50,000 | $45,000 | -$5,000 | 90% |
| Feb 2026 | $60,000 | $62,000 | $110,000 | $107,000 | -$3,000 | 103% |
| Mar 2026 | $70,000 | $75,000 | $180,000 | $182,000 | +$2,000 | 107% |
| Apr 2026 | $65,000 | $68,000 | $245,000 | $250,000 | +$5,000 | 105% |
| May 2026 | $80,000 | $73,000 | $325,000 | $323,000 | -$2,000 | 91% |
| Jun 2026 | $75,000 | - | $400,000 | - | - | - |

**Burn Rate Calculation:**
- Burn Rate = (Actual Spend / Planned Spend) × 100%
- Target: 95-105% (within 5% of plan)
- Current Average: 99% ✅ Good

### Spending Trend
```
Monthly Spend:
Jan: ████████ $45K
Feb: ██████████ $62K
Mar: ████████████ $75K ← Peak
Apr: ███████████ $68K
May: ███████████ $73K
Jun: [Projected] ███████████ $70K
```

---

## 💼 Labor Costs Detail

### Internal Labor

| Team Member | Role | Rate | Allocation | Hours YTD | Cost YTD | Budget | Remaining | Status |
|-------------|------|------|------------|-----------|----------|--------|-----------|--------|
| [Name] | Project Manager | $150/hr | 100% | 800 hrs | $120,000 | $150,000 | $30,000 | 🟢 |
| [Name] | Tech Lead | $175/hr | 75% | 500 hrs | $87,500 | $100,000 | $12,500 | 🟢 |
| [Name] | Senior Dev | $140/hr | 100% | 650 hrs | $91,000 | $110,000 | $19,000 | 🟢 |
| [Name] | Developer | $100/hr | 100% | 700 hrs | $70,000 | $80,000 | $10,000 | 🟢 |
| [Name] | QA Lead | $120/hr | 50% | 300 hrs | $36,000 | $45,000 | $9,000 | 🟢 |
| **TOTAL** | | | | **2,950 hrs** | **$404,500** | **$485,000** | **$80,500** | **🟢** |

**Notes:**
- Internal rates include overhead/benefits (loaded rates)
- Allocation % = time dedicated to this project
- Hours YTD = actual hours logged to project

### External Labor (Contractors/Consultants)

| Vendor/Contractor | Role | Rate | Contract Type | Hours/Days | Cost YTD | Budget | Variance | Status |
|-------------------|------|------|---------------|------------|----------|--------|----------|--------|
| [Vendor A] | Cloud Architect | $200/hr | T&M | 200 hrs | $40,000 | $35,000 | +$5,000 | 🟡 |
| [Vendor B] | UX Designer | $150/hr | Fixed Price | - | $25,000 | $25,000 | $0 | 🟢 |
| [Contractor] | DevOps Engineer | $175/hr | T&M | 150 hrs | $26,250 | $40,000 | -$13,750 | 🟢 |
| **TOTAL** | | | | **350 hrs** | **$91,250** | **$100,000** | **-$8,750** | **🟢** |

**Contract Types:**
- **T&M:** Time & Materials (pay for actual hours)
- **Fixed Price:** Agreed total, regardless of hours
- **Retainer:** Monthly fee for availability

---

## 🛠️ Non-Labor Costs Detail

### Software & Licenses

| Item | Vendor | License Type | Quantity | Unit Cost | Annual Cost | Cost YTD | Budget | Status |
|------|--------|--------------|----------|-----------|-------------|----------|--------|--------|
| Jira Cloud | Atlassian | Subscription | 15 users | $8/user/mo | $1,440 | $720 | $1,500 | 🟢 |
| AWS Services | Amazon | Usage-based | - | Variable | $36,000 | $22,000 | $40,000 | 🟢 |
| Figma | Figma | Subscription | 5 users | $15/user/mo | $900 | $450 | $1,000 | 🟢 |
| GitHub Enterprise | GitHub | Subscription | 20 users | $21/user/mo | $5,040 | $2,520 | $5,500 | 🟢 |
| **TOTAL** | | | | | **$43,380** | **$25,690** | **$48,000** | **🟢** |

### Hardware & Equipment

| Item | Vendor | Quantity | Unit Cost | Total Cost | Purchase Date | Budget | Variance |
|------|--------|----------|-----------|------------|---------------|--------|----------|
| MacBook Pro | Apple | 5 | $2,500 | $12,500 | Jan 2026 | $15,000 | -$2,500 |
| Monitors | Dell | 10 | $400 | $4,000 | Feb 2026 | $5,000 | -$1,000 |
| Dev Servers | HP | 3 | $5,000 | $15,000 | Mar 2026 | $20,000 | -$5,000 |
| **TOTAL** | | | | **$31,500** | | **$40,000** | **-$8,500** |

### Travel & Expenses

| Category | Budget | Spent | Remaining | Notes |
|----------|--------|-------|-----------|-------|
| Client Meetings | $10,000 | $3,500 | $6,500 | 2 trips completed, 3 planned |
| Training Conferences | $8,000 | $2,500 | $5,500 | AWS re:Invent, others TBD |
| Team Offsite | $5,000 | $0 | $5,000 | Planned for Q3 |
| Misc Expenses | $2,000 | $500 | $1,500 | Office supplies, food |
| **TOTAL** | **$25,000** | **$6,500** | **$18,500** | |

---

## 📈 Financial Forecasting

### Forecast to Completion

| Category | Spent to Date | Committed | Remaining Work | Forecast Total | Original Budget | Variance | EAC Status |
|----------|---------------|-----------|----------------|----------------|-----------------|----------|------------|
| Labor - Internal | $404,500 | $80,000 | $115,500 | $600,000 | $585,000 | +$15,000 | 🟡 |
| Labor - External | $91,250 | $15,000 | $5,750 | $112,000 | $100,000 | +$12,000 | 🟡 |
| Software | $25,690 | $0 | $17,310 | $43,000 | $48,000 | -$5,000 | 🟢 |
| Hardware | $31,500 | $5,000 | $3,500 | $40,000 | $40,000 | $0 | 🟢 |
| Cloud | $55,000 | $20,000 | $10,000 | $85,000 | $80,000 | +$5,000 | 🟡 |
| Travel | $6,500 | $5,000 | $8,500 | $20,000 | $25,000 | -$5,000 | 🟢 |
| Training | $15,000 | $10,000 | $3,000 | $28,000 | $30,000 | -$2,000 | 🟢 |
| Contingency | $0 | $0 | $20,000 | $20,000 | $61,000 | -$41,000 | 🟢 |
| **TOTAL** | **$629,440** | **$135,000** | **$183,560** | **$948,000** | **$969,000** | **-$21,000** | **🟢** |

**EAC:** Estimate at Completion (what we expect final cost to be)
**Forecast Method:** Bottom-up based on remaining work

### Budget Performance Metrics

| Metric | Value | Target | Status |
|--------|-------|--------|--------|
| **Cost Performance Index (CPI)** | 1.03 | >0.95 | 🟢 Good |
| **Budget Consumption Rate** | 62% | 60% | 🟢 On Track |
| **Forecast Variance** | -2.2% | ±5% | 🟢 Within Range |
| **Contingency Used** | 0% | <50% at this stage | 🟢 Good |

**CPI Calculation:**
- CPI = Earned Value / Actual Cost
- CPI > 1.0 = Under budget (good)
- CPI < 1.0 = Over budget (bad)
- Current: 1.03 = Spending $1 for $1.03 of value ✅

---

## ⚠️ Budget Risks & Issues

### Active Budget Risks

| Risk ID | Risk Description | Probability | Impact | Potential Cost | Mitigation | Owner |
|---------|------------------|-------------|--------|----------------|------------|-------|
| BR-001 | Cloud costs escalating faster than projected | High | Medium | +$15K | Implement cost monitoring, optimize usage | [Name] |
| BR-002 | Additional contractor hours needed for Phase 3 | Medium | High | +$25K | Re-scope or use internal resources | [Name] |
| BR-003 | Currency fluctuation (vendor in EUR) | Low | Medium | +$5K | Lock exchange rate for remaining payments | [Name] |

### Budget Issues

| Issue ID | Description | Impact | Resolution | Status |
|----------|-------------|--------|------------|--------|
| BI-001 | Unexpected AWS data transfer costs | +$3K | Optimize data architecture | 🟡 In Progress |
| BI-002 | Contractor hourly rate increased | +$2K | Negotiated volume discount | 🟢 Resolved |

---

## 💵 Cash Flow Management

### Monthly Cash Flow

| Month | Planned Disbursement | Actual Disbursement | Cumulative | Funding Received | Cash Balance |
|-------|---------------------|---------------------|------------|------------------|--------------|
| Jan | $50,000 | $45,000 | $45,000 | $200,000 | $155,000 |
| Feb | $60,000 | $62,000 | $107,000 | $0 | $93,000 |
| Mar | $70,000 | $75,000 | $182,000 | $0 | $18,000 |
| Apr | $65,000 | $68,000 | $250,000 | $250,000 | $0 |
| May | $80,000 | $73,000 | $323,000 | $0 | -$73,000 |
| Jun | $75,000 | - | - | $200,000 | - |

**Notes:**
- Negative balance in May required bridge funding
- Funding schedule aligned with milestone completions
- Consider earlier invoicing to improve cash flow

---

## 📋 Procurement & Purchase Orders

### Open Purchase Orders

| PO # | Vendor | Description | PO Date | PO Amount | Invoiced | Paid | Remaining | Status |
|------|--------|-------------|---------|-----------|----------|------|-----------|--------|
| PO-001 | AWS | Cloud services Q2 | 04/01 | $25,000 | $15,000 | $12,000 | $10,000 | Open |
| PO-002 | Vendor A | Consulting block | 03/15 | $40,000 | $35,000 | $30,000 | $5,000 | Open |
| PO-003 | Dell | Servers | 03/01 | $15,000 | $15,000 | $15,000 | $0 | Closed |

**Committed but Not Yet PO'd:**
- Cloud architect services: $15K
- Additional dev hardware: $5K
- Conference registrations: $3K

---

## 📊 Budget Variance Analysis

### Top 3 Favorable Variances (Under Budget)

1. **Travel (-$5,000, -20%)**
   - Reason: More virtual meetings than expected
   - Action: Maintain virtual-first approach

2. **Hardware (-$8,500, -21%)**
   - Reason: Negotiated bulk discount, some team using existing equipment
   - Action: None, favorable variance

3. **Software Licenses (-$5,000, -10%)**
   - Reason: Delayed some tool purchases, using open source alternatives
   - Action: Continue evaluating needs vs wants

### Top 3 Unfavorable Variances (Over Budget)

1. **External Labor (+$12,000, +12%)**
   - Reason: Cloud architect expertise needed more than estimated
   - Impact: 🟡 Medium
   - Action: Evaluate training internal resources vs continuing contractor

2. **Internal Labor (+$15,000, +3%)**
   - Reason: More complex requirements, additional rework
   - Impact: 🟡 Medium
   - Action: Tighten requirements process, reduce scope if continues

3. **Cloud Infrastructure (+$5,000, +6%)**
   - Reason: Higher than expected data transfer costs
   - Impact: 🟡 Medium
   - Action: Optimize architecture, implement cost alerts

---

## 🎯 Budget Control Actions

### Completed Actions
- ✅ Renegotiated contractor rates (saved $3K)
- ✅ Moved to annual AWS reservations (saving $6K/year)
- ✅ Consolidated software tools (eliminated 2 redundant licenses)

### In Progress Actions
- 🟡 Reviewing cloud optimization opportunities (target: -$10K)
- 🟡 Training internal team on cloud architecture (reduce contractor dependency)
- 🟡 Re-scope Phase 3 to stay within budget (remove nice-to-haves)

### Planned Actions
- 📅 Q3: Comprehensive budget review and reforecast
- 📅 Q3: Evaluate contingency usage and reallocation
- 📅 Q4: Final budget reconciliation

---

## 📝 Change Order Log

### Approved Budget Changes

| Change # | Date | Description | Category | Amount | New Budget | Approved By |
|----------|------|-------------|----------|--------|------------|-------------|
| BC-001 | 02/15 | Additional security testing | Testing | +$15,000 | $686,000 | [Sponsor] |
| BC-002 | 04/01 | Scope reduction - Feature X | Development | -$20,000 | $666,000 | [Sponsor] |
| BC-003 | 05/10 | Add chat feature | Development | +$58,000 | $724,000 | [Sponsor] |

**Current Approved Budget:** $724,000  
**Original Budget:** $671,000  
**Net Change:** +$53,000 (+7.9%)

---

## 💡 Best Practices

### Budget Management Do's ✅

1. **Track Weekly** - Update actuals every Friday
2. **Forecast Monthly** - Reforecast based on trends
3. **Communicate Early** - Flag variances >5% immediately
4. **Document Everything** - All expenses properly coded
5. **Use Contingency Wisely** - Only for true unknowns
6. **Monitor Burn Rate** - Daily spend vs planned
7. **Approve Before Spending** - No surprises
8. **Reconcile Regularly** - Match actuals to invoices

### Budget Management Don'ts ❌

1. **Don't Hide Overruns** - Transparency is key
2. **Don't Raid Contingency Early** - Save for real risks
3. **Don't Commit Without Approval** - Follow process
4. **Don't Ignore Small Variances** - They compound
5. **Don't Forget Committed Costs** - Track POs
6. **Don't Assume Budget Rollover** - Use it or lose it
7. **Don't Skip Reconciliation** - Errors accumulate
8. **Don't Underspend Quality** - Cheap isn't always good

---

## 🔔 Alerts & Thresholds

### Automatic Alerts Configured

| Condition | Threshold | Alert Recipients | Frequency |
|-----------|-----------|------------------|-----------|
| Category >110% of budget | Any category | PM, Budget Owner | Immediate |
| Weekly spend >20% over plan | Any week | PM | Weekly |
| Forecast >105% of total budget | Overall | PM, Sponsor | Monthly |
| Contingency <20% remaining | Overall | PM, Sponsor | Monthly |
| Large invoice pending | >$10K | PM, Finance | Upon receipt |

---

## 📎 Related Templates

- [Project Charter](./project-charter-template.md) - Initial budget approval
- [Risk Register](./risk-register-template.md) - Budget risks
- [Change Request](./change-request-template.md) - Budget change approvals
- [Weekly Status Report](./weekly-status-report-template.md) - Report budget status

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
