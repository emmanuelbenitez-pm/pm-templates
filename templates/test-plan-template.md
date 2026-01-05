# Test Plan Template

## 📋 Document Information

| Field | Details |
|-------|---------|
| **Project Name** | [Enter project name] |
| **Test Manager** | [Name] |
| **Project Manager** | [Name] |
| **Date Created** | [MM/DD/YYYY] |
| **Last Updated** | [MM/DD/YYYY] |
| **Version** | [1.0] |
| **Test Phase** | Unit / Integration / System / UAT / Regression / Performance |

---

## 🎯 Test Plan Overview

### Purpose

This test plan outlines the strategy, scope, approach, resources, and schedule for testing activities for [Project Name]. It defines what will be tested, how it will be tested, when it will be tested, and who will test it.

### Objectives

**Primary Testing Objectives:**
1. [Objective 1: e.g., Verify all functional requirements are met]
2. [Objective 2: e.g., Ensure system performance meets SLAs]
3. [Objective 3: e.g., Validate security controls are effective]

**Success Criteria:**
- All critical and high priority test cases pass
- >95% of all test cases pass
- No critical or high severity defects open
- Performance benchmarks met
- Security vulnerabilities addressed
- UAT sign-off obtained

---

## 📊 Test Scope

### In Scope

**Features to be Tested:**
- [Feature 1 - User authentication]
- [Feature 2 - Data entry and validation]
- [Feature 3 - Reporting functionality]
- [Feature 4 - API integrations]
- [Feature 5 - Mobile responsiveness]

**Test Types in Scope:**
- ✅ Functional Testing
- ✅ Integration Testing
- ✅ Performance Testing
- ✅ Security Testing
- ✅ Usability Testing
- ✅ Regression Testing
- ✅ User Acceptance Testing (UAT)

**Environments:**
- Development
- QA/Test
- Staging
- Production (smoke testing only)

---

### Out of Scope

**Not to be Tested:**
- ❌ Third-party vendor systems (tested by vendor)
- ❌ Legacy system features (unchanged)
- ❌ Infrastructure layer (tested by IT Ops)
- ❌ [Specific out-of-scope item]

**Deferred to Future Releases:**
- [Feature X - planned for Phase 2]
- [Feature Y - nice-to-have, not MVP]

---

### Test Approach by Type

#### Functional Testing
**Objective:** Verify features work as specified in requirements

**Approach:**
- Black box testing based on requirements
- Manual test cases for UI workflows
- Automated tests for APIs
- Data-driven testing for various inputs
- Boundary value analysis
- Equivalence partitioning

**Tools:** [Selenium, Postman, Manual]

---

#### Integration Testing
**Objective:** Verify components work together correctly

**Approach:**
- Top-down integration (UI → API → Database)
- Test API contracts between services
- Test data flow across components
- Test error handling across boundaries

**Tools:** [Postman, SoapUI, JMeter]

---

#### Performance Testing
**Objective:** Validate system meets performance requirements

**Approach:**
- Load testing (expected load)
- Stress testing (beyond capacity)
- Spike testing (sudden load increase)
- Endurance testing (sustained load)

**Targets:**
- Response time: <200ms (95th percentile)
- Throughput: 1000 requests/second
- Concurrent users: 500
- Uptime: 99.9%

**Tools:** [JMeter, LoadRunner, k6]

---

#### Security Testing
**Objective:** Identify vulnerabilities and ensure security controls

**Approach:**
- OWASP Top 10 vulnerability scan
- Penetration testing
- Authentication/authorization testing
- Data encryption verification
- SQL injection testing
- XSS testing

**Tools:** [OWASP ZAP, Burp Suite, Nessus]

---

#### Usability Testing
**Objective:** Ensure user-friendly interface and experience

**Approach:**
- Task-based user testing
- A/B testing of UI variations
- Accessibility testing (WCAG 2.1)
- Cross-browser testing
- Mobile responsiveness testing

**Tools:** [UserTesting.com, BrowserStack, Manual]

---

#### Regression Testing
**Objective:** Ensure new changes don't break existing functionality

**Approach:**
- Automated regression suite runs on every build
- Manual smoke testing after deployments
- Full regression before major releases
- Risk-based prioritization of test cases

**Tools:** [Selenium, TestNG, Jenkins]

---

## 📋 Test Deliverables

### Test Artifacts

| Deliverable | Description | Owner | Due Date | Status |
|-------------|-------------|-------|----------|--------|
| Test Plan | This document | [QA Lead] | [MM/DD] | ✅ Complete |
| Test Cases | Detailed test scenarios | [QA Team] | [MM/DD] | 🟡 In Progress |
| Test Data | Sample data for testing | [QA + BA] | [MM/DD] | 🟡 In Progress |
| Test Scripts | Automated test code | [QA Automation] | [MM/DD] | ⚪ Not Started |
| Test Environment | Configured test environment | [DevOps] | [MM/DD] | 🟢 Ready |
| Test Execution Report | Daily/weekly test results | [QA Lead] | [Daily] | 🟡 Ongoing |
| Defect Report | Bug tracking and metrics | [QA Lead] | [Daily] | 🟡 Ongoing |
| Test Summary Report | Final test outcomes | [QA Lead] | [MM/DD] | ⚪ Not Started |
| UAT Sign-off | Business acceptance | [Business Owner] | [MM/DD] | ⚪ Not Started |

---

## 📝 Test Cases

### Test Case Template

#### TC-001: [Test Case Title]

| Field | Details |
|-------|---------|
| **Test Case ID** | TC-001 |
| **Test Scenario** | [High-level scenario being tested] |
| **Module** | [Feature/Module name] |
| **Priority** | Critical / High / Medium / Low |
| **Test Type** | Functional / Integration / Performance / Security |
| **Created By** | [QA Engineer Name] |
| **Created Date** | [MM/DD/YYYY] |

**Prerequisites:**
- [Prerequisite 1: e.g., User account created]
- [Prerequisite 2: e.g., Test data loaded]
- [Prerequisite 3: e.g., Application running]

**Test Data:**
- Username: [testuser@example.com]
- Password: [TestPass123!]
- [Additional test data]

**Test Steps:**

| Step # | Action | Expected Result |
|--------|--------|-----------------|
| 1 | Navigate to login page | Login page displays correctly |
| 2 | Enter valid username | Username field accepts input |
| 3 | Enter valid password | Password field accepts input (masked) |
| 4 | Click "Login" button | User redirected to dashboard |
| 5 | Verify user name displayed | User's name appears in top-right corner |

**Actual Result:**
[To be filled during execution]

**Status:**
☐ Not Run ☐ Pass ☐ Fail ☐ Blocked ☐ Skipped

**Executed By:** [Name]  
**Execution Date:** [MM/DD/YYYY]  
**Notes/Comments:** [Any observations, screenshots, etc.]

---

### Test Case Summary

| Priority | Total | Not Run | Pass | Fail | Blocked | Pass % |
|----------|-------|---------|------|------|---------|--------|
| Critical | [#] | [#] | [#] | [#] | [#] | [%] |
| High | [#] | [#] | [#] | [#] | [#] | [%] |
| Medium | [#] | [#] | [#] | [#] | [#] | [%] |
| Low | [#] | [#] | [#] | [#] | [#] | [%] |
| **TOTAL** | **[#]** | **[#]** | **[#]** | **[#]** | **[#]** | **[%]** |

**Target:** >95% pass rate, 0 critical/high failures

---

## 🐛 Defect Management

### Defect Lifecycle
```
New → Assigned → In Progress → Fixed → Ready for Retest → Retested → Closed
                                  ↓
                              Reopened (if retest fails)
```

### Defect Severity Definitions

| Severity | Definition | Example | Response Time | Fix Priority |
|----------|------------|---------|---------------|--------------|
| **Critical** | System crash, data loss, security breach | Application won't start | Immediate | Highest |
| **High** | Major feature broken, no workaround | Login doesn't work | 4 hours | High |
| **Medium** | Feature broken, workaround exists | Report export fails, can copy/paste | 1-2 days | Medium |
| **Low** | Minor issue, cosmetic | Button text typo | 1 week | Low |

### Defect Report Template

#### BUG-001: [Defect Title]

| Field | Details |
|-------|---------|
| **Defect ID** | BUG-001 |
| **Summary** | [One-line description] |
| **Severity** | Critical / High / Medium / Low |
| **Priority** | P1 / P2 / P3 / P4 |
| **Status** | New / Assigned / In Progress / Fixed / Closed / Reopened |
| **Reported By** | [QA Engineer] |
| **Reported Date** | [MM/DD/YYYY] |
| **Assigned To** | [Developer] |
| **Test Case** | [TC-XXX that found this bug] |
| **Environment** | Dev / QA / Staging / Production |
| **Browser/Device** | [Chrome 120 / iPhone 14 / etc.] |

**Description:**
[Detailed explanation of the defect]

**Steps to Reproduce:**
1. [Step 1]
2. [Step 2]
3. [Step 3]

**Expected Result:**
[What should happen]

**Actual Result:**
[What actually happens]

**Attachments:**
- Screenshot: [link]
- Error logs: [link]
- Video recording: [link]

**Root Cause:** [To be filled by developer]  
**Fix Description:** [To be filled by developer]  
**Fixed In Build:** [Build number]

**Retest Results:**
- Retested By: [QA Engineer]
- Retest Date: [MM/DD/YYYY]
- Result: ☐ Pass ☐ Fail (Reopen)

---

### Defect Metrics

| Metric | Target | Current | Status |
|--------|--------|---------|--------|
| **Total Defects** | - | [#] | - |
| **Critical Defects** | 0 | [#] | 🟢🟡🔴 |
| **High Defects** | <5 | [#] | 🟢🟡🔴 |
| **Defect Detection Rate** | >90% in QA | [%] | 🟢🟡🔴 |
| **Defect Resolution Time (Avg)** | <3 days | [X days] | 🟢🟡🔴 |
| **Defect Reopen Rate** | <10% | [%] | 🟢🟡🔴 |
| **Defects Per Test Case** | <0.3 | [X] | 🟢🟡🔴 |

---

## 👥 Test Team & Responsibilities

### Test Team Structure

| Role | Name | Responsibilities | Allocation |
|------|------|------------------|------------|
| **QA Lead** | [Name] | Test strategy, planning, reporting, team coordination | 100% |
| **QA Engineer 1** | [Name] | Manual testing, test case creation, defect tracking | 100% |
| **QA Engineer 2** | [Name] | Manual testing, UAT coordination | 100% |
| **QA Automation Engineer** | [Name] | Test automation, CI/CD integration | 75% |
| **Performance Tester** | [Name] | Load/performance testing | 50% |
| **Security Tester** | [Name] | Security testing, penetration testing | 25% |

### RACI Matrix

| Activity | QA Lead | QA Eng | Auto Eng | Perf Test | Dev Lead | PM |
|----------|---------|--------|----------|-----------|----------|-----|
| Test Plan | A/R | C | C | C | C | C |
| Test Cases | A | R | R | R | C | I |
| Test Execution | A | R | R | R | I | I |
| Defect Logging | A | R | R | R | I | I |
| Defect Triage | C | C | C | C | A/R | C |
| Test Reporting | A/R | C | C | C | I | I |
| UAT Coordination | C | R | I | I | I | A |

**Legend:** R = Responsible, A = Accountable, C = Consulted, I = Informed

---

## 🛠️ Test Environment

### Environment Configuration

| Environment | Purpose | URL | Owner | Status |
|-------------|---------|-----|-------|--------|
| **Development** | Development testing | [dev-url] | [DevOps] | 🟢 Available |
| **QA/Test** | Primary test environment | [qa-url] | [QA Lead] | 🟢 Available |
| **Staging** | Pre-production testing | [staging-url] | [DevOps] | 🟢 Available |
| **Production** | Smoke testing only | [prod-url] | [DevOps] | 🔐 Restricted |

### Environment Requirements

**Hardware:**
- Server: [Specs - CPU, RAM, Storage]
- Database: [Specs]
- Load balancer: [If applicable]

**Software:**
- OS: [Ubuntu 24.04 LTS]
- Web Server: [Nginx 1.24]
- Application Server: [Node.js 20]
- Database: [PostgreSQL 16]
- Cache: [Redis 7]

**Test Data:**
- User accounts: [X users with various roles]
- Sample data: [Y records in database]
- Test files: [Document uploads, images, etc.]

**Access:**
- VPN required: Yes / No
- Credentials: [Stored in password manager]
- Permissions: [Who has access]

---

## 📅 Test Schedule

### Test Timeline

| Phase | Start Date | End Date | Duration | Owner | Status |
|-------|-----------|----------|----------|-------|--------|
| Test Planning | [MM/DD] | [MM/DD] | 1 week | [QA Lead] | 🟢 Complete |
| Test Case Design | [MM/DD] | [MM/DD] | 2 weeks | [QA Team] | 🟡 In Progress |
| Test Environment Setup | [MM/DD] | [MM/DD] | 1 week | [DevOps] | 🟢 Complete |
| Test Execution - Functional | [MM/DD] | [MM/DD] | 3 weeks | [QA Team] | ⚪ Not Started |
| Test Execution - Integration | [MM/DD] | [MM/DD] | 1 week | [QA Team] | ⚪ Not Started |
| Performance Testing | [MM/DD] | [MM/DD] | 1 week | [Perf Tester] | ⚪ Not Started |
| Security Testing | [MM/DD] | [MM/DD] | 1 week | [Security] | ⚪ Not Started |
| Defect Fixes & Retesting | [MM/DD] | [MM/DD] | 2 weeks | [Dev/QA] | ⚪ Not Started |
| Regression Testing | [MM/DD] | [MM/DD] | 1 week | [QA Team] | ⚪ Not Started |
| UAT | [MM/DD] | [MM/DD] | 2 weeks | [Business] | ⚪ Not Started |
| Final Sign-off | [MM/DD] | [MM/DD] | 3 days | [Stakeholders] | ⚪ Not Started |

**Total Duration:** [X weeks]

---

### Daily Testing Activities

**Morning (9:00 AM - 12:00 PM):**
- Review overnight build results
- Triage new defects
- Assign test cases for the day
- Execute high-priority test cases

**Afternoon (1:00 PM - 5:00 PM):**
- Continue test execution
- Log defects
- Retest fixed defects
- Update test status

**End of Day:**
- Update test execution report
- Communicate blockers
- Plan next day's testing

---

## 📊 Test Metrics & Reporting

### Key Metrics Tracked

**Test Coverage:**
- Requirements coverage: [X% of requirements have test cases]
- Code coverage: [Y% of code covered by automated tests]

**Test Progress:**
- Test cases executed: [X of Y] ([%])
- Test cases passed: [X of Y] ([%])
- Test cases failed: [X of Y] ([%])

**Defect Metrics:**
- Total defects: [#]
- Critical/High defects: [#]
- Defects per day: [#]
- Defect density: [# per KLOC]
- Average time to fix: [X days]

**Test Efficiency:**
- Test case execution rate: [# per day]
- Defect detection effectiveness: [% found in QA vs production]
- Test automation ROI: [Hours saved]

---

### Daily Test Status Report

**Date:** [MM/DD/YYYY]  
**Overall Status:** 🟢 On Track / 🟡 At Risk / 🔴 Off Track

**Today's Execution:**
- Test cases executed: [#]
- Test cases passed: [#]
- Test cases failed: [#]
- Blockers: [#]

**Defects:**
- New defects: [#]
- Defects fixed: [#]
- Defects retested: [#]
- Open critical/high: [#]

**Key Accomplishments:**
- [Accomplishment 1]
- [Accomplishment 2]

**Issues/Blockers:**
- [Issue 1]
- [Issue 2]

**Next Day Plan:**
- [Priority 1]
- [Priority 2]

---

### Weekly Test Summary Report

**Week Of:** [MM/DD/YYYY]  
**Overall Status:** 🟢 On Track / 🟡 At Risk / 🔴 Off Track

**Test Progress:**
- Planned: [X test cases]
- Executed: [Y test cases] ([%])
- Passed: [Z test cases] ([%])

**Defect Summary:**
| Severity | Opened | Fixed | Retested | Closed | Open |
|----------|--------|-------|----------|--------|------|
| Critical | [#] | [#] | [#] | [#] | [#] |
| High | [#] | [#] | [#] | [#] | [#] |
| Medium | [#] | [#] | [#] | [#] | [#] |
| Low | [#] | [#] | [#] | [#] | [#] |

**Key Highlights:**
- [Highlight 1]
- [Highlight 2]

**Risks/Issues:**
- [Risk/Issue 1 and mitigation]

**Next Week Plan:**
- [Priority 1]
- [Priority 2]

---

## ⚠️ Risks & Mitigation

### Test Risks

| Risk | Probability | Impact | Mitigation | Owner |
|------|-------------|--------|------------|-------|
| Test environment instability | Medium | High | Daily smoke tests, quick DevOps response | [DevOps Lead] |
| Insufficient test data | Medium | Medium | Early test data preparation, generate synthetic data | [BA + QA] |
| Key QA resource unavailable | Low | High | Cross-train team, document critical knowledge | [QA Lead] |
| Late requirement changes | High | High | Change control process, impact analysis | [PM] |
| Integration delays | Medium | High | Early integration testing, parallel development | [Dev Lead] |
| Performance issues discovered late | Medium | High | Early performance testing, continuous monitoring | [Perf Tester] |

---

## ✅ Entry & Exit Criteria

### Entry Criteria (Before Testing Starts)

**Must Have:**
- [ ] Requirements finalized and approved
- [ ] Test plan approved
- [ ] Test cases reviewed and approved
- [ ] Test environment available and stable
- [ ] Test data prepared
- [ ] Build deployed to test environment
- [ ] Unit tests passing
- [ ] Code freeze (for final testing phase)

**Cannot Start Testing Without:** All critical entry criteria met

---

### Exit Criteria (Testing Complete)

**Must Have:**
- [ ] All test cases executed
- [ ] >95% test cases passed
- [ ] All critical defects resolved
- [ ] All high defects resolved or accepted
- [ ] Regression testing passed
- [ ] Performance benchmarks met
- [ ] Security vulnerabilities addressed
- [ ] UAT sign-off obtained
- [ ] Test summary report completed
- [ ] Known issues documented

**Cannot Release Without:** All critical exit criteria met

---

## 🎓 Test Tools & Infrastructure

### Testing Tools

| Tool | Purpose | Version | License | Owner |
|------|---------|---------|---------|-------|
| Selenium | UI automation | 4.x | Open Source | [QA Auto Eng] |
| Postman | API testing | Latest | Free/Paid | [QA Team] |
| JMeter | Performance testing | 5.x | Open Source | [Perf Tester] |
| OWASP ZAP | Security testing | Latest | Open Source | [Security] |
| TestNG | Test framework | Latest | Open Source | [QA Auto Eng] |
| Jenkins | CI/CD | Latest | Open Source | [DevOps] |
| Jira | Defect tracking | Cloud | Paid | [QA Lead] |

### Test Automation

**Automation Strategy:**
- Automate all regression test cases
- Automate all API test cases
- Automate smoke tests
- Manual testing for exploratory and new features

**Automation Goals:**
- Automation coverage: >80% of test cases
- Execution time: <30 minutes for full suite
- Maintenance: <10% of test development time

**CI/CD Integration:**
- Automated tests run on every commit
- Full regression on nightly builds
- Performance tests weekly
- Security scans weekly

---

## 📎 Related Templates

- [Quality Checklist](./quality-checklist-template.md) - Quality gates
- [Issues Log](./issues-log-template.md) - Track defects
- [Requirements Document](./project-charter-template.md) - What to test
- [Risk Register](./risk-register-template.md) - Test risks

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
