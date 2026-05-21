# Cybersecurity Risk Assessment of a Social Media Platform

## 📌 Overview

This project presents a structured cybersecurity risk assessment for a social media platform based on the NIST SP 800-30 framework.

The objective is to identify, analyze, and mitigate risks affecting system confidentiality, integrity, and availability.

---

## 🧠 Methodology

The project follows a complete risk management lifecycle:

1. Asset Identification
2. Threat Identification
3. Vulnerability Identification
4. Risk Identification
5. Risk Analysis (Likelihood × Impact)
6. Risk Evaluation
7. Risk Treatment
8. Control Implementation

---

## 🏗️ System Description

The analyzed system is a social media platform supporting:

* User authentication
* Content sharing (posts, images, videos)
* Messaging and interaction
* Data storage and analytics

---

## 🔐 Identified Assets

* User Database
* Authentication Server
* Web Application
* Media Storage
* Messaging System
* Logging System
* API Services

---

## ⚠️ Key Risks

| Risk | Description                  |
| ---- | ---------------------------- |
| R1   | Data Breach in User Database |
| R2   | Unauthorized Access          |
| R3   | Malware Injection            |
| R4   | API Abuse                    |
| R5   | Media Data Exposure          |
| R6   | Insider Misuse               |
| R7   | DDoS Attack                  |

---

## 📊 Risk Analysis

Risks were evaluated using:

* Likelihood scale (1–5)
* Impact scale (1–5)

Example:
Risk Score = Likelihood × Impact

---

## 🛡️ Risk Treatment

| Risk | Treatment                              |
| ---- | -------------------------------------- |
| R1   | Mitigate (Encryption + Access Control) |
| R2   | Mitigate (MFA)                         |
| R3   | Mitigate (Input Validation)            |
| R4   | Mitigate (Rate Limiting)               |
| R5   | Mitigate (Secure Configurations)       |
| R6   | Accept (Monitoring)                    |
| R7   | Transfer (Cloud DDoS Protection)       |

---

## 🔧 Implemented Controls

* Data Encryption
* Multi-Factor Authentication (MFA)
* Role-Based Access Control (RBAC)
* Input Validation
* Web Application Firewall (WAF)
* Rate Limiting
* Logging & Monitoring
* SIEM Integration

---

## 🧱 Security Approach

The project applies a **layered security model**:

* Identity & Access Layer → MFA, RBAC
* Application Layer → Input Validation, WAF
* Data Layer → Encryption
* Monitoring Layer → Logging, SIEM
* Perimeter Layer → DDoS Protection

---

## 🛠️ Tools Used

* SimpleRisk (Risk Management Platform)
* LaTeX (Report Formatting)

---

## 📂 Repository Structure

```
├── report/
├── screenshots/
├── latex/
└── README.md
```

---

## 📸 Screenshots

Screenshots from SimpleRisk demonstrate:

* Asset creation
* Risk register
* Risk scoring
* Mitigation entries
* Control implementation
* Asset-control mapping

---

## 🎯 Key Takeaways

* Structured risk management is essential for modern systems
* Mapping risks to controls ensures effective mitigation
* Layered security improves resilience

---

## 👨‍💻 Authors

* Amer Ashoush
* Ali Aboela
* Omar Maher

---

## 📜 License

This project is for academic purposes.
