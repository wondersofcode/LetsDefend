# Log Analysis Notes

## Windows Event IDs Worth Knowing
| Event ID | Meaning |
|---|---|
| 4624 | Successful logon |
| 4625 | Failed logon |
| 4688 | New process created |
| 4720 | User account created |

## Common Red Flags in Logs
- Logon at unusual hours
- Multiple failed logons followed by a success (possible brute force success)
- PowerShell with encoded commands
- Unexpected outbound connections to rare/new domains

*(Keep expanding this as you see new patterns)*
