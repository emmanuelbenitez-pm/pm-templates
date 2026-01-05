# Change Request Template

## 📋 Change Request Information

| Field | Details |
|-------|---------|
| **CR Number** | CR-[YYYY]-[###] |
| **Project Name** | [Enter project name] |
| **Submitted By** | [Name, Title] |
| **Submission Date** | [MM/DD/YYYY] |
| **Priority** | 🔴 Critical / 🟠 High / 🟡 Medium / 🟢 Low |
| **Type** | Scope Addition / Scope Removal / Schedule Change / Budget Change / Process Change / Quality Change |
| **Status** | 🟡 Submitted / 🔵 Under Review / 🟢 Approved / 🔴 Rejected / ⚫ Withdrawn |

---

## 🎯 Change Request Summary

**One-Line Summary:**
[Brief description - one sentence]

**Example:**
> Add real-time chat feature to user dashboard

---

## 📝 Detailed Description

### Current State
[What exists today? What is the baseline?]

**Example:**
> Users currently communicate via email only. Dashboard has no messaging capability. Support tickets average 2-day response time.

### Proposed Change
[What exactly is being requested? Be specific.]

**Example:**
> Add real-time chat widget to user dashboard enabling:
> - Direct messaging between users and support team
> - File sharing (images, PDFs up to 10MB)
> - Chat history (last 30 days)
> - Typing indicators and read receipts
> - Mobile responsive design

### Desired Future State
[What will the situation be after this change?]

**Example:**
> Users can get instant support via dashboard chat. Support team can handle 3x more inquiries. Response time reduced to < 5 minutes for 80% of queries.

---

## 💼 Business Justification

### Problem Statement
[What problem does this solve? Why is this needed?]

**Example:**
> Customer satisfaction score dropped to 3.2/5 due to slow email support. Competitors offer real-time chat. We're losing customers to faster-response alternatives.

### Business Value
[What's the benefit? How does this help the business?]

**Example:**
> - Improve customer satisfaction: 3.2 → 4.5 target
> - Reduce support costs: handle 3x more queries with same team
> - Competitive parity: match competitor feature set
> - Revenue retention: reduce churn from 15% to 10%

### Opportunity Cost
[What happens if we DON'T do this?]

**Example:**
> - Continue losing customers to competitors (current: 15% churn)
> - Customer satisfaction continues declining
> - Support team remains overwhelmed
> - Estimated revenue loss: $500K/year in churned customers

---

## 📊 Impact Analysis

### Schedule Impact
| Aspect | Impact | Details |
|--------|--------|---------|
| **Development Time** | +3 weeks | Backend API + Frontend widget + Testing |
| **Current Milestone** | Delayed | Milestone 3 pushed from [MM/DD] to [MM/DD] |
| **Overall Timeline** | +2 weeks | With parallel work, only 2-week overall delay |
| **Critical Path** | ⚠️ Affected | This becomes new critical path item |

**Schedule Details:**
- Development: 2 weeks (Backend 1 week + Frontend 1 week)
- Testing: 1 week (QA + UAT)
- Deployment: Included in Milestone 3
- **Total:** 3 weeks added to critical path

### Budget Impact
| Category | Cost | Details |
|----------|------|---------|
| **Development** | +$45,000 | 3 engineers × 3 weeks × $5K/week |
| **Third-Party Tool** | +$2,400/year | Chat service API (monthly: $200) |
| **Infrastructure** | +$600/year | Additional server capacity |
| **Testing** | +$8,000 | QA effort + UAT coordination |
| **Documentation** | +$2,000 | User guides + API docs |
| **Training** | +$3,000 | Support team training |
| **Total One-Time** | **+$58,000** | |
| **Total Recurring** | **+$3,000/year** | |

**Budget Status:**
- Current Project Budget: $500,000
- Budget Used: $320,000 (64%)
- Budget Remaining: $180,000
- Change Request Cost: $58,000
- New Budget Remaining: $122,000 ✅ **Within budget**

### Scope Impact
| Change Type | Impact | Details |
|-------------|--------|---------|
| **Scope Addition** | ✅ Yes | New feature not in original scope |
| **Scope Removal** | ❌ No | Nothing removed |
| **Scope Modification** | ❌ No | No existing features modified |

**Features Added:**
- Real-time chat widget (new)
- File sharing capability (new)
- Chat history storage (new)
- Mobile responsive chat (new)

**Original Scope Items Affected:**
- Dashboard UI may need layout adjustment (minor)
- User notification system integration required (minor)

### Resource Impact
| Resource | Impact | Details |
|----------|--------|---------|
| **Backend Engineer** | +1 week full-time | Chat API development |
| **Frontend Engineer** | +1 week full-time | Widget development |
| **Full-Stack Engineer** | +1 week full-time | Integration work |
| **QA Engineer** | +1 week 50% | Testing chat functionality |
| **UX Designer** | +2 days | Chat widget design |
| **Tech Writer** | +3 days | Documentation |

**Resource Availability:**
- ✅ All resources available
- ⚠️ Backend engineer has competing priority (can be resolved)
- ✅ No new hires needed

### Quality Impact
| Aspect | Impact | Mitigation |
|--------|--------|------------|
| **Testing Time** | Reduced by 1 week | Add extra QA resource |
| **Technical Debt** | Medium risk | Allocate refactoring time in Sprint +1 |
| **Code Complexity** | Increased | Require architecture review |
| **Security** | New attack surface | Security audit before deployment |
| **Performance** | Minimal impact | Load testing with chat enabled |

### Risk Impact
| New Risk | Probability | Impact | Mitigation |
|----------|-------------|--------|------------|
| Chat service vendor downtime | Medium | High | Implement fallback to email |
| Real-time performance issues | Low | Medium | Load testing, scalable architecture |
| User adoption lower than expected | Medium | Medium | Marketing campaign, training |
| Integration complexity underestimated | Medium | High | Technical spike before committing |

---

## 🔄 Alternatives Considered

### Alternative 1: Third-Party Chat Widget (e.g., Intercom, Zendesk Chat)
**Pros:**
- Faster implementation (1 week vs 3 weeks)
- Proven, mature solution
- Less development/maintenance burden
- Built-in analytics

**Cons:**
- Monthly cost: $500-800/month ($6K-10K/year)
- Less customization
- Vendor lock-in
- User data stored externally

**Cost:** $10K/year recurring, $10K one-time integration
**Timeline:** 1 week
**Recommendation:** ⚠️ Consider if timeline critical

### Alternative 2: Enhance Email Support Instead
**Pros:**
- Much cheaper ($5K)
- Faster to implement (1 week)
- Uses existing infrastructure
- No new technology risks

**Cons:**
- Doesn't solve real-time problem
- Still slower than competitors
- Won't reduce churn as effectively
- Limited improvement to customer satisfaction

**Cost:** $5K one-time
**Timeline:** 1 week
**Recommendation:** ❌ Doesn't address core problem

### Alternative 3: Defer to Phase 2 (Post-MVP)
**Pros:**
- No impact to current timeline
- Can be better planned
- Learn from MVP user feedback first

**Cons:**
- Continued customer churn (3-6 months)
- Revenue loss: ~$200K in churned customers
- Competitive disadvantage continues
- Support team remains overwhelmed

**Cost:** $0 now, $58K later + $200K opportunity cost
**Timeline:** No change now
**Recommendation:** ❌ Opportunity cost too high

---

## ✅ Recommended Option

**Selection:** Build custom chat feature (Original proposal)

**Rationale:**
1. Best long-term value (lower recurring cost)
2. Full control and customization
3. User data remains internal
4. Can evolve with our needs
5. Timeline acceptable (2-week overall delay)
6. Within budget constraints

**Trade-offs Accepted:**
- Longer implementation than third-party
- Additional maintenance burden
- Higher initial cost than email enhancement

---

## 📋 Prerequisites & Dependencies

### Prerequisites (Must Be Complete Before Starting)
- [ ] Budget approval secured
- [ ] Schedule impact accepted by sponsor
- [ ] Chat service API vendor selected
- [ ] Technical architecture reviewed and approved
- [ ] Security requirements documented

### Dependencies (What This Change Depends On)
- Milestone 2 completion (database schema updates)
- User notification system completion
- Real-time infrastructure setup (WebSockets)

### Impacts To (What This Change Affects)
- Milestone 3 timeline (2-week delay)
- Dashboard UI redesign (minor layout changes)
- User onboarding flow (add chat introduction)
- Support team processes (new workflow)

---

## 🎯 Acceptance Criteria

### Functional Requirements
- [ ] Users can initiate chat from dashboard
- [ ] Real-time messaging with <1 second latency
- [ ] File sharing (images, PDFs up to 10MB)
- [ ] Chat history stored for 30 days
- [ ] Support team can handle multiple chats simultaneously (up to 5)
- [ ] Mobile responsive (iOS, Android browsers)
- [ ] Typing indicators work
- [ ] Read receipts display correctly

### Non-Functional Requirements
- [ ] 99.9% uptime SLA
- [ ] Support 100 concurrent chats minimum
- [ ] Page load time increase <500ms
- [ ] GDPR/privacy compliant
- [ ] Accessible (WCAG 2.1 Level AA)

### Success Metrics
- Customer satisfaction: 3.2 → 4.5 (target)
- Average response time: 2 days → 5 minutes (target)
- Support tickets handled: 100/week → 300/week (target)
- Customer churn: 15% → 10% (target)

---

## 📅 Implementation Plan

### Phase 1: Design & Planning (Week 1)
- [ ] Technical architecture design
- [ ] UX/UI mockups
- [ ] Security review
- [ ] Chat service vendor selection
- [ ] Detailed task breakdown

### Phase 2: Development (Week 2-3)
- [ ] Backend API development (Week 2)
- [ ] Frontend widget development (Week 2)
- [ ] Integration work (Week 3)
- [ ] Unit testing (Ongoing)

### Phase 3: Testing (Week 4)
- [ ] QA functional testing
- [ ] Performance/load testing
- [ ] Security testing
- [ ] UAT with support team

### Phase 4: Deployment (Week 4)
- [ ] Production deployment
- [ ] Support team training
- [ ] User communication
- [ ] Monitoring setup

### Phase 5: Post-Launch (Week 5+)
- [ ] Monitor usage and performance
- [ ] Gather user feedback
- [ ] Bug fixes and refinements
- [ ] Success metrics tracking

---

## 👥 Stakeholder Sign-Off

### Approval Required From

#### Executive Sponsor
- **Name:** [Name, Title]
- **Signature:** ________________
- **Date:** [MM/DD/YYYY]
- **Decision:** ✅ Approved / ❌ Rejected / 🟡 Conditional
- **Conditions (if any):** [List conditions for approval]

#### Project Manager
- **Name:** [Name]
- **Signature:** ________________
- **Date:** [MM/DD/YYYY]
- **Recommendation:** ✅ Support / ⚠️ Concerns / ❌ Oppose
- **Comments:** [PM perspective]

#### Technical Lead
- **Name:** [Name]
- **Signature:** ________________
- **Date:** [MM/DD/YYYY]
- **Technical Feasibility:** ✅ Feasible / ⚠️ Challenging / ❌ Not Feasible
- **Comments:** [Technical perspective]

#### Business Owner
- **Name:** [Name, Title]
- **Signature:** ________________
- **Date:** [MM/DD/YYYY]
- **Business Value:** ✅ High / 🟡 Medium / 🔴 Low
- **Comments:** [Business perspective]

### Consulted (Input Provided)
| Name | Role | Input Date | Key Feedback |
|------|------|------------|--------------|
| [Name] | UX Designer | [MM/DD] | [Summary of feedback] |
| [Name] | Security Lead | [MM/DD] | [Summary of feedback] |
| [Name] | Support Manager | [MM/DD] | [Summary of feedback] |

### Informed (Notified of Decision)
- Product team
- Marketing team
- Customer success team
- All project stakeholders

---

## 📊 Change Control Board Review

### CCB Meeting Details
- **Meeting Date:** [MM/DD/YYYY]
- **Attendees:** [List of CCB members]
- **Discussion Summary:** [Key points discussed]
- **Vote:** [For: X, Against: Y, Abstain: Z]

### CCB Decision
**Status:** ✅ Approved / ❌ Rejected / 🟡 Deferred / 🔄 Requires Revision

**Decision Date:** [MM/DD/YYYY]

**Decision Rationale:**
[Why was this decision made?]

**Conditions/Stipulations:**
- [Condition 1, if any]
- [Condition 2, if any]

---

## 📝 Communication Plan

### Internal Communication
- **Team:** Email announcement, team meeting discussion
- **Stakeholders:** Updated project status report
- **Executives:** Executive summary via email

### External Communication
- **Customers:** Feature announcement (post-launch)
- **Partners:** Update in quarterly review (if applicable)

### Timing
- CCB decision: Immediately after approval
- Team notification: Within 24 hours
- Customer announcement: Upon deployment

---

## 🔄 Change Request History

### Status Updates
| Date | Status | Updated By | Notes |
|------|--------|------------|-------|
| [MM/DD] | Submitted | [Name] | Initial submission |
| [MM/DD] | Under Review | [Name] | Sent to CCB |
| [MM/DD] | Approved | [CCB Chair] | Approved with conditions |
| [MM/DD] | In Progress | [PM] | Implementation started |
| [MM/DD] | Complete | [PM] | Deployed to production |

### Revisions
| Version | Date | Changes Made | Reason |
|---------|------|--------------|--------|
| 1.0 | [MM/DD] | Initial draft | - |
| 1.1 | [MM/DD] | Updated cost estimate | CFO requested breakdown |
| 2.0 | [MM/DD] | Reduced scope | Timeline concerns |

---

## 📎 Attachments

- [ ] Cost-benefit analysis spreadsheet
- [ ] Technical design document
- [ ] UX/UI mockups
- [ ] Risk assessment
- [ ] Vendor comparison
- [ ] Customer feedback data

---

## 💡 Change Request Best Practices

### When to Submit a Change Request

**ALWAYS submit for:**
- ✅ Scope additions or removals
- ✅ Budget increases >5% or $10K
- ✅ Schedule changes >1 week
- ✅ Resource changes (team size +/-)
- ✅ Technology/architecture changes
- ✅ Quality standard changes

**May not need formal CR for:**
- Minor bug fixes
- Clarifications of existing requirements
- Process improvements (no scope/budget/schedule impact)
- Internal team workflow changes

### Writing Effective Change Requests

**Do:**
- ✅ Be specific and quantify impact
- ✅ Provide clear business justification
- ✅ Include multiple alternatives
- ✅ Show you've thought through implications
- ✅ Use data to support your case

**Don't:**
- ❌ Be vague ("improve the system")
- ❌ Surprise stakeholders (socialize first)
- ❌ Downplay impact to get approval
- ❌ Submit reactively without analysis
- ❌ Only present one option

---

## ⚠️ Common Change Request Mistakes

### Anti-Patterns to Avoid

❌ **Scope Creep in Disguise**
> "This is just a small tweak"
- Reality: 3 weeks of work, major impact
- Fix: Be honest about real impact

❌ **Gold Plating**
> "While we're at it, let's add..."
- Reality: Unnecessary features bloating scope
- Fix: Focus on minimum to achieve goal

❌ **Analysis Paralysis**
> "Let me do 2 more weeks of research"
- Reality: Delaying decision unnecessarily
- Fix: Set decision deadline, work with available info

❌ **Fait Accompli**
> "I already built it, just need approval"
- Reality: Undermines governance, wastes effort if rejected
- Fix: Get approval BEFORE building

❌ **Emergency Bypass**
> "This is urgent, no time for change control"
- Reality: Sets bad precedent, often not truly urgent
- Fix: Have expedited CR process for real emergencies

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
