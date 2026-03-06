# SMB Admin Share Access

MITRE ATT&CK  
T1021.002 – SMB/Windows Admin Shares

## Description

Attackers often access administrative shares such as ADMIN$ for lateral movement or file transfer.

## Data Source

Windows Security Logs

## Relevant Event IDs

5140 – Network share accessed

## Detection Logic

Detect access to administrative shares.

## Detection Query

See queries/smb_admin_share_access.kql

## Investigation Steps

1 Identify source system accessing share  
2 Determine user performing access  
3 Verify administrative activity legitimacy

## False Positives

System administrators performing remote management.