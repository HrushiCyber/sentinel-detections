# Privileged Logon Detection

MITRE ATT&CK  
T1078 – Valid Accounts

## Description

Detect logons where elevated privileges are assigned.

## Data Source

Windows Security Logs

## Relevant Event IDs

4672 – Special privileges assigned to new logon

## Detection Logic

Monitor logons with administrative privileges.

## Detection Query

See queries/privileged_logon.kql

## Investigation Steps

1 Identify privileged account  
2 Confirm administrative activity  
3 Check login location and system

## False Positives

Normal administrator logins.