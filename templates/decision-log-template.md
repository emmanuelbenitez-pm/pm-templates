# Decision Log Template

## 📋 Document Information

| Field | Details |
|-------|---------|
| **Project Name** | [Enter project name] |
| **Project Manager** | [Name] |
| **Date Created** | [MM/DD/YYYY] |
| **Last Updated** | [MM/DD/YYYY] |
| **Version** | [1.0] |

---

## 🎯 What is a Decision Log?

A Decision Log captures **key decisions** made throughout the project lifecycle, including the context, rationale, alternatives considered, and who made the decision. It prevents re-litigation of decisions and provides accountability.

### Why Decision Logs Matter

**Benefits:**
- ✅ **Accountability** - Clear record of who decided what
- ✅ **Context Preservation** - Future team members understand "why"
- ✅ **Prevents Re-discussion** - "We already decided this, see DEC-005"
- ✅ **Lessons Learned** - Review decision outcomes vs expectations
- ✅ **Audit Trail** - Compliance and governance
- ✅ **Knowledge Transfer** - Onboard new team members faster

**Common Problems Without Decision Log:**
- ❌ Same discussion happens repeatedly
- ❌ No one remembers why approach was chosen
- ❌ Decisions made verbally get lost
- ❌ Accountability unclear when things go wrong
- ❌ New team members redo analysis already done

---

## 📊 Decision Categories

### By Impact Level

| Level | Definition | Approval Authority | Examples |
|-------|------------|-------------------|----------|
| 🔴 **Strategic** | Project direction, major change | Executive Sponsor | Architecture choice, scope change, vendor selection |
| 🟠 **Significant** | Affects timeline/budget/quality | Project Manager + Sponsor | Technology stack, resource allocation, milestone dates |
| 🟡 **Operational** | Day-to-day execution | Project Manager | Sprint planning, task assignment, process tweaks |
| 🟢 **Tactical** | Team-level decisions | Team Lead | Code approach, tool selection, design details |

### By Decision Type

- **Technical Decisions** - Architecture, technology, design
- **Business Decisions** - Scope, priorities, requirements
- **Resource Decisions** - Staffing, budget, vendors
- **Process Decisions** - Methodology, workflow, governance
- **Risk Decisions** - Risk response strategies
- **Quality Decisions** - Standards, acceptance criteria

---

## 📋 Decision Log

### 🔴 STRATEGIC DECISIONS

#### DEC-001: [Decision Title]
| Field | Details |
|-------|---------|
| **Decision ID** | DEC-001 |
| **Date Decided** | [MM/DD/YYYY] |
| **Category** | Technical / Business / Resource / Process / Risk / Quality |
| **Impact Level** | 🔴 Strategic |
| **Status** | ✅ Approved / 🟡 Pending / ❌ Rejected / 🔄 Revisited |
| **Decision Maker** | [Name, Title] |
| **Decision Type** | Consensus / Majority / Authority / Consultative |

**Decision:**
[Clear, concise statement of what was decided]

**Example:**
> We will use AWS as our cloud platform for the entire application stack.

**Context/Background:**
[Why did this decision need to be made? What was happening?]

**Example:**
> Project requires scalable cloud infrastructure. Team has experience with multiple cloud providers. CFO concerned about vendor lock-in.

**Problem Statement:**
[What problem were we trying to solve?]

**Example:**
> Need to select cloud platform that balances: scalability, cost, team expertise, and multi-cloud optionality.

**Options Considered:**

**Option A: AWS**
- **Pros:**
  - Team has 5+ years AWS experience
  - Largest market share, most mature services
  - Best documentation and community support
- **Cons:**
  - Potential vendor lock-in
  - Slightly higher cost than alternatives
  - Proprietary services harder to migrate
- **Cost:** $500K/year estimated
- **Risk:** Medium vendor lock-in risk

**Option B: Azure**
- **Pros:**
  - Better enterprise integration (AD, Office 365)
  - Good for hybrid cloud
  - Competitive pricing
- **Cons:**
  - Team has limited Azure experience
  - Smaller ecosystem than AWS
  - 2-3 month learning curve
- **Cost:** $450K/year estimated
- **Risk:** High learning curve risk

**Option C: Multi-Cloud (AWS + GCP)**
- **Pros:**
  - No vendor lock-in
  - Best-of-breed approach
  - Maximum flexibility
- **Cons:**
  - Increased complexity
  - Higher operational overhead
  - Team needs expertise in both
- **Cost:** $600K/year estimated
- **Risk:** High complexity risk

**Option D: On-Premise**
- **Pros:**
  - Full control
  - No ongoing cloud costs
- **Cons:**
  - High upfront capital
  - Slower to scale
  - Team must manage infrastructure
- **Cost:** $2M upfront + $200K/year
- **Risk:** High scalability risk

**Evaluation Criteria:**
| Criterion | Weight | AWS | Azure | Multi-Cloud | On-Prem |
|-----------|--------|-----|-------|-------------|---------|
| Team Expertise | 25% | 9/10 | 4/10 | 5/10 | 3/10 |
| Cost Efficiency | 20% | 7/10 | 8/10 | 5/10 | 4/10 |
| Scalability | 20% | 10/10 | 9/10 | 10/10 | 5/10 |
| Feature Set | 15% | 10/10 | 8/10 | 9/10 | 6/10 |
| Vendor Independence | 10% | 4/10 | 4/10 | 9/10 | 10/10 |
| Time to Production | 10% | 9/10 | 6/10 | 5/10 | 3/10 |
| **TOTAL SCORE** | | **7.9** | **6.5** | **6.9** | **4.7** |

**Recommendation:**
[What was recommended and by whom?]

**Example:**
> Tech Lead and Architect recommended AWS based on team expertise and time-to-market. CFO initially concerned about lock-in but agreed given 2-year timeline pressure.

**Decision Rationale:**
[Why this option was chosen]

**Example:**
> AWS selected because:
> 1. Team expertise reduces risk and accelerates delivery
> 2. Time-to-market is critical (18-month deadline)
> 3. AWS feature set most mature for our needs
> 4. Can implement abstraction layer to mitigate lock-in
> 5. Cost premium acceptable given other benefits

**Stakeholders Consulted:**
| Name | Role | Input | Agreement |
|------|------|-------|-----------|
| [Name] | Tech Lead | Recommended AWS | ✅ Strongly Agree |
| [Name] | Architect | Recommended AWS | ✅ Strongly Agree |
| [Name] | CFO | Concerned about lock-in | 🟡 Reluctant Agree |
| [Name] | CTO | Preferred multi-cloud | ❌ Disagree (overruled) |

**Assumptions:**
- Team will remain stable (no significant attrition)
- AWS pricing will remain competitive
- Requirements won't require services only available elsewhere
- Vendor lock-in risk acceptable for 3-5 year horizon

**Constraints:**
- Must deliver MVP in 18 months
- Budget ceiling of $600K/year
- Team cannot grow beyond 15 people
- Must maintain 99.9% uptime SLA

**Dependencies:**
- Vendor contract negotiation (Q1)
- Team training completed (Q1-Q2)
- Architecture review approval (before implementation)

**Consequences & Implications:**
- All infrastructure engineers need AWS certification
- Development standards must include cloud-native patterns
- Budgets allocated for AWS Reserved Instances
- Monitoring/logging consolidated to AWS CloudWatch initially

**Implementation Plan:**
1. **Q1 2026:** AWS account setup, training
2. **Q2 2026:** Pilot project on AWS
3. **Q3 2026:** Full migration plan
4. **Q4 2026:** Production deployment

**Success Metrics:**
- Time to first production deployment: < 6 months
- Team productivity: maintain or improve velocity
- Cost: stay within $500K/year budget
- Uptime: achieve 99.9% SLA

**Review Date:**
[MM/DD/YYYY - typically 6-12 months] - Review decision effectiveness

**Follow-up Actions:**
- [ ] Negotiate AWS Enterprise Agreement - Owner: [Name] - Due: [MM/DD]
- [ ] AWS Solutions Architect certification for 5 engineers - Owner: [Name] - Due: [MM/DD]
- [ ] Document AWS best practices - Owner: [Name] - Due: [MM/DD]
- [ ] Create abstraction layer architecture - Owner: [Name] - Due: [MM/DD]

**Outcome (Update After Implementation):**
[To be filled in after decision is implemented]
- **Actual Result:** [What actually happened]
- **vs Expected:** [How it compared to expectations]
- **Lessons Learned:** [What we learned from this decision]

**Related Decisions:**
- Links to: DEC-005 (Database selection)
- Supersedes: DEC-002 (Initial cloud provider discussion)
- Impacts: DEC-008 (CI/CD pipeline tooling)

**Attachments:**
- [Cost comparison spreadsheet]
- [Technical evaluation document]
- [Vendor proposals]
- [Risk assessment]

---

### 🟠 SIGNIFICANT DECISIONS

#### DEC-002: [Decision Title]
[Similar structure but can be briefer]

| Field | Details |
|-------|---------|
| **Decision ID** | DEC-002 |
| **Date** | [MM/DD/YYYY] |
| **Category** | [Category] |
| **Impact** | 🟠 Significant |
| **Decision Maker** | [Name] |

**Decision:** [What was decided]

**Rationale:** [Why]

**Options Considered:** [Brief list]

**Chosen:** [Selected option and why]

**Implications:** [Key impacts]

---

### 🟡 OPERATIONAL DECISIONS

#### DEC-003: [Decision Title]
[Even briefer format for day-to-day decisions]

---

## 📊 Decision Summary Dashboard

### Decision Count by Category
| Category | Strategic | Significant | Operational | Total |
|----------|-----------|-------------|-------------|-------|
| Technical | [#] | [#] | [#] | [#] |
| Business | [#] | [#] | [#] | [#] |
| Resource | [#] | [#] | [#] | [#] |
| Process | [#] | [#] | [#] | [#] |
| **TOTAL** | **[#]** | **[#]** | **[#]** | **[#]** |

### Decision Status
| Status | Count | % |
|--------|-------|---|
| ✅ Approved & Implemented | [#] | [%] |
| 🟡 Approved, Pending Implementation | [#] | [%] |
| 🔄 Under Review | [#] | [%] |
| ❌ Rejected | [#] | [%] |
| 🔁 Revisited/Changed | [#] | [%] |

### Decisions by Quarter
```
Q1 2026: ███████ (7 decisions)
Q2 2026: ████████████ (12 decisions)
Q3 2026: ██████ (6 decisions)
Q4 2026: ████ (4 decisions)
```

---

## 🎯 Decision-Making Process

### Decision Framework
```
Problem Identified
        ↓
Gather Information
        ↓
Identify Options (3-5 options)
        ↓
Evaluate Options
        ↓
Consult Stakeholders
        ↓
Make Decision
        ↓
Document in Log
        ↓
Communicate Decision
        ↓
Implement
        ↓
Review Outcome
```

### Decision-Making Methods

#### 1. **Consensus Decision**
- **When:** Team has equal say, high buy-in needed
- **Process:** Discuss until everyone agrees
- **Pros:** High buy-in, best for team decisions
- **Cons:** Slow, may result in compromise solution

#### 2. **Consultative Decision**
- **When:** Leader wants input but makes final call
- **Process:** Gather input, leader decides
- **Pros:** Balanced - input + speed
- **Cons:** Some may feel unheard

#### 3. **Authority Decision**
- **When:** Urgent, clear accountability needed
- **Process:** Decision maker decides unilaterally
- **Pros:** Fast, clear accountability
- **Cons:** Low buy-in, may miss important info

#### 4. **Majority Vote**
- **When:** Democratic approach needed
- **Process:** Vote, majority wins
- **Pros:** Fair process, efficient
- **Cons:** Winner/loser dynamic

#### 5. **Delegation**
- **When:** Expert knowledge required
- **Process:** Delegate to subject matter expert
- **Pros:** Best expertise applied
- **Cons:** Requires trust, expertise validation

---

## 💡 Best Practices

### Making Good Decisions

**Before Deciding:**
1. ✅ **Define the problem clearly** - "We need faster deployment" not "We have problems"
2. ✅ **Identify decision criteria** - What matters? (cost, time, quality, risk)
3. ✅ **Generate 3-5 options** - Don't decide between only 2
4. ✅ **Evaluate objectively** - Use scoring matrix
5. ✅ **Consult right people** - Technical, business, impacted stakeholders
6. ✅ **Consider consequences** - Second and third order effects
7. ✅ **Check assumptions** - What must be true for this to work?

**While Deciding:**
1. ✅ **Use data** - Not just opinions
2. ✅ **Consider reversibility** - Can we undo this if wrong?
3. ✅ **Avoid cognitive biases** - Confirmation bias, sunk cost, etc.
4. ✅ **Set decision deadline** - Don't analyze forever
5. ✅ **Be explicit about trade-offs** - What are we giving up?

**After Deciding:**
1. ✅ **Document immediately** - While context is fresh
2. ✅ **Communicate clearly** - Why, not just what
3. ✅ **Commit fully** - No "I told you so" from dissenters
4. ✅ **Monitor outcomes** - Was it the right decision?
5. ✅ **Learn and adapt** - Adjust if not working

### Writing Good Decision Records

**Poor Decision Documentation:**
❌ "We decided to use React"
- Why? What else did you consider? Who decided?

**Good Decision Documentation:**
✅ "After evaluating React, Vue, and Angular against criteria of team expertise, ecosystem, and learning curve, tech lead decided React for faster time-to-market. Vue was close second but smaller community. All 5 frontend devs consulted and agreed."

**Essential Elements:**
- WHO made the decision (accountability)
- WHAT was decided (clear statement)
- WHY this option (rationale)
- WHAT ELSE was considered (alternatives)
- WHAT are the implications (consequences)
- WHEN to review (follow-up date)

---

## ⚠️ Red Flags in Decision Making

### Warning Signs

🚩 **Rushed Decision**
- Deciding without adequate analysis
- Skipping stakeholder consultation
- Not documenting properly

🚩 **Analysis Paralysis**
- Studying forever without deciding
- Requesting more and more data
- Fear of making wrong choice

🚩 **Decision Avoiding**
- Postponing difficult decisions
- Waiting for "perfect information"
- Delegating to avoid responsibility

🚩 **Poor Decision Quality**
- Only 1-2 options considered
- No evaluation criteria used
- Key stakeholders not consulted
- Assumptions not validated

🚩 **Reversal Pattern**
- Same decision made repeatedly
- Constant second-guessing
- Lack of commitment

---

## 🔄 When to Revisit Decisions

### Valid Reasons to Revisit

✅ **New Information**
- Market conditions changed
- Technology evolved significantly
- Requirements shifted

✅ **Assumptions Proven Wrong**
- Expected cost savings didn't materialize
- Technical approach not working
- Team expertise lower than expected

✅ **External Changes**
- Regulatory changes
- Vendor acquisition/closure
- Budget cuts

✅ **Scheduled Review**
- 6-month review revealed issues
- Metrics show poor performance
- Pilot program failed

### Invalid Reasons (Don't Revisit)

❌ **Disagreement alone** - "I didn't agree" not enough
❌ **Buyer's remorse** - Difficulty doesn't mean wrong
❌ **Political pressure** - New stakeholder wants different option
❌ **Implementation challenges** - All approaches have issues

### Revisiting Process

When revisiting:
1. Create new decision (DEC-XXX-R1)
2. Link to original decision
3. Document what changed
4. Full evaluation process again
5. Be explicit about "why now"

---

## 📋 Decision Templates by Type

### Technical Architecture Decision

**Simplified Template:**
```
Decision: [Technology/Approach chosen]
Problem: [What we're solving]
Options: [3-5 alternatives]
Criteria: [Performance, cost, maintainability, team expertise]
Scores: [Matrix showing evaluation]
Chosen: [Winner and why]
Trade-offs: [What we're giving up]
```

### Scope Change Decision

**Simplified Template:**
```
Decision: [Add/Remove/Modify scope]
Reason: [Why change is needed]
Impact: Schedule [+/- X weeks], Budget [+/- $X], Resources [+/- X people]
Approval: [Sponsor signature]
Alternatives Considered: [Brief list]
Risks: [New risks introduced]
```

### Vendor Selection Decision

**Simplified Template:**
```
Decision: [Vendor selected]
RFP Responses: [Vendors evaluated]
Evaluation Criteria: [Weighted scoring]
Finalist Interviews: [Top 2-3]
Reference Checks: [Results]
Contract Terms: [Key points]
Selected: [Winner and rationale]
```

---

## 📎 Related Templates

- [Project Charter](./project-charter-template.md) - Document initial strategic decisions
- [Risk Register](./risk-register-template.md) - Risk response decisions
- [Issues Log](./issues-log-template.md) - Issue resolution decisions
- [Change Request](./change-request-template.md) - Scope change decisions
- [Lessons Learned](./lessons-learned-template.md) - Review decision outcomes

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
