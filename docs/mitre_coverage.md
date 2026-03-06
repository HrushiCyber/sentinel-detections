# MITRE ATT&CK Coverage

This table maps detections to MITRE ATT&CK techniques.

| Detection | Technique | Tactic |
|-----------|-----------|--------|
| Kerberoasting | T1558.003 | Credential Access |
| Mimikatz Credential Dumping | T1003 | Credential Access |
| Pass the Hash | T1550.002 | Credential Access |
| PsExec Execution | T1021.002 | Lateral Movement |
| RDP Logon | T1021.001 | Lateral Movement |
| SMB Admin Share | T1021.002 | Lateral Movement |
| Scheduled Task Creation | T1053 | Persistence |
| Registry Run Key | T1547.001 | Persistence |
| Account Creation | T1136 | Persistence |
| Group Membership Change | T1098 | Privilege Escalation |
| Token Impersonation | T1134 | Privilege Escalation |
| Event Log Cleared | T1070.001 | Defense Evasion |
| Encoded PowerShell | T1027 | Defense Evasion |
| PowerShell Download | T1105 | Command & Control |
| Impossible Travel | T1078 | Initial Access |