# Security Recommendations

## 1. Overview

This document presents security recommendations based on the findings of th Botium Toys security audit case study.

The recommendations focus on addressing identified security gaps, reducing potential risks and improving the organization's overall security posture.

## 2. Recommendations

### 2.1 Implement Least Privilege and Separation of Duties

**Finding:**
All employees have access to internally stored data. Least privilege and separation of duties have not been implemented.

**Recommended Actions:**

- Restrict access to sensitive information based on employees's job responsibilities.
- Apply the principle of least privilege to user accounts.
- Separate critical responsibilities to reduce the risk of unauthorized actions.
- Review user permissions regularly.
- Remove access when employees no longer require it.

**Expected Outcome:**

Reduced exposure of sensitive information and a lower risk of unauthorized access or misuse of employee accounts.

**Priority:** High

### 2.2 Encrypt Sensitive Customer Information

**Finding:**

Customer Credit Card information is not currently encrypted.

**Recommended Actions:**

- Implement encryption to protect stored payment card information.
- Protect sensitive information during transmission.
- Review how customer payment information is stored and accessed.
- Restrict access to payment card information to authorized personnel.

**Expected Outcome:**

Improved confidentiality of customer information and reduced exposure in the event of unauthorized access.

### 2.3 Implement Data Backups and Disaster Recovery Plans

**Finding:**

Botium Toys does not have backups of critical data or disaster recovery plans.

**Recommended Actions:**

- Establish regular backups of critical business data.
- Store backup copies separately from primary systems.
- Define Backup schedules and retention requirements.
- Develop a disaster recovery plan.
- Test Backup restoration procedures periodically.

**Expected Outcome:**

Improved Business continuity and the ability to recover critical information after data loss or a disruptive event.

### 2.4 Improve Password Management

**Finding:**

The existing password policy has insufficient requirements and there is no centralized password management system.

**Recommended Actions:**

- Update password policies to establish appropriate security requirements.
- Implement a centralized password management solution.
- Enforce secure password practices across employee accounts.
- Review account recovery and password reset procedures.

**Expected Outcome:**

Reduced risk of password-related account compromise and improved account management efficiency.

Priority: High

### 2.5 Implement Intrusion Detection Capabilities

**Finding:**

The organization does not currently have an Intrusion Detection System (IDS).

**Recommended Actions:**

- Evaluate and implement an IDS appropriate for the organization's network.
- Configure detection rules to identify suspicious network activity.
- Establish procedures for reviewing and responding to alerts.
- Periodically review detection rules and system performance.

**Expected Outcome:**

Improved visibility into network activity and a greater ability to identify potential security incidents.

Priority: High

### 2.6 Establish Legacy System Maintenance Procedures

**Finding:**

Legacy systems are monitored and maintained, but there is no regular maintenance schedule and intervention methods are unclear.

**Recommended Actions:**

- Establish a documented maintenance schedule.
- Define procedures for identifying and addressing system issues.
- Keep an inventory of legacy systems and their status.
- Evaluate the possiblity of replacing systems that can no longer be adequately maintained.

**Expected Outcome:**

More consistent maintenance, better visibility into legacy system risks, and reduced exposure to known vulnerabilities.

Priority: Medium

### 2.7 Improve Asset Management

**Finding:**

The organization does not have asset management practices, making it difficult for IT to identify which assets may be at risk.

**Recommended Actions:**

- Maintain an up-to-date inventory of organizational assets.
- Classify assets according to their sensitivity and business importance.
- Idenfity asset owners and responisble departments.
- Document the systems and information that are critical to business operations.
- Review the inventory regularly
 
**Expected Outcome:**

Improved asset visibility and more effective identification, prioritization and management of security risks.

Priority: High

## 3. Implementation Priorities

The following table summarizes the recommended implementation order based on the potential impact of the identified security gaps.

| Priority | Recommended Action |
|---|---|
| High | Restrict access to sensitive information through least privilege and separation of duties. |
| High | Implement encryption for sensitive customer information. |
| High | Establish data backups and disaster recovery plans. |
| High | Improve password policies and centralized password management. |
| High | Implement Intrusion detection capabilites. |
| High | Implement asset identification and classification. |
| Medium | Establish regular legacy system maintenance procedures. |

These priorities represent an analytical recommendation based on the case study findings, not an implementation schedule provided by Botium Toys.

## 4. Conclusion

Botium Toys has several security controls already in place, including a firewall, antivirus software, physical locks, CCTV and fire detection systems.

However, significant gaps remain in access management, data protection, backup and recovery capabilities, intrusion detection and asset management.

Addressing these weaknesses should be a priority to reduce the organization's overall risk, improve its security posture and strengthen its ability to protect customer information and maintain business operations.

## 5. Assessment Limitations

These recommendations are based on the information provided in the Google Cybersecurity Professional Certificate case study. They have not been validated through independent technical testing or implementation.
