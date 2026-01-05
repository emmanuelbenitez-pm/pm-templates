# Go-Live Checklist Template

## 📋 Document Information

| Field | Details |
|-------|---------|
| **Project Name** | [Enter project name] |
| **Go-Live Date** | [MM/DD/YYYY] |
| **Go-Live Time** | [HH:MM AM/PM Timezone] |
| **Project Manager** | [Name] |
| **Technical Lead** | [Name] |
| **Business Owner** | [Name] |
| **Date Created** | [MM/DD/YYYY] |
| **Last Updated** | [MM/DD/YYYY] |
| **Version** | [1.0] |

---

## 🎯 Go-Live Overview

### Go-Live Plan Summary

**What We're Launching:**
[Brief description of what's being deployed]

**Example:**
> New cloud-based CRM system replacing legacy custom system. Includes customer management, opportunity tracking, reporting, and mobile access for 500 users across 5 locations.

---

### Go-Live Details

| Item | Details |
|------|---------|
| **Go-Live Date** | [MM/DD/YYYY] |
| **Go-Live Time** | [HH:MM AM/PM Timezone] |
| **Deployment Window** | [X hours] |
| **Deployment Type** | Big Bang / Phased Rollout / Blue-Green / Canary |
| **Rollback Time Limit** | [X hours] |
| **Business Impact** | High / Medium / Low |
| **Risk Level** | High / Medium / Low |
| **User Impact** | [X users affected] |
| **Backup Plan** | Yes / No |

---

### Go-Live Team

| Role | Name | Phone | Email | Responsibility |
|------|------|-------|-------|----------------|
| **Go-Live Manager** | [Name] | [Phone] | [Email] | Overall coordination |
| **Technical Lead** | [Name] | [Phone] | [Email] | Technical execution |
| **Business Owner** | [Name] | [Phone] | [Email] | Business decisions |
| **DevOps Lead** | [Name] | [Phone] | [Email] | Infrastructure/deployment |
| **QA Lead** | [Name] | [Phone] | [Email] | Smoke testing |
| **Support Lead** | [Name] | [Phone] | [Email] | User support |
| **Communication Lead** | [Name] | [Phone] | [Email] | Stakeholder comms |

**War Room:**
- Location: [Conference Room / Virtual - Zoom link]
- Hours: [Start time - End time]
- Communication: [Primary channel - Slack #golive]

---

## ✅ PRE-GO-LIVE CHECKLIST

### 4 Weeks Before Go-Live

#### Requirements & Testing

- [ ] **All acceptance criteria met**
  - Owner: [QA Lead]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Evidence: UAT sign-off document dated [MM/DD]

- [ ] **All critical defects resolved**
  - Owner: [Dev Lead]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Evidence: 0 critical/high defects in tracking system

- [ ] **Performance testing passed**
  - Owner: [QA Lead]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Criteria: Response time <2 sec, 500 concurrent users
  - Evidence: Load test report dated [MM/DD]

- [ ] **Security testing passed**
  - Owner: [Security Team]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Criteria: Zero critical vulnerabilities
  - Evidence: Security audit report dated [MM/DD]

- [ ] **Integration testing passed**
  - Owner: [Integration Lead]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Evidence: All 5 integrations tested end-to-end

- [ ] **Regression testing passed**
  - Owner: [QA Lead]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Criteria: >95% test cases passed
  - Evidence: Test execution report dated [MM/DD]

---

#### Infrastructure & Environment

- [ ] **Production environment provisioned**
  - Owner: [DevOps]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Details: [Server specs, database, load balancer]

- [ ] **Production environment configured**
  - Owner: [DevOps]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Details: Security, networking, monitoring

- [ ] **Database production-ready**
  - Owner: [DBA]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Details: Schema, indexes, permissions, backup

- [ ] **SSL certificates installed**
  - Owner: [DevOps]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Expiry: [MM/DD/YYYY]

- [ ] **DNS configured**
  - Owner: [Network Team]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - URL: [production-url.com]

- [ ] **Load balancer configured**
  - Owner: [DevOps]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Details: Health checks, SSL termination

- [ ] **Monitoring configured**
  - Owner: [DevOps]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Tools: [New Relic, Datadog, etc.]
  - Alerts: Configured for critical metrics

- [ ] **Backup/recovery tested**
  - Owner: [DBA]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - RTO: [X hours], RPO: [X hours]
  - Test date: [MM/DD]

---

### 2 Weeks Before Go-Live

#### Data Migration

- [ ] **Data migration plan approved**
  - Owner: [Data Team]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Reviewed by: [Business Owner, DBA]

- [ ] **Data cleansing completed**
  - Owner: [BA]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Quality: >95% records clean

- [ ] **Data migration tested (dev)**
  - Owner: [Data Team]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Date: [MM/DD]

- [ ] **Data migration tested (staging)**
  - Owner: [Data Team]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Date: [MM/DD]
  - Duration: [X hours]

- [ ] **Data migration rehearsal (pre-prod)**
  - Owner: [Data Team]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Date: [MM/DD]
  - Success rate: [X%]

- [ ] **Data validation scripts prepared**
  - Owner: [QA]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Scripts: [Record count, data integrity, relationships]

---

#### Training & Documentation

- [ ] **User training completed**
  - Owner: [Training Manager]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Completion: [X% of users trained]

- [ ] **Super users certified**
  - Owner: [Training Manager]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Count: [X super users ready]

- [ ] **Help desk trained**
  - Owner: [Training Manager]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Training date: [MM/DD]

- [ ] **User documentation published**
  - Owner: [BA]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Location: [Internal portal URL]

- [ ] **Quick reference guides distributed**
  - Owner: [Training Manager]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Format: PDF + laminated cards

- [ ] **Video tutorials available**
  - Owner: [Training Manager]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Count: [X videos]

- [ ] **Technical documentation complete**
  - Owner: [Tech Lead]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Includes: Architecture, runbooks, troubleshooting

---

### 1 Week Before Go-Live

#### Final Approvals

- [ ] **Business owner sign-off**
  - Owner: [Business Owner]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Signed document: [Link to document]
  - Date: [MM/DD]

- [ ] **Technical lead sign-off**
  - Owner: [Tech Lead]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Signed document: [Link]

- [ ] **Security sign-off**
  - Owner: [Security Team]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Signed document: [Link]

- [ ] **Change approval obtained**
  - Owner: [PM]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - CAB approval: [MM/DD]
  - Change ticket: [CHG-XXXXX]

- [ ] **Executive sponsor approval**
  - Owner: [Sponsor]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Date: [MM/DD]

---

#### Communication

- [ ] **Stakeholder notification sent**
  - Owner: [PM]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Sent: [MM/DD]
  - Recipients: [Executive team, managers]

- [ ] **End user notification sent**
  - Owner: [Communication Lead]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Sent: [MM/DD]
  - Recipients: [All 500 users]

- [ ] **Downtime/maintenance window communicated**
  - Owner: [Communication Lead]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Window: [MM/DD HH:MM - HH:MM]

- [ ] **Support contacts published**
  - Owner: [Support Lead]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Location: [Help desk portal, email, poster]

---

#### Deployment Preparation

- [ ] **Deployment runbook finalized**
  - Owner: [DevOps]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Location: [Confluence/Wiki link]
  - Steps: [X steps documented]

- [ ] **Deployment scripts tested**
  - Owner: [DevOps]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Test date: [MM/DD]
  - Environment: Staging

- [ ] **Rollback plan documented**
  - Owner: [DevOps]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Time estimate: [X hours]

- [ ] **Rollback tested**
  - Owner: [DevOps]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Test date: [MM/DD]

- [ ] **Code freeze implemented**
  - Owner: [Tech Lead]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Start date: [MM/DD]

- [ ] **Production deployment package built**
  - Owner: [DevOps]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Version: [v1.0.0]
  - Build: [#12345]

---

#### Support Readiness

- [ ] **Help desk staffing plan confirmed**
  - Owner: [Support Lead]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Coverage: [X agents, 7am-7pm]

- [ ] **Super users on-floor schedule set**
  - Owner: [Training Manager]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Coverage: [One per department]

- [ ] **Escalation process documented**
  - Owner: [Support Lead]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Levels: L1 (Help Desk) → L2 (Super User) → L3 (IT)

- [ ] **Knowledge base articles created**
  - Owner: [BA]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Count: [50 articles]

- [ ] **Support ticket system configured**
  - Owner: [Support Lead]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Categories created, routing rules set

---

### Day Before Go-Live

#### Final Checks

- [ ] **Go/No-Go meeting held**
  - Owner: [PM]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Date/Time: [MM/DD HH:MM]
  - Decision: ☐ GO / ☐ NO-GO
  - Attendees: [Sponsor, Business Owner, Tech Lead, PM]

- [ ] **Production environment smoke tested**
  - Owner: [QA]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Test cases: [20 critical paths]
  - Results: All passed

- [ ] **Data migration ready to execute**
  - Owner: [Data Team]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Scripts: Final version
  - Duration estimate: [X hours]

- [ ] **Team contact list verified**
  - Owner: [PM]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - All phone numbers tested

- [ ] **War room/command center set up**
  - Owner: [PM]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Location: [Room or Zoom link]

- [ ] **Deployment tools/access verified**
  - Owner: [DevOps]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - VPN, credentials, permissions checked

- [ ] **Monitoring dashboards configured**
  - Owner: [DevOps]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Displayed in war room

- [ ] **Communication channels tested**
  - Owner: [PM]
  - Status: ☐ Not Started / ☐ In Progress / ☑ Complete
  - Slack, email, phone bridge

---

## 🚀 GO-LIVE DAY CHECKLIST

### T-4 Hours: Pre-Deployment

- [ ] **Go-live team assembled**
  - Time: [HH:MM]
  - Attendees confirmed: [All key roles present]

- [ ] **Deployment checklist reviewed**
  - Time: [HH:MM]
  - Team: [All members acknowledge understanding]

- [ ] **Legacy system final backup**
  - Time: [HH:MM]
  - Owner: [DBA]
  - Verified: Yes / No

- [ ] **Production database backup**
  - Time: [HH:MM]
  - Owner: [DBA]
  - Verified: Yes / No

- [ ] **Monitoring alerts paused (if applicable)**
  - Time: [HH:MM]
  - Owner: [DevOps]
  - Duration: [X hours]

- [ ] **Legacy system access disabled**
  - Time: [HH:MM]
  - Owner: [IT]
  - Read-only mode enabled

---

### T-0: Deployment Window

#### Data Migration

- [ ] **Start data migration**
  - Time Started: [HH:MM]
  - Owner: [Data Team]
  - Status: ☐ In Progress / ☐ Complete / ☐ Failed

- [ ] **Monitor migration progress**
  - Owner: [Data Team]
  - Checkpoints: [Every 30 min]
  - Issues: [Log any issues]

- [ ] **Data migration completed**
  - Time Completed: [HH:MM]
  - Duration: [X hours]
  - Owner: [Data Team]

- [ ] **Data validation executed**
  - Time: [HH:MM]
  - Owner: [QA]
  - Record counts match: Yes / No
  - Sample records verified: [X of X passed]
  - Issues: [None / Log issues]

---

#### Application Deployment

- [ ] **Deploy application code**
  - Time Started: [HH:MM]
  - Owner: [DevOps]
  - Version: [v1.0.0]
  - Status: ☐ In Progress / ☐ Complete / ☐ Failed

- [ ] **Run database scripts**
  - Time: [HH:MM]
  - Owner: [DBA]
  - Scripts: [List of scripts run]
  - Status: Success / Failed

- [ ] **Deploy configuration changes**
  - Time: [HH:MM]
  - Owner: [DevOps]
  - Status: Success / Failed

- [ ] **Restart application services**
  - Time: [HH:MM]
  - Owner: [DevOps]
  - All services started: Yes / No

- [ ] **Deployment completed**
  - Time Completed: [HH:MM]
  - Duration: [X minutes]
  - Status: Success / Failed

---

#### Post-Deployment Verification

- [ ] **Smoke test: User login**
  - Time: [HH:MM]
  - Tester: [Name]
  - Result: ☐ Pass / ☐ Fail

- [ ] **Smoke test: Customer record access**
  - Time: [HH:MM]
  - Tester: [Name]
  - Result: ☐ Pass / ☐ Fail

- [ ] **Smoke test: Create opportunity**
  - Time: [HH:MM]
  - Tester: [Name]
  - Result: ☐ Pass / ☐ Fail

- [ ] **Smoke test: Run report**
  - Time: [HH:MM]
  - Tester: [Name]
  - Result: ☐ Pass / ☐ Fail

- [ ] **Smoke test: Mobile access**
  - Time: [HH:MM]
  - Tester: [Name]
  - Result: ☐ Pass / ☐ Fail

- [ ] **Smoke test: Email integration**
  - Time: [HH:MM]
  - Tester: [Name]
  - Result: ☐ Pass / ☐ Fail

- [ ] **Smoke test: All critical paths**
  - Time: [HH:MM]
  - Test cases: [X of X passed]
  - Issues: [None / Log issues]

---

#### Technical Checks

- [ ] **Application health check**
  - Time: [HH:MM]
  - Owner: [DevOps]
  - Status: Healthy / Degraded / Down

- [ ] **Database health check**
  - Time: [HH:MM]
  - Owner: [DBA]
  - Connections: [X active]
  - Performance: Normal / Degraded

- [ ] **Integration endpoints tested**
  - Time: [HH:MM]
  - Owner: [Integration Lead]
  - All 5 integrations: Working / Issues

- [ ] **Monitoring verified**
  - Time: [HH:MM]
  - Owner: [DevOps]
  - Metrics collecting: Yes / No
  - Alerts working: Yes / No

- [ ] **Performance baseline captured**
  - Time: [HH:MM]
  - Owner: [DevOps]
  - Response times: [Avg X ms]
  - Error rate: [X%]

---

#### Go-Live Decision

- [ ] **Go-Live decision made**
  - Time: [HH:MM]
  - Decision Maker: [Business Owner]
  - Decision: ☐ GO LIVE / ☐ ROLLBACK
  - Rationale: [Brief explanation]

**If GO LIVE:**

- [ ] **System opened to pilot users (if phased)**
  - Time: [HH:MM]
  - Users: [X users]
  - Duration: [X hours]

- [ ] **Pilot results reviewed**
  - Time: [HH:MM]
  - Issues: [None / Minor / Major]
  - Decision: ☐ Proceed / ☐ Rollback

- [ ] **System opened to all users**
  - Time: [HH:MM]
  - Announcement sent: Yes / No
  - Users able to access: Yes / No

**If ROLLBACK:**

- [ ] **Rollback initiated**
  - Time: [HH:MM]
  - Owner: [DevOps]
  - See Rollback Checklist below

---

### T+1 Hour: Early Operations

- [ ] **First users logged in successfully**
  - Time: [HH:MM]
  - Count: [X users]
  - Issues: [None / Log issues]

- [ ] **Monitor user activity**
  - Owner: [DevOps]
  - Active users: [X]
  - Transactions: [X per min]

- [ ] **Monitor support tickets**
  - Owner: [Support Lead]
  - Tickets: [X opened]
  - Critical: [X]

- [ ] **Super users on-floor**
  - Locations: [All departments covered]
  - Status: [No issues / Issues reported]

- [ ] **Monitor system performance**
  - Owner: [DevOps]
  - Response time: [X ms avg]
  - Error rate: [X%]
  - Issues: [None / Log issues]

---

### T+4 Hours: Mid-Day Check

- [ ] **User adoption tracking**
  - Active users: [X of X expected]
  - Adoption rate: [X%]

- [ ] **Support ticket review**
  - Total tickets: [X]
  - Critical: [X] - Status: [Resolved / In progress]
  - Common issues: [List top 3]

- [ ] **System stability check**
  - Uptime: [X%]
  - Performance: [Within targets / Degraded]
  - Issues: [None / Log issues]

- [ ] **Integration health check**
  - All integrations: [Working / Issues]
  - Data sync: [Current / Delayed]

---

### End of Day (T+8 Hours)

- [ ] **Day 1 metrics collected**
  - Total users: [X]
  - Total transactions: [X]
  - Support tickets: [X]
  - Critical issues: [X]

- [ ] **Day 1 debrief meeting**
  - Time: [HH:MM]
  - Attendees: [Go-live team]
  - Issues identified: [List]
  - Actions for Day 2: [List]

- [ ] **Stakeholder update sent**
  - Time: [HH:MM]
  - Sent by: [PM]
  - Content: Day 1 summary

- [ ] **Support handoff briefing**
  - Time: [HH:MM]
  - Day shift → Night shift
  - Open issues: [X]
  - Watch items: [List]

---

## 🔄 ROLLBACK CHECKLIST

**TRIGGER CRITERIA FOR ROLLBACK:**
- Critical system failure (cannot be fixed within 2 hours)
- Data corruption or loss
- Security breach
- >25% of users unable to access system
- Business owner decision

---

### Rollback Execution

- [ ] **Rollback decision made and communicated**
  - Time: [HH:MM]
  - Decision Maker: [Name]
  - Team notified: Yes / No

- [ ] **User access disabled**
  - Time: [HH:MM]
  - Owner: [DevOps]
  - Method: [Maintenance page]

- [ ] **Stop all application services**
  - Time: [HH:MM]
  - Owner: [DevOps]
  - All stopped: Yes / No

- [ ] **Restore database backup**
  - Time Started: [HH:MM]
  - Owner: [DBA]
  - Backup: [Timestamp of backup]
  - Time Completed: [HH:MM]

- [ ] **Restore application code**
  - Time: [HH:MM]
  - Owner: [DevOps]
  - Version: [Previous version]

- [ ] **Restore configuration**
  - Time: [HH:MM]
  - Owner: [DevOps]

- [ ] **Restart legacy system**
  - Time: [HH:MM]
  - Owner: [IT]
  - Access restored: Yes / No

- [ ] **Verify legacy system operational**
  - Time: [HH:MM]
  - Tester: [Name]
  - Smoke tests: [X of X passed]

- [ ] **Communicate rollback to users**
  - Time: [HH:MM]
  - Method: [Email, announcement]
  - Message: [Legacy system restored]

- [ ] **Post-mortem scheduled**
  - Date/Time: [MM/DD HH:MM]
  - Purpose: Analyze failure, plan next attempt

---

## 📊 POST-GO-LIVE MONITORING

### Day 1-7 (First Week)

**Daily Monitoring:**

- [ ] **Daily metrics report**
  - Owner: [PM]
  - Metrics: Active users, transactions, tickets, uptime
  - Distribution: Go-live team, stakeholders

- [ ] **Daily stand-up meeting**
  - Time: [HH:MM]
  - Duration: 15 minutes
  - Attendees: Go-live team
  - Agenda: Yesterday recap, today plan, blockers

- [ ] **Support ticket triage**
  - Frequency: Every 4 hours
  - Owner: [Support Lead]
  - Escalation: Critical issues to tech team immediately

- [ ] **System performance monitoring**
  - Owner: [DevOps]
  - Frequency: Continuous
  - Alert on: Response time >3 sec, error rate >1%

**Week 1 Key Metrics:**
| Metric | Target | Actual | Status |
|--------|--------|--------|--------|
| User Adoption | >80% | [X%] | 🟢🟡🔴 |
| System Uptime | >99% | [X%] | 🟢🟡🔴 |
| Avg Response Time | <2 sec | [X sec] | 🟢🟡🔴 |
| Support Tickets | <100 | [X] | 🟢🟡🔴 |
| Critical Issues | 0 | [X] | 🟢🟡🔴 |

---

### Week 2-4 (Stabilization)

- [ ] **Week 2 review meeting**
  - Date: [MM/DD]
  - Topics: Adoption, issues, optimizations
  - Decisions: [Document decisions]

- [ ] **Week 4 review meeting**
  - Date: [MM/DD]
  - Topics: 30-day assessment
  - Decisions: Transition to BAU support

- [ ] **Post-implementation review**
  - Date: [MM/DD]
  - Format: Retrospective
  - Output: Lessons learned document

---

## 💡 Best Practices

### Go-Live Do's ✅

1. **Test Everything** - Test deployment process multiple times
2. **Have a Rollback Plan** - Know exactly how to rollback
3. **Communicate Clearly** - Keep everyone informed
4. **Monitor Closely** - Watch system like a hawk Day 1
5. **Support Users** - Be visible and available
6. **Document Issues** - Log everything for learning
7. **Stay Calm** - Things will go wrong, stay composed
8. **Celebrate Wins** - Recognize team effort

### Go-Live Don'ts ❌

1. **Don't Skip Testing** - Never deploy untested changes
2. **Don't Go Live Friday** - Avoid weekends for support
3. **Don't Go Live During Peak** - Choose low-usage times
4. **Don't Ignore Red Flags** - Better to delay than fail
5. **Don't Deploy Without Backup** - Always have current backup
6. **Don't Assume Success** - Monitor closely, verify
7. **Don't Disappear** - Team must be available post-launch
8. **Don't Skip Communication** - Users need to know what's happening

---

## 📞 Emergency Contacts

### Key Contacts

| Role | Name | Primary Phone | Secondary | Available |
|------|------|---------------|-----------|-----------|
| Executive Sponsor | [Name] | [Phone] | [Phone] | 24/7 |
| Business Owner | [Name] | [Phone] | [Email] | 7am-9pm |
| Project Manager | [Name] | [Phone] | [Slack] | 24/7 |
| Technical Lead | [Name] | [Phone] | [Email] | 24/7 |
| DevOps Lead | [Name] | [Phone] | [Slack] | 24/7 |
| DBA | [Name] | [Phone] | [Email] | On-call |
| Support Lead | [Name] | [Phone] | [Email] | Business hours |
| Vendor Support | [Company] | [Phone] | [Portal] | 24/7 |

### Escalation Path

**Level 1:** Help Desk → Super Users  
**Level 2:** Tech Team → On-call Engineer  
**Level 3:** Technical Lead → Vendor Support  
**Level 4:** Project Manager → Business Owner  
**Level 5:** Executive Sponsor → CTO

---

## 📎 Related Templates

- [Test Plan](./test-plan-template.md) - Pre-go-live testing
- [Communication Plan](./communication-plan-template.md) - User communications
- [Training Plan](./training-plan-template.md) - User readiness
- [Transition Plan](./transition-plan-template.md) - Handoff to operations

---

## 📋 Sign-Off

### Go-Live Approval

**Go/No-Go Decision:**

- [ ] **Business Owner:** GO / NO-GO - [Signature] [Date]
- [ ] **Technical Lead:** GO / NO-GO - [Signature] [Date]
- [ ] **Project Manager:** GO / NO-GO - [Signature] [Date]
- [ ] **Executive Sponsor:** GO / NO-GO - [Signature] [Date]

**Consensus Decision:** ☐ GO LIVE / ☐ NO-GO / ☐ DELAY

**Date Approved:** [MM/DD/YYYY HH:MM]

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
