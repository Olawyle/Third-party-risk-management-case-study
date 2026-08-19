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
