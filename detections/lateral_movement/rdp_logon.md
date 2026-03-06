# Remote Desktop Logon Detection

MITRE ATT&CK  
T1021.001 – Remote Desktop Protocol

## Description

Attackers commonly use Remote Desktop Protocol (RDP) for lateral movement within a compromised network.

This detection identifies successful RDP logins.

## Data Source

Windows Security Logs

## Relevant Event IDs

4624 – Successful logon

Logon Type  
10 – Remote Interactive

## Detection Logic

Monitor successful RDP authentication events.

## Detection Query

See queries/rdp_logon.kql

## Investigation Steps

1 Identify source IP and host initiating RDP session  
2 Confirm user identity and privileges  
3 Check whether login occurred during unusual hours  
4 Investigate suspicious activity following login

## False Positives

Legitimate remote administration.