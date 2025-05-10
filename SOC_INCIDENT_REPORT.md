# 🛡️ SOC INCIDENT REPORT

**Analyst:** Christopher Amos  
**Date:** May 2025  
**Simulation Lab:** TryHackMe – SOC Level 1 Analyst Simulator  
**Environment:** Simulated SOC ticketing queue with 11 suspicious emails  
**Purpose:** Demonstrate hands-on threat triage and incident response capabilities  

---

## 📄 Executive Summary

This report summarizes the analysis and response to 11 simulated email-based threats received through a SOC ticketing system. Each email was reviewed for indicators of compromise (IOCs), malicious attachments or links, and spoofing techniques. Out of 11 cases, 6 were confirmed phishing attempts involving credential harvesting, malware delivery, or impersonation. All threats were contained, documented, and handled at the Tier 1 level without requiring escalation.

---

## ⏱ Timeline of Events

| Time (UTC) | Action Taken |
|------------|--------------|
| 10:00      | First suspicious email reported by user |
| 10:10      | Began triage and IOC extraction process |
| 10:15–11:30 | Analyzed 11 emails for malicious intent |
| 11:35      | Final ticket closed and documentation completed |

---

## 📌 Indicators of Compromise (IOCs)

| Type        | Example                                  |
|-------------|-------------------------------------------|
| **Sender**  | support@micros0ft-reset[.]com            |
| **Subject** | "Account Suspension Notice – Immediate Action Required" |
| **URL**     | hxxp://security-reset[.]update/link     |
| **Hash**    | 9a5b1c0fcdabeac22e3894578c9c...          |
| **IP**      | 192.0.2.42                               |

*IOCs were compiled using VirusTotal, URLScan, and header analysis.*

---

## ✅ Outcome

- **11 tickets triaged**
- **6 confirmed phishing attempts**
- **5 false positives (newsletters, internal test alerts)**
- **0 escalated to Tier 2**
- All malicious indicators documented and tagged
- User education note prepared for simulated incident follow-up

---

## 🧠 Lessons Learned

- Pattern recognition accelerated triage over time  
- SPF/DKIM failures are strong early flags but must be correlated  
- URLs alone aren’t always malicious — content and intent matter  
- Writing concise, professional notes improves clarity for escalation  
- Working through volume improves confidence in decision-making under pressure

---

🛡️ *Prepared by Christopher Amos – as part of my cybersecurity analyst portfolio to demonstrate practical SOC skills and documentation capabilities.*
