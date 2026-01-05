# Product Backlog Template

## 📋 Document Information

| Field | Details |
|-------|---------|
| **Product Name** | [Enter product name] |
| **Product Owner** | [Name] |
| **Scrum Master** | [Name] |
| **Date Created** | [MM/DD/YYYY] |
| **Last Updated** | [MM/DD/YYYY] |
| **Version** | [1.0] |
| **Current Sprint** | Sprint [#] |

---

## 🎯 Product Backlog Overview

### What is a Product Backlog?

A Product Backlog is an ordered list of everything that is known to be needed in the product. It is the single source of requirements for any changes to be made to the product. The Product Owner is responsible for the Product Backlog, including its content, availability, and ordering.

### Product Vision

**Vision Statement:**
[One paragraph describing what the product aims to achieve and for whom]

**Example:**
> "To provide small business owners with an intuitive, affordable project management tool that helps them deliver projects on time and within budget, without requiring formal PM training."

**Target Users:**
- [User Persona 1: e.g., Small business owners]
- [User Persona 2: e.g., Freelance consultants]
- [User Persona 3: e.g., Startup teams <10 people]

**Success Metrics:**
- [Metric 1: e.g., 10,000 active users within 6 months]
- [Metric 2: e.g., 4.5+ star rating in app stores]
- [Metric 3: e.g., 60% user retention after 3 months]

---

## 📊 Backlog Structure

### Hierarchy
```
Theme (Strategic)
    ↓
Epic (Large feature)
    ↓
User Story (Deliverable in 1 sprint)
    ↓
Task (Development work)
    ↓
Sub-task (Granular work item)
```

### Item Types

| Type | Description | Typical Size | Example |
|------|-------------|--------------|---------|
| **Theme** | Strategic business goal | Multiple epics | "User Onboarding Experience" |
| **Epic** | Large feature/capability | 2-4 sprints | "User Registration System" |
| **User Story** | Specific user functionality | 1-5 days | "As a user, I can reset my password via email" |
| **Task** | Technical work | Hours | "Create password reset API endpoint" |
| **Bug** | Defect to fix | Varies | "Login button doesn't work on mobile Safari" |
| **Spike** | Research/investigation | 1-3 days | "Investigate OAuth integration options" |
| **Tech Debt** | Refactoring/improvement | Varies | "Refactor authentication module" |

---

## 📋 Product Backlog Items

### Backlog Format

| ID | Type | Priority | Title | Description | Story Points | Status | Sprint |
|----|------|----------|-------|-------------|--------------|--------|--------|
| PBI-001 | Epic | High | User Authentication | Complete auth system | 34 | 🟡 In Progress | 3-5 |
| PBI-002 | Story | High | User login | As a user, I can log in with email/password | 5 | 🟢 Done | 3 |
| PBI-003 | Story | High | Password reset | As a user, I can reset my password via email | 3 | 🟡 In Progress | 4 |
| PBI-004 | Story | Medium | Social login | As a user, I can log in with Google/Facebook | 8 | ⚪ To Do | 5 |
| PBI-005 | Story | High | User dashboard | As a user, I see my projects on dashboard | 5 | ⚪ To Do | 5 |
| PBI-006 | Bug | Critical | Login timeout | Users getting logged out after 5 min | 2 | 🔴 Blocked | 4 |

**Status Legend:**
- 🟢 Done - Completed and accepted
- 🟡 In Progress - Currently being worked on
- ⚪ To Do - Ready for development
- 🔴 Blocked - Cannot proceed
- ⏸️ On Hold - Paused

---

## 🎯 User Story Template

### User Story Format

#### PBI-XXX: [Story Title]

**As a** [type of user]  
**I want** [goal/desire]  
**So that** [benefit/value]

**Example:**
> **As a** project manager  
> **I want** to see a Gantt chart of my project timeline  
> **So that** I can visualize dependencies and identify schedule risks

---

### Story Details

| Field | Details |
|-------|---------|
| **Story ID** | PBI-XXX |
| **Title** | [Short, descriptive title] |
| **Priority** | Critical / High / Medium / Low |
| **Story Points** | [1, 2, 3, 5, 8, 13, 21] (Fibonacci) |
| **Business Value** | [High / Medium / Low] |
| **Sprint** | Sprint [#] |
| **Status** | To Do / In Progress / Done |
| **Assigned To** | [Developer Name] |
| **Created By** | [Product Owner] |
| **Created Date** | [MM/DD/YYYY] |

---

### Acceptance Criteria

**Given** [initial context/state]  
**When** [action/event]  
**Then** [expected outcome]

**Example Acceptance Criteria:**

✅ **AC1:** Given I am on the login page, When I enter valid credentials and click Login, Then I am redirected to my dashboard

✅ **AC2:** Given I enter invalid credentials, When I click Login, Then I see an error message "Invalid email or password"

✅ **AC3:** Given I have entered my email, When I click "Forgot Password", Then I receive a password reset email within 5 minutes

✅ **AC4:** Given the password reset link is clicked, When it's been >24 hours since sent, Then the link is expired and shows error

---

### Additional Information

**Dependencies:**
- [PBI-XXX: e.g., User registration must be complete]
- [External: e.g., Email service provider configured]

**Technical Notes:**
- [Note 1: e.g., Use JWT for session management]
- [Note 2: e.g., Password must be hashed with bcrypt]
- [Note 3: e.g., Rate limit password reset to 3 attempts/hour]

**UI/UX Notes:**
- [Link to mockup/wireframe]
- [Specific design considerations]

**Testing Notes:**
- [Test case 1]
- [Test case 2]
- [Security testing required]

**Definition of Done:**
- [ ] Code complete and checked in
- [ ] Unit tests written and passing (>80% coverage)
- [ ] Code review completed
- [ ] Acceptance criteria met
- [ ] Tested in QA environment
- [ ] Documentation updated
- [ ] Product Owner approval

---

## 🏆 Prioritization

### Priority Criteria

**Priority Levels:**

**🔴 Critical (P0):**
- Blocking other work
- Security vulnerability
- Production down
- Legal/compliance requirement

**🟠 High (P1):**
- High business value
- User-facing feature (MVP)
- Significant impact if delayed
- Committed to customer

**🟡 Medium (P2):**
- Important but not urgent
- Can be deferred 1-2 sprints
- Nice-to-have enhancement
- Internal improvement

**🟢 Low (P3):**
- Future consideration
- Low ROI
- Experimental
- Distant roadmap item

---

### Prioritization Framework: RICE

**RICE Score = (Reach × Impact × Confidence) / Effort**

| Story ID | Reach | Impact | Confidence | Effort | RICE Score | Priority |
|----------|-------|--------|------------|--------|------------|----------|
| PBI-001 | 5000 users | 3 (High) | 80% | 5 weeks | 2400 | High |
| PBI-002 | 1000 users | 2 (Med) | 100% | 2 weeks | 1000 | Medium |
| PBI-003 | 500 users | 1 (Low) | 50% | 3 weeks | 83 | Low |

**Definitions:**
- **Reach:** How many users will this impact per time period?
- **Impact:** How much will this impact each user? (3=High, 2=Medium, 1=Low, 0.5=Minimal)
- **Confidence:** How confident are we in our estimates? (100%=High, 80%=Med, 50%=Low)
- **Effort:** How much time will this take? (Person-weeks)

---

### MoSCoW Method

**Must Have:**
- [Story 1] - Critical for MVP
- [Story 2] - Legal requirement
- [Story 3] - Core functionality

**Should Have:**
- [Story 4] - Important but not critical
- [Story 5] - Significant value add

**Could Have:**
- [Story 6] - Nice to have if time permits
- [Story 7] - Enhancement

**Won't Have (This Release):**
- [Story 8] - Deferred to Phase 2
- [Story 9] - Low priority

---

## 📅 Sprint Planning

### Current Sprint: Sprint [#]

**Sprint Goal:**
[One sentence describing what this sprint aims to achieve]

**Example:**
> "Complete user authentication system and enable users to log in, log out, and reset passwords."

**Sprint Duration:** [2 weeks]  
**Sprint Start:** [MM/DD/YYYY]  
**Sprint End:** [MM/DD/YYYY]

---

### Sprint Backlog

**Committed Stories:**

| Story ID | Title | Story Points | Assigned To | Status |
|----------|-------|--------------|-------------|--------|
| PBI-002 | User login | 5 | [Dev 1] | 🟢 Done |
| PBI-003 | Password reset | 3 | [Dev 2] | 🟡 In Progress |
| PBI-006 | Fix login timeout | 2 | [Dev 1] | ⚪ To Do |

**Total Committed:** 10 points  
**Team Velocity:** 12 points/sprint (average)  
**Capacity:** 80% utilized (good)

---

### Sprint Burndown
```
Story Points Remaining:
Day 1:  ████████████ (10 points)
Day 3:  ██████████ (8 points)
Day 5:  ████████ (6 points)
Day 7:  ██████ (5 points) ← Current
Day 9:  ████ (3 points - projected)
Day 10: ██ (1 point - projected)
Sprint End: ✅ (0 points - target)
```

**Trend:** 🟢 On track to complete all committed stories

---

## 📊 Backlog Metrics

### Backlog Health

| Metric | Target | Current | Status |
|--------|--------|---------|--------|
| **Total Items** | <100 | [X] | 🟢🟡🔴 |
| **Ready for Sprint** | >2 sprints worth | [X items] | 🟢🟡🔴 |
| **Refined Items** | >80% | [%] | 🟢🟡🔴 |
| **Epics in Progress** | <3 | [X] | 🟢🟡🔴 |
| **Blocked Items** | 0 | [X] | 🟢🟡🔴 |
| **Avg Story Age** | <30 days | [X days] | 🟢🟡🔴 |

**Healthy Backlog Indicators:**
- ✅ Stories clearly defined
- ✅ Priorities up to date
- ✅ Next 2 sprints planned
- ✅ Acceptance criteria documented
- ✅ Story points estimated
- ✅ No long-stale items

---

### Velocity Tracking

| Sprint | Committed Points | Completed Points | Velocity | Trend |
|--------|------------------|------------------|----------|-------|
| Sprint 1 | 10 | 8 | 8 | - |
| Sprint 2 | 12 | 12 | 12 | ↗️ |
| Sprint 3 | 15 | 13 | 13 | → |
| Sprint 4 | 14 | 14 | 14 | ↗️ |
| **Average** | | | **11.75** | |

**Velocity Trend:** Improving (🟢)

---

## 🔄 Backlog Refinement

### Refinement Process

**When:** Weekly, mid-sprint  
**Duration:** 1-2 hours  
**Attendees:** Product Owner, Scrum Master, Development Team

**Agenda:**
1. **Review New Items** (20 min)
   - New stories added since last session
   - Discuss and ask questions

2. **Refine Upcoming Stories** (30 min)
   - Stories for next 2 sprints
   - Break down large stories
   - Add acceptance criteria
   - Estimate story points

3. **Re-prioritize** (20 min)
   - Move items up/down based on business needs
   - Remove obsolete items

4. **Clarify Requirements** (20 min)
   - Answer team questions
   - Provide missing details
   - Update story descriptions

**Output:**
- [ ] Next sprint ready (all stories refined and estimated)
- [ ] Priorities updated
- [ ] Blockers identified and addressed
- [ ] Team has clarity on upcoming work

---

### Story Readiness Checklist

**A story is "ready" when:**
- [ ] Written in user story format (As a... I want... So that...)
- [ ] Acceptance criteria defined (Given... When... Then...)
- [ ] Story points estimated by team
- [ ] Dependencies identified
- [ ] Mockups/wireframes attached (if UI work)
- [ ] Technical approach discussed
- [ ] No blocking questions remaining
- [ ] Small enough to complete in one sprint

**Definition of Ready:** All checkboxes above must be checked

---

## 🎯 Epics

### Epic Template

#### Epic: [Epic Name]

**Epic ID:** EPIC-XXX

**Description:**
[Detailed description of the epic and its purpose]

**Business Objective:**
[What business goal does this epic support?]

**Success Metrics:**
- [Metric 1: e.g., 80% of users complete onboarding]
- [Metric 2: e.g., Average onboarding time <5 minutes]

**User Stories in Epic:**
- [ ] PBI-001: [Story title] (5 points) - Sprint 3
- [ ] PBI-002: [Story title] (3 points) - Sprint 3
- [ ] PBI-003: [Story title] (8 points) - Sprint 4
- [ ] PBI-004: [Story title] (5 points) - Sprint 4

**Total Estimate:** 21 story points  
**Expected Duration:** 2 sprints  
**Progress:** [X/Y stories complete] ([%])

**Dependencies:**
- [Dependency 1]
- [Dependency 2]

**Risks:**
- [Risk 1 and mitigation]
- [Risk 2 and mitigation]

**Status:** 🟡 In Progress  
**Owner:** [Product Owner]  
**Target Completion:** Sprint [#]

---

## 📈 Roadmap

### Product Roadmap (Next 6 Months)
```
Q1 2026
├── ✅ MVP Launch
│   ├── User authentication
│   ├── Project creation
│   └── Basic task management
│
Q2 2026
├── 🟡 Collaboration Features (Current)
│   ├── Team invites
│   ├── Comments
│   ├── File sharing
│   └── Activity feed
│
Q3 2026
├── ⚪ Reporting & Analytics
│   ├── Project dashboards
│   ├── Time tracking
│   ├── Budget tracking
│   └── Export capabilities
│
Q4 2026
├── ⚪ Mobile Apps
│   ├── iOS app
│   ├── Android app
│   └── Offline mode
```

**Roadmap Themes:**
- Q1: Core Functionality
- Q2: Collaboration
- Q3: Insights & Analytics
- Q4: Mobile Experience

---

## 🐛 Bug Tracking

### Bug Backlog

| Bug ID | Severity | Title | Affected Feature | Reported By | Status |
|--------|----------|-------|------------------|-------------|--------|
| BUG-001 | Critical | Login fails on Safari | Authentication | User | 🔴 Open |
| BUG-002 | High | Date picker wrong timezone | Project dates | QA | 🟡 In Progress |
| BUG-003 | Medium | Export PDF layout broken | Reports | User | ⚪ To Do |
| BUG-004 | Low | Button hover effect | UI | Designer | ⚪ To Do |

**Bug Prioritization:**
- **Critical:** Production down, data loss, security
- **High:** Major feature broken, many users affected
- **Medium:** Feature broken, workaround exists
- **Low:** Cosmetic, minor inconvenience

**Bug SLA:**
- Critical: Fix within 4 hours
- High: Fix within 1 sprint
- Medium: Fix within 2 sprints
- Low: Fix when capacity allows

---

## 💡 Best Practices

### Product Backlog Do's ✅

1. **Keep it Prioritized** - Top items most important
2. **Keep it Refined** - Next 2 sprints ready
3. **Keep it Small** - Stories fit in one sprint
4. **Keep it Clear** - Acceptance criteria defined
5. **Keep it Visible** - Accessible to whole team
6. **Keep it Updated** - Review and adjust regularly
7. **Keep it Focused** - Remove obsolete items
8. **Keep it Estimated** - Story points for planning

### Product Backlog Don'ts ❌

1. **Don't Over-Refine** - Don't detail stories 6+ months out
2. **Don't Skip Acceptance Criteria** - Leads to rework
3. **Don't Ignore Technical Debt** - Balance with features
4. **Don't Let it Bloat** - Remove old/obsolete items
5. **Don't Commit Too Early** - Keep options open
6. **Don't Surprise the Team** - Involve them in refinement
7. **Don't Forget Business Value** - Always know "why"
8. **Don't Make it Perfect** - Good enough to start

---

## 🔧 Estimation

### Story Point Scale (Fibonacci)

| Points | Complexity | Time | Example |
|--------|------------|------|---------|
| **1** | Trivial | <4 hours | Fix typo, update text |
| **2** | Simple | 4-8 hours | Simple form field |
| **3** | Easy | 1-2 days | Basic CRUD operation |
| **5** | Medium | 2-3 days | API integration |
| **8** | Complex | 3-5 days | Complex feature |
| **13** | Very Complex | 1-2 weeks | Major subsystem |
| **21** | Epic | 2-4 weeks | Too large, break down |

**Factors in Estimation:**
- Development time
- Testing time
- Complexity
- Uncertainty
- Dependencies

**Estimation Techniques:**
- Planning Poker (team consensus)
- T-shirt sizing (S, M, L, XL)
- Relative estimation (compare to known stories)

---

## 📎 Related Templates

- [Meeting Notes](./meeting-notes-template.md) - Sprint ceremonies
- [Decision Log](./decision-log-template.md) - Product decisions
- [Risk Register](./risk-register-template.md) - Product risks
- [Quality Checklist](./quality-checklist-template.md) - Definition of Done

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
