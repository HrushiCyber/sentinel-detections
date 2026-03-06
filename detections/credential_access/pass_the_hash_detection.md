# Pass the Hash Detection

MITRE ATT&CK  
T1550.002 – Pass the Hash

## Description

Detects network logons using NTLM authentication which may indicate pass-the-hash activity.

## Data Source

Windows Security Logs

## Relevant Event IDs

4624 – Successful logon

## Detection Query

See queries/pass_the_hash_detection.kql

## Investigation Steps

1 Identify source machine  
2 Check repeated NTLM authentication  
3 Investigate account activity  
4 Validate user behavior

## False Positives

Legacy systems using NTLM authentication.