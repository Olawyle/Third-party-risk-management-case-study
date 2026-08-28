# Stage 4 — Control Assessment & Findings

## 1. Objective

Evaluate the effectiveness of CloudServe Technologies Ltd.'s relevant security and operational controls using the evidence obtained during due diligence, and identify material control weaknesses requiring treatment.

The assessment builds on the Tier 1 — Critical classification established in Stage 2 and the evidence requirements defined during Stage 3.

---

## 2. Assessment Approach

Controls were evaluated based on:

- Control design
- Control implementation
- Evidence quality
- Operating effectiveness
- Identified exceptions or weaknesses
- Potential business and security impact

Vendor assertions were not treated as sufficient evidence of control effectiveness on their own.

> **Assessment Note:** Evidence used in this portfolio case study is simulated and is clearly identified as portfolio demonstration material. No actual CloudServe or FinServe confidential information is used.

---

## 3. Control Assessment Summary

| Control ID | Control Area | Assessment |
|---|---|---|
| CTRL-IAM-001 | Identity & Privileged Access | Effective |
| CTRL-DATA-001 | Data Protection & Encryption | Effective |
| CTRL-VULN-001 | Vulnerability Management & Penetration Testing | Partially Effective |
| CTRL-IR-001 | Security Incident Response & Notification | Partially Effective |
| CTRL-BCP-001 | Business Continuity & Disaster Recovery | Partially Effective |
| CTRL-FPR-001 | Fourth-Party Risk Management | Partially Effective |
| CTRL-PRIV-001 | Privacy & Data Processing | Partially Effective |
| CTRL-EXIT-001 | Data Return & Secure Destruction | Effective |

### Assessment Summary

| Outcome | Count |
|---|---:|
| Effective | 3 |
| Partially Effective | 5 |
| Ineffective | 0 |
| Unable to Validate | 0 |
| Total Controls Assessed | 8 |

The assessment identified weaknesses requiring remediation but did not identify an ineffective control requiring immediate rejection of the vendor relationship.

---

## 4. Key Findings

### FND-001 — Open High-Severity Penetration Testing Findings

**Control:** CTRL-VULN-001  
**Severity:** High  
**Status:** Open

**Observation:** The most recent penetration test identified two high-severity findings that remain open at the time of assessment.

**Risk:** Unresolved vulnerabilities could increase the likelihood or impact of unauthorized access to application functionality, sensitive information, or connected services.

**Recommendation:**

1. Complete remediation within the agreed timeline.
2. Provide evidence demonstrating remediation.
3. Perform validation testing.
4. Document compensating controls where required.
5. Escalate overdue high-severity vulnerabilities through security governance.

---

### FND-002 — Disaster Recovery RTO Failure

**Control:** CTRL-BCP-001  
**Severity:** High  
**Status:** Open

**Observation:** The latest disaster recovery exercise identified a failure to meet the documented Recovery Time Objective (RTO) for a critical application dependency.

**Risk:** Failure to recover critical services within the required timeframe could result in prolonged service disruption affecting FinServe's customer-facing and operational processes.

**Recommendation:**

1. Identify and address the root cause.
2. Complete corrective actions.
3. Conduct repeat recovery testing.
4. Provide evidence demonstrating achievement of the required RTO.
5. Track the remediation through formal governance.

---

### FND-003 — Outdated Security Assessment for Critical Fourth Party

**Control:** CTRL-FPR-001  
**Severity:** Medium  
**Status:** Open

**Observation:** A critical cloud infrastructure provider supporting CloudServe has a security assessment that is more than 18 months old.

**Risk:** Limited current assurance may reduce visibility into the security posture of a critical fourth-party dependency.

**Recommendation:**

1. Complete the outstanding security reassessment.
2. Obtain current independent assurance evidence where available.
3. Establish defined reassessment frequencies for critical fourth parties.
4. Track overdue assessments through vendor governance.

---

### FND-004 — Data Protection Incident Notification Requirement

**Control:** CTRL-PRIV-001  
**Severity:** Medium  
**Status:** Open

**Observation:** The current Data Processing Agreement does not clearly establish notification timelines for certain regulatory data-protection incidents.

**Risk:** Ambiguity could delay coordination and escalation between CloudServe and FinServe during a privacy-related incident.

**Recommendation:**

1. Review the Data Processing Agreement.
2. Define clear notification timelines.
3. Establish escalation responsibilities.
4. Align contractual requirements with FinServe's incident-response and regulatory obligations.
5. Retain the updated agreement as remediation evidence.

---

## 5. Overall Assessment

The control assessment indicates that CloudServe has several established controls, but five control areas require improvement.

The most significant exposures relate to:

- Open high-severity security vulnerabilities
- Disaster recovery performance against the required RTO
- Assurance over critical fourth-party dependencies
- Clarity of privacy incident-notification obligations

Given the vendor's **Tier 1 — Critical** classification, these findings should be formally tracked through remediation and considered during the subsequent residual-risk assessment.

The findings do not, at this stage, require automatic termination of the proposed vendor relationship.

---

## 6. Stage 4 Outcome

**Overall Control Assessment:** Partially Effective

**Controls Assessed:** 8

**Effective:** 3

**Partially Effective:** 5

**Findings:** 4

**High:** 2

**Medium:** 2

**Finding Status:** Open — Remediation Required

**Next Stage:** Risk Treatment & Remediation

The identified findings will be carried forward into Stage 5 for treatment planning, ownership, target dates, remediation tracking, and subsequent validation.