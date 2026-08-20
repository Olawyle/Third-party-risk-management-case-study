# Vendor Control Assessment

## 1. Assessment Information

| Field | Value |
|---|---|
| Vendor | CloudServe Technologies Ltd. |
| Client | FinServe Financial Services Ltd. |
| Vendor Tier | Tier 1 — Critical |
| Inherent Risk Score | 4.20 / 5.00 |
| Inherent Risk Rating | Critical |
| Assessment Type | Enhanced Due Diligence |
| Assessment Status | In Progress |
| Assessment Version | 1.0 |

---

## 2. Purpose

The purpose of this control assessment is to evaluate whether CloudServe Technologies Ltd. has implemented appropriate controls to address the risks identified during the inherent risk assessment.

The assessment considers:

- Control design
- Control implementation
- Supporting evidence
- Control operating effectiveness
- Identified gaps
- Compensating controls
- Remediation requirements

The assessment does not assume that a vendor's response automatically demonstrates effective control implementation.

Where appropriate, vendor statements must be supported by objective evidence.

---

## 3. Assessment Methodology

Each control will be evaluated against the following factors:

### 3.1 Control Design

Does the control adequately address the identified risk?

### 3.2 Control Implementation

Has the vendor demonstrated that the control has actually been implemented?

### 3.3 Evidence Quality

Is the supporting evidence relevant, current, complete, and sufficiently reliable?

### 3.4 Operating Effectiveness

Where evidence permits, does the control appear to operate consistently and effectively?

### 3.5 Exceptions

Are there documented limitations, exclusions, weaknesses, or control failures?

---

## 4. Control Assessment Outcomes

| Outcome | Definition |
|---|---|
| **Effective** | The control is appropriately designed, implemented, and supported by sufficient evidence. |
| **Partially Effective** | The control exists but has limitations, weaknesses, or incomplete evidence that reduce assurance. |
| **Ineffective** | A material control weakness or failure has been identified. |
| **Unable to Validate** | Available information or evidence is insufficient to determine whether the control is effective. |
| **Not Applicable** | The control does not apply to the vendor relationship and the justification has been accepted. |

---

## 5. Finding Severity

Where a control does not receive an Effective outcome, a finding may be created.

| Severity | Description |
|---|---|
| **Critical** | Control weakness could result in severe impact to confidentiality, integrity, availability, regulatory compliance, or business operations. |
| **High** | Significant control weakness that could materially increase third-party risk. |
| **Medium** | Control weakness with a meaningful but more limited potential impact. |
| **Low** | Minor control deficiency or improvement opportunity. |

Finding severity should consider:

- Impact
- Likelihood
- Data sensitivity
- Data volume
- Business criticality
- Access level
- Regulatory exposure
- Existing compensating controls
- Vendor environment

---

## 6. Evidence-Based Assessment Principle

The assessment will distinguish between:

**Vendor Assertion**

What the vendor says it does.

**Control Evidence**

Documentation or other objective evidence supporting the assertion.

**Assessment Conclusion**

The TPRM team's determination based on the available information.

Example:

> Vendor states that MFA is enforced for privileged accounts.

This statement alone does not establish that MFA is effectively implemented.

Supporting evidence may include:

- IAM policy
- Configuration evidence
- Access-control documentation
- Independent audit evidence

The final assessment should therefore be based on the available evidence rather than the vendor's declaration alone.

---

## 7. Assessment Record Structure

Each assessed control will be documented using the following structure:

### Control ID

Unique identifier for the control.

### Risk Area

Risk addressed by the control.

### Control Requirement

What the vendor is expected to implement.

### Vendor Response

Summary of the vendor's response.

### Evidence Reviewed

Evidence used to validate the response.

### Assessment

TPRM team's assessment of the control.

### Result

Effective / Partially Effective / Ineffective / Unable to Validate / Not Applicable.

### Finding

Description of any identified deficiency.

### Severity

Critical / High / Medium / Low.

### Recommendation

Required corrective action or improvement.

### Assessment Status

Current status of the control assessment.

---

## 8. Assessment Limitations

This portfolio case study uses simulated vendor responses and evidence for demonstration purposes.

No actual CloudServe confidential information is being used.

Any simulated evidence will be clearly identified as:

**SIMULATED / PORTFOLIO DEMONSTRATION — NOT ACTUAL VENDOR EVIDENCE**

The assessment conclusions therefore demonstrate the TPRM methodology and decision-making process rather than representing an actual assessment of CloudServe Technologies Ltd.

---

## 9. Assessment Status

**Controls Assessed:** 0

**Effective:** 0

**Partially Effective:** 0

**Ineffective:** 0

**Unable to Validate:** 0

**Findings Identified:** 0

**Overall Control Assessment:** In Progress

---

# 10. Control Assessment — Identity & Privileged Access

## CTRL-IAM-001 — Multi-Factor Authentication for Privileged Accounts

### Risk Area

Identity and Access Management

### Related Inherent Risk

**Access & Integration: 4 / 5 — High**

CloudServe may provide administrative and vendor support access to the SaaS environment. Compromise of privileged credentials could therefore result in unauthorized access to sensitive information or critical functionality.

### Control Requirement

CloudServe should enforce Multi-Factor Authentication (MFA) for all privileged and administrative accounts.

### Vendor Response

**Response: Implemented**

CloudServe states that MFA is mandatory for all privileged administrative accounts.

### Evidence Reviewed

**Simulated Evidence:**

- IAM Policy v3.2
- Privileged Access Management Procedure v2.1
- SOC 2 Type II control mapping
- Sample privileged access configuration

**Evidence Classification:**

SIMULATED / PORTFOLIO DEMONSTRATION — NOT ACTUAL VENDOR EVIDENCE

### Evidence Assessment

The simulated evidence indicates that MFA is formally required for privileged accounts and that privileged access is subject to additional access controls.

The SOC 2 Type II control mapping provides additional independent assurance that the control is included within the vendor's control environment.

However, the assessment does not include live configuration validation or direct testing of the production environment.

### Assessment

The control appears appropriately designed and implemented based on the available simulated evidence.

The remaining limitation is that production configuration has not been independently validated as part of this portfolio exercise.

### Result

**EFFECTIVE**

### Finding

No finding identified.

### Severity

**N/A**

### Recommendation

Maintain mandatory MFA for all privileged accounts and periodically review privileged access to ensure MFA enforcement remains effective.

### Assessment Status

**Accepted**

---

# 11. Control Assessment — Data Protection

## CTRL-DATA-001 — Encryption of Data in Transit and at Rest

### Risk Area

Data Protection

### Related Inherent Risk

**Data Sensitivity: 4 / 5 — High**

**Data Volume: 5 / 5 — Critical**

CloudServe may process and store approximately 500,000 customer and employee records, including potentially sensitive and financial information.

Unauthorized disclosure of this information could result in significant privacy, regulatory, financial, and reputational impact.

### Control Requirement

CloudServe should encrypt sensitive customer information:

- In transit
- At rest
- Within applicable backups and replicated environments

Encryption should use industry-accepted cryptographic standards and appropriate key-management practices.

### Vendor Response

**Response: Implemented**

CloudServe states that customer data is encrypted in transit and at rest.

The vendor states that:

- TLS is used for data transmitted over external connections.
- Data at rest is encrypted using industry-accepted encryption standards.
- Encryption keys are managed through controlled key-management processes.

### Evidence Reviewed

**Simulated Evidence:**

- Encryption Standard v2.0
- Data Protection Policy v3.1
- Cloud Security Architecture Summary
- Key Management Procedure v2.2
- SOC 2 Type II control mapping

**Evidence Classification:**

SIMULATED / PORTFOLIO DEMONSTRATION — NOT ACTUAL VENDOR EVIDENCE

### Evidence Assessment

The simulated documentation indicates that encryption is implemented for data in transit and at rest.

The evidence also indicates that encryption key management is subject to documented procedures.

The SOC 2 Type II control mapping provides additional independent assurance that encryption-related controls form part of the vendor's control environment.

However, the portfolio assessment does not include direct technical validation of the production environment or independent cryptographic configuration testing.

### Assessment

The control appears appropriately designed and implemented based on the available simulated evidence.

Given the sensitivity and volume of information involved, encryption is considered an important mitigating control.

The absence of direct production validation represents a limitation of this portfolio assessment but does not, based on the available evidence, indicate a control failure.

### Result

**EFFECTIVE**

### Finding

No finding identified.

### Severity

**N/A**

### Recommendation

CloudServe should maintain documented encryption standards and periodically review cryptographic algorithms, protocols, and key-management practices to ensure they remain aligned with current security requirements.

### Assessment Status

**Accepted**

---
HIGH DATA SENSITIVITY
        +
CRITICAL DATA VOLUME
        ↓
ENCRYPTION CONTROL
        ↓
EVIDENCE REVIEW
        ↓
EFFECTIVE
        ↓
NO CONTROL FINDING

# 12. Control Assessment — Vulnerability Management

## CTRL-VULN-001 — Vulnerability Management and Penetration Testing

### Risk Area

Vulnerability Management / Application Security

### Related Inherent Risk

**Access & Integration: 4 / 5 — High**

CloudServe provides a technology service that may integrate with FinServe systems and process sensitive information.

A vulnerability affecting the platform, application, API, or supporting infrastructure could potentially result in unauthorized access, data exposure, or service disruption.

### Control Requirement

CloudServe should maintain a formal vulnerability management program that includes:

- Regular vulnerability scanning
- Risk-based vulnerability classification
- Defined remediation timelines
- Application security testing
- Independent penetration testing
- Tracking and remediation of identified vulnerabilities

### Vendor Response

**Response: Partially Implemented**

CloudServe states that:

- Automated vulnerability scanning is performed regularly.
- Vulnerabilities are risk-rated using a documented methodology.
- Critical vulnerabilities are subject to accelerated remediation.
- Annual penetration testing is performed.

However, the most recent penetration test identified **two high-severity findings that remain open**.

The vendor states that remediation is in progress.

### Evidence Reviewed

**Simulated Evidence:**

- Vulnerability Management Policy v3.0
- Vulnerability Remediation Standard v2.1
- 2026 Penetration Test Executive Summary
- Vulnerability Management Dashboard — Q2 2026
- Remediation Tracking Report

**Evidence Classification:**

SIMULATED / PORTFOLIO DEMONSTRATION — NOT ACTUAL VENDOR EVIDENCE

### Evidence Assessment

The evidence demonstrates that CloudServe has a formal vulnerability management process and conducts recurring vulnerability scanning and penetration testing.

However, the most recent penetration testing identified two high-severity findings that remain unresolved.

The existence of open high-severity findings does not automatically mean that the overall vulnerability management program is ineffective. The assessment must also consider:

- Age of the findings
- Business impact
- Exploitability
- Compensating controls
- Documented remediation plan
- Target remediation dates

The available evidence indicates that remediation activities have been initiated but are not yet complete.

### Assessment

The control is appropriately designed and appears to be operating, but unresolved high-severity penetration-test findings create a material control weakness.

Because the findings remain open, the control cannot currently be considered fully effective.

### Result

**PARTIALLY EFFECTIVE**

### Finding

**FND-001 — Open High-Severity Penetration Testing Findings**

The most recent penetration test identified two high-severity findings that remain open at the time of assessment.

Although remediation has reportedly commenced, the findings represent unresolved security weaknesses that could increase the likelihood or impact of exploitation.

### Severity

**HIGH**

### Risk Impact

If the identified vulnerabilities were exploited, an attacker could potentially gain unauthorized access to application functionality, sensitive information, or connected services.

The potential impact is elevated because CloudServe may process a large volume of customer and employee information and may integrate with FinServe systems.

### Recommendation

CloudServe should:

1. Complete remediation of the identified high-severity findings within the agreed remediation timeline.
2. Provide evidence demonstrating successful remediation.
3. Perform validation testing to confirm that the vulnerabilities have been resolved.
4. Document any compensating controls where remediation cannot be completed within the required timeframe.
5. Escalate overdue high-severity vulnerabilities through appropriate security governance channels.

### Remediation Status

**Open**

### Assessment Status

**Exception Identified**

# 13. Control Assessment — Incident Response

## CTRL-IR-001 — Security Incident Response and Notification

### Risk Area

Incident Response / Security Incident Management

### Related Inherent Risk

**Data Sensitivity: 4 / 5 — High**

**Data Volume: 5 / 5 — Critical**

**Business Criticality: 4 / 5 — High**

A security incident affecting CloudServe could potentially expose sensitive information, disrupt important business processes, and affect a significant number of individuals.

### Control Requirement

CloudServe should maintain a documented incident response capability covering:

- Incident identification
- Triage and classification
- Containment
- Investigation
- Eradication
- Recovery
- Root-cause analysis
- Customer notification
- Regulatory escalation where applicable
- Post-incident remediation

CloudServe should also maintain contractual commitments to notify FinServe of incidents affecting FinServe data or services within an agreed timeframe.

### Vendor Response

**Response: Implemented**

CloudServe states that it maintains a formal incident response program and dedicated incident response procedures.

The vendor states that:

- Security incidents are classified according to severity.
- Security incidents are escalated to designated response personnel.
- Incident response exercises are performed periodically.
- Customers are notified of incidents affecting their data or services according to contractual requirements.

### Evidence Reviewed

**Simulated Evidence:**

- Incident Response Plan v4.0
- Security Incident Classification Standard v2.2
- Incident Escalation Procedure v2.1
- 2026 Incident Response Tabletop Exercise Summary
- Customer Security Incident Notification Procedure

**Evidence Classification:**

SIMULATED / PORTFOLIO DEMONSTRATION — NOT ACTUAL VENDOR EVIDENCE

### Evidence Assessment

The simulated evidence demonstrates that CloudServe has a documented incident response framework and defined escalation procedures.

The incident response tabletop exercise provides evidence that the documented response capability is periodically tested rather than existing only as a written policy.

The evidence also indicates that customer notification requirements are formally defined.

However, the portfolio assessment does not independently validate CloudServe's actual incident detection and response performance during a live security event.

### Assessment

The control appears appropriately designed and implemented based on the available evidence.

The existence of documented procedures, defined escalation responsibilities, and periodic testing provides reasonable assurance that CloudServe has established an incident response capability.

### Result

**EFFECTIVE**

### Finding

No finding identified.

### Severity

**N/A**

### Recommendation

CloudServe should continue to conduct periodic incident response exercises and ensure that lessons learned from exercises and actual incidents are tracked through formal remediation processes.

FinServe should also ensure that contractual incident notification timelines are clearly defined and aligned with its internal regulatory and incident-management requirements.

### Assessment Status

**Accepted**

---
# 14. Control Assessment — Business Continuity & Disaster Recovery

## CTRL-BCP-001 — Business Continuity and Disaster Recovery

### Risk Area

Business Continuity / Disaster Recovery / Resilience

### Related Inherent Risk

**Business Criticality: 4 / 5 — High**

CloudServe may support important customer-facing and operational processes for FinServe.

A prolonged service disruption could result in operational delays, customer impact, financial consequences, and reputational damage.

### Control Requirement

CloudServe should maintain documented business continuity and disaster recovery capabilities covering:

- Critical business services
- Recovery priorities
- Recovery Time Objectives (RTO)
- Recovery Point Objectives (RPO)
- Backup procedures
- Disaster recovery procedures
- Alternative processing capabilities
- Recovery testing
- Lessons learned and remediation

### Vendor Response

**Response: Partially Implemented**

CloudServe states that it maintains documented business continuity and disaster recovery plans.

The vendor states that:

- Critical services have defined recovery objectives.
- Customer data is backed up regularly.
- Disaster recovery capabilities are tested periodically.
- Recovery procedures are maintained by designated technical teams.

However, the most recent disaster recovery exercise identified a **failure to meet the documented RTO for one critical application dependency**.

CloudServe has initiated remediation but has not yet completed validation testing.

### Evidence Reviewed

**Simulated Evidence:**

- Business Continuity Plan v3.2
- Disaster Recovery Plan v4.1
- Service Recovery Matrix
- RTO/RPO Register
- 2026 Disaster Recovery Test Summary
- DR Remediation Tracker

**Evidence Classification:**

SIMULATED / PORTFOLIO DEMONSTRATION — NOT ACTUAL VENDOR EVIDENCE

### Evidence Assessment

The evidence demonstrates that CloudServe has documented business continuity and disaster recovery processes.

The vendor has also established recovery objectives and conducts periodic recovery testing.

However, the latest DR exercise identified a failure to meet the documented RTO for a critical application dependency.

This indicates that the documented recovery capability does not currently perform fully in accordance with the stated recovery requirement.

### Assessment

The control is appropriately designed and substantially implemented, but the identified RTO failure represents a resilience gap.

Because the affected dependency supports a critical component of the service, remediation and validation should be completed before the control is considered fully effective.

### Result

**PARTIALLY EFFECTIVE**

### Finding

**FND-002 — Disaster Recovery RTO Failure**

The most recent disaster recovery exercise identified a failure to meet the documented Recovery Time Objective for a critical application dependency.

Although remediation has been initiated, the recovery capability has not yet been successfully revalidated.

### Severity

**HIGH**

### Risk Impact

Failure to recover a critical service within the required timeframe could result in prolonged service disruption and materially affect FinServe's customer-facing and operational processes.

The risk is elevated because CloudServe has been classified as a Tier 1 critical vendor.

### Recommendation

CloudServe should:

1. Complete remediation of the identified recovery deficiency.
2. Identify and address the root cause of the RTO failure.
3. Conduct a repeat recovery test.
4. Provide evidence demonstrating successful achievement of the required RTO.
5. Review whether the documented RTO remains appropriate for the service.
6. Track the remediation through formal governance until closure.

### Remediation Status

**Open**

### Assessment Status

**Exception Identified**

---

# 15. Control Assessment — Fourth-Party Risk

## CTRL-FPR-001 — Subprocessor and Fourth-Party Risk Management

### Risk Area

Fourth-Party Risk / Supply Chain Security

### Related Inherent Risk

**Fourth-Party Dependency: 4 / 5 — High**

CloudServe may rely on external providers for cloud infrastructure, data storage, backup, security services, and other technology capabilities.

A security incident or service failure involving a critical fourth party could therefore affect CloudServe's ability to protect FinServe information or maintain service availability.

### Control Requirement

CloudServe should maintain a formal fourth-party risk management process that includes:

- Identification of material subprocessors
- Risk assessment before onboarding
- Security requirements for critical fourth parties
- Ongoing monitoring
- Contractual security obligations
- Incident notification requirements
- Change notification
- Business continuity considerations
- Periodic reassessment

### Vendor Response

**Response: Partially Implemented**

CloudServe states that it maintains a formal subprocessor management process.

The vendor states that:

- Material subprocessors are identified.
- Security assessments are performed before onboarding critical subprocessors.
- Contractual security requirements are included in supplier agreements.
- Customers are notified of material subprocessor changes.

However, the current subprocessor inventory identifies one critical cloud infrastructure provider for which CloudServe's latest security assessment is **more than 18 months old**.

CloudServe has stated that an updated assessment is scheduled but has not yet been completed.

### Evidence Reviewed

**Simulated Evidence:**

- Subprocessor Management Policy v2.4
- Current Subprocessor Register
- Fourth-Party Risk Assessment Procedure
- Sample Critical Supplier Security Assessment
- Cloud Infrastructure Provider Assurance Report
- Subprocessor Change Notification Procedure

**Evidence Classification:**

SIMULATED / PORTFOLIO DEMONSTRATION — NOT ACTUAL VENDOR EVIDENCE

### Evidence Assessment

The evidence demonstrates that CloudServe has established a formal process for identifying and assessing material subprocessors.

The subprocessor register provides visibility into the vendor's external dependencies.

However, the assessment identified a gap in the currency of security assurance for one critical cloud infrastructure provider.

The latest available assessment for the provider is more than 18 months old.

Given the criticality of the dependency, the evidence does not currently provide sufficient assurance that the provider's security posture remains adequately assessed.

### Assessment

The control is partially effective.

CloudServe has established an appropriate fourth-party risk management framework, but the identified gap in ongoing assurance for a critical dependency reduces the effectiveness of the control.

### Result

**PARTIALLY EFFECTIVE**

### Finding

**FND-003 — Outdated Security Assessment for Critical Fourth Party**

CloudServe's current subprocessor inventory identifies a critical cloud infrastructure provider whose most recent security assessment is more than 18 months old.

The absence of current assurance evidence creates uncertainty regarding the provider's current security posture.

### Severity

**MEDIUM**

### Risk Impact

A security weakness or service disruption affecting the critical cloud infrastructure provider could potentially impact CloudServe's confidentiality, availability, or integrity and consequently affect FinServe.

The risk is partially mitigated by CloudServe's existing subprocessor governance framework and contractual requirements.

### Recommendation

CloudServe should:

1. Complete the outstanding security reassessment of the critical cloud infrastructure provider.
2. Obtain current independent assurance evidence where available.
3. Establish defined reassessment frequencies for critical fourth parties.
4. Track overdue fourth-party assessments through formal risk governance.
5. Escalate material fourth-party risk exceptions to appropriate management.

### Remediation Status

**Open**

### Assessment Status

**Exception Identified**

---
