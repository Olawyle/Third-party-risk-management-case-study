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

