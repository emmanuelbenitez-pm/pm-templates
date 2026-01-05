# Quality Checklist Template

## 📋 Document Information

| Field | Details |
|-------|---------|
| **Project Name** | [Enter project name] |
| **Project Manager** | [Name] |
| **Quality Manager** | [Name] |
| **Date Created** | [MM/DD/YYYY] |
| **Last Updated** | [MM/DD/YYYY] |
| **Version** | [1.0] |

---

## 🎯 What is a Quality Checklist?

A Quality Checklist is a structured tool to verify that deliverables meet predefined quality standards and acceptance criteria before proceeding to the next phase or releasing to stakeholders.

### Purpose

**Benefits:**
- ✅ **Consistent Quality** - Same standards applied every time
- ✅ **Early Detection** - Catch issues before they become expensive
- ✅ **Clear Expectations** - Everyone knows what "done" means
- ✅ **Audit Trail** - Document quality verification
- ✅ **Accountability** - Clear ownership of quality checks
- ✅ **Risk Mitigation** - Prevent defects from progressing

**Without Quality Checklists:**
- ❌ Inconsistent quality standards
- ❌ Defects discovered late (expensive to fix)
- ❌ Rework and delays
- ❌ Stakeholder dissatisfaction
- ❌ Technical debt accumulation

---

## 📊 Quality Framework

### Quality Hierarchy
```
Quality Policy (Organization Level)
        ↓
Quality Standards (Project Level)
        ↓
Quality Criteria (Phase/Deliverable Level)
        ↓
Quality Checklist Items (Specific Checks)
        ↓
Quality Metrics (Measurement)
```

### Quality Dimensions

| Dimension | Definition | Example Criteria |
|-----------|------------|------------------|
| **Functionality** | Does it work as intended? | All features operational, requirements met |
| **Reliability** | Does it work consistently? | 99.9% uptime, error rate <0.1% |
| **Usability** | Is it easy to use? | Users complete tasks in <X time, satisfaction >4/5 |
| **Performance** | Is it fast enough? | Response time <200ms, handles 1000 concurrent users |
| **Security** | Is it secure? | OWASP Top 10 addressed, penetration test passed |
| **Maintainability** | Can it be maintained? | Code coverage >80%, documentation complete |
| **Portability** | Does it work everywhere? | Cross-browser compatible, mobile responsive |

---

## ✅ Master Quality Checklist

### Project Initiation Phase

#### Project Charter Quality Checklist

| # | Quality Criteria | Pass/Fail | Verified By | Date | Notes |
|---|------------------|-----------|-------------|------|-------|
| 1 | Business case clearly articulated | ☐ Pass ☐ Fail | [Name] | [MM/DD] | |
| 2 | Project objectives SMART (Specific, Measurable, Achievable, Relevant, Time-bound) | ☐ Pass ☐ Fail | [Name] | [MM/DD] | |
| 3 | Scope boundaries defined (in-scope and out-of-scope) | ☐ Pass ☐ Fail | [Name] | [MM/DD] | |
| 4 | Key stakeholders identified | ☐ Pass ☐ Fail | [Name] | [MM/DD] | |
| 5 | Success criteria defined and measurable | ☐ Pass ☐ Fail | [Name] | [MM/DD] | |
| 6 | Budget estimate provided with justification | ☐ Pass ☐ Fail | [Name] | [MM/DD] | |
| 7 | High-level timeline with major milestones | ☐ Pass ☐ Fail | [Name] | [MM/DD] | |
| 8 | Risks identified and mitigation strategies outlined | ☐ Pass ☐ Fail | [Name] | [MM/DD] | |
| 9 | Assumptions and constraints documented | ☐ Pass ☐ Fail | [Name] | [MM/DD] | |
| 10 | Executive sponsor sign-off obtained | ☐ Pass ☐ Fail | [Name] | [MM/DD] | |

**Acceptance Criteria:** All items must PASS to proceed to Planning phase.

**Approver:** [Executive Sponsor Name]  
**Approval Date:** [MM/DD/YYYY]  
**Status:** ☐ Approved ☐ Rejected ☐ Conditional

---

### Planning Phase

#### Requirements Quality Checklist

| # | Quality Criteria | Pass/Fail | Verified By | Date | Notes |
|---|------------------|-----------|-------------|------|-------|
| 1 | All requirements have unique identifier | ☐ Pass ☐ Fail | [BA] | [MM/DD] | |
| 2 | Requirements are clear and unambiguous | ☐ Pass ☐ Fail | [BA] | [MM/DD] | |
| 3 | Requirements are testable/verifiable | ☐ Pass ☐ Fail | [QA] | [MM/DD] | |
| 4 | Requirements are feasible within constraints | ☐ Pass ☐ Fail | [Tech Lead] | [MM/DD] | |
| 5 | Requirements are complete (no TBDs) | ☐ Pass ☐ Fail | [BA] | [MM/DD] | |
| 6 | Requirements are consistent (no conflicts) | ☐ Pass ☐ Fail | [BA] | [MM/DD] | |
| 7 | Requirements are prioritized (MoSCoW or similar) | ☐ Pass ☐ Fail | [PO] | [MM/DD] | |
| 8 | Acceptance criteria defined for each requirement | ☐ Pass ☐ Fail | [BA] | [MM/DD] | |
| 9 | Non-functional requirements documented | ☐ Pass ☐ Fail | [Architect] | [MM/DD] | |
| 10 | Requirements traceability matrix created | ☐ Pass ☐ Fail | [BA] | [MM/DD] | |
| 11 | Stakeholder review completed | ☐ Pass ☐ Fail | [PM] | [MM/DD] | |
| 12 | Stakeholder sign-off obtained | ☐ Pass ☐ Fail | [PM] | [MM/DD] | |

**Acceptance Criteria:** All items must PASS, stakeholder sign-off required.

---

#### Design Quality Checklist

| # | Quality Criteria | Pass/Fail | Verified By | Date | Notes |
|---|------------------|-----------|-------------|------|-------|
| 1 | Architecture addresses all functional requirements | ☐ Pass ☐ Fail | [Architect] | [MM/DD] | |
| 2 | Architecture addresses all non-functional requirements | ☐ Pass ☐ Fail | [Architect] | [MM/DD] | |
| 3 | Design follows company architecture standards | ☐ Pass ☐ Fail | [Architect] | [MM/DD] | |
| 4 | Security considerations documented | ☐ Pass ☐ Fail | [Security] | [MM/DD] | |
| 5 | Scalability approach defined | ☐ Pass ☐ Fail | [Architect] | [MM/DD] | |
| 6 | Data model/schema designed and reviewed | ☐ Pass ☐ Fail | [DBA] | [MM/DD] | |
| 7 | Integration points identified and documented | ☐ Pass ☐ Fail | [Architect] | [MM/DD] | |
| 8 | API contracts/interfaces defined | ☐ Pass ☐ Fail | [Tech Lead] | [MM/DD] | |
| 9 | UI/UX mockups match requirements | ☐ Pass ☐ Fail | [UX Designer] | [MM/DD] | |
| 10 | Design reviewed by technical team | ☐ Pass ☐ Fail | [Tech Lead] | [MM/DD] | |
| 11 | Design reviewed by security team | ☐ Pass ☐ Fail | [Security] | [MM/DD] | |
| 12 | Design sign-off obtained | ☐ Pass ☐ Fail | [Architect] | [MM/DD] | |

**Acceptance Criteria:** All items must PASS, architecture review complete.

---

### Development Phase

#### Code Quality Checklist

| # | Quality Criteria | Pass/Fail | Verified By | Date | Notes |
|---|------------------|-----------|-------------|------|-------|
| 1 | Code follows company coding standards | ☐ Pass ☐ Fail | [Reviewer] | [MM/DD] | |
| 2 | Code is properly commented | ☐ Pass ☐ Fail | [Reviewer] | [MM/DD] | |
| 3 | No hard-coded values (use config/constants) | ☐ Pass ☐ Fail | [Reviewer] | [MM/DD] | |
| 4 | Error handling implemented | ☐ Pass ☐ Fail | [Reviewer] | [MM/DD] | |
| 5 | Logging implemented appropriately | ☐ Pass ☐ Fail | [Reviewer] | [MM/DD] | |
| 6 | Unit tests written (>80% code coverage) | ☐ Pass ☐ Fail | [Developer] | [MM/DD] | |
| 7 | All unit tests passing | ☐ Pass ☐ Fail | [CI/CD] | [MM/DD] | |
| 8 | Static code analysis passed (no critical issues) | ☐ Pass ☐ Fail | [CI/CD] | [MM/DD] | |
| 9 | Security scan passed (no critical vulnerabilities) | ☐ Pass ☐ Fail | [Security] | [MM/DD] | |
| 10 | Code review completed by peer | ☐ Pass ☐ Fail | [Reviewer] | [MM/DD] | |
| 11 | Code review comments addressed | ☐ Pass ☐ Fail | [Developer] | [MM/DD] | |
| 12 | Pull request approved by tech lead | ☐ Pass ☐ Fail | [Tech Lead] | [MM/DD] | |
| 13 | No code smells or technical debt introduced | ☐ Pass ☐ Fail | [Reviewer] | [MM/DD] | |
| 14 | Performance considerations addressed | ☐ Pass ☐ Fail | [Reviewer] | [MM/DD] | |

**Acceptance Criteria:** All items must PASS before merge to main branch.

---

#### Definition of Done (Sprint/Story)

| # | Quality Criteria | Pass/Fail | Verified By | Date | Notes |
|---|------------------|-----------|-------------|------|-------|
| 1 | Code complete and checked into repository | ☐ Pass ☐ Fail | [Developer] | [MM/DD] | |
| 2 | Unit tests written and passing | ☐ Pass ☐ Fail | [Developer] | [MM/DD] | |
| 3 | Code review completed and approved | ☐ Pass ☐ Fail | [Reviewer] | [MM/DD] | |
| 4 | Integration tests passing | ☐ Pass ☐ Fail | [QA] | [MM/DD] | |
| 5 | Functional testing passed in dev environment | ☐ Pass ☐ Fail | [QA] | [MM/DD] | |
| 6 | Acceptance criteria met | ☐ Pass ☐ Fail | [PO] | [MM/DD] | |
| 7 | No critical or high severity bugs | ☐ Pass ☐ Fail | [QA] | [MM/DD] | |
| 8 | Documentation updated (code comments, README, API docs) | ☐ Pass ☐ Fail | [Developer] | [MM/DD] | |
| 9 | Deployed to test environment | ☐ Pass ☐ Fail | [DevOps] | [MM/DD] | |
| 10 | Product Owner acceptance obtained | ☐ Pass ☐ Fail | [PO] | [MM/DD] | |

**Acceptance Criteria:** All items must PASS to mark story as DONE.

---

### Testing Phase

#### Test Readiness Checklist

| # | Quality Criteria | Pass/Fail | Verified By | Date | Notes |
|---|------------------|-----------|-------------|------|-------|
| 1 | Test environment available and stable | ☐ Pass ☐ Fail | [DevOps] | [MM/DD] | |
| 2 | Test data prepared | ☐ Pass ☐ Fail | [QA] | [MM/DD] | |
| 3 | Test cases written and reviewed | ☐ Pass ☐ Fail | [QA Lead] | [MM/DD] | |
| 4 | Test cases mapped to requirements | ☐ Pass ☐ Fail | [QA] | [MM/DD] | |
| 5 | Testing tools/automation ready | ☐ Pass ☐ Fail | [QA] | [MM/DD] | |
| 6 | Test team trained on application | ☐ Pass ☐ Fail | [QA Lead] | [MM/DD] | |
| 7 | Defect tracking system configured | ☐ Pass ☐ Fail | [QA Lead] | [MM/DD] | |
| 8 | Entry criteria met (code complete, unit tests pass) | ☐ Pass ☐ Fail | [Tech Lead] | [MM/DD] | |

**Acceptance Criteria:** All items must PASS to begin formal testing phase.

---

#### Test Execution Quality Checklist

| # | Quality Criteria | Pass/Fail | Verified By | Date | Notes |
|---|------------------|-----------|-------------|------|-------|
| 1 | All test cases executed | ☐ Pass ☐ Fail | [QA] | [MM/DD] | |
| 2 | Test execution results documented | ☐ Pass ☐ Fail | [QA] | [MM/DD] | |
| 3 | All critical defects resolved | ☐ Pass ☐ Fail | [Dev/QA] | [MM/DD] | |
| 4 | All high defects resolved or accepted | ☐ Pass ☐ Fail | [Dev/QA] | [MM/DD] | |
| 5 | Regression testing completed | ☐ Pass ☐ Fail | [QA] | [MM/DD] | |
| 6 | Performance testing completed and passed | ☐ Pass ☐ Fail | [QA] | [MM/DD] | |
| 7 | Security testing completed and passed | ☐ Pass ☐ Fail | [Security] | [MM/DD] | |
| 8 | Cross-browser/device testing completed | ☐ Pass ☐ Fail | [QA] | [MM/DD] | |
| 9 | Test coverage >95% of requirements | ☐ Pass ☐ Fail | [QA Lead] | [MM/DD] | |
| 10 | Test summary report created | ☐ Pass ☐ Fail | [QA Lead] | [MM/DD] | |

**Acceptance Criteria:** All items must PASS to proceed to UAT.

---

#### UAT Sign-off Checklist

| # | Quality Criteria | Pass/Fail | Verified By | Date | Notes |
|---|------------------|-----------|-------------|------|-------|
| 1 | UAT test cases executed by business users | ☐ Pass ☐ Fail | [Business] | [MM/DD] | |
| 2 | All critical scenarios tested | ☐ Pass ☐ Fail | [Business] | [MM/DD] | |
| 3 | Business acceptance criteria met | ☐ Pass ☐ Fail | [Business] | [MM/DD] | |
| 4 | All UAT defects resolved or accepted | ☐ Pass ☐ Fail | [PM] | [MM/DD] | |
| 5 | User documentation reviewed and approved | ☐ Pass ☐ Fail | [Business] | [MM/DD] | |
| 6 | Training materials reviewed and approved | ☐ Pass ☐ Fail | [Business] | [MM/DD] | |
| 7 | Known issues documented and communicated | ☐ Pass ☐ Fail | [PM] | [MM/DD] | |
| 8 | Formal UAT sign-off obtained | ☐ Pass ☐ Fail | [Business Owner] | [MM/DD] | |

**Acceptance Criteria:** All items must PASS, formal sign-off required.

---

### Deployment Phase

#### Pre-Deployment Checklist

| # | Quality Criteria | Pass/Fail | Verified By | Date | Notes |
|---|------------------|-----------|-------------|------|-------|
| 1 | Production environment ready | ☐ Pass ☐ Fail | [DevOps] | [MM/DD] | |
| 2 | Database migration scripts tested | ☐ Pass ☐ Fail | [DBA] | [MM/DD] | |
| 3 | Rollback plan documented and tested | ☐ Pass ☐ Fail | [DevOps] | [MM/DD] | |
| 4 | Backup of current production taken | ☐ Pass ☐ Fail | [DevOps] | [MM/DD] | |
| 5 | Deployment runbook finalized | ☐ Pass ☐ Fail | [DevOps] | [MM/DD] | |
| 6 | All dependencies identified and available | ☐ Pass ☐ Fail | [DevOps] | [MM/DD] | |
| 7 | Monitoring and alerting configured | ☐ Pass ☐ Fail | [DevOps] | [MM/DD] | |
| 8 | Security certificates valid | ☐ Pass ☐ Fail | [Security] | [MM/DD] | |
| 9 | Change Advisory Board approval obtained | ☐ Pass ☐ Fail | [PM] | [MM/DD] | |
| 10 | Communication plan executed (stakeholders notified) | ☐ Pass ☐ Fail | [PM] | [MM/DD] | |
| 11 | Support team trained and ready | ☐ Pass ☐ Fail | [Support Mgr] | [MM/DD] | |
| 12 | Go/No-Go meeting held and go decision made | ☐ Pass ☐ Fail | [Sponsor] | [MM/DD] | |

**Acceptance Criteria:** All items must PASS to proceed with deployment.

---

#### Post-Deployment Checklist

| # | Quality Criteria | Pass/Fail | Verified By | Date | Notes |
|---|------------------|-----------|-------------|------|-------|
| 1 | Deployment completed successfully | ☐ Pass ☐ Fail | [DevOps] | [MM/DD] | |
| 2 | Smoke testing passed | ☐ Pass ☐ Fail | [QA] | [MM/DD] | |
| 3 | Application responding correctly | ☐ Pass ☐ Fail | [DevOps] | [MM/DD] | |
| 4 | Database migration successful | ☐ Pass ☐ Fail | [DBA] | [MM/DD] | |
| 5 | No critical errors in logs | ☐ Pass ☐ Fail | [DevOps] | [MM/DD] | |
| 6 | Monitoring showing healthy status | ☐ Pass ☐ Fail | [DevOps] | [MM/DD] | |
| 7 | Performance metrics within acceptable range | ☐ Pass ☐ Fail | [DevOps] | [MM/DD] | |
| 8 | User access verified | ☐ Pass ☐ Fail | [QA] | [MM/DD] | |
| 9 | Support team notified of go-live | ☐ Pass ☐ Fail | [PM] | [MM/DD] | |
| 10 | Users notified of go-live | ☐ Pass ☐ Fail | [PM] | [MM/DD] | |
| 11 | First 24 hours monitoring - no critical issues | ☐ Pass ☐ Fail | [DevOps] | [MM/DD] | |
| 12 | Deployment retrospective scheduled | ☐ Pass ☐ Fail | [PM] | [MM/DD] | |

**Acceptance Criteria:** All items must PASS to declare successful deployment.

---

### Project Closure Phase

#### Project Closure Checklist

| # | Quality Criteria | Pass/Fail | Verified By | Date | Notes |
|---|------------------|-----------|-------------|------|-------|
| 1 | All deliverables accepted by stakeholders | ☐ Pass ☐ Fail | [PM] | [MM/DD] | |
| 2 | All project objectives met | ☐ Pass ☐ Fail | [Sponsor] | [MM/DD] | |
| 3 | Final budget reconciliation completed | ☐ Pass ☐ Fail | [Finance] | [MM/DD] | |
| 4 | All vendor contracts closed | ☐ Pass ☐ Fail | [Procurement] | [MM/DD] | |
| 5 | Final project report completed | ☐ Pass ☐ Fail | [PM] | [MM/DD] | |
| 6 | Lessons learned session held | ☐ Pass ☐ Fail | [PM] | [MM/DD] | |
| 7 | Lessons learned documented | ☐ Pass ☐ Fail | [PM] | [MM/DD] | |
| 8 | Project documentation archived | ☐ Pass ☐ Fail | [PM] | [MM/DD] | |
| 9 | Knowledge transfer to operations completed | ☐ Pass ☐ Fail | [Tech Lead] | [MM/DD] | |
| 10 | Support model transitioned | ☐ Pass ☐ Fail | [Support Mgr] | [MM/DD] | |
| 11 | Team members released to other projects | ☐ Pass ☐ Fail | [PM] | [MM/DD] | |
| 12 | Final stakeholder communication sent | ☐ Pass ☐ Fail | [PM] | [MM/DD] | |
| 13 | Project celebration held | ☐ Pass ☐ Fail | [PM] | [MM/DD] | |
| 14 | Formal project closure approval obtained | ☐ Pass ☐ Fail | [Sponsor] | [MM/DD] | |

**Acceptance Criteria:** All items must PASS to formally close project.

---

## 📊 Quality Metrics

### Key Quality Indicators

| Metric | Target | Current | Status | Trend |
|--------|--------|---------|--------|-------|
| **Defect Density** | <5 defects per 1000 LOC | [X] | 🟢🟡🔴 | ↗️→↘️ |
| **Code Coverage** | >80% | [X%] | 🟢🟡🔴 | ↗️→↘️ |
| **Test Pass Rate** | >95% | [X%] | 🟢🟡🔴 | ↗️→↘️ |
| **Defect Detection Rate** | >90% in QA (not production) | [X%] | 🟢🟡🔴 | ↗️→↘️ |
| **Mean Time to Resolution** | <4 hours critical, <2 days high | [X hrs] | 🟢🟡🔴 | ↗️→↘️ |
| **Customer Satisfaction** | >4.0/5 | [X.X] | 🟢🟡🔴 | ↗️→↘️ |
| **Requirements Stability** | <10% change after baseline | [X%] | 🟢🟡🔴 | ↗️→↘️ |
| **Code Review Coverage** | 100% | [X%] | 🟢🟡🔴 | ↗️→↘️ |

**Legend:**
- 🟢 Green: Meeting or exceeding target
- 🟡 Yellow: Within 10% of target
- 🔴 Red: More than 10% below target

---

### Defect Tracking

| Severity | Open | In Progress | Resolved | Closed | Total |
|----------|------|-------------|----------|--------|-------|
| Critical | [#] | [#] | [#] | [#] | [#] |
| High | [#] | [#] | [#] | [#] | [#] |
| Medium | [#] | [#] | [#] | [#] | [#] |
| Low | [#] | [#] | [#] | [#] | [#] |
| **TOTAL** | **[#]** | **[#]** | **[#]** | **[#]** | **[#]** |

**Defect Aging:**
- 0-3 days: [#] defects
- 4-7 days: [#] defects
- 8-14 days: [#] defects
- 15+ days: [#] defects 🚩

---

## 💡 Best Practices

### Creating Effective Checklists

**Do's ✅:**
1. **Be Specific** - "Code coverage >80%" not "Good code coverage"
2. **Make it Binary** - Clear pass/fail, no ambiguity
3. **Assign Ownership** - Who verifies each item
4. **Set Deadlines** - When must it be complete
5. **Automate When Possible** - CI/CD, static analysis
6. **Review Regularly** - Update checklist based on lessons learned
7. **Keep it Manageable** - 10-20 items per phase, not 100
8. **Document Exceptions** - If something can't pass, document why

**Don'ts ❌:**
1. **Don't Be Vague** - "High quality" is not measurable
2. **Don't Overdo It** - Too many items = checklist fatigue
3. **Don't Skip Documentation** - If it's not written, it didn't happen
4. **Don't Allow Shortcuts** - Enforce the checklist rigorously
5. **Don't Forget to Update** - Stale checklists are worse than none
6. **Don't Blame** - Focus on process improvement, not finger-pointing

---

### Quality Gate Process

**Phase Gate Decision:**

**GREEN LIGHT (Proceed):**
- ✅ All critical items PASS
- ✅ All high items PASS or have approved exceptions
- ✅ Formal approval obtained

**YELLOW LIGHT (Conditional Proceed):**
- ⚠️ Some non-critical items FAIL
- ⚠️ Mitigation plan in place
- ⚠️ Conditional approval with remediation deadline

**RED LIGHT (Do Not Proceed):**
- 🔴 Critical items FAIL
- 🔴 No mitigation plan
- 🔴 Risk too high to proceed

---

## 📋 Checklist Templates by Project Type

### Agile/Scrum Project

**Sprint Quality Checklist:**
- [ ] Sprint goal met
- [ ] All committed stories complete
- [ ] Definition of Done met for all stories
- [ ] Sprint demo completed
- [ ] Sprint retrospective held
- [ ] Velocity calculated and tracked
- [ ] Next sprint planned

---

### Waterfall Project

**Phase Gate Checklist:**
- [ ] Phase deliverables complete
- [ ] Phase acceptance criteria met
- [ ] Quality review conducted
- [ ] Stakeholder sign-off obtained
- [ ] Risks/issues resolved
- [ ] Budget within tolerance
- [ ] Next phase ready to begin

---

### Product Launch

**Launch Readiness Checklist:**
- [ ] Product testing complete
- [ ] Marketing materials ready
- [ ] Sales team trained
- [ ] Support documentation complete
- [ ] Pricing finalized
- [ ] Legal/compliance approval
- [ ] Go/No-Go decision made

---

## 📎 Related Templates

- [Project Charter](./project-charter-template.md) - Define quality standards
- [Risk Register](./risk-register-template.md) - Quality risks
- [Issues Log](./issues-log-template.md) - Quality issues
- [Lessons Learned](./lessons-learned-template.md) - Quality improvements

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
