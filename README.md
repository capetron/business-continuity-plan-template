# Business Continuity Plan Template

A comprehensive business continuity plan (BCP) template for organizations of all sizes. This template provides a complete framework for maintaining critical business operations during and after a disruptive event -- whether a natural disaster, cyberattack, pandemic, supply chain failure, or infrastructure outage.

Includes a Business Impact Analysis (BIA) worksheet, critical function matrix, communication tree, recovery strategy options, and plan maintenance schedule. Suitable for compliance with ISO 22301, NIST SP 800-34, CMMC, HIPAA, SOC 2, and regulatory requirements across industries.

## Table of Contents

- [How to Use This Template](#how-to-use-this-template)
- [Section 1: Plan Overview](#section-1-plan-overview)
- [Section 2: Risk Assessment](#section-2-risk-assessment)
- [Section 3: Business Impact Analysis](#section-3-business-impact-analysis)
- [Section 4: Critical Function Matrix](#section-4-critical-function-matrix)
- [Section 5: Recovery Strategies](#section-5-recovery-strategies)
- [Section 6: Communication Tree](#section-6-communication-tree)
- [Section 7: Emergency Response Procedures](#section-7-emergency-response-procedures)
- [Section 8: IT Disaster Recovery Integration](#section-8-it-disaster-recovery-integration)
- [Section 9: Supply Chain Continuity](#section-9-supply-chain-continuity)
- [Section 10: Plan Testing and Exercises](#section-10-plan-testing-and-exercises)
- [Section 11: Plan Maintenance](#section-11-plan-maintenance)
- [Appendices](#appendices)

---

## How to Use This Template

1. **Secure executive sponsorship** -- BCP requires top-down support and funding
2. **Assemble your BCP team** -- representatives from each department
3. **Complete the Risk Assessment** (Section 2) to identify your threats
4. **Conduct the Business Impact Analysis** (Section 3) to prioritize functions
5. **Build the Critical Function Matrix** (Section 4)
6. **Select Recovery Strategies** (Section 5) for each critical function
7. **Build Communication Trees** (Section 6)
8. **Document Emergency Procedures** (Section 7)
9. **Test the plan** (Section 10) -- a plan that has not been tested is not a plan
10. **Maintain the plan** (Section 11) -- review at least annually

---

## Section 1: Plan Overview

### 1.1 Purpose

This Business Continuity Plan ensures that `[ORGANIZATION NAME]` can maintain or rapidly resume critical business functions during and after a disruptive event, minimizing financial impact, protecting employees, and meeting obligations to customers, partners, and regulators.

### 1.2 Scope

This plan covers:
- All business units and departments at `[LOCATIONS]`
- Critical business functions identified in the BIA
- IT systems and infrastructure (coordinated with the IT Disaster Recovery Plan)
- Third-party dependencies and supply chain
- Employee safety and communication

### 1.3 Plan Activation Authority

| Disruption Level | Description | Activation Authority | Response |
|-----------------|-------------|---------------------|----------|
| Level 1 - Minor | Single department affected, <4 hours | Department manager | Department-level response |
| Level 2 - Moderate | Multiple departments, 4-24 hours | VP / Director | BCP team activated |
| Level 3 - Major | Organization-wide, >24 hours | CEO / COO | Full plan activation |
| Level 4 - Catastrophic | Facility loss or regional event | CEO / COO | Full plan + alternate site |

### 1.4 Key Assumptions

- Critical personnel are available or alternates have been designated
- Insurance coverage is current and adequate
- Backup systems and data are intact and tested
- Alternate work locations have been identified
- Budget for recovery operations has been pre-authorized

---

## Section 2: Risk Assessment

### 2.1 Threat Identification

Evaluate each threat for your specific location and industry:

| Threat Category | Specific Threat | Likelihood (1-5) | Impact (1-5) | Risk Score | Mitigation Controls |
|----------------|----------------|-------------------|--------------|-----------|-------------------|
| **Natural** | Hurricane/tornado | `[ ]` | `[ ]` | `[ ]` | |
| **Natural** | Flood | `[ ]` | `[ ]` | `[ ]` | |
| **Natural** | Earthquake | `[ ]` | `[ ]` | `[ ]` | |
| **Natural** | Severe winter storm | `[ ]` | `[ ]` | `[ ]` | |
| **Natural** | Pandemic | `[ ]` | `[ ]` | `[ ]` | |
| **Technological** | Power outage (extended) | `[ ]` | `[ ]` | `[ ]` | |
| **Technological** | ISP/telecom outage | `[ ]` | `[ ]` | `[ ]` | |
| **Technological** | Server/system failure | `[ ]` | `[ ]` | `[ ]` | |
| **Technological** | Cloud provider outage | `[ ]` | `[ ]` | `[ ]` | |
| **Cyber** | Ransomware attack | `[ ]` | `[ ]` | `[ ]` | |
| **Cyber** | Data breach | `[ ]` | `[ ]` | `[ ]` | |
| **Cyber** | DDoS attack | `[ ]` | `[ ]` | `[ ]` | |
| **Human** | Key person unavailability | `[ ]` | `[ ]` | `[ ]` | |
| **Human** | Workplace violence | `[ ]` | `[ ]` | `[ ]` | |
| **Human** | Sabotage/insider threat | `[ ]` | `[ ]` | `[ ]` | |
| **Supply Chain** | Critical vendor failure | `[ ]` | `[ ]` | `[ ]` | |
| **Supply Chain** | Material shortage | `[ ]` | `[ ]` | `[ ]` | |
| **Regulatory** | Compliance violation/shutdown | `[ ]` | `[ ]` | `[ ]` | |
| **Facility** | Fire | `[ ]` | `[ ]` | `[ ]` | |
| **Facility** | HVAC failure | `[ ]` | `[ ]` | `[ ]` | |
| **Facility** | Water damage | `[ ]` | `[ ]` | `[ ]` | |

**Scoring:** Likelihood: 1=Rare, 2=Unlikely, 3=Possible, 4=Likely, 5=Almost Certain. Impact: 1=Negligible, 2=Minor, 3=Moderate, 4=Major, 5=Catastrophic. Risk Score = Likelihood x Impact.

### 2.2 Risk Heat Map

| | Negligible (1) | Minor (2) | Moderate (3) | Major (4) | Catastrophic (5) |
|---|---|---|---|---|---|
| **Almost Certain (5)** | 5 - Medium | 10 - High | 15 - Critical | 20 - Critical | 25 - Critical |
| **Likely (4)** | 4 - Low | 8 - Medium | 12 - High | 16 - Critical | 20 - Critical |
| **Possible (3)** | 3 - Low | 6 - Medium | 9 - Medium | 12 - High | 15 - Critical |
| **Unlikely (2)** | 2 - Low | 4 - Low | 6 - Medium | 8 - Medium | 10 - High |
| **Rare (1)** | 1 - Low | 2 - Low | 3 - Low | 4 - Low | 5 - Medium |

---

## Section 3: Business Impact Analysis

### 3.1 BIA Worksheet

Complete one worksheet per business function:

**Business Function:** `[NAME]`
**Department:** `[DEPARTMENT]`
**Function Owner:** `[NAME AND TITLE]`

| Question | Answer |
|----------|--------|
| Describe the business function | |
| How many staff perform this function? | |
| What IT systems/applications are required? | |
| What non-IT resources are required (equipment, facilities, materials)? | |
| What external dependencies exist (vendors, partners, utilities)? | |
| What internal dependencies exist (other departments/functions)? | |
| Can this function be performed manually if IT is unavailable? | Yes / No / Partial |
| Can this function be performed remotely? | Yes / No / Partial |
| What is the peak period for this function? | |

**Impact Over Time:**

| Downtime Period | Financial Impact | Operational Impact | Regulatory Impact | Reputational Impact |
|----------------|-----------------|-------------------|-------------------|-------------------|
| 0-4 hours | $ | | | |
| 4-8 hours | $ | | | |
| 8-24 hours | $ | | | |
| 1-3 days | $ | | | |
| 3-7 days | $ | | | |
| 7+ days | $ | | | |

**Maximum Tolerable Downtime (MTD):** `[TIME]`
**Recovery Time Objective (RTO):** `[TIME]`
**Recovery Point Objective (RPO):** `[TIME]`
**Minimum Staff Required:** `[NUMBER]`

---

## Section 4: Critical Function Matrix

Summarize all BIA results in a single matrix, sorted by priority:

| Priority | Business Function | Department | MTD | RTO | RPO | Min Staff | IT Systems Required | Manual Workaround? | Remote Capable? |
|----------|-------------------|------------|-----|-----|-----|-----------|--------------------|--------------------|----------------|
| 1 | | | | | | | | | |
| 2 | | | | | | | | | |
| 3 | | | | | | | | | |
| 4 | | | | | | | | | |
| 5 | | | | | | | | | |
| 6 | | | | | | | | | |
| 7 | | | | | | | | | |
| 8 | | | | | | | | | |

---

## Section 5: Recovery Strategies

### 5.1 People Strategies

| Strategy | Description | When to Use |
|----------|-------------|-------------|
| Remote work | Employees work from home using VPN | IT available, facility unavailable |
| Cross-training | Trained alternates perform critical functions | Key person unavailable |
| Temporary staffing | Contracted temp workers for non-specialized roles | Extended staffing shortage |
| Alternate site | Relocate to backup office or co-working space | Facility destroyed or inaccessible |
| Staggered shifts | Extended hours with rotating staff | Reduced workforce (pandemic) |

### 5.2 Technology Strategies

| Strategy | RTO Achievable | Cost | Systems |
|----------|---------------|------|---------|
| Cloud-based SaaS | Minutes | Varies | Email, CRM, collaboration |
| Hot standby (active-active) | <1 hour | $$$$$ | Mission-critical databases |
| Warm standby | 4-12 hours | $$$ | Important servers |
| Backup and restore | 12-48 hours | $$ | Non-critical systems |
| Manual workarounds | Immediate | $ | When IT is completely unavailable |

### 5.3 Facility Strategies

| Strategy | Activation Time | Capacity | Use Case |
|----------|----------------|----------|----------|
| Remote work (all staff) | Immediate | 100% if VPN capacity allows | Short-term facility loss |
| Co-working space agreement | 24-48 hours | Partial | Small team relocation |
| Reciprocal agreement | 48-72 hours | Partial | Similar-sized partner org |
| Pre-contracted alternate site | 24 hours | Full | Extended facility loss |
| Mobile recovery unit | 24-48 hours | Partial | Any scenario |

### 5.4 Selected Strategies by Function

| Function | People Strategy | Tech Strategy | Facility Strategy | Estimated Cost |
|----------|----------------|--------------|-------------------|---------------|
| | | | | |

---

## Section 6: Communication Tree

### 6.1 Internal Notification Chain

```
CEO / COO
  |
  +-- VP Operations
  |     +-- Department Managers
  |           +-- Team Leads
  |                 +-- Individual Contributors
  |
  +-- CISO / IT Director
  |     +-- IT Recovery Team
  |
  +-- Communications / PR
  |     +-- External stakeholder notifications
  |
  +-- HR Director
  |     +-- Employee welfare and safety
  |
  +-- Legal Counsel
        +-- Regulatory notifications
```

### 6.2 Contact Methods (Priority Order)

1. Company mass notification system (e.g., Everbridge, AlertMedia)
2. Mobile phone (call, then text if no answer)
3. Personal email (pre-registered backup email)
4. Emergency contact (family member on file)

### 6.3 Emergency Contact Roster

| Name | Title | Work Phone | Mobile | Personal Email | Alternate |
|------|-------|-----------|--------|---------------|-----------|
| | | | | | |

### 6.4 External Notification Templates

**Customer notification:**
> [ORGANIZATION NAME] is currently experiencing a disruption affecting [services]. We have activated our business continuity plan and are working to restore full operations by [estimated time]. For urgent needs, please contact [alternate number/email]. We will provide updates every [interval].

**Employee notification:**
> ATTENTION: [ORGANIZATION NAME] BCP has been activated due to [event type]. [INSTRUCTIONS: e.g., Do not report to office. Work remotely. Check email for updates.] Next update by [time].

---

## Section 7: Emergency Response Procedures

### 7.1 Immediate Response (First 60 Minutes)

- [ ] Ensure the physical safety of all employees
- [ ] Account for all personnel (headcount / check-in via notification system)
- [ ] Contact emergency services if needed (911)
- [ ] Assess the situation and determine scope
- [ ] Activate BCP team call
- [ ] Make activation decision (Level 1-4)
- [ ] Begin notifications per communication tree

### 7.2 Short-Term Response (1-24 Hours)

- [ ] Establish command center (physical or virtual)
- [ ] Complete damage/impact assessment
- [ ] Activate selected recovery strategies
- [ ] Communicate with customers and partners
- [ ] Engage insurance carrier
- [ ] Begin critical function recovery (Priority 1 first)
- [ ] Establish regular status update cadence

### 7.3 Sustained Operations (24+ Hours)

- [ ] Execute recovery strategies for all affected functions
- [ ] Monitor recovery progress against RTO targets
- [ ] Manage employee welfare (lodging, meals, counseling)
- [ ] Continue stakeholder communications
- [ ] Track all costs for insurance claims
- [ ] Begin planning for return to normal operations

---

## Section 8: IT Disaster Recovery Integration

This BCP coordinates with the IT Disaster Recovery Plan for technology recovery. Key integration points:

| BCP Component | IT DR Component | Coordination |
|--------------|----------------|-------------|
| Critical function RTOs | System RTOs | BCP function RTOs drive IT system RTOs |
| Communication tree | IT team notification | IT team included in BCP communication tree |
| Alternate site | Recovery site / cloud failover | IT pre-configures recovery site connectivity |
| Manual workarounds | System restoration timeline | BCP provides manual procedures while IT restores systems |

**IT DR Plan location:** `[LINK OR PATH TO IT DR PLAN]`

---

## Section 9: Supply Chain Continuity

### 9.1 Critical Vendors and Alternates

| Vendor | Service/Product | Criticality | Contract SLA | Alternate Vendor | Switching Time |
|--------|----------------|------------|-------------|-----------------|---------------|
| | | High/Med/Low | | | |

### 9.2 Single Points of Failure

| Dependency | Impact If Lost | Mitigation | Status |
|-----------|---------------|-----------|--------|
| | | | |

---

## Section 10: Plan Testing and Exercises

### 10.1 Testing Schedule

| Exercise Type | Frequency | Duration | Participants |
|--------------|-----------|----------|-------------|
| Communication test (call tree) | Quarterly | 30 minutes | All staff |
| Tabletop exercise | Semi-annually | 2-3 hours | BCP team + executives |
| Functional exercise (partial activation) | Annually | 4-8 hours | BCP team + affected departments |
| Full-scale exercise | Every 2 years | 1-2 days | All departments |

### 10.2 Tabletop Scenarios

1. **Ransomware event:** All servers encrypted on a Friday night. Backups appear intact but have not been verified.
2. **Facility fire:** Building is destroyed. All on-site equipment is a total loss. Employees cannot access the office for 3+ months.
3. **Pandemic wave:** 40% of workforce is unable to work for 2-3 weeks. Key personnel are affected.
4. **Critical vendor failure:** Your primary SaaS platform (CRM/ERP) goes offline indefinitely. No timeline for recovery.
5. **Power and internet outage:** Regional outage expected to last 3-5 days. Generator fuel is limited.

### 10.3 After-Action Report Template

- **Exercise date and type:**
- **Scenario:**
- **Participants:**
- **Objectives met (Y/N for each):**
- **Strengths identified:**
- **Gaps identified:**
- **Action items with owners and deadlines:**

---

## Section 11: Plan Maintenance

| Activity | Frequency | Responsible |
|----------|-----------|------------|
| Full plan review and update | Annually | BCP Coordinator |
| Contact information update | Quarterly | HR + BCP Coordinator |
| BIA refresh | Annually | Department heads |
| Risk assessment update | Annually | Risk committee |
| After any real incident | Within 30 days | BCP team |
| After organizational change (M&A, restructure, new facility) | As needed | BCP Coordinator |
| Regulatory/compliance review | Annually | Compliance officer |

---

## Appendices

### Appendix A: Emergency Contact Numbers

| Service | Phone | Account/Reference |
|---------|-------|------------------|
| Police (non-emergency) | | |
| Fire department (non-emergency) | | |
| Building management | | |
| Electric utility | | |
| ISP | | |
| Insurance agent | | Policy #: |
| Legal counsel | | |
| PR / Communications firm | | |

### Appendix B: Vital Records

| Record Type | Location | Backup Location | Access Requirements |
|-------------|----------|----------------|-------------------|
| Insurance policies | | | |
| Contracts (customer) | | | |
| Contracts (vendor) | | | |
| Financial records | | | |
| Employee records | | | |
| IT asset inventory | | | |

### Appendix C: Recovery Resource Requirements

| Resource | Quantity Needed | Source | Lead Time | Cost Estimate |
|----------|---------------|--------|-----------|--------------|
| Laptops | | | | |
| Monitors | | | | |
| Phones | | | | |
| Desks/chairs | | | | |
| Internet circuit | | | | |

---

## Professional Disaster Recovery Services

**Petronella Technology Group** helps businesses build resilient IT infrastructure:

- [Disaster Recovery Planning](https://petronellatech.com/cybersecurity/disaster-recovery/) - Custom DR strategies
- [Managed IT Services](https://petronellatech.com/managed-it-services/) - 24/7 monitoring and backup management
- [Cybersecurity Services](https://petronellatech.com/cybersecurity/) - Comprehensive security posture
- [Compliance Consulting](https://petronellatech.com/compliance/cmmc-compliance-guide/) - CMMC, HIPAA, SOC 2

**Petronella Technology Group** is headquartered in Raleigh, NC. [Contact us](https://petronellatech.com/contact-us/) or call (919) 348-4912.

---

## About

Created and maintained by [Petronella Technology Group](https://petronellatech.com) - a cybersecurity and managed IT services firm based in Raleigh, NC. With 23+ years of experience and zero client breaches, we help businesses secure their infrastructure and achieve compliance.

- **Website:** [petronellatech.com](https://petronellatech.com)
- **Phone:** 919-348-4912
- **Free Assessment:** [Book a consultation](https://book.petronella.ai/blake)

## License

MIT License - See [LICENSE](LICENSE) for details.
