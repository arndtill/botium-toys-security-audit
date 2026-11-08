# Risk Assessment

## 1. Overview

This report evaluates the security risks identified in the Botium Toys case study.

The assessment is based on the organization's asset inventory, existing security controls and compliance practices. Its purpose is to identify security gaps, evaluate their potential impact and establish areas requiring improvement.

## 2. Overall Risk Assessment

The original case study assigns Botium Toys an overall risk score of 8/10, indicating a fairly high level of risk.

This rating is attributed to inadequate asset management, missing security controls and insufficient adherence to compliance best practices.

The case study identifies two main areas of concern:

- **Asset Loss Impact:** Medium. IT does not have sufficient knowledge of which assets may be at risk, making it difficult to determine the potential consequences of asset loss.
- **Regulatory and Compliance Risk:** High. Incomplete security controls and insufficient compliance practices may expose the organization to regulatory penalties and other consequences.

## 3. Identified Risks

### 3.1 Excessive Internal Access

**Evidence:**

- All employees have access to internally stored data.
- Least privilege has not been implemented.
- Separation of duties has not been established.

**Potential Impact:**

Unauthorized or unnecessary access could expose sensitive customer information, including personally identifiable information (PII/SPII) and payment card data. It also increases the potential impact of compromised employee accounts or malicious insider activity.

**Risk Consideration:** High.

### 3.2 Unprotected Payment Card Information

**Evidence:**

- Customer Credit Card information is accepted, processed, transmitted and stored locally in the internal database.
- Encryption is not implemented to protect this information.
- Access restrictions are insufficient.

**Potential Impact:**

Exposure of Payment Card information could lead to financial losses, damage to customer trust and potential PCI DSS compliance issues.

**Risk Consideration:** High.

### 3.3 Lack of Backup and Disaster Recovery Capabilities

**Evidence:**

 - Critical data is not backed up.
 - No disaster recovery plans are currently in place.

 **Potential Impact:**
 
 A security incident, hardware failure or other disruptive event could result in permanent data loss and prolonged interruption of business operations.

 **Risk Consideration:** High

 ### 3.4 Inadequate Password Management

 **Evidence:**

 - The existing password policy does not meet current minimum complexity expectations.
 - No centralized password management system enforces minimum requirements.
 - Password resets and recovery tickets sometimes affect employee productivity.

 **Potential Impact:**

 Weak password practices may increase the likelihood of account compromise. Inefficient password management also creates operational difficulties.

 **Risk Consideration:** Medium

 ### 3.5 Insufficient Intrusion Detection
 
 **Evidence:**

 - No Intrusion Detection System (IDS) installed.

 **Potential Impact:**

 Suspicious network activity may go undetected, reducing organization's ability to identify potential security incidents in a timely manner.

 **Risk Consideration: High**

 ### 3.6 Inadequate Legacy System Maintenance Procedures

 **Evidence:**

 - Legacy systems require manual monitoring and maintenance.
 - There is no regular maintenance schedule.
 - Intervention methods are unclear.

 **Potential Impact:**

 Inconsistent maintenance may allow vulnerabilities and outdated configurations to remain unaddressed, increasing exposure to security incidents and operational disruptions.

 **Risk Consideration:** Medium

 ### 3.7 Inadequate Asset Management

 **Evidence:**

 - Asset Management practices are insufficient.
 - IT may not know which assets are at risk.
 - Asset identification and classification require improvement.

 **Potential Impact:**

  The organization may struggle to identify vulnerabilities, prioritize security controls and determine the consequences of asset loss.

 **Risk Consideration:** High

 ## 4. NIST Cybersecurity Framework - Identify

 The findings are particularly relevant to the Identify function of the NIST Cybersecurity Framework (NIST CSF).

 This function emphasizes understanding organizational assets, systems, data and related cybersecurity risks.

 Based on the case study, Botium Toys should prioritize:

 - Identifying and maintaining an accurate inventory of organizational assets.
 - Classifying assets according to their sensitivity and business importance.
 - Determining the potential impact of asset loss.
 - Identifying systems and information that require additional protection.
 - Understanding how asset-related risks affect business continuity.

 Improving these practices would lead to a stronger foundation for managing the organization's security risks.

 ## 5. Risk Assessment Summary

 The assessment identifies several significant weaknesses in Botium Toys's security posture.

 The most critical areas requiring attention are:

 1. Excessive access to internally stored information.
 2. Lack of encryption for Customer Payment Card information.
 3. Absence of critical data backups and disaster recovery plans.
 4. Insufficient asset identification and classification.
 5. Lack of intrusion detection capabilities.

 These findings support the overall risk score of 8/10 provided in the case study.

 ## 6. Assessment Limitations

 This assessment is only based on the information provided in the original Google Cybersecurity Professional Certificate case study.

 Individual risk considerations represent an analytical assessment of the reported findings. They are not independently calculated risk scores or results from technical testing.
