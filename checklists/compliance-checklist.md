# Compliance Checklist

## 1. Overview

This checklist evaluates Botium Toys's compliance practices against the requirements and criteria identified in the original case study.

The assessment covers the Payment Card Industry Data Security Standard (PCI DSS), the General Data Protection Regulation (GDPR) and System and Organization Controls (SOC).

## 2. PCI DSS Assessment

PCI DSS establishes security requirements for organizations that accept, process, transmit or store payment card information.

| Requirement | Status | Evidence and Observations |
|---|---|---|
| Only authorized users have access to customers's credit card information. | Does Not Meet | All employees have access to internally stored data and may access cardholder information. |
| Credit Card Information is stored, accepted, processed and transmitted in a secure environment | Does Not Meet | The case identifies insufficient access restrictions and a lack of encryption for customer credit card information. |
| Encryption procedures are implemented for payment information | Does Not Meet | Customer Credit Card information is not currently encrypted. |
| Secure password management policies are implemented. | Does Not Meet | A password policy exists, but its requirements are insufficient. There is also no centralized password management system. |

## 3. GDPR Assessment

The General Data Protection Regulation (GDPR) establishes requirements for protecting the personal data and privacy of individuals in the European Union.

| Requirement | Status | Evidence and Observations |
|---|---|---|
| EU customers's data is kept private and secure | Does not Meet | All employees have access to internally stored data, and customer credit card information is not encrypted. |
| A plan exists to notify EU customers within 72 hours of a data breach | Meets | The organization has a plan to notify EU customers within 72 hours of a security breach. |
| Data is properly classified and inventoried | Does Not Meet | Asset management is inadequate and IT may not know whic assets are at risk. |
| Privacy policies, procedures and processes are documented and maintained. | Meets | The organization has developed and enforces privacy policies, procedures and processes among IT and other employees. |

## 4. SOC Assessment

System and Organization Controls (SOC) are used to evaluate controls related to the security, confidentiality, processing integrity and availability of information.

| Requirement | Status | Evidence and Observations |
|---|---|---|
| User access policies are established | Does Not Meet | Least Privilege and separation of duties have not been implemented. All employees have access to internally stored data. |
| Sensitive PII/SPII is kept confidential and private. | Does Not Meet | All employees have access to internally stored data, including potentially sensitive customer information. |
| Data integrity is maintained through consistent, complete, accurate and validated information. | Meets | IT has implemented controls to ensure data integrity. |
| Data is available to authorized individuals. | Partially Meets | IT has ensured data availability, but access is not sufficiently restricted through least privilege. |

### 5. Assessment Summary

The assessment identifies significant gaps in Botium Toys's compliance practices.

PCI DSS:

- Access to payment card information is not sufficiently restricted.
- Credit card information is not encrypted.
- Password management practices require improvement.

GDPR:

- Customer data protection and asset classification require improvement.
- The organization has a 72-hour breach notification plan.
- Privacy policies and procedures are documented and enforced.

SOC:

- User access restrinctions are insufficient.
- Sensitive customer information is not adequately protected.
- Data integrity controls and availability measures are reported as implemented.

## 6. Assessment Limitations

This assessment is only based on the information provided in the case study. No independent compliance audit, technical testing, or legal review was performed.

The results indicate potential compliance gaps and should not be intepreted as a formal determination of regulatory compliance.
