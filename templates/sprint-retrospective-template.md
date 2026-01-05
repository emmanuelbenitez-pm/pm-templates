# Sprint Retrospective Template

## 📋 Document Information

| Field | Details |
|-------|---------|
| **Sprint Number** | Sprint [#] |
| **Sprint Goal** | [What the sprint aimed to achieve] |
| **Sprint Dates** | [MM/DD/YYYY] - [MM/DD/YYYY] |
| **Retrospective Date** | [MM/DD/YYYY] |
| **Facilitator** | [Scrum Master Name] |
| **Participants** | [Team member names] |
| **Duration** | [X minutes] |
| **Version** | [1.0] |

---

## 🎯 Sprint Overview

### Sprint Summary

**Sprint Goal:**
[One sentence describing what the sprint aimed to achieve]

**Example:**
> "Complete user authentication system and deploy to staging environment for UAT."

**Sprint Goal Achievement:**
- ✅ Achieved / ⚠️ Partially Achieved / ❌ Not Achieved

**Reason:**
[Brief explanation of why goal was/wasn't achieved]

---

### Sprint Metrics

| Metric | Target | Actual | Variance | Status |
|--------|--------|--------|----------|--------|
| **Story Points Committed** | 45 | 45 | 0 | 🟢 |
| **Story Points Completed** | 45 | 42 | -3 | 🟡 |
| **Velocity** | 45 | 42 | -3 | 🟡 |
| **Stories Completed** | 10 | 9 | -1 | 🟡 |
| **Carry-over Stories** | 0 | 1 | +1 | 🟡 |
| **Defects Found** | <5 | 3 | -2 | 🟢 |
| **Defects Fixed** | All | All | 0 | 🟢 |
| **Code Review Time** | <24 hrs | 18 hrs | -6 hrs | 🟢 |
| **Team Satisfaction** | >4.0/5 | 4.2/5 | +0.2 | 🟢 |

**Sprint Burndown:**
```
Story Points Remaining:
Day 1:  ████████████████ (45 pts)
Day 3:  ██████████████ (38 pts)
Day 5:  ████████████ (32 pts)
Day 7:  ██████████ (25 pts)
Day 9:  ████████ (18 pts)
Day 10: ████ (10 pts)
Day 12: ██ (5 pts)
Day 14: █ (3 pts) ← Sprint end (3 pts carry-over)
```

**Velocity Trend:**
```
Last 5 Sprints:
Sprint 10: ████████ (38 pts)
Sprint 11: ██████████ (42 pts)
Sprint 12: ████████████ (45 pts)
Sprint 13: ███████████ (43 pts)
Sprint 14: ██████████ (42 pts) ← This sprint
Average:   ██████████ (42 pts)
```

---

## 🎨 Retrospective Format

### Format Used: Start-Stop-Continue

**Why This Format:**
[Brief explanation of why you chose this format for this retrospective]

**Other Formats Available:**
- Start-Stop-Continue ⭐ (Used this sprint)
- Glad-Sad-Mad
- 4 L's (Liked, Learned, Lacked, Longed For)
- Sailboat (Wind/Anchors)
- Timeline
- Appreciations
- Mad-Sad-Glad

---

## ✅ What Went Well (Continue)

### Things to Keep Doing

#### 1. Daily Standups at 9:00 AM Sharp ⭐

**Description:**
Team consistently started standups on time at 9:00 AM, lasting exactly 15 minutes.

**Impact:**
- ✅ Better team alignment
- ✅ Blockers identified and resolved faster
- ✅ No time wasted
- ✅ Set positive tone for the day

**Evidence:**
- 10/10 standups started on time this sprint
- Average duration: 14 minutes
- 3 blockers identified and resolved same day

**Who Raised:** [Dev 1, Dev 2, QA Lead]

**Action:** 🟢 **CONTINUE** - Keep this practice

---

#### 2. Pair Programming for Complex Features ⭐

**Description:**
Backend and frontend developers paired on authentication integration (Story-345).

**Impact:**
- ✅ Fewer bugs (0 defects vs typical 2-3)
- ✅ Knowledge sharing (junior dev learned OAuth)
- ✅ Faster completion (3 days vs estimated 5)
- ✅ Better code quality

**Evidence:**
- Story completed 40% faster
- Zero defects found in code review
- Both developers can now handle auth features

**Who Raised:** [Tech Lead, Dev 3]

**Action:** 🟢 **CONTINUE** - Use for complex features (>8 pts)

---

#### 3. Automated Deployment to Staging

**Description:**
CI/CD pipeline automatically deploys to staging on merge to develop branch.

**Impact:**
- ✅ QA can test immediately after merge
- ✅ Reduced deployment time (2 hours → 5 minutes)
- ✅ Fewer deployment errors
- ✅ Faster feedback loop

**Evidence:**
- 23 successful automated deployments this sprint
- 0 failed deployments
- QA started testing within 10 minutes of merge

**Who Raised:** [QA Lead, DevOps]

**Action:** 🟢 **CONTINUE** - Extend to production (next sprint)

---

#### 4. Weekly Tech Debt Friday ⭐

**Description:**
Every Friday afternoon (2 hours) dedicated to paying down technical debt.

**Impact:**
- ✅ Code quality improving
- ✅ Test coverage increased (75% → 82%)
- ✅ Fewer bugs in new features
- ✅ Team morale improved

**Evidence:**
- Refactored 3 modules this sprint
- Code coverage up 7%
- Tech debt backlog reduced by 15%

**Who Raised:** [Tech Lead, Dev Team]

**Action:** 🟢 **CONTINUE** - Permanent practice

---

#### 5. Sprint Demo with Pizza 🍕

**Description:**
End-of-sprint demo with stakeholders, followed by team pizza celebration.

**Impact:**
- ✅ Better stakeholder engagement (10/12 attended)
- ✅ Immediate feedback on features
- ✅ Team bonding and celebration
- ✅ Positive energy entering next sprint

**Who Raised:** [Product Owner, Team]

**Action:** 🟢 **CONTINUE** - Budget approved for future sprints

---

## ❌ What Didn't Go Well (Stop)

### Things to Stop Doing

#### 1. Accepting Stories Without Acceptance Criteria 🛑

**Description:**
Story-456 was pulled into sprint without clear acceptance criteria, causing confusion and rework.

**Impact:**
- ❌ 2 days wasted on wrong implementation
- ❌ Had to redo work after Product Owner clarification
- ❌ Developer frustration
- ❌ Story carried over to next sprint

**Evidence:**
- Story estimated at 5 pts, took 10 pts of effort
- 3 rounds of rework required
- Team satisfaction score dipped on Day 8

**Who Raised:** [Dev 2, Dev 4]

**Root Cause:**
- Product Owner rushed story into sprint
- Team didn't push back on unclear requirements
- Sprint planning was rushed (30 min vs usual 2 hrs)

**Action:** 🔴 **STOP** - No stories without acceptance criteria

**Prevention:**
- [ ] Update Definition of Ready checklist
- [ ] Scrum Master to enforce in sprint planning
- [ ] Product Owner commits to reviewing backlog by Thursday before sprint

---

#### 2. Last-Minute Pull Requests on Friday 🛑

**Description:**
Large PRs submitted Friday afternoon, forcing reviewers to work weekend or delay merge.

**Impact:**
- ❌ Reviewers felt pressured
- ❌ Lower quality reviews (2 bugs slipped through)
- ❌ Weekend work for some team members
- ❌ Stressful end to sprint

**Evidence:**
- 4 PRs submitted after 3pm Friday
- Average PR review time: 15 min (rushed vs usual 45 min)
- 2 bugs found in production that should've been caught in review

**Who Raised:** [Dev 1, Dev 3, Dev 5]

**Root Cause:**
- Poor time management
- Underestimation of tasks
- Fear of not completing sprint commitment

**Action:** 🔴 **STOP** - No PRs after 2pm Friday

**Prevention:**
- [ ] PR cutoff time: Thursday 5pm (ideal), Friday 12pm (absolute deadline)
- [ ] Team agreement: If not ready by Friday 12pm, carry to next sprint
- [ ] Better task breakdown to identify late completion earlier

---

#### 3. Skipping Code Reviews for "Quick Fixes" 🛑

**Description:**
3 "hotfixes" merged without code review to "save time."

**Impact:**
- ❌ Introduced 2 new bugs
- ❌ Violated team agreements
- ❌ Created technical debt
- ❌ Set bad precedent

**Evidence:**
- 3 hotfixes without review
- 2 resulted in production issues
- 4 hours spent fixing issues vs 30 min for proper review

**Who Raised:** [Tech Lead, QA Lead]

**Root Cause:**
- Pressure to fix issues quickly
- Overconfidence in "simple" fixes
- Unclear escalation process

**Action:** 🔴 **STOP** - ALL code requires review, no exceptions

**Prevention:**
- [ ] Update team working agreement
- [ ] Emergency process: Pair review in real-time (10 min max)
- [ ] Track "quick fixes" that caused issues

---

## 🔄 What to Start Doing (Start)

### New Practices to Try

#### 1. Mid-Sprint Check-in (Day 7) 🆕

**Proposal:**
Add 15-minute team check-in on Day 7 to assess sprint progress and adjust if needed.

**Why:**
- Several times this sprint we realized too late that stories were blocked
- Could have re-prioritized or asked for help earlier
- Better than waiting until Day 14 to discover problems

**Expected Benefits:**
- Earlier identification of blockers
- Opportunity to re-prioritize
- Less carry-over work
- Better sprint goal achievement

**Who Proposed:** [Scrum Master, Dev 2]

**Team Vote:** 8 for, 0 against, 1 abstain

**Action:** 🟢 **START** - Try for 3 sprints, then retrospect

**Implementation:**
- [ ] Day 7, 2:00 PM, 15 minutes
- [ ] Agenda: Sprint burndown review, blockers, risk to sprint goal
- [ ] Scrum Master to facilitate

---

#### 2. Definition of Done Checklist 🆕

**Proposal:**
Create checklist that must be completed before marking story as "Done."

**Why:**
- Inconsistent interpretation of "Done"
- Some stories marked done without tests
- Documentation sometimes forgotten
- QA finding issues that should've been caught

**Expected Benefits:**
- Consistent quality
- Fewer defects reaching QA
- Clear expectations
- Better velocity accuracy

**Who Proposed:** [QA Lead, Tech Lead]

**Team Vote:** 9 for, 0 against

**Action:** 🟢 **START** - Implement next sprint

**Definition of Done Draft:**
- [ ] Code complete and checked into repo
- [ ] Unit tests written (>80% coverage)
- [ ] Code review approved
- [ ] Acceptance criteria met
- [ ] Tested in dev environment
- [ ] Documentation updated
- [ ] No critical/high bugs
- [ ] Product Owner accepted

---

#### 3. Rotating Facilitator for Retrospectives 🆕

**Proposal:**
Different team member facilitates retrospective each sprint instead of always Scrum Master.

**Why:**
- Fresh perspectives on format
- Team ownership of process
- Professional development
- Scrum Master can participate fully

**Expected Benefits:**
- More variety in retrospective formats
- Team engagement increased
- Skill development
- New insights from different facilitators

**Who Proposed:** [Dev 3]

**Team Vote:** 7 for, 2 neutral, 0 against

**Action:** 🟢 **START** - Try for 3 sprints

**Implementation:**
- [ ] Volunteer schedule created
- [ ] Facilitator trains next facilitator
- [ ] Format selection guide provided
- [ ] Scrum Master available as backup

---

#### 4. Bug Bash Day (Last Day of Sprint) 🆕

**Proposal:**
Dedicate last 2 hours of sprint to whole team testing/bug hunting.

**Why:**
- QA finding issues late in sprint
- Developers not testing outside their story
- Integration issues discovered late
- End-to-end scenarios not always tested

**Expected Benefits:**
- Earlier defect detection
- Better integration testing
- Team understanding of full system
- Fewer surprises in production

**Who Proposed:** [QA Lead]

**Team Vote:** 6 for, 3 neutral, 0 against

**Action:** 🟢 **START** - Pilot next sprint

**Implementation:**
- [ ] Schedule: Day 14, 2:00-4:00 PM
- [ ] QA prepares test scenarios
- [ ] Everyone tests (including PO and SM)
- [ ] Log all findings immediately

---

## 💡 Insights & Learnings

### Key Insights

#### Insight #1: Sprint Planning Quality Directly Affects Sprint Success

**Observation:**
The one sprint with rushed planning (30 min) resulted in most issues - unclear stories, wrong estimates, carry-over work.

**Learning:**
Quality sprint planning is worth the investment. Rushing saves 90 minutes but costs days of rework.

**Action:**
- Protect 2-hour sprint planning time slot
- No exceptions for "quick planning"
- Better prep: PO refines backlog by Thursday

---

#### Insight #2: Pair Programming Has Hidden Benefits

**Observation:**
Beyond fewer bugs, pair programming led to knowledge sharing, better morale, and faster onboarding of junior devs.

**Learning:**
ROI of pair programming is higher than expected when accounting for intangible benefits.

**Action:**
- Use strategically (complex features, onboarding, knowledge transfer)
- Not for everything (simple CRUD can be solo)

---

#### Insight #3: Team Morale Correlates with Sprint Success

**Observation:**
Sprint 14 had highest team satisfaction (4.2/5) and second-highest velocity (42 pts). Sprint 11 (lowest satisfaction 3.5) had lowest velocity (38 pts).

**Data:**
```
Sprint | Satisfaction | Velocity
11     | 3.5/5       | 38 pts
12     | 3.8/5       | 45 pts
13     | 4.0/5       | 43 pts
14     | 4.2/5       | 42 pts
```

**Learning:**
Happy team = productive team. Invest in morale (pizza, celebrations, addressing concerns).

---

## 📊 Team Health Check

### Team Satisfaction Survey Results

**Question: How satisfied were you with this sprint? (1-5)**

| Rating | Count | % |
|--------|-------|---|
| 5 (Very Satisfied) | 4 | 44% |
| 4 (Satisfied) | 3 | 33% |
| 3 (Neutral) | 2 | 22% |
| 2 (Dissatisfied) | 0 | 0% |
| 1 (Very Dissatisfied) | 0 | 0% |
| **Average** | **4.2/5** | |

**Trend:** ↗️ Improving (was 4.0 last sprint)

---

### Team Temperature Check

**How did the sprint feel?**

😊 **Positive Comments:**
- "Best sprint in months - we worked well together"
- "Loved the pair programming session"
- "Finally got to pay down some tech debt"
- "Pizza demo was fun and stakeholders were engaged"

😐 **Neutral Comments:**
- "Sprint was okay, nothing special"
- "Wish we'd completed all stories"

😟 **Concerns:**
- "Still too many meetings" (2 people)
- "Felt rushed at end of sprint"
- "Need better requirements upfront"

---

### Psychological Safety Check

**Questions:**

**"I feel safe speaking up with ideas, questions, or concerns"**
- Strongly Agree: 6
- Agree: 3
- Neutral: 0
- Disagree: 0

**"Team treats mistakes as learning opportunities"**
- Strongly Agree: 5
- Agree: 4
- Neutral: 0
- Disagree: 0

**"I can be myself on this team"**
- Strongly Agree: 7
- Agree: 2
- Neutral: 0
- Disagree: 0

**Assessment:** 🟢 High psychological safety (excellent)

---

## 🎯 Action Items

### Action Items from This Retrospective

| # | Action | Owner | Due Date | Status |
|---|--------|-------|----------|--------|
| 1 | Update Definition of Ready (no stories without AC) | [Scrum Master] | Before Sprint 15 planning | ⚪ To Do |
| 2 | Create Definition of Done checklist | [Tech Lead] | Before Sprint 15 planning | ⚪ To Do |
| 3 | Schedule mid-sprint check-in (Day 7) | [Scrum Master] | Recurring | ⚪ To Do |
| 4 | Set up PR cutoff policy (Fri 12pm) | [Tech Lead] | Before Sprint 15 | ⚪ To Do |
| 5 | Organize rotating facilitator schedule | [Scrum Master] | Before Sprint 16 | ⚪ To Do |
| 6 | Schedule Bug Bash for Sprint 15 | [QA Lead] | Sprint 15, Day 14 | ⚪ To Do |
| 7 | Update team working agreement | [Scrum Master] | Before Sprint 15 | ⚪ To Do |
| 8 | Train next retrospective facilitator | [Scrum Master] | Before Sprint 15 | ⚪ To Do |

---

### Previous Sprint Action Items - Status Update

| # | Action | Owner | Status | Notes |
|---|--------|-------|--------|-------|
| 1 | Implement automated deployment | [DevOps] | ✅ Done | Working great! |
| 2 | Create tech debt backlog | [Tech Lead] | ✅ Done | 45 items identified |
| 3 | Schedule weekly tech debt time | [Scrum Master] | ✅ Done | Friday 2-4pm |
| 4 | Improve sprint planning prep | [PO] | 🟡 In Progress | Better but not perfect |
| 5 | Set up pair programming schedule | [Tech Lead] | ✅ Done | Used 3x this sprint |

**Completion Rate:** 80% (4/5 completed)

---

## 🏆 Recognitions & Appreciations

### Shout-Outs

**Team Appreciations:**

**🏆 [Dev 1]**
> "Thank you for staying late to help me debug the authentication issue. Couldn't have figured it out without you!" - Dev 2

**🏆 [QA Lead]**
> "Your detailed bug reports are amazing - screenshots, steps, logs. Makes fixes so much faster!" - Dev Team

**🏆 [Product Owner]**
> "Great job being flexible when we had to descope Story-456. Your understanding made a stressful situation manageable." - Team

**🏆 [Scrum Master]**
> "Thank you for protecting our focus time and shielding us from unnecessary meetings this sprint." - Team

**🏆 Entire Team**
> "Best team collaboration I've seen in 5 years. You all showed up for each other." - Tech Lead

---

## 📈 Trends & Patterns

### Multi-Sprint Analysis

**Velocity Stability:**
```
Last 6 Sprints:
Sprint 9:  36 pts (Low due to holiday)
Sprint 10: 38 pts
Sprint 11: 42 pts
Sprint 12: 45 pts
Sprint 13: 43 pts
Sprint 14: 42 pts
Average:   41 pts
Std Dev:   3.2 pts (Good - consistent)
```

**Trend:** → Stable around 42 points

---

**Carry-over Rate:**
```
Sprint 9:  2 stories carried over
Sprint 10: 1 story carried over
Sprint 11: 0 stories ✅
Sprint 12: 0 stories ✅
Sprint 13: 1 story
Sprint 14: 1 story
```

**Trend:** → Improving (was 2-3 stories regularly)

---

**Defect Trend:**
```
Sprint 9:  8 defects found
Sprint 10: 6 defects found
Sprint 11: 7 defects found
Sprint 12: 4 defects found
Sprint 13: 5 defects found
Sprint 14: 3 defects found ✅
```

**Trend:** ↘️ Decreasing (good!)

**Analysis:** Code reviews, pair programming, and tech debt work paying off.

---

## 💬 Open Discussion Notes

### Topics Discussed

**Topic 1: Meeting Overload**
- Concern raised: Too many meetings cutting into focus time
- Discussion: Listed all recurring meetings (standups, planning, review, retro, refinement)
- Conclusion: All meetings necessary, but can optimize
- Action: Combine refinement with backlog grooming (save 30 min/week)

**Topic 2: Remote vs In-Office**
- Mixed feelings about hybrid schedule
- Remote days: More focus time, less commute stress
- Office days: Better collaboration, clearer communication
- Conclusion: Keep current 2 days remote, 3 days office
- Revisit in 3 months

**Topic 3: Sprint Duration**
- Question: Should we try 1-week sprints instead of 2-week?
- Discussion: Pros (more frequent feedback) vs Cons (planning overhead)
- Conclusion: Stick with 2 weeks, working well
- Mid-sprint check-in will give similar benefit

---

## 🎓 Retrospective About the Retrospective

### Meta Retrospective

**What worked well in this retrospective:**
- ✅ Start-Stop-Continue format was clear and actionable
- ✅ Everyone participated (9/9 team members)
- ✅ Good mix of tactical and strategic topics
- ✅ Ended on time (60 minutes)
- ✅ Action items are specific and owned

**What could be better:**
- ⚠️ Could use more data/metrics
- ⚠️ Ran a bit over time (5 minutes)
- ⚠️ Some topics deserved deeper discussion

**Next retrospective format:**
Consider "4 L's" (Liked, Learned, Lacked, Longed For) for variety.

---

## 📎 Related Templates

- [Product Backlog](./product-backlog-template.md) - Sprint planning source
- [Meeting Notes](./meeting-notes-template.md) - Document discussions
- [Lessons Learned](./lessons-learned-template.md) - Project-level learnings
- [Decision Log](./decision-log-template.md) - Document team decisions

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
