# TPRM Inherent Risk Scoring Methodology

## 1. Purpose

This methodology establishes a consistent and repeatable approach for assessing the inherent risk associated with a third-party vendor before considering the effectiveness of existing security controls.

The methodology is designed to support:

* Vendor risk classification
* Risk-based due diligence
* Vendor tiering
* Allocation of assessment resources
* Management decision-making
* Consistent treatment of third-party risk

---

## 2. Inherent Risk Definition

**Inherent risk** represents the level of risk associated with a third-party relationship before considering the effectiveness of mitigating controls.

For this assessment:

> **Inherent Risk = Risk exposure arising from the nature of the vendor relationship before control effectiveness is considered.**

This distinction is important because a vendor may present significant inherent exposure while maintaining strong security controls that reduce its residual risk.

---

## 3. Risk Dimensions

The assessment uses five primary dimensions:

| Dimension                   | Description                                                                                         |
| --------------------------- | --------------------------------------------------------------------------------------------------- |
| **Data Sensitivity**        | Sensitivity and confidentiality of information the vendor may process or access                     |
| **Data Volume**             | Scale of information potentially processed or exposed                                               |
| **Business Criticality**    | Potential operational impact if the vendor's service becomes unavailable                            |
| **Access & Integration**    | Level of system, administrative, API, or network access associated with the relationship            |
| **Fourth-Party Dependency** | Dependence on subcontractors or other external providers within the vendor's service delivery chain |

Each dimension is scored from **1 to 5**.

---

## 4. Scoring Scale

| Score | Rating       | General Interpretation                                  |
| ----: | ------------ | ------------------------------------------------------- |
| **1** | Low          | Limited exposure or business impact                     |
| **2** | Low-Moderate | Some exposure with limited potential impact             |
| **3** | Moderate     | Meaningful exposure or business impact                  |
| **4** | High         | Significant exposure or business impact                 |
| **5** | Critical     | Severe exposure or potentially material business impact |

---

## 5. Data Sensitivity Scoring

| Score | Criteria                                                                                                                                  |
| ----: | ----------------------------------------------------------------------------------------------------------------------------------------- |
| **1** | Public or non-sensitive information                                                                                                       |
| **2** | Internal business information with limited sensitivity                                                                                    |
| **3** | Confidential business information or standard personal information                                                                        |
| **4** | Sensitive personal, financial, regulated, or highly confidential information                                                              |
| **5** | Highly sensitive or regulated information where compromise could create severe legal, financial, regulatory, or reputational consequences |

---

## 6. Data Volume Scoring

| Score | Criteria                                                                                        |
| ----: | ----------------------------------------------------------------------------------------------- |
| **1** | Very limited number of records                                                                  |
| **2** | Small volume of records                                                                         |
| **3** | Moderate volume of records                                                                      |
| **4** | Large volume of records                                                                         |
| **5** | Very large-scale processing or concentration of significant organizational/customer information |

The volume threshold should be interpreted in the context of the organization's size and the sensitivity of the information involved.

---

## 7. Business Criticality Scoring

| Score | Criteria                                                                                                       |
| ----: | -------------------------------------------------------------------------------------------------------------- |
| **1** | Non-critical service; disruption has minimal business impact                                                   |
| **2** | Limited operational dependency; reasonable alternatives exist                                                  |
| **3** | Meaningful operational dependency; disruption would affect business processes                                  |
| **4** | Significant dependency; prolonged disruption would materially affect operations                                |
| **5** | Mission-critical dependency; failure could cause severe operational, financial, regulatory, or customer impact |

---

## 8. Access & Integration Scoring

| Score | Criteria                                                                                                                                  |
| ----: | ----------------------------------------------------------------------------------------------------------------------------------------- |
| **1** | No access to organizational systems or sensitive information                                                                              |
| **2** | Limited user-level access with minimal integration                                                                                        |
| **3** | Access to confidential information or moderate system integration                                                                         |
| **4** | Significant data access, API integration, or privileged/vendor access                                                                     |
| **5** | Extensive privileged access, direct connectivity to critical systems, or access capable of materially affecting organizational operations |

---

## 9. Fourth-Party Dependency Scoring

| Score | Criteria                                                                                                          |
| ----: | ----------------------------------------------------------------------------------------------------------------- |
| **1** | Minimal external dependency with limited security impact                                                          |
| **2** | Limited subcontractor dependency                                                                                  |
| **3** | Multiple material subcontractors or moderate dependency                                                           |
| **4** | Significant reliance on critical subcontractors or cloud providers                                                |
| **5** | Extensive or concentrated fourth-party dependency where failure or compromise could materially affect the service |

---

## 10. Overall Inherent Risk Calculation

The five risk dimensions will be scored independently.

The overall inherent risk score will be calculated using the arithmetic mean:

**Inherent Risk Score = (Data Sensitivity + Data Volume + Business Criticality + Access & Integration + Fourth-Party Dependency) ÷ 5**

The resulting score will be rounded to two decimal places.

---

## 11. Inherent Risk Rating

|   Average Score | Inherent Risk Rating |
| --------------: | -------------------- |
| **1.00 – 1.79** | Low                  |
| **1.80 – 2.59** | Low-Moderate         |
| **2.60 – 3.39** | Moderate             |
| **3.40 – 4.19** | High                 |
| **4.20 – 5.00** | Critical             |

---

## 12. Risk Override Criteria

The calculated average score should not be the sole basis for the final risk classification.

A risk override may be considered where a specific characteristic creates a material exposure that is not adequately represented by the average score.

Potential override triggers include:

* Direct access to highly critical production systems
* Processing of highly sensitive regulated information
* Material regulatory dependency
* Significant concentration risk
* Critical single-provider dependency
* Severe data residency or cross-border concerns
* Known significant security concerns
* Material unresolved security findings

Any override must be documented with a clear rationale and approved according to the organization's risk governance process.

---

## 13. Assessment Principles

The assessment follows these principles:

### Risk-Based

The depth of due diligence should be proportionate to the vendor's inherent risk.

### Evidence-Based

Risk conclusions should be supported by documented information and, where appropriate, independent evidence.

### Consistent

The same scoring criteria should be applied consistently across vendors.

### Proportionate

Not every vendor requires the same level of assessment effort.

### Reviewable

Risk scores and decisions should be documented so that another reviewer can understand how the conclusion was reached.

---

## 14. Control Effectiveness

Control effectiveness is **not considered when calculating inherent risk**.

Controls will be evaluated separately during the **Evidence & Control Assessment** stage.

This allows the assessment to distinguish between:

**Inherent Risk → Control Effectiveness → Residual Risk**

This separation prevents strong controls from masking the underlying exposure associated with a vendor relationship.

---

## 15. Methodology Governance

The risk-scoring methodology should be reviewed periodically to ensure that:

* Risk thresholds remain appropriate
* Regulatory requirements are reflected
* Organizational risk appetite is considered
* Emerging third-party risks are incorporated
* Scoring remains consistent across vendor assessments

**Methodology Status:** Active for this case study

**Version:** 1.0

**Assessment Stage:** Session 2 — Inherent Risk Assessment & Vendor Tiering

