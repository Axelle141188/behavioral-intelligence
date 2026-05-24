# 🧠 Behavioral Intelligence — Fraud Pattern Analysis

> *"Understanding why people get defrauded is just as important as understanding how."*

---

## Overview

This repository maps the main financial fraud and social engineering patterns, analyzed through two complementary lenses: the **psychology of manipulation** and **detectable technical indicators**.

The goal is not simply to describe attacks — it is to understand the human mechanisms that make them possible.

---

## 📊 Fraud Pattern Table

| Fraud Type | Psychological Trigger | Victim Behavior | Technical Indicators | Detection Opportunities |
|---|---|---|---|---|
| **Internal Accounting Fraud** (e.g. Wirecard) | Halo effect, groupthink, confirmation bias | Blind trust, absence of critical thinking, collective validation | Revenue concentrated in opaque regions, non-rotating auditor, funds never directly verified | Auditor rotation, Bank Confirmation procedure, whistleblower protection |
| **APP Fraud / Fake Banking Advisor** | Artificial urgency, authority impersonation, illusion of control | Acute stress, obedience to authority, fast action without reflection | SMS sender name spoofing, transfers to recently opened relay accounts, inbound call followed by unusual transfer | Behavioral detection, independent verification callback, Naegelen Law anti-spoofing |
| **Insider Threat** (e.g. Valdy / CCF) | Automatic institutional trust, invisibility of temporary status | Absence of oversight, presumption of good faith toward the employee | Repeated Master Data modifications, unsolicited card orders, multiple payment limit increases | UEBA, Four-Eyes Principle, Segregation of Duties, automatic client alerts |
| **Romance Scam** | Emotional isolation, need for attachment, progressive trust-building | Emotional dependency, sharing of personal information, repeated voluntary transfers | Recently created social media profile, refusal of video or voice calls, progressive financial requests | Detection of unusual international transfers, banking behavioral alerts, reporting via Stop-Escroqueries |
| **Banking Phishing** | Fear, urgency, institutional authority | Immediate link click, credential entry without verification, panic response | Suspicious URL mimicking the real bank, spoofed email header, fake login page | Anti-phishing filters, Strong Customer Authentication (SCA/PSD2), client awareness |
| **Deepfake Fraud** | Visual and auditory trust, hierarchical authority | Compliance without verification, fast action under apparent pressure from a superior | AI-generated video or voice, urgent transfer request outside normal channels, unsolicited contact | Independent verification via separate channel, anti-fraud protocols for large transfers, employee training |
| **Pig Butchering Scam** | Progressive emotional bond, greed, FOMO (Fear Of Missing Out) | Progressive and voluntary investments, borrowing to invest further, denial in the face of warning signs | Fictitious crypto platform, gains displayed but not withdrawable, initial contact via "wrong number" on messaging app | Reporting of unregulated platforms, banking alerts on repeated crypto transfers, financial education |

---

## 🔁 Cross-Cutting Patterns

Beyond individual cases, three psychological mechanisms recur systematically across almost every form of fraud:

**1. Artificial Urgency**  
Creating time pressure short-circuits critical thinking. Whether it is an alarming text message or a fake CFO on a Zoom call, urgency is the universal tool of manipulation.

**2. Legitimacy Impersonation**  
Posing as a recognized authority — a bank, a senior manager, an official platform — exploits the obedience reflex documented by Milgram. Perceived legitimacy disables critical judgment.

**3. Victim Isolation**  
Cutting the victim off from their support network — "don't tell anyone", an exclusive online relationship, professional confidentiality — is a constant across fraud types. An active support network remains the strongest protection against manipulation.

---

## 📚 Methodological Note

> *"This analysis draws on recognized threat intelligence frameworks (MITRE ATT&CK, ENISA reports), enriched with a behavioral and psychological dimension. The goal is to bridge technical pattern recognition with an understanding of human bias — because fraud is, above all, a human problem."*

---

## 🔗 Related Resources

- [Fraud Case Files](https://github.com/Axelle141188/fraud-case-files) — In-depth analysis of real fraud cases
- [AI Fraud Detection System](https://github.com/Axelle141188/ai-fraud-detection) — ML-based fraud detection project
- [SEPA Social Engineering Detector](https://github.com/Axelle141188/sepa-social-engineering-detector) — NLP-based detector for SEPA fraud patterns
- [Threat Intelligence Dashboard](https://github.com/Axelle141188/threat-intelligence-dashboard) — Real-time threat monitoring system
