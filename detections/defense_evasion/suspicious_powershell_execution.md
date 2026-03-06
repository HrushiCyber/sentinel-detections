# Suspicious PowerShell Execution

MITRE ATT&CK  
T1059.001 – PowerShell

## Description

PowerShell is frequently abused by attackers to execute malicious scripts or commands directly on a system.  
This detection identifies execution of PowerShell commands containing potentially dangerous functions such as `Invoke-Expression`.

## Data Source

Windows Security Event Logs

## Relevant Event IDs

4104 – PowerShell Script Block Logging

## Detection Logic

Detect PowerShell scripts that contain suspicious execution patterns.

## Detection Query

See queries/suspicious_powershell_execution.kql

## Investigation Steps

1 Identify the user executing the PowerShell command  
2 Review the script block content  
3 Determine whether the command was executed interactively or through a script  
4 Inspect associated process activity on the host

## False Positives

Legitimate administrative PowerShell automation.