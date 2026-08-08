# 🔍 Investigation Write-ups

This folder contains my hands-on incident investigations from LetsDefend's SOC Simulator, organized by attack category.

## 📐 Write-up Format

Every case folder contains a `README.md` with this structure:

1. **Scenario / Alert Summary** — what triggered the alert
2. **Investigation Steps** — my process, tools used, questions I asked
3. **Evidence / IOCs** — indicators found (IPs, hashes, domains — redacted/sanitized where needed)
4. **MITRE ATT&CK Mapping** — relevant tactics & techniques
5. **Verdict** — True Positive / False Positive, with justification
6. **Remediation & Recommendations** — what action should be taken
7. **Lessons Learned** — what I took away from the case

## 📂 Categories

| Folder | Focus |
|---|---|
| `phishing/` | Email-based threats, malicious attachments, credential harvesting |
| `malware/` | Malware detection, static analysis, execution behavior |
| `network-intrusion/` | Suspicious network traffic, C2 communication, lateral movement |
| `brute-force/` | Credential attacks, failed login patterns, account compromise |
| `web-attacks/` | Web app attacks (SQLi, XSS, etc.) detected via logs |
| `insider-threat/` | Anomalous internal user behavior |
| `endpoint-security/` | Host-based alerts, process/persistence anomalies |

Each category folder has its own `README.md` explaining what belongs there, plus numbered case subfolders (`001-case-name/`).
