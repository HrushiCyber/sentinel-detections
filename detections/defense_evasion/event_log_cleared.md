# Event Log Clearing

MITRE ATT&CK  
T1070.001 – Clear Windows Event Logs

## Description

Attackers may clear Windows event logs to remove evidence of their activities.

## Data Source

Windows Security Logs

## Relevant Event IDs

1102 – Audit log cleared

## Detection Query

See queries/event_log_cleared.kql

## Investigation Steps

1 Identify the account that cleared the logs
2 Review activity before log clearing
3 Investigate potential compromise

## False Positives

Rare administrative log maintenance.