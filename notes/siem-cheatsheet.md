# SIEM Cheatsheet

Quick reference notes for SIEM-based alert triage.

## Alert Triage Checklist
- [ ] What is the alert severity?
- [ ] What asset/user is involved?
- [ ] Is this a known false-positive pattern?
- [ ] What's the timeline of events around this alert?
- [ ] Are there related alerts on the same asset?

## Useful Log Fields to Check
- Source/Destination IP
- Timestamp
- User account
- Process name / command line
- HTTP status codes / User-Agent (for web logs)

*(Expand this as you learn more query patterns and detection logic)*
