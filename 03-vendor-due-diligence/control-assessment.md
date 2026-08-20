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