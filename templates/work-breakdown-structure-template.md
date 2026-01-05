# Work Breakdown Structure (WBS) Template

## 📋 Document Information

| Field | Details |
|-------|---------|
| **Project Name** | [Enter project name] |
| **Project Manager** | [Name] |
| **Date Created** | [MM/DD/YYYY] |
| **Last Updated** | [MM/DD/YYYY] |
| **Version** | [1.0] |
| **WBS Dictionary Included** | Yes / No |

---

## 🎯 What is a WBS?

A Work Breakdown Structure (WBS) is a hierarchical decomposition of the total scope of work to be carried out by the project team to accomplish the project objectives and create the required deliverables.

### Key Principles

**The 100% Rule:**
- WBS includes 100% of the work defined by project scope
- Includes all deliverables: internal, external, interim
- Everything not in WBS is out of scope

**Decomposition Guidelines:**
- Break down to manageable work packages
- Each level more detailed than above
- Stop at level where you can estimate time/cost
- Typically 3-5 levels deep
- Work packages are lowest level (80 hours or less)

**WBS vs Activities:**
- WBS = WHAT (deliverables, nouns)
- Schedule = WHEN (activities, verbs)
- Example WBS: "Requirements Document"
- Example Activity: "Write Requirements Document"

---

## 📊 WBS Hierarchy

### Level Definitions

**Level 0:** Project (Root)
- The entire project

**Level 1:** Major Deliverables or Phases
- High-level project components
- Typically 3-8 major deliverables

**Level 2:** Sub-deliverables or Phase Components
- Breakdown of Level 1
- More specific deliverable categories

**Level 3:** Detailed Deliverables or Work Packages
- Further decomposition
- Often the lowest level for small projects

**Level 4+:** Work Packages (if needed)
- Smallest manageable units
- Can be estimated and assigned
- Typically 8-80 hours of work

---

## 🗂️ WBS Structure

### Project WBS Hierarchy
```
[Project Name] (Level 0)
│
├── 1.0 Project Management (Level 1)
│   ├── 1.1 Project Planning
│   │   ├── 1.1.1 Project Charter
│   │   ├── 1.1.2 Project Plan
│   │   ├── 1.1.3 Resource Plan
│   │   └── 1.1.4 Communication Plan
│   ├── 1.2 Project Monitoring & Control
│   │   ├── 1.2.1 Status Reports
│   │   ├── 1.2.2 Risk Management
│   │   ├── 1.2.3 Change Management
│   │   └── 1.2.4 Quality Assurance
│   └── 1.3 Project Closure
│       ├── 1.3.1 Final Report
│       ├── 1.3.2 Lessons Learned
│       └── 1.3.3 Project Archive
│
├── 2.0 Requirements (Level 1)
│   ├── 2.1 Requirements Gathering
│   │   ├── 2.1.1 Stakeholder Interviews
│   │   ├── 2.1.2 User Workshops
│   │   ├── 2.1.3 Current State Analysis
│   │   └── 2.1.4 Competitive Analysis
│   ├── 2.2 Requirements Documentation
│   │   ├── 2.2.1 Business Requirements
│   │   ├── 2.2.2 Functional Requirements
│   │   ├── 2.2.3 Non-Functional Requirements
│   │   └── 2.2.4 Requirements Traceability Matrix
│   └── 2.3 Requirements Validation
│       ├── 2.3.1 Requirements Review
│       ├── 2.3.2 Stakeholder Sign-off
│       └── 2.3.3 Requirements Baseline
│
├── 3.0 Design (Level 1)
│   ├── 3.1 Architecture Design
│   │   ├── 3.1.1 System Architecture
│   │   ├── 3.1.2 Data Architecture
│   │   ├── 3.1.3 Integration Architecture
│   │   └── 3.1.4 Security Architecture
│   ├── 3.2 Detailed Design
│   │   ├── 3.2.1 Database Design
│   │   ├── 3.2.2 API Design
│   │   ├── 3.2.3 UI/UX Design
│   │   └── 3.2.4 Component Design
│   └── 3.3 Design Review & Approval
│       ├── 3.3.1 Technical Review
│       ├── 3.3.2 Security Review
│       └── 3.3.3 Design Sign-off
│
├── 4.0 Development (Level 1)
│   ├── 4.1 Development Environment Setup
│   │   ├── 4.1.1 Dev Infrastructure
│   │   ├── 4.1.2 CI/CD Pipeline
│   │   ├── 4.1.3 Code Repository Setup
│   │   └── 4.1.4 Development Tools
│   ├── 4.2 Backend Development
│   │   ├── 4.2.1 Database Implementation
│   │   ├── 4.2.2 API Development
│   │   ├── 4.2.3 Business Logic
│   │   └── 4.2.4 Integration Services
│   ├── 4.3 Frontend Development
│   │   ├── 4.3.1 UI Components
│   │   ├── 4.3.2 User Flows
│   │   ├── 4.3.3 API Integration
│   │   └── 4.3.4 Responsive Design
│   └── 4.4 Code Quality
│       ├── 4.4.1 Unit Tests
│       ├── 4.4.2 Code Reviews
│       ├── 4.4.3 Static Analysis
│       └── 4.4.4 Documentation
│
├── 5.0 Testing (Level 1)
│   ├── 5.1 Test Planning
│   │   ├── 5.1.1 Test Strategy
│   │   ├── 5.1.2 Test Cases
│   │   ├── 5.1.3 Test Data
│   │   └── 5.1.4 Test Environment Setup
│   ├── 5.2 Test Execution
│   │   ├── 5.2.1 Integration Testing
│   │   ├── 5.2.2 System Testing
│   │   ├── 5.2.3 Performance Testing
│   │   └── 5.2.4 Security Testing
│   ├── 5.3 User Acceptance Testing
│   │   ├── 5.3.1 UAT Planning
│   │   ├── 5.3.2 UAT Execution
│   │   ├── 5.3.3 Defect Resolution
│   │   └── 5.3.4 UAT Sign-off
│   └── 5.4 Test Reporting
│       ├── 5.4.1 Test Summary Report
│       ├── 5.4.2 Defect Analysis
│       └── 5.4.3 Quality Metrics
│
├── 6.0 Deployment (Level 1)
│   ├── 6.1 Deployment Planning
│   │   ├── 6.1.1 Deployment Strategy
│   │   ├── 6.1.2 Rollback Plan
│   │   ├── 6.1.3 Deployment Checklist
│   │   └── 6.1.4 Communication Plan
│   ├── 6.2 Infrastructure Preparation
│   │   ├── 6.2.1 Production Environment
│   │   ├── 6.2.2 Database Migration
│   │   ├── 6.2.3 Security Configuration
│   │   └── 6.2.4 Monitoring Setup
│   ├── 6.3 Deployment Execution
│   │   ├── 6.3.1 Code Deployment
│   │   ├── 6.3.2 Data Migration
│   │   ├── 6.3.3 Smoke Testing
│   │   └── 6.3.4 Go/No-Go Decision
│   └── 6.4 Post-Deployment
│       ├── 6.4.1 Monitoring
│       ├── 6.4.2 Issue Resolution
│       └── 6.4.3 Performance Tuning
│
├── 7.0 Training & Documentation (Level 1)
│   ├── 7.1 Documentation
│   │   ├── 7.1.1 User Documentation
│   │   ├── 7.1.2 Admin Documentation
│   │   ├── 7.1.3 Technical Documentation
│   │   └── 7.1.4 API Documentation
│   ├── 7.2 Training Materials
│   │   ├── 7.2.1 Training Guides
│   │   ├── 7.2.2 Video Tutorials
│   │   ├── 7.2.3 Quick Reference Cards
│   │   └── 7.2.4 FAQs
│   └── 7.3 Training Delivery
│       ├── 7.3.1 End User Training
│       ├── 7.3.2 Admin Training
│       ├── 7.3.3 Support Team Training
│       └── 7.3.4 Train-the-Trainer
│
└── 8.0 Change Management (Level 1)
    ├── 8.1 Change Strategy
    │   ├── 8.1.1 Impact Assessment
    │   ├── 8.1.2 Stakeholder Analysis
    │   ├── 8.1.3 Communication Strategy
    │   └── 8.1.4 Resistance Management
    ├── 8.2 Change Execution
    │   ├── 8.2.1 Awareness Campaign
    │   ├── 8.2.2 Training Rollout
    │   ├── 8.2.3 Support Model
    │   └── 8.2.4 Feedback Mechanism
    └── 8.3 Adoption Monitoring
        ├── 8.3.1 Usage Metrics
        ├── 8.3.2 User Satisfaction
        └── 8.3.3 Benefits Realization
```

---

## 📋 WBS Dictionary

### WBS Dictionary Template

For each work package, document:

---

#### WBS ID: 1.1.1
**WBS Element:** Project Charter

| Attribute | Details |
|-----------|---------|
| **Description** | Document that formally authorizes the project and provides PM authority |
| **Deliverables** | • Signed project charter document<br>• Executive presentation<br>• Stakeholder approval |
| **Acceptance Criteria** | • All required sections complete<br>• Budget and timeline approved<br>• Executive sponsor signature obtained |
| **Assumptions** | • Stakeholders available for interviews<br>• Business case already approved<br>• Project sponsor identified |
| **Constraints** | • Must complete within 2 weeks<br>• Budget approval limited to $500K<br>• Cannot start work until charter approved |
| **Dependencies** | • Business case (prerequisite)<br>• Stakeholder availability |
| **Resources Required** | • Project Manager (40 hours)<br>• Business Analyst (20 hours)<br>• Executive sponsor (4 hours) |
| **Estimated Duration** | 2 weeks |
| **Estimated Cost** | $8,000 |
| **Assigned To** | [Project Manager Name] |
| **Quality Standards** | • PMI PMBOK standards<br>• Company project charter template<br>• Legal review for contracts |
| **Risks** | • Stakeholder unavailability delays charter<br>• Scope disagreement during review |

---

#### WBS ID: 4.2.2
**WBS Element:** API Development

| Attribute | Details |
|-----------|---------|
| **Description** | Develop RESTful APIs for backend services including authentication, data CRUD operations, and business logic |
| **Deliverables** | • API endpoints (12 total)<br>• API documentation (OpenAPI/Swagger)<br>• Postman collection<br>• Unit tests (>80% coverage) |
| **Acceptance Criteria** | • All endpoints documented<br>• Response time <200ms (95th percentile)<br>• Security review passed<br>• Unit tests passing |
| **Assumptions** | • Database schema finalized<br>• Authentication framework selected<br>• Development environment ready |
| **Constraints** | • Must use company API standards<br>• Must integrate with existing auth system<br>• Performance requirements defined |
| **Dependencies** | • Database design (3.2.1)<br>• Authentication framework (4.2.3)<br>• API design specs (3.2.2) |
| **Resources Required** | • Senior Backend Engineer (80 hours)<br>• Backend Engineer (120 hours)<br>• Code reviewer (20 hours) |
| **Estimated Duration** | 4 weeks |
| **Estimated Cost** | $28,000 |
| **Assigned To** | [Senior Backend Engineer Name] |
| **Quality Standards** | • REST API best practices<br>• Company coding standards<br>• OWASP security guidelines |
| **Risks** | • Integration complexity higher than estimated<br>• Performance requirements difficult to meet<br>• Third-party API changes |

---

## 📊 WBS Numbering Schemes

### Common Numbering Systems

#### Decimal Numbering (Recommended)
```
1.0 Project Management
  1.1 Planning
    1.1.1 Charter
    1.1.2 Schedule
  1.2 Execution
    1.2.1 Status Reports
```

**Pros:** Clear hierarchy, easy to insert items, unlimited depth  
**Cons:** Can get long at deep levels

---

#### Outline Numbering
```
I. Project Management
   A. Planning
      1. Charter
      2. Schedule
   B. Execution
      1. Status Reports
```

**Pros:** Familiar format, good for documents  
**Cons:** Limited depth (runs out of letters)

---

#### Coded Numbering
```
PM - Project Management
  PM-PL - Planning
    PM-PL-01 - Charter
    PM-PL-02 - Schedule
  PM-EX - Execution
    PM-EX-01 - Status Reports
```

**Pros:** Memorable codes, good for tags/labels  
**Cons:** Requires code dictionary

---

## 🎯 WBS Development Process

### Step-by-Step Creation

#### Step 1: Identify Major Deliverables (Level 1)
**Method:** Top-down decomposition

**Questions to Ask:**
- What are the main deliverables?
- What are the major phases?
- What must be completed?

**Example Level 1 Items:**
- Project Management
- Requirements
- Design
- Development
- Testing
- Deployment

---

#### Step 2: Decompose Level 1 (Level 2)
**Method:** Break each Level 1 into sub-deliverables

**Questions to Ask:**
- What components make up this deliverable?
- What stages are involved?
- What categories exist?

**Example for "Development":**
- Environment Setup
- Backend Development
- Frontend Development
- Code Quality

---

#### Step 3: Continue Decomposition (Level 3+)
**Stop When:**
- Work package can be estimated (time/cost)
- Work package can be assigned to one person/team
- Work package is 8-80 hours of work
- Further decomposition adds no value

**Don't Over-Decompose:**
- ❌ Too detailed = maintenance nightmare
- ❌ Tasks belong in schedule, not WBS
- ❌ Stop at deliverables, not activities

---

#### Step 4: Review and Validate

**Validation Checklist:**
- [ ] 100% Rule: All scope included?
- [ ] Mutually exclusive: No overlap?
- [ ] Deliverable-oriented: Nouns, not verbs?
- [ ] Appropriate detail: Can estimate?
- [ ] Balanced: Similar level of detail across?
- [ ] Complete: All phases covered?
- [ ] Traceable: Can map to requirements?

---

## 📊 WBS by Project Type

### Software Development Project
```
1.0 Planning & Requirements
2.0 Design & Architecture
3.0 Development
4.0 Testing
5.0 Deployment
6.0 Documentation & Training
7.0 Project Management
```

---

### Construction Project
```
1.0 Design
2.0 Site Preparation
3.0 Foundation
4.0 Structure
5.0 Mechanical Systems
6.0 Interior Finishes
7.0 Landscaping
8.0 Inspections & Permits
9.0 Project Management
```

---

### Marketing Campaign
```
1.0 Campaign Strategy
2.0 Creative Development
3.0 Content Production
4.0 Media Buying
5.0 Campaign Execution
6.0 Performance Tracking
7.0 Project Management
```

---

### Infrastructure Migration
```
1.0 Assessment & Planning
2.0 Infrastructure Design
3.0 Migration Preparation
4.0 Pilot Migration
5.0 Full Migration
6.0 Validation & Optimization
7.0 Decommissioning
8.0 Project Management
```

---

## 🔗 WBS Integration

### WBS Relationship to Other Documents

**WBS → Schedule:**
- WBS work packages become schedule activities
- WBS provides what, schedule provides when
- Each work package expands to 1+ activities

**WBS → Budget:**
- Cost estimated for each work package
- Roll up costs to higher levels
- Map to budget categories

**WBS → Risk Register:**
- Identify risks for each WBS element
- Link risks to specific work packages
- Risk impact affects WBS elements

**WBS → RACI Matrix:**
- Assign ownership to WBS elements
- Define R-A-C-I for each work package
- Ensure all WBS items have owners

**WBS → Requirements:**
- Trace requirements to WBS elements
- Ensure all requirements covered
- Map acceptance criteria to deliverables

---

## 💡 WBS Best Practices

### Do's ✅

1. **Start with Deliverables** - Not activities
2. **Use Nouns** - "Requirements Document" not "Write Requirements"
3. **Apply 100% Rule** - Include all work
4. **Balance Detail** - Consistent decomposition depth
5. **Involve Team** - Get input from those doing work
6. **Validate with Stakeholders** - Ensure nothing missed
7. **Update as Needed** - WBS is living document
8. **Create WBS Dictionary** - Document work packages

### Don'ts ❌

1. **Don't Include Activities** - That's the schedule
2. **Don't Over-Decompose** - Stop when can estimate
3. **Don't Forget Project Management** - It's work too
4. **Don't Mix Organization Types** - Phase OR deliverable, not both
5. **Don't Skip Validation** - Review for completeness
6. **Don't Create in Isolation** - Involve team
7. **Don't Forget Non-Technical Work** - Training, documentation, etc.
8. **Don't Make it Perfect** - Good enough to start

---

## 🎓 WBS Organization Approaches

### Approach 1: Phase-Based (Lifecycle)

**Structure:**
```
1.0 Initiation
2.0 Planning
3.0 Execution
4.0 Monitoring & Control
5.0 Closure
```

**Best For:**
- Projects with clear phases
- Traditional waterfall
- Governance-heavy projects

**Pros:** Clear phase gates, easy to understand  
**Cons:** May not reflect deliverables well

---

### Approach 2: Deliverable-Based (Product)

**Structure:**
```
1.0 Requirements Document
2.0 Design Specifications
3.0 Software Application
4.0 Test Reports
5.0 Training Materials
```

**Best For:**
- Product development
- Construction
- Deliverable-focused projects

**Pros:** Clear deliverables, maps to scope  
**Cons:** Doesn't show sequence

---

### Approach 3: Hybrid (Phase + Deliverable)

**Structure:**
```
1.0 Requirements Phase
  1.1 Requirements Document
  1.2 Prototype
2.0 Design Phase
  2.1 Architecture Design
  2.2 Detailed Design
```

**Best For:**
- Most projects
- Balance of structure and clarity

**Pros:** Best of both approaches  
**Cons:** Can get complex

---

### Approach 4: Geographic (Location)

**Structure:**
```
1.0 North America Region
  1.1 US Deployment
  1.2 Canada Deployment
2.0 Europe Region
  2.1 UK Deployment
  2.2 Germany Deployment
```

**Best For:**
- Multi-location projects
- Global rollouts

**Pros:** Clear geographic organization  
**Cons:** May duplicate work across regions

---

## 📊 WBS Analysis

### Work Package Size Guidelines

| Size Category | Duration | Effort | When to Use |
|---------------|----------|--------|-------------|
| **Micro** | <8 hours | <1 day | Too small - combine |
| **Small** | 8-40 hours | 1-5 days | ✅ Good size |
| **Medium** | 40-80 hours | 1-2 weeks | ✅ Good size |
| **Large** | 80-160 hours | 2-4 weeks | ⚠️ Consider decomposing |
| **Huge** | >160 hours | >4 weeks | ❌ Must decompose |

**Rule of Thumb:** 8-80 hour rule (1-10 days)

---

### WBS Depth Analysis

| Levels | Typical Use | Detail Level |
|--------|-------------|--------------|
| **2 Levels** | Very small projects (<1 month) | High-level only |
| **3 Levels** | Small projects (1-3 months) | Adequate detail |
| **4 Levels** | Medium projects (3-12 months) | ✅ Most common |
| **5 Levels** | Large projects (1-2 years) | Very detailed |
| **6+ Levels** | Mega projects (2+ years) | Risk of over-detail |

---

## 📋 WBS Templates by Industry

### IT/Software WBS
```
1.0 Project Management
2.0 Business Analysis
3.0 System Design
4.0 Development
5.0 Quality Assurance
6.0 Implementation
7.0 Training
8.0 Support
```

---

### Construction WBS
```
1.0 Preconstruction
2.0 Site Work
3.0 Concrete
4.0 Masonry
5.0 Metals
6.0 Woods & Plastics
7.0 Thermal & Moisture
8.0 Doors & Windows
9.0 Finishes
10.0 Specialties
11.0 Equipment
12.0 Furnishings
13.0 Special Construction
14.0 Conveying Systems
15.0 Mechanical
16.0 Electrical
```

---

### Event Planning WBS
```
1.0 Event Concept & Planning
2.0 Venue Selection & Setup
3.0 Marketing & Promotion
4.0 Registration & Logistics
5.0 Content & Programming
6.0 Catering & Hospitality
7.0 Technology & AV
8.0 Event Execution
9.0 Post-Event Activities
```

---

## 📎 Related Templates

- [Project Charter](./project-charter-template.md) - Defines scope for WBS
- [Budget Tracking](./budget-tracking-template.md) - Budget by WBS element
- [RACI Matrix](./raci-matrix-template.md) - Assign ownership to WBS
- [Risk Register](./risk-register-template.md) - Risks by WBS element

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
