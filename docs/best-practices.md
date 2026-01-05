# Best Practices 💡

Lessons learned from 15+ years and 50+ projects managing complex technical programs.

## 🎯 Core Principles

### 1. Templates Are Tools, Not Goals

**Bad:** "We must complete all 29 templates for this project"  
**Good:** "Which 5-7 templates will add the most value?"

**Lesson Learned:**
On a $50M banking divestiture, we initially used 25 templates. After 2 months, we realized 12 were rarely updated and provided little value. We consolidated to 15 templates and saved 5 hours/week while improving clarity.

**Action:** Start minimal, add templates only when you feel the pain of not having them.

---

### 2. Living Documents Beat Perfect Documents

**Bad:** Spend 2 weeks creating perfect Project Charter, never update it  
**Good:** Create good-enough charter in 2 hours, update weekly

**Lesson Learned:**
I once spent 3 days crafting a "perfect" Risk Register. It had 50 risks, detailed probability/impact analysis, and beautiful formatting. It was never updated after Week 3 because maintaining it was too painful.

**Action:** Create documents that are easy to update. Simple beats comprehensive if simple gets used.

---

### 3. Adapt to Your Audience

**Bad:** Use same Status Report for executives and technical team  
**Good:** Executive dashboard (1 page) + Technical status (detailed)

**Lesson Learned:**
CTO told me: "I don't read past the first page." I was sending 5-page status reports. Created 1-page dashboard for execs, kept detailed report for team. Executive engagement improved 10x.

**Action:** Know your audience. Executives want summaries, teams want details.

---

## 📋 Template-Specific Best Practices

### Project Charter

**Do's:**
- ✅ Keep it to 3-5 pages maximum
- ✅ Get explicit sign-off from sponsor
- ✅ Review and update at major milestones
- ✅ Use it in kickoff meeting
- ✅ Post visibly for team to reference

**Don'ts:**
- ❌ Don't make it a novel (>10 pages)
- ❌ Don't set unrealistic success criteria
- ❌ Don't skip the "Out of Scope" section
- ❌ Don't create and forget

**War Story:**
Skipped "Out of Scope" on a cloud migration. Six months in, business wanted to include data warehouse migration (not planned). Resulted in 3-month delay and budget overrun. Now I'm obsessive about explicitly stating what's NOT included.

---

### Stakeholder Analysis

**Do's:**
- ✅ Update quarterly (stakeholders change)
- ✅ Be honest about power/interest levels
- ✅ Share selectively (not everyone needs to see it)
- ✅ Use it to plan communications

**Don'ts:**
- ❌ Don't make it public (sensitive info)
- ❌ Don't ignore low power/high interest stakeholders
- ❌ Don't forget to identify detractors

**War Story:**
Identified VP of Operations as "Low Interest" early on. He became vocal opponent at month 6 when he realized project affected his team. Should have engaged him earlier despite apparent low interest.

**Lesson:** Interview stakeholders, don't assume their level of interest.

---

### Risk Register

**Do's:**
- ✅ Review weekly in team meeting
- ✅ Focus on top 5 risks each week
- ✅ Update probability as you learn more
- ✅ Celebrate when risks are retired
- ✅ Include "What could go right" (opportunities)

**Don'ts:**
- ❌ Don't let it grow to 100+ risks (unwieldy)
- ❌ Don't rate everything "High" (crying wolf)
- ❌ Don't have mitigation plans without owners
- ❌ Don't forget to retire resolved risks

**War Story:**
Risk Register grew to 87 risks. Nobody read it. Consolidated to "Top 10 Risks" dashboard. Engagement went from 0% to 100% of team.

**Lesson:** Less is more. Focus on what matters.

---

### Status Reports

**Do's:**
- ✅ Lead with RAG status (Red/Amber/Green)
- ✅ Highlight decisions needed
- ✅ Include "What you can do to help"
- ✅ Send consistently (same day/time)
- ✅ Use visuals (charts beat tables)

**Don'ts:**
- ❌ Don't bury the lede (bad news first)
- ❌ Don't sugarcoat problems
- ❌ Don't send if nothing changed (say that)
- ❌ Don't exceed 2 pages

**War Story:**
Project was Red (critical issues) but I wrote "Amber" to avoid alarming stakeholders. Issues exploded. Learned: Bad news doesn't age well. Call it early.

**Lesson:** Honest early = trust. Sugarcoating = loss of credibility.

---

### RACI Matrix

**Do's:**
- ✅ Have exactly one "Accountable" per task
- ✅ Workshop with team (don't dictate)
- ✅ Focus on decisions and deliverables, not every task
- ✅ Review when roles change

**Don'ts:**
- ❌ Don't have multiple "Accountable" (confusion)
- ❌ Don't confuse "Responsible" with "Accountable"
- ❌ Don't make it too granular (>50 rows)
- ❌ Don't create and file away

**War Story:**
Created RACI with 2 people "Accountable" for architecture decisions. Result: 6 weeks of debate, no decisions. Changed to single Accountable (with others as Consulted). Decisions happened.

**Lesson:** Collaboration ≠ consensus. Someone must own the decision.

---

## 🚀 Project Lifecycle Best Practices

### Initiation

**Key Principle:** Invest time upfront to save pain later

**Best Practices:**
1. **Spend 2-3 weeks on Charter & Planning** (don't rush)
2. **Identify all stakeholders early** (they'll find you anyway)
3. **Get executive sponsor commitment** (not just signature)
4. **Document assumptions explicitly** (they'll bite you)
5. **Create visual timeline** (Gantt chart or roadmap)

**Common Mistakes:**
- Rushing to execution without clear scope
- Underestimating effort (planning fallacy)
- Assuming sponsor support = active involvement
- Not identifying constraints early

---

### Planning

**Key Principle:** Plan enough to start, adapt as you learn

**Best Practices:**
1. **Create WBS with team** (not alone)
2. **Build in 20% buffer** (things take longer)
3. **Identify dependencies early** (they're project killers)
4. **Risk identification workshop** (diverse perspectives)
5. **Get team commitment** (estimates + workload)

**Common Mistakes:**
- Planning in isolation (PM alone)
- Optimistic estimates without buffer
- Missing external dependencies
- Not involving team in planning

**War Story:**
Planned entire 18-month program alone over weekend. Team rejected plan Monday morning. Re-planned with team over 2 days. Plan was better AND team was committed.

---

### Execution

**Key Principle:** Communicate, communicate, communicate

**Best Practices:**
1. **Daily standups for team** (15 min, not optional)
2. **Weekly stakeholder updates** (proactive, not reactive)
3. **Biweekly risk reviews** (stay ahead of issues)
4. **Monthly retrospectives** (continuous improvement)
5. **Celebrate wins visibly** (momentum matters)

**Common Mistakes:**
- Only communicating when asked
- Letting issues fester
- Not celebrating progress
- Skipping team check-ins

---

### Monitoring & Control

**Key Principle:** Measure what matters, course-correct quickly

**Best Practices:**
1. **Track 5-7 key metrics** (not 50)
2. **Visualize progress** (burndown, dashboards)
3. **Flag problems early** (Yellow before Red)
4. **Update forecasts regularly** (EAC)
5. **Document changes** (change log)

**Common Mistakes:**
- Too many metrics (analysis paralysis)
- Lagging indicators only (no leading)
- Waiting too long to escalate
- Ignoring trend data

---

### Closure

**Key Principle:** Learn and transition, don't just end

**Best Practices:**
1. **Hold retrospective** (what worked, what didn't)
2. **Document lessons learned** (for next project)
3. **Celebrate with team** (recognition matters)
4. **Transition to operations** (don't drop)
5. **Archive documents** (for future reference)

**Common Mistakes:**
- Skipping retrospective (missed learning)
- Abrupt team dissolution (morale hit)
- No operational handoff (support chaos)
- Not archiving knowledge

---

## 🎭 Stakeholder Management Best Practices

### Executive Stakeholders

**What They Want:**
- Bottom line impact
- Risk summary
- Decision requirements
- 1-page updates

**How to Engage:**
- Monthly steering committee
- 1-page status dashboard
- Escalate only critical issues
- Propose solutions, not just problems

**War Story:**
Sent CFO detailed 5-page status reports. Never got responses. Switched to "3 bullet points + 1 chart" email. Now get responses within hours.

---

### Technical Teams

**What They Want:**
- Clear requirements
- Autonomy to implement
- Minimal meetings
- Recognition for work

**How to Engage:**
- Detailed user stories
- Technical design input
- Daily standups (short)
- Public recognition

---

### Business Users

**What They Want:**
- Understand "what's in it for me"
- Be heard (feedback loops)
- Clear timeline
- Manageable change

**How to Engage:**
- User stories (not technical specs)
- Beta/UAT testing
- Training with plenty of notice
- Change management support

---

## 📊 Metrics That Matter

### Don't Track:
- ❌ Hours logged (meaningless)
- ❌ Lines of code (wrong incentive)
- ❌ Number of meetings (activity ≠ progress)

### Do Track:
- ✅ **% Completion** (progress toward goal)
- ✅ **Velocity** (if Agile)
- ✅ **Burn rate** (spending vs budget)
- ✅ **Cycle time** (how long things take)
- ✅ **Defect rate** (quality indicator)
- ✅ **Team morale** (retention predictor)

**War Story:**
Tracked "tasks completed" religiously. Looked great (100+ tasks closed). Project was Red because all critical path items were blocked. Switched to tracking "critical path progress" (5 tasks). Now focus on what matters.

---

## 🔥 Crisis Management

### When Project Goes Red

**Step 1: Acknowledge Reality (Day 1)**
- Call it Red (don't sugarcoat)
- Identify root cause
- Assess recovery options

**Step 2: Create Recovery Plan (Day 2-3)**
- What can be descoped?
- What can be delayed?
- What needs more resources?
- What's the realistic new timeline?

**Step 3: Get Buy-In (Day 4-5)**
- Present options to sponsor
- Get decision on path forward
- Communicate plan to team
- Reset expectations with stakeholders

**Step 4: Execute Recovery (Ongoing)**
- Daily status checks
- Remove blockers aggressively
- Shield team from noise
- Celebrate small wins

**War Story:**
Project went Red at month 9 of 12. Tried to "work harder" for 2 weeks. Made it worse. Finally admitted we needed help. Got 3 contractors, descoped 2 features, extended 6 weeks. Delivered successfully. Should have called it earlier.

---

## 🤝 Team Management

### Building High-Performing Teams

**Do's:**
- ✅ Clear goals and roles
- ✅ Psychological safety (can raise concerns)
- ✅ Regular feedback
- ✅ Remove obstacles
- ✅ Celebrate wins

**Don'ts:**
- ❌ Micromanage
- ❌ Blame individuals
- ❌ Skip 1-on-1s
- ❌ Ignore morale issues

**War Story:**
Had brilliant developer who was toxic to team. Kept him because of skills. Lost 3 other developers. Should have addressed behavior immediately.

**Lesson:** One toxic person can destroy team. Address quickly or remove.

---

### Remote Team Best Practices

**Challenges:**
- Time zones
- Communication gaps
- Isolation
- Trust building

**Solutions:**
- **Overlap hours:** 2-3 hours minimum
- **Over-communicate:** Default to transparency
- **Video on:** Build connection
- **Async documentation:** Don't block on meetings
- **Virtual social:** Coffee chats, team activities

---

## 💰 Budget Management

### Best Practices

**Do's:**
- ✅ Track weekly (not monthly)
- ✅ Forecast at completion (EAC)
- ✅ Build 10-20% contingency
- ✅ Separate committed from spent
- ✅ Get approval before overrun

**Don'ts:**
- ❌ Don't hide budget issues
- ❌ Don't rob Peter to pay Paul (category shifts)
- ❌ Don't commit without approval
- ❌ Don't forget soft costs (team time)

**War Story:**
Budget showed Green (under by $50K) at month 8. Realized we had $200K in committed but not yet invoiced costs. Actually over by $150K. Now track committed + spent.

---

## 🎯 Decision Making

### Fast Decision Framework

**For Small Decisions (<$10K, <1 week impact):**
- Make it yourself
- Inform stakeholders
- Document in Decision Log

**For Medium Decisions ($10K-$100K, 1-4 week impact):**
- Consult 2-3 key stakeholders
- Make recommendation
- Get sponsor approval
- Document in Decision Log

**For Large Decisions (>$100K, >1 month impact):**
- Full stakeholder analysis
- Options with pros/cons
- Steering committee decision
- Formal approval
- Document thoroughly

**War Story:**
Debated $5K tool purchase for 3 weeks (8 meetings, 20+ emails). Wasted $10K in time discussing $5K decision. Now: Decisions under $10K get made in <24 hours.

---

## 🚧 Common Pitfalls

### Pitfall 1: Scope Creep

**Symptoms:**
- "Small changes" adding up
- No formal change process
- Stakeholders bypassing PM
- Timeline slipping

**Solutions:**
- Change Request process (enforced)
- "Out of Scope" parking lot
- Weekly scope review
- Sponsor gatekeeping

---

### Pitfall 2: Resource Overallocation

**Symptoms:**
- Team working overtime consistently
- Quality declining
- Morale dropping
- Burnout

**Solutions:**
- Track utilization (not >85%)
- Force prioritization
- Push back on unrealistic timelines
- Add resources or descope

---

### Pitfall 3: Communication Breakdown

**Symptoms:**
- Surprises in meetings
- Misaligned expectations
- Duplicate work
- Finger-pointing

**Solutions:**
- Over-communicate
- Single source of truth (Confluence/SharePoint)
- Regular syncs
- Clear RACI

---

## 🏆 Success Patterns

### Pattern 1: Start Small, Scale

**Example:**
- Sprint 1: Prove concept (2 weeks)
- Sprint 2-3: Build MVP (1 month)
- Sprint 4-6: Full features (2 months)
- Continuously validate with users

**Why It Works:**
- Early feedback
- Course correction
- Momentum building
- Risk reduction

---

### Pattern 2: Empowered Teams

**Example:**
- Clear goals, not prescriptive tasks
- Team decides "how"
- PM removes obstacles
- Trust + autonomy

**Why It Works:**
- Ownership and accountability
- Better solutions (team knows best)
- Higher morale
- Faster execution

---

### Pattern 3: Ruthless Prioritization

**Example:**
- Must Have (20% of features)
- Should Have (30% of features)
- Nice to Have (50% of features)
- Ship Must Have first

**Why It Works:**
- Focus on value
- Faster time to market
- Reduce waste
- Flexibility for changes

---

## 💡 Final Thoughts

### The 80/20 Rule

**80% of value comes from 20% of templates**

Your critical templates:
1. Project Charter
2. Status Report
3. Risk Register
4. Issues Log
5. Lessons Learned

**Master these 5 before expanding.**

---

### Continuous Improvement

**After Every Project:**
- What templates added value?
- What templates were ignored?
- What was missing?
- How can we improve?

**Your templates should evolve.**

---

### When in Doubt...

**Ask yourself:**
1. Does this add value? (If no, skip)
2. Will anyone use this? (If no, skip)
3. Can I make it simpler? (Usually yes)
4. Am I solving a real problem? (Better be yes)

---

## 📚 Recommended Reading

**Project Management:**
- "The Lean Startup" - Eric Ries
- "Team Topologies" - Matthew Skelton
- "Accelerate" - Nicole Forsgren

**Leadership:**
- "Radical Candor" - Kim Scott
- "The Manager's Path" - Camille Fournier
- "An Elegant Puzzle" - Will Larson

**Communication:**
- "Crucial Conversations" - Kerry Patterson
- "Never Split the Difference" - Chris Voss

---

## 🆘 Need More Help?

- Review other [docs](README.md)
- Open an [issue](../../issues)
- Browse [templates](../templates/)

---

**Remember: Perfect is the enemy of done. Start simple, iterate, improve.** 🚀

---

_Last updated: January 2026_  
_Based on 15+ years managing 50+ complex technical programs_
```
