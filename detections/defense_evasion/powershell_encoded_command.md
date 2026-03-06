# PowerShell Encoded Command

MITRE ATT&CK  
T1027 – Obfuscated/Encoded Commands

## Description

Attackers often encode PowerShell commands using Base64 to evade detection.

## Data Source

Windows Security Logs

## Relevant Event IDs

4688 – Process creation

## Detection Query

See queries/powershell_encoded_command.kql

## Investigation Steps

1 Decode command
2 Identify script purpose
3 Investigate host compromise

## False Positives

Administrative automation scripts.