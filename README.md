# Virtual-Work-Experience-Forage
# Forage – Cybersecurity Risk Assessment

## 📌 Overview

This project was completed as part of a **Forage virtual work experience program** focused on cybersecurity risk assessment and security operations.

The project involved analysing a simulated organisation, identifying cybersecurity risks and vulnerabilities, assessing their potential impact, and recommending appropriate security controls and mitigations.

The scenario covered two simulated organisations:

* **Orion Health Services** – a healthcare technology provider experiencing a ransomware attack.
* **RetailNova Pty Ltd** – a retail organisation with e-commerce, cloud, POS, CRM, ERP, and third-party integrations.

> **Note:** These are simulated scenarios provided as part of the Forage virtual work experience and do not represent real client engagements.

---

## 🎯 Objectives

The main objectives of the project were to:

* Identify important organisational assets
* Identify relevant cybersecurity threats
* Identify potential vulnerabilities
* Assess cybersecurity risks
* Evaluate likelihood and business impact
* Calculate inherent and residual risk
* Prioritise risks using a 5×5 risk matrix
* Recommend appropriate security controls and mitigations
* Assess the potential business impact of cybersecurity incidents

---

## 🔐 Key Cybersecurity Concepts

### Risk Assessment

The assessment used:

**Risk Rating = Likelihood × Consequence**

Likelihood was assessed on a scale from **1–5**:

| Rating | Likelihood     |
| ------ | -------------- |
| 1      | Rare           |
| 2      | Unlikely       |
| 3      | Possible       |
| 4      | Likely         |
| 5      | Almost Certain |

Consequence was also assessed from **1–5**:

| Rating | Consequence   |
| ------ | ------------- |
| 1      | Insignificant |
| 2      | Minor         |
| 3      | Moderate      |
| 4      | Major         |
| 5      | Extreme       |

The resulting scores were mapped to the provided **5×5 cybersecurity risk matrix** to determine the overall risk level.

---

## 🦠 Scenario 1 – Ransomware Incident

The Orion Health Services scenario involved a ransomware attack initiated through a **phishing email containing a malicious Excel attachment**.

### Key findings

* Employee credentials were compromised
* Mimikatz was used for credential harvesting
* A suspicious overseas login was identified
* Files were encrypted using the `.orionlock` extension
* File servers and HR/Finance systems were affected
* The backup server was partially encrypted
* Employee payroll records and patient appointment information were potentially compromised

### Recommended controls

* Phishing-awareness training
* Strong email filtering
* Multi-factor authentication (MFA)
* Credential protection
* Network segmentation
* Endpoint monitoring
* Secure and isolated backups
* Incident response procedures

---

## 🛒 Scenario 2 – RetailNova Risk Assessment

The RetailNova scenario involved a large retail organisation operating:

* E-commerce website
* Mobile application
* Cloud-connected POS systems
* Salesforce CRM
* SAP ERP
* AWS infrastructure
* Third-party logistics, marketing, and loyalty services

### Key risks identified

#### 1. E-commerce Customer Data Breach

**Threat:** External cybercriminals

**Assets at risk:**

* Customer personal information
* Purchase history
* Loyalty data
* Payment tokens

**Key mitigations:**

* Vulnerability scanning
* Penetration testing
* Secure software development
* MFA
* Security monitoring

#### 2. Phishing and Credential Compromise

**Threat:** Cybercriminals using phishing attacks

**Assets at risk:**

* Employee accounts
* Salesforce
* SAP
* AWS
* Internal systems

**Key mitigations:**

* MFA
* Phishing simulations
* Email filtering
* Security awareness training
* Suspicious-login monitoring

#### 3. Third-Party Data Breach

**Threat:** Compromised third-party vendor

**Assets at risk:**

* Customer information
* Marketing data
* Loyalty data

**Key mitigations:**

* Third-party security assessments
* Vendor security requirements
* Data minimisation
* Vendor monitoring
* Incident notification requirements

---

## 📊 Risk Assessment Process

The assessment followed this general process:

```text
Identify Assets
      ↓
Identify Threats
      ↓
Identify Vulnerabilities
      ↓
Identify Existing Controls
      ↓
Assess Likelihood
      ↓
Assess Consequence
      ↓
Calculate Inherent Risk
      ↓
Apply Mitigations
      ↓
Calculate Residual Risk
      ↓
Prioritise Risks
```

---

## 🛠️ Skills Demonstrated

* Cybersecurity risk assessment
* Threat identification
* Vulnerability identification
* Asset identification
* Risk analysis
* Risk prioritisation
* 5×5 risk matrices
* Likelihood and impact assessment
* Security controls
* Risk mitigation
* Incident impact assessment
* Ransomware analysis
* Phishing analysis
* Third-party risk
* Security awareness
* Basic incident response

---

## 📁 Project Deliverables

This repository contains my completed work from the Forage cybersecurity virtual work experience, including:

* Security breach impact assessment
* Threat and vulnerability identification
* Cybersecurity risk assessments
* Risk prioritisation
* Recommended security mitigations

---

## 🎓 Learning Outcome

This project provided practical experience in approaching cybersecurity from a **risk-based perspective**, rather than focusing only on technical vulnerabilities.

It helped develop an understanding of how cybersecurity risks can affect:

* Confidentiality
* Integrity
* Availability
* Business operations
* Financial performance
* Customer data
* Regulatory and reputational exposure

---

## ⚠️ Disclaimer

This project was completed using **simulated scenarios provided by Forage for educational purposes**. The organisations and incidents described in this repository are fictional/simulated and should not be interpreted as real-world security assessments.

## 📚 Program

**Forage – Cybersecurity Virtual Work Experience**

Focus areas: **Cybersecurity Operations, Risk Assessment & Threat Identification**
