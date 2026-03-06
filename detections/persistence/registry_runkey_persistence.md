# Registry Run Key Persistence

MITRE ATT&CK  
T1547.001 – Registry Run Keys / Startup Folder

## Description

Attackers commonly create registry run keys to maintain persistence on a system.
These keys cause malicious programs to execute automatically during system startup.

## Data Source

Windows Security Logs

## Relevant Event IDs

4657 – Registry value modification

## Detection Query

See queries/registry_runkey_persistence.kql

## Investigation Steps

1 Identify registry key modified
2 Verify user performing the change
3 Check executable referenced by registry value
4 Investigate associated process activity

## False Positives

Legitimate software installation modifying startup registry entries.