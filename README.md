# 🛡️ SOC Analyst Portfolio — WONDERSOFCODE

![LetsDefend](https://img.shields.io/badge/LetsDefend-Practitioner-blue)
![Status](https://img.shields.io/badge/Status-Actively%20Learning-brightgreen)
![Focus](https://img.shields.io/badge/Focus-Blue%20Team%20%7C%20SOC-red)

I'm an aspiring **SOC Analyst / Blue Team practitioner** building hands-on incident response and monitoring skills through [LetsDefend](https://letsdefend.io). This repository is my public portfolio: real investigation write-ups, completed learning paths & certificates, and study notes — organized so a recruiter or hiring manager can quickly see how I think through security incidents.

> ⚠️ **A note on content:** All analysis, conclusions, and write-ups here are my own work and wording. I do not reproduce LetsDefend's proprietary alert data, question banks, or answer keys verbatim — this repo reflects my *methodology and reasoning*, in line with LetsDefend's Terms of Use.

---

## 📚 Table of Contents

- [About Me](#-about-me)
- [Skills & Tools](#-skills--tools)
- [Repository Architecture](#-repository-architecture)
- [Learning Paths & Certificates](#-learning-paths--certificates)
- [Investigation Write-ups](#-investigation-write-ups)
- [Notes & Cheatsheets](#-notes--cheatsheets)
- [Contact](#-contact)

---

## 👤 About Me

Currently a Information Security student building hands-on SOC experience 
through LetsDefend's simulated environment. I'm working toward a Junior SOC Analyst role, 
focusing on log analysis, alert triage, and incident investigation. This repo tracks my 
practical progress alongside my coursework.
- 🎯 Goal: SOC Analyst
- 🌍 Based in: Sumgait, Azerbaijan.
- 🔗 LetsDefend profile: [Click](https://app.letsdefend.io/user/wanhecho)

---

## 🧰 Skills & Tools

| Category | Tools / Skills |
|---|---|
| **SIEM & Log Analysis** | LetsDefend SIEM, log correlation, alert triage |
| **Network Analysis** | Wireshark, tcpdump, PCAP analysis |
| **Endpoint Investigation** | Process trees, EDR alert analysis, persistence checks |
| **Email Security** | Header analysis, phishing triage, attachment analysis |
| **Threat Intelligence** | VirusTotal, AbuseIPDB, urlscan.io, MITRE ATT&CK |
| **Detection Engineering** | Sigma rules (basic), YARA (basic) |
| **Frameworks** | MITRE ATT&CK, Cyber Kill Chain, NIST IR lifecycle |

---

## 🏗️ Repository Architecture

```
letsdefend-portfolio/
├── README.md                     → this file (main landing page)
│
├── writeups/                     → alert investigations, grouped by category
│   ├── phishing/
│   ├── malware/
│   ├── network-intrusion/
│   ├── brute-force/
│   ├── web-attacks/
│   ├── insider-threat/
│   └── endpoint-security/
│       └── 00X-case-name/
│           ├── README.md         → full write-up for this case
│           └── screenshots/      → supporting (redacted) evidence
│
├── learning-paths/                → LetsDefend Learning Path progress
│   ├── README.md                  → progress tracker table
│   └── certificates/              → certificate files (PDF/PNG)
│
├── notes/                         → personal SOC/security study notes
│   ├── siem-cheatsheet.md
│   ├── mitre-attack-mapping.md
│   ├── log-analysis-notes.md
│   └── tools-reference.md
│
└── resources/                     → curated external links & references
    └── README.md
```

**Why this structure?**
- `writeups/` grouped **by attack category** (not just numbered) so a reviewer can jump straight to, say, phishing cases if that's what they care about.
- `learning-paths/` separates *structured course completion* (certificates) from *hands-on investigation* (writeups) — these demonstrate different things: theory vs. applied skill.
- `notes/` shows continuous learning beyond just completed exercises.

---

## 🎓 Learning Paths & Certificates

Tracking my progress through LetsDefend's structured Learning Paths. Full details and certificate files are in [`learning-paths/`](./learning-paths/).

| Learning Path | Status | Certificate |
|---|---|---|
| SOC Analyst Learning Path | ⬜ In Progress / ✅ Completed | [View](./learning-paths/certificates/) |
| Incident Responder Learning Path | ⬜ Not Started | — |
| Threat Hunting Learning Path | ⬜ Not Started | — |
| Malware Analyst Learning Path | ⬜ Not Started | — |

*(Update statuses and add rows as you complete each path)*

---

## 🔍 Investigation Write-ups

Each case below follows a consistent format: **Scenario → Investigation → IOCs → MITRE ATT&CK Mapping → Verdict → Lessons Learned**. See [`writeups/`](./writeups/) for the full index.

### 🎣 Phishing / Email Security
| # | Title | Verdict | Link |
|---|---|---|---|
| 001 | [Example: Suspicious Attachment in Invoice Email] | True Positive | [View](./writeups/phishing/001-example-case/README.md) |

### 🦠 Malware
| # | Title | Verdict | Link |
|---|---|---|---|

### 🌐 Network Intrusion
| # | Title | Verdict | Link |
|---|---|---|

### 🔓 Brute Force / Credential Attacks
| # | Title | Verdict | Link |
|---|---|---|

### 🕸️ Web Attacks
| # | Title | Verdict | Link |
|---|---|---|

### 🕵️ Insider Threat
| # | Title | Verdict | Link |
|---|---|---|

### 💻 Endpoint Security
| # | Title | Verdict | Link |
|---|---|---|

*(Add a row and folder each time you complete a new case)*

---

## 📝 Notes & Cheatsheets

Study notes I keep updated as I learn — see [`notes/`](./notes/):
- [SIEM Cheatsheet](./notes/siem-cheatsheet.md)
- [MITRE ATT&CK Mapping Reference](./notes/mitre-attack-mapping.md)
- [Log Analysis Notes](./notes/log-analysis-notes.md)
- [Tools Reference](./notes/tools-reference.md)

---

## 📫 Contact

- LinkedIn: [Click](https://www.linkedin.com/in/tunar-eyyublu/)
- Email: tunareyyublu0@gmail.com
- LetsDefend Profile: [Click](https://app.letsdefend.io/user/wanhecho)

---
⭐ *If you're a recruiter reviewing this — thanks for stopping by! Every write-up here reflects my own investigation process and reasoning.*
