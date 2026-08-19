# Inherent Risk Assessment

## 1. Assessment Overview

**Vendor:** CloudServe Technologies Ltd.
**Client:** FinServe Financial Services Ltd.
**Assessment Type:** Initial Inherent Risk Assessment
**Assessment Stage:** Session 2
**Methodology Version:** 1.0
**Assessment Status:** In Progress

---

## 2. Risk Dimension 1 — Data Sensitivity

### 2.1 Assessment Question

**What is the sensitivity of the information CloudServe may process, store, or access on behalf of FinServe?**

### 2.2 Relevant Information

Based on the vendor profile documented during Session 1, CloudServe may process:

* Customer identification information
* Customer contact information
* Customer service records
* Employee/user information
* Business operational information
* Potentially financial or account-related information

The exact data elements remain subject to vendor and business-owner validation.

### 2.3 Risk Considerations

The proposed service may involve confidential customer and business information.

Unauthorized access, disclosure, modification, or loss of this information could potentially result in:

* Customer privacy impact
* Financial loss
* Regulatory or compliance consequences
* Reputational damage
* Operational disruption

The potential processing of financial or other sensitive information increases the significance of the data exposure.

### 2.4 Assigned Score

**Data Sensitivity Score: 4 / 5 — High**

### 2.5 Rationale

A score of **4** is assigned because CloudServe may process confidential customer information and potentially financial or other sensitive information on behalf of FinServe.

The potential sensitivity of the information creates a significant confidentiality and privacy exposure if the vendor's security controls were compromised.

The score remains subject to validation of the exact information categories processed by CloudServe. If the final data inventory demonstrates that highly sensitive or regulated information is routinely processed, the score may require escalation to **5 — Critical**.

### 2.6 Evidence Required for Validation

The following information should be obtained during due diligence:

* Data inventory
* Data-flow diagram
* Data classification information
* Data processing description
* Data Processing Agreement (DPA), where applicable
* Privacy/security documentation
* Evidence of encryption controls
* Data retention and deletion requirements

**Assessment Status:** Provisionally Assessed

**Score:** 4 / 5

## 3. Risk Dimension 2 — Data Volume

### 3.1 Assessment Question

**What is the scale of information that CloudServe may process or store on behalf of FinServe?**

### 3.2 Relevant Information

The business scenario established during Session 1 indicates that CloudServe may process information relating to approximately:

**500,000 customer and employee records**

This figure represents the current estimated population associated with the proposed service and remains subject to validation.

### 3.3 Risk Considerations

The volume of information is an important component of third-party risk because a compromise affecting a large population can increase the potential scale of:

* Unauthorized disclosure
* Privacy impact
* Regulatory exposure
* Customer impact
* Financial loss
* Incident response requirements
* Reputational damage

The concentration of a large volume of records within a single third-party platform also increases the potential impact of a significant security incident.

### 3.4 Assigned Score

**Data Volume Score: 5 / 5 — Critical**

### 3.5 Rationale

A score of **5** is assigned because the proposed service may process approximately **500,000 customer and employee records**, representing a significant concentration of organizational and personal information.

A compromise affecting the platform could therefore affect a substantial number of individuals simultaneously.

The volume also increases the potential scale of regulatory, operational, financial, and reputational consequences following a material security incident.

The score is based on the current scenario estimate and should be validated against the actual number of records expected to be processed during the vendor onboarding process.

### 3.6 Evidence Required for Validation

The following information should be obtained:

* Estimated number of records processed
* Expected data growth over the contract period
* Data inventory
* Record categories and volumes
* Data retention periods
* Backup volumes
* Data deletion procedures
* Contractual limitations on data processing

**Assessment Status:** Provisionally Assessed

**Score:** 5 / 5

## 4. Risk Dimension 3 — Business Criticality

### 4.1 Assessment Question

**How significant would the business impact be if CloudServe's services became unavailable or materially degraded?**

### 4.2 Relevant Information

The Session 1 assessment established that CloudServe is proposed to support:

* Customer relationship management
* Customer service workflows
* Operational workflow processing
* Case and service request management
* Internal reporting
* Business process coordination

The vendor may therefore become an important dependency for both customer-facing and internal operational activities.

### 4.3 Business Impact Considerations

A prolonged CloudServe outage could result in:

* Disruption to customer service activities
* Delays in operational workflows
* Increased manual processing
* Reduced employee productivity
* Potential customer dissatisfaction
* Potential financial impact
* Potential regulatory or compliance implications
* Reputational impact

The severity of the actual impact will depend on the organization's recovery requirements, available alternatives, and the extent to which CloudServe becomes embedded within critical processes.

### 4.4 Assigned Score

**Business Criticality Score: 4 / 5 — High**

### 4.5 Rationale

A score of **4** is assigned because CloudServe is expected to support important customer-facing and operational processes.

A prolonged disruption could materially affect FinServe's ability to perform these activities and could create operational, customer, financial, regulatory, and reputational consequences.

A score of **5 — Critical** has not been assigned because the assessment has not yet established that CloudServe supports mission-critical processes for which no viable alternative or workaround exists.

The final score should be validated against:

* Maximum Tolerable Downtime (MTD)
* Recovery Time Objective (RTO)
* Recovery Point Objective (RPO)
* Service Level Agreement (SLA)
* Availability of alternative systems
* Manual workaround capabilities
* Business continuity arrangements

### 4.6 Evidence Required for Validation

The following information should be obtained:

* Business Impact Analysis (BIA)
* Business owner's criticality assessment
* Contractual SLA
* RTO and RPO requirements
* Maximum Tolerable Downtime
* Business continuity documentation
* Disaster recovery commitments
* Alternative service/workaround assessment
* Vendor availability and uptime history

**Assessment Status:** Provisionally Assessed

**Score:** 4 / 5

## 5. Risk Dimension 4 — Access & Integration

### 5.1 Assessment Question

**What level of access, system integration, connectivity, or administrative privilege may CloudServe have within FinServe's environment?**

### 5.2 Relevant Information

The proposed CloudServe deployment may involve:

* Authenticated user access
* API-based system integration
* Vendor technical/support access
* Administrative access to the SaaS environment
* Exchange of information between CloudServe and FinServe systems

The exact architecture and access model have not yet been validated.

### 5.3 Access Risk Considerations

Third-party access may introduce risks including:

* Compromise of vendor credentials
* Excessive user privileges
* Unauthorized administrative activity
* Insecure API integrations
* Compromised integration credentials or tokens
* Uncontrolled remote support access
* Insufficient monitoring of vendor activity
* Unauthorized access to FinServe information

The potential impact increases where a vendor can access sensitive information or interact with systems supporting important business processes.

### 5.4 Assigned Score

**Access & Integration Score: 4 / 5 — High**

### 5.5 Rationale

A score of **4** is assigned because the proposed relationship may involve API-based integration, vendor support access, and administrative access associated with the SaaS environment.

These characteristics create a significant third-party attack surface and could increase the impact of a compromise involving CloudServe accounts, credentials, integration mechanisms, or privileged personnel.

A score of **5 — Critical** has not been assigned because the current assessment does not establish that CloudServe will have direct privileged access to FinServe's most critical production systems or unrestricted network connectivity.

The final score should be validated against the approved technical architecture and access model.

### 5.6 Key Validation Questions

The following questions should be answered before finalizing the risk assessment:

1. Will CloudServe personnel have access to FinServe data?
2. Will CloudServe personnel have privileged administrative access?
3. Will the platform integrate directly with FinServe production systems?
4. What authentication mechanism will be used?
5. Will Single Sign-On (SSO) and Multi-Factor Authentication (MFA) be mandatory?
6. How will API credentials and secrets be managed?
7. Will network connectivity be required?
8. Will remote vendor support access be permitted?
9. How will privileged activity be logged and monitored?
10. How quickly can vendor access be revoked?

### 5.7 Evidence Required for Validation

The following evidence should be requested or reviewed:

* High-level architecture diagram
* Data-flow diagram
* Access control model
* Privileged access management procedures
* SSO/MFA documentation
* API security documentation
* Network connectivity requirements
* Vendor support access procedure
* Logging and monitoring documentation
* Access review procedures

**Assessment Status:** Provisionally Assessed

**Score:** 4 / 5

## 6. Risk Dimension 5 — Fourth-Party Dependency

### 6.1 Assessment Question

**To what extent does CloudServe depend on subcontractors, cloud infrastructure providers, or other external service providers to deliver the service to FinServe?**

### 6.2 Relevant Information

CloudServe operates as a Software-as-a-Service provider and may rely on external providers to support areas such as:

* Cloud infrastructure
* Data storage
* Backup and disaster recovery
* Security monitoring
* Customer support
* Identity and authentication
* Software development
* Other technology services

The complete list of material subcontractors and fourth parties has not yet been validated.

### 6.3 Fourth-Party Risk Considerations

A significant dependency on external providers may introduce additional risks, including:

* Security weaknesses within a subcontractor
* Cloud infrastructure outages
* Unauthorized access to FinServe information
* Fourth-party data breaches
* Cross-border data processing
* Concentration risk
* Inadequate contractual protections
* Delayed incident notification
* Dependency on a single critical service provider

The impact of these risks depends on the criticality of the fourth party and the level of control and oversight maintained by CloudServe.

### 6.4 Assigned Score

**Fourth-Party Dependency Score: 4 / 5 — High**

### 6.5 Rationale

A score of **4** is assigned because CloudServe's SaaS delivery model is expected to involve material dependencies on external infrastructure and service providers.

A significant failure or security incident involving a critical fourth party could affect CloudServe's availability, confidentiality, integrity, or ability to deliver services to FinServe.

A score of **5 — Critical** has not been assigned because the current assessment has not established that CloudServe has a highly concentrated dependency on a single fourth party or that its critical subcontractors have unrestricted access to FinServe information.

The score should be reassessed once CloudServe provides its current material subprocessor inventory and supporting assurance information.

### 6.6 Key Validation Questions

The following questions should be addressed during due diligence:

1. Which cloud infrastructure providers does CloudServe use?
2. Where are FinServe's data and backups hosted?
3. Which subcontractors can access FinServe information?
4. Which fourth parties are considered critical to service delivery?
5. Does CloudServe perform risk assessments before engaging material subcontractors?
6. What security requirements are imposed contractually on fourth parties?
7. How does CloudServe monitor fourth-party security?
8. How is FinServe notified of material subcontractor changes?
9. Are critical fourth parties included in business continuity and disaster recovery planning?
10. Does CloudServe have contingency arrangements for the failure of a critical fourth party?

### 6.7 Evidence Required for Validation

The following evidence should be requested:

* Current subprocessor/subcontractor list
* Fourth-party risk management procedure
* Material subcontractor risk assessments
* Cloud provider assurance reports
* Relevant SOC 2 or ISO 27001 reports
* Data-processing agreements
* Contractual security requirements
* Fourth-party business continuity arrangements
* Material change-notification process

**Assessment Status:** Provisionally Assessed

**Score:** 4 / 5

## 7. Overall Inherent Risk Calculation

### 7.1 Risk Score Summary

| Risk Dimension          |  Score | Rating   |
| ----------------------- | -----: | -------- |
| Data Sensitivity        |      4 | High     |
| Data Volume             |      5 | Critical |
| Business Criticality    |      4 | High     |
| Access & Integration    |      4 | High     |
| Fourth-Party Dependency |      4 | High     |
| **Total**               | **21** | —        |

### 7.2 Calculation

The methodology established that the overall inherent risk score is calculated using the arithmetic mean of the five risk dimensions.

**Inherent Risk Score = (Data Sensitivity + Data Volume + Business Criticality + Access & Integration + Fourth-Party Dependency) ÷ 5**

**Inherent Risk Score = (4 + 5 + 4 + 4 + 4) ÷ 5**

**Inherent Risk Score = 21 ÷ 5**

**Inherent Risk Score = 4.20**

### 7.3 Overall Inherent Risk Rating

Based on the approved scoring methodology:

|     Score Range | Risk Rating  |
| --------------: | ------------ |
|     1.00 – 1.79 | Low          |
|     1.80 – 2.59 | Low-Moderate |
|     2.60 – 3.39 | Moderate     |
|     3.40 – 4.19 | High         |
| **4.20 – 5.00** | **Critical** |

**Overall Inherent Risk Score: 4.20 / 5.00**

**Overall Inherent Risk Rating: CRITICAL**

### 7.4 Risk Interpretation

The assessment indicates that the proposed CloudServe relationship presents a **Critical inherent risk profile before considering the effectiveness of mitigating controls**.

The primary drivers are:

* Potential processing of sensitive customer and business information
* Potential exposure involving approximately 500,000 records
* Significant business dependency
* Potential API and administrative/vendor access
* Dependence on external infrastructure and subcontractors

The Critical rating reflects the exposure associated with the nature of the proposed vendor relationship. It does **not** indicate that CloudServe's security controls are ineffective.

Control effectiveness will be evaluated separately during the **Evidence & Control Assessment** stage.

### 7.5 Risk Classification Decision

**Final Inherent Risk Rating: CRITICAL**

**Inherent Risk Score: 4.20 / 5.00**

**Assessment Basis:** Five-dimensional risk scoring methodology defined in Version 1.0.

**Control Effectiveness Considered:** No

**Residual Risk Considered:** No

### 7.6 Due Diligence Implication

Given the Critical inherent risk classification, CloudServe should be subject to **enhanced third-party due diligence** before the relationship is approved.

The assessment should require, at minimum:

* Detailed security questionnaire
* Independent security assurance evidence
* Review of relevant SOC 2 Type II or ISO 27001 evidence where available
* Penetration testing assurance
* Access control assessment
* Data protection and privacy assessment
* Business continuity and disaster recovery assessment
* Incident response assessment
* Fourth-party/subprocessor assessment
* Contractual security requirements
* Ongoing monitoring requirements

The final due diligence scope should remain risk-based and proportionate to the actual services, data, access, and regulatory exposure confirmed during validation.

### 7.7 Important Risk Distinction

The Critical inherent risk rating should not be interpreted as a final determination that the vendor is unacceptable.

The TPRM lifecycle will continue through:

**Inherent Risk → Due Diligence → Control Assessment → Risk Treatment → Residual Risk → Risk Decision**

A vendor with Critical inherent risk may ultimately have an acceptable residual risk if appropriate controls are demonstrated and validated.

### 7.8 Assessment Status

**Inherent Risk Assessment:** Complete

**Overall Score:** 4.20 / 5.00

**Overall Rating:** Critical

**Next Stage:** Vendor Tiering & Due Diligence Requirements
