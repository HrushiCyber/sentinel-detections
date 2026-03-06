# Token Impersonation Detection

MITRE ATT&CK  
T1134 – Access Token Manipulation

## Description

Attackers may impersonate tokens to escalate privileges.

## Data Source

Windows Security Logs

## Relevant Event IDs

4673 – Sensitive privilege used

## Detection Logic

Detect usage of sensitive privileges.

## Detection Query

See queries/token_impersonation.kql

## Investigation Steps

1 Identify user invoking privilege  
2 Review system processes involved  
3 Investigate unusual activity

## False Positives

Administrative tools requiring elevated privileges.