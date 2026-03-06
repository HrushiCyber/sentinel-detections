# Kerberoasting Detection

MITRE ATT&CK  
T1558.003 – Kerberoasting

## Description

Kerberoasting is an attack where attackers request Kerberos service tickets
and crack them offline to obtain service account passwords.

## Data Source

Windows Security Logs

Event ID  
4769

## Detection Query

See queries/kerberoasting_detection.kql

## Investigation Steps

1 Identify requesting account  
2 Check number of ticket requests  
3 Validate service account activity

## False Positives

Service accounts generating large ticket volumes