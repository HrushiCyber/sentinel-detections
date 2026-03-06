# Mimikatz Credential Dumping

MITRE ATT&CK  
T1003 – Credential Dumping

## Description

Detects use of Mimikatz tool commonly used to extract credentials from LSASS memory.

## Data Source

Windows Security Logs

## Relevant Event IDs

4688 – Process creation

## Detection Query

See queries/mimikatz_detection.kql

## Investigation Steps

1 Identify process executing Mimikatz  
2 Check parent process  
3 Validate user privileges  
4 Investigate system compromise indicators

## False Positives

Security testing tools or penetration testing.