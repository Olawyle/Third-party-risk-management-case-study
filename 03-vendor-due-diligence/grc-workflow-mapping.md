# GRC Workflow Mapping

## 1. Purpose

This document maps the Third-Party Risk Management (TPRM) workflow developed in this case study to common enterprise Governance, Risk, and Compliance (GRC) platforms.

The objective is to demonstrate how the activities documented in this portfolio case study could be operationalized within a GRC technology environment.

The workflow covers:

- Vendor onboarding
- Vendor profiling
- Inherent risk assessment
- Vendor tiering
- Due diligence
- Evidence collection
- Control assessment
- Findings management
- Remediation
- Residual risk assessment
- Risk acceptance
- Ongoing monitoring
- Vendor offboarding

---

## 2. Portfolio Implementation vs GRC Platform Mapping

This project is implemented as a documented TPRM case study using GitHub and Markdown.

The GRC platforms referenced in this document represent **workflow mappings and portfolio demonstrations**.

They do not represent live production activity performed in those platforms.

### Portfolio Implementation

| Component | Implementation |
|---|---|
| TPRM Documentation | GitHub |
| Vendor Profile | Markdown |
| Risk Assessment | Markdown |
| Due Diligence | Markdown |
| Evidence Register | Markdown |
| Control Assessment | Markdown |
| Findings Register | Markdown |
| Remediation Tracking | Markdown |
| GRC Workflow Mapping | Markdown |

### Enterprise GRC Equivalent

In a production environment, these activities could be supported by platforms such as:

- ServiceNow
- Archer
- OneTrust
- Vanta
- Jira

The specific platform configuration would depend on the organization's technology architecture, licensing, processes, and integration strategy.

---

## 3. End-to-End TPRM Workflow

The TPRM lifecycle developed in this case study follows:

```text
Vendor Identification
        ↓
Vendor Onboarding
        ↓
Vendor Profile
        ↓
Inherent Risk Assessment
        ↓
Vendor Tiering
        ↓
Due Diligence
        ↓
Evidence Collection
        ↓
Control Assessment
        ↓
Findings
        ↓
Remediation
        ↓
Residual Risk Assessment
        ↓
Risk Acceptance / Treatment
        ↓
Approval
        ↓
Ongoing Monitoring
        ↓
Periodic Reassessment
        ↓
Vendor Offboarding

## 4. Platform Role Summary

The following platforms can support different components of the TPRM lifecycle. The appropriate platform depends on the organization's existing technology environment, process maturity, and business requirements.

| Platform | Primary Role in TPRM Workflow |
|---|---|
| ServiceNow | Workflow orchestration, vendor records, risk records, issues, tasks, approvals, and remediation workflows |
| Archer | Enterprise risk management, third-party risk assessments, controls, findings, and risk reporting |
| OneTrust | Privacy risk, third-party assessments, data processing, regulatory requirements, and privacy workflows |
| Vanta | Security and compliance evidence collection, control monitoring, and assurance activities |
| Jira | Remediation task management, issue tracking, and coordination with technical/security teams |

### Platform Selection Principle

Organizations do not necessarily need to use all of these platforms.

The selected technology should support the organization's existing TPRM methodology, risk framework, control environment, and operational workflows.

---

## 5. Core Principle

A mature TPRM program should not be defined by the GRC platform itself.

The technology should support the organization's established risk methodology and make the process more consistent, scalable, measurable, and auditable.

The fundamental TPRM process remains:

**Identify → Assess → Mitigate → Monitor → Reassess**

### Key Principle

> **Technology enables the TPRM process; it does not replace risk-based decision-making.**

A GRC platform should help organizations:

- Centralize vendor information
- Standardize risk assessments
- Automate assessment workflows
- Manage evidence
- Track control effectiveness
- Record findings
- Assign remediation actions
- Monitor remediation status
- Support risk acceptance
- Maintain an audit trail
- Generate management reporting

### Portfolio Application

For this case study, GitHub and Markdown are being used to document the TPRM process.

The GRC platforms referenced in this document represent how the same workflow could be operationalized within an enterprise environment.

No claim is being made that these platforms were used to execute the CloudServe assessment.

The purpose is to demonstrate an understanding of how **TPRM processes, risk decisions, controls, findings, and remediation activities translate into enterprise GRC workflows.**

## 6. Vendor Onboarding and Vendor Record

Vendor onboarding is the starting point of the TPRM lifecycle.

Before a vendor can be assessed, the organization should establish a complete vendor record containing enough information to determine the vendor's potential risk exposure.

---

### 6.1 Portfolio Case Study Record

The CloudServe Technologies Ltd. vendor profile developed in this case study contains the core information required to establish a third-party record.

The vendor record includes:

- Vendor name
- Service provided
- Business purpose
- Data handled
- Data sensitivity
- Data volume
- System access
- Business criticality
- Fourth-party dependency
- Geographic considerations
- Inherent risk
- Vendor tier

These attributes form the foundation for determining the appropriate level of third-party due diligence.

---

### 6.2 Example Enterprise GRC Vendor Record

| Vendor Attribute | Portfolio Value |
|---|---|
| Vendor Name | CloudServe Technologies Ltd. |
| Service | Cloud-based SaaS platform |
| Vendor Tier | Tier 1 — Critical |
| Business Criticality | 4 / 5 |
| Data Sensitivity | 4 / 5 |
| Data Volume | 5 / 5 |
| Access & Integration | 4 / 5 |
| Fourth-Party Dependency | 4 / 5 |
| Inherent Risk Score | 4.20 / 5.00 |
| Inherent Risk Rating | Critical |
| Assessment Type | Enhanced Due Diligence |
| Assessment Frequency | Annual / Risk-Based |
| Current Assessment Status | In Progress |

---

### 6.3 ServiceNow Mapping

In a ServiceNow-based implementation, the vendor could be represented as a third-party or vendor record containing:

#### Vendor Information

- Vendor name
- Vendor type
- Service provided
- Business owner
- Procurement owner
- Contract information
- Relationship status

#### Risk Information

- Inherent risk score
- Risk rating
- Criticality
- Data classification
- Access level
- Regulatory considerations

#### Workflow Information

- Assessment status
- Assigned assessor
- Assessment due date
- Approval status
- Findings
- Remediation tasks
- Review date

The vendor record would act as a central reference point for the third-party relationship.

---

### 6.4 Archer Mapping

In an Archer implementation, the vendor record could be connected to the following workflow:

```text
Vendor
   ↓
Business Service
   ↓
Inherent Risk Assessment
   ↓
Due Diligence Assessment
   ↓
Controls
   ↓
Findings
   ↓
Remediation
   ↓
Residual Risk

### 6.5 OneTrust Mapping

Where OneTrust is used for third-party risk and privacy workflows, the vendor relationship could be connected to:

- Third-party assessment
- Privacy assessment
- Data processing activities
- Data classification
- Subprocessor information
- Regulatory requirements
- Contractual obligations
- Remediation actions

This would be particularly relevant to CloudServe because the case study involves the processing of potentially sensitive information.

---

### 6.6 Vendor Tiering Trigger

The inherent risk assessment resulted in a score of **4.20 / 5.00**, which is classified as **Critical**.

This risk rating triggers an **Enhanced Due Diligence** workflow.

#### Workflow Trigger

```text
Vendor Created
      ↓
Initial Risk Assessment
      ↓
Risk Score: 4.20 / 5.00
      ↓
Risk Rating: Critical
      ↓
Vendor Tier: Tier 1
      ↓
Enhanced Due Diligence
      ↓
Security Assessment
      ↓
Privacy Assessment
      ↓
Business Continuity Assessment
      ↓
Fourth-Party Assessment
      ↓
Control Assessment

### 6.7 Risk-Based Workflow Principle

The depth of the assessment should be proportional to the vendor's risk.

A low-risk vendor should not automatically receive the same level of due diligence as a critical vendor.

#### Example Assessment Approach

| Vendor Tier | Assessment Approach |
|---|---|
| Tier 1 — Critical | Enhanced due diligence, evidence validation, control assessment, approval, and ongoing monitoring |
| Tier 2 — High | Standard security and privacy assessment with targeted evidence collection |
| Tier 3 — Moderate | Proportionate questionnaire and selected evidence |
| Tier 4 — Low | Basic due diligence and contractual checks |

A risk-based approach allows organizations to focus resources on vendors that could create the greatest business impact.

#### Risk-Based Decision Principle

> **The higher the potential impact and inherent risk, the greater the level of due diligence and oversight required.**

This approach helps prevent unnecessary assessment effort for low-risk vendors while ensuring that critical vendors receive appropriate scrutiny.

---

### 6.8 Workflow Outcome

For the CloudServe Technologies Ltd. case study, the initial risk assessment produces the following workflow outcome:

| Assessment Element | Outcome |
|---|---|
| Inherent Risk Score | 4.20 / 5.00 |
| Risk Rating | Critical |
| Vendor Tier | Tier 1 — Critical |
| Assessment Type | Enhanced Due Diligence |
| Security Assessment | Required |
| Privacy Assessment | Required |
| Business Continuity Assessment | Required |
| Fourth-Party Assessment | Required |
| Control Assessment | Required |
| Ongoing Monitoring | Required |

#### Resulting TPRM Workflow

```text
Inherent Risk Assessment
          ↓
Critical Risk Rating
          ↓
Tier 1 Vendor Classification
          ↓
Enhanced Due Diligence
          ↓
Evidence Collection
          ↓
Control Assessment
          ↓
Findings Identification
          ↓
Remediation
          ↓
Residual Risk Assessment
          ↓
Risk Treatment / Acceptance
          ↓
Ongoing Monitoring

## 7. Due Diligence and Evidence Collection

Once a vendor has been classified and the appropriate assessment level has been determined, the organization initiates the due diligence process.

For a Tier 1 critical vendor such as CloudServe Technologies Ltd., the assessment requires enhanced due diligence supported by appropriate evidence.

The objective is to obtain sufficient information to determine whether the vendor's controls adequately address the identified risks.

---

### 7.1 Due Diligence Workflow

The due diligence workflow developed in this case study follows:

```text
Enhanced Due Diligence Trigger
            ↓
Assessment Questionnaire
            ↓
Evidence Request
            ↓
Vendor Response
            ↓
Evidence Submission
            ↓
Evidence Review
            ↓
Control Assessment
            ↓
Finding Identification
            ↓
Remediation

### 7.2 Portfolio Artifacts

The CloudServe assessment includes the following due diligence artifacts:

| Portfolio Artifact | Purpose |
|---|---|
| Due Diligence Questionnaire | Captures vendor responses across key risk domains |
| Evidence Request Register | Tracks evidence requested from the vendor |
| Control Assessment | Evaluates the effectiveness of vendor controls |
| Findings & Remediation Register | Tracks identified control weaknesses and remediation |
| GRC Workflow Mapping | Demonstrates how the process could be operationalized in an enterprise GRC environment |

These artifacts collectively provide an auditable assessment trail.

---

### 7.3 Evidence-Based Assessment

Vendor responses should not automatically be treated as evidence of effective controls.

The assessment should distinguish between:

| Assessment Element | Description |
|---|---|
| Vendor Assertion | What the vendor states it does |
| Supporting Evidence | Documentation or evidence supporting the vendor's response |
| Control Assessment | Evaluation of whether the control is appropriately designed and implemented |
| Assessment Result | Effective, Partially Effective, Ineffective, Unable to Validate, or Not Applicable |
| Finding | Identified control weakness requiring remediation |

For example:

> Vendor states that MFA is mandatory for privileged accounts.

The statement alone does not establish that MFA is effectively implemented.

Supporting evidence could include:

- IAM policy
- Access control procedure
- Configuration evidence
- Independent assurance report
- Relevant audit evidence

The assessment conclusion should therefore be based on available evidence rather than the vendor's declaration alone.

---

### 7.4 ServiceNow Mapping

In a ServiceNow-based implementation, the due diligence workflow could be represented through:

- Vendor assessment record
- Assessment questionnaire
- Assessment tasks
- Evidence requests
- Evidence attachments
- Control assessments
- Issues or findings
- Remediation tasks
- Approval workflows

A simplified workflow could be represented as:

```text
Vendor Record
      ↓
Assessment Created
      ↓
Questionnaire Assigned
      ↓
Vendor Response
      ↓
Evidence Submitted
      ↓
Assessor Review
      ↓
Control Assessment
      ↓
Finding / No Finding
      ↓
Remediation Task

### 7.5 Archer Mapping

In an Archer implementation, the due diligence process could connect the following records:

```text
Third Party
     ↓
Risk Assessment
     ↓
Assessment Questionnaire
     ↓
Control Responses
     ↓
Evidence
     ↓
Control Assessment
     ↓
Findings
     ↓
Remediation
     ↓
Residual Risk

### 7.6 Vanta Mapping

Vanta can support the evidence and compliance assurance component of the workflow.

For a vendor assessment, Vanta-style capabilities could support the collection or validation of security and compliance evidence such as:

- SOC 2 reports
- ISO 27001 certification
- Security policies
- Penetration testing evidence
- Security control information
- Compliance documentation
- Security monitoring information

In this case study, Vanta is **not being used to perform the actual CloudServe assessment**.

Instead, its potential role is mapped as an example of how automated security and compliance evidence could supplement the traditional questionnaire process.

---

### 7.7 OneTrust Mapping

OneTrust can support third-party risk and privacy-related assessment activities.

For CloudServe, relevant workflows could include:

- Third-party risk assessment
- Privacy assessment
- Data processing assessment
- Subprocessor assessment
- Data protection requirements
- Contractual privacy requirements
- Privacy-related remediation

This is particularly relevant because CloudServe may process sensitive information on behalf of FinServe.

---

### 7.8 Evidence Quality Assessment

Evidence should be evaluated based on several key attributes:

| Evidence Attribute | Assessment Consideration |
|---|---|
| Relevance | Does the evidence address the specific control being assessed? |
| Currency | Is the evidence sufficiently recent? |
| Completeness | Does it provide enough information to support the assessment? |
| Authenticity | Can the source and origin of the evidence be established? |
| Independence | Is the evidence independently validated where appropriate? |
| Scope | Does the evidence cover the relevant service, environment, and assessment period? |

The strength and reliability of the evidence should influence the level of assurance assigned to the control.

---

### 7.9 Risk-Based Evidence Collection

Evidence requirements should be proportional to the vendor's risk.

A Tier 1 critical vendor may require stronger and more extensive evidence than a low-risk vendor.

#### Example Evidence Requirements

| Risk Level | Example Evidence Requirement |
|---|---|
| Critical | Independent assurance reports, penetration testing evidence, security policies, control evidence, BCP/DR evidence, and privacy documentation |
| High | Relevant independent assurance reports and targeted control evidence |
| Moderate | Questionnaire responses and selected supporting evidence |
| Low | Basic security and contractual documentation |

The objective is not to collect the largest possible volume of documentation.

The objective is to obtain **sufficient, relevant, and reliable evidence to support a risk-based decision**.

---

### 7.10 Evidence-to-Control Traceability

The assessment should maintain traceability between evidence and the controls being evaluated.

#### Example

| Evidence | Related Control | Assessment |
|---|---|---|
| IAM Policy | CTRL-IAM-001 | Effective |
| Encryption Standard | CTRL-DATA-001 | Effective |
| Penetration Test | CTRL-VULN-001 | Partially Effective |
| DR Test Summary | CTRL-BCP-001 | Partially Effective |
| Subprocessor Assessment | CTRL-FPR-001 | Partially Effective |
| Data Processing Agreement | CTRL-PRIV-001 | Partially Effective |
| Data Deletion Procedure | CTRL-EXIT-001 | Effective |

This traceability demonstrates how evidence supports the control assessment and ultimately contributes to the overall risk decision.

---

### 7.11 Workflow Outcome

The due diligence workflow produces a documented evidence trail:

```text
Vendor Response
      ↓
Evidence Submitted
      ↓
Evidence Quality Review
      ↓
Control Mapping
      ↓
Control Effectiveness Assessment
      ↓
Findings Identified
      ↓
Remediation Required

## 8. Control Assessment and Findings Management

The control assessment stage evaluates whether the vendor's controls are appropriately designed, implemented, and operating effectively.

For the CloudServe Technologies Ltd. assessment, the control assessment is based on the evidence collected during the due diligence process.

The assessment process follows:

```text
Evidence
   ↓
Control Mapping
   ↓
Control Design Assessment
   ↓
Control Operating Effectiveness Assessment
   ↓
Assessment Result
   ↓
Finding Identification
   ↓
Risk Evaluation
   ↓
Remediation

### 8.1 Control Assessment Workflow

The control assessment determines whether the evidence provided by the vendor supports the effectiveness of the relevant control.

The assessment considers two primary dimensions:

| Assessment Dimension | Purpose |
|---|---|
| Control Design | Determines whether the control is appropriately designed to address the identified risk |
| Operating Effectiveness | Determines whether the control is implemented and operating as intended |

A control should not automatically be rated effective simply because a policy or procedure exists.

The assessment should consider whether the control is:

- Appropriately designed
- Implemented
- Supported by sufficient evidence
- Operating consistently
- Relevant to the identified risk
- Subject to appropriate oversight

---

### 8.2 Control Effectiveness Rating

The following rating model is used for this case study:

| Rating | Definition |
|---|---|
| Effective | Control is appropriately designed, implemented, and supported by sufficient evidence |
| Partially Effective | Control exists but has a weakness, limitation, or evidence gap |
| Ineffective | Control is absent, inadequately designed, or not operating as intended |
| Unable to Validate | Available evidence is insufficient to determine control effectiveness |
| Not Applicable | Control does not apply to the vendor or service |

---

### 8.3 Control Assessment Decision Logic

The assessment decision process can be represented as:

```text
Is the control designed appropriately?
              ↓
             Yes
              ↓
Is the control implemented?
              ↓
             Yes
              ↓
Is sufficient evidence available?
              ↓
             Yes
              ↓
Is the control operating effectively?
              ↓
        ┌─────┴─────┐
       Yes           No
        ↓             ↓
   Effective    Partially Effective
                      or
                  Ineffective

### 8.4 CloudServe Control Assessment

The assessment of CloudServe Technologies Ltd. produced the following control effectiveness results:

| Control ID | Control Area | Assessment |
|---|---|---|
| CTRL-IAM-001 | Identity & Access Management | Effective |
| CTRL-DATA-001 | Data Protection & Encryption | Effective |
| CTRL-VULN-001 | Vulnerability Management | Partially Effective |
| CTRL-BCP-001 | Business Continuity & Disaster Recovery | Partially Effective |
| CTRL-FPR-001 | Fourth-Party Risk Management | Partially Effective |
| CTRL-PRIV-001 | Privacy & Data Protection | Partially Effective |
| CTRL-EXIT-001 | Data Retention & Secure Deletion | Effective |

The controls assessed as **Partially Effective** require further review, remediation, or formal risk treatment.

---

### 8.5 Evidence-to-Finding Relationship

A control weakness should be converted into a formal finding when the identified deficiency creates a meaningful risk exposure.

The relationship between evidence, controls, and findings can be represented as:

```text
Evidence Reviewed
       ↓
Control Assessment
       ↓
Control Weakness Identified
       ↓
Risk Impact Evaluated
       ↓
Finding Created
       ↓
Severity Assigned
       ↓
Remediation Required


### 8.6 Findings and Remediation GRC Workflow

Findings identified during the CloudServe assessment should be recorded, assigned, tracked, and remediated through a controlled workflow.

The objective is to ensure that every identified weakness has:

- A unique finding ID
- A defined risk rating
- An accountable owner
- A remediation action
- A target completion date
- A documented status
- Supporting evidence
- Validation before closure

#### Finding Management Workflow

```text
Control Assessment
       ↓
Finding Identified
       ↓
Finding Logged
       ↓
Severity Assigned
       ↓
Remediation Owner Assigned
       ↓
Remediation Plan Created
       ↓
Target Date Established
       ↓
Remediation in Progress
       ↓
Evidence Submitted
       ↓
Validation
       ↓
Finding Closed

### 8.7 Residual Risk and Risk Acceptance

Residual risk is the level of risk that remains after existing controls and planned risk treatments have been considered.

For third-party risk management, remediation does not always eliminate risk completely. The organization must therefore determine whether the remaining risk is acceptable.

#### Residual Risk Workflow

```text
Inherent Risk
      ↓
Existing Controls
      ↓
Control Assessment
      ↓
Findings Identified
      ↓
Risk Treatment
      ↓
Remediation
      ↓
Residual Risk Assessment
      ↓
Risk Acceptance Decision

### 8.8 End-to-End GRC Workflow

The complete CloudServe third-party risk assessment can be represented as an end-to-end GRC workflow.

The workflow connects vendor onboarding, risk assessment, due diligence, evidence collection, control assessment, findings, remediation, and residual risk.

#### Complete TPRM Workflow

```text
Vendor Onboarding
       ↓
Vendor Profile Created
       ↓
Inherent Risk Assessment
       ↓
Vendor Tiering
       ↓
Enhanced Due Diligence
       ↓
Questionnaire
       ↓
Evidence Collection
       ↓
Evidence Review
       ↓
Control Assessment
       ↓
Findings Identified
       ↓
Remediation
       ↓
Remediation Validation
       ↓
Residual Risk Assessment
       ↓
Risk Treatment / Acceptance
       ↓
Vendor Approval
       ↓
Ongoing Monitoring
       ↓
Periodic Reassessment