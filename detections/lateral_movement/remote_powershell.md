# Remote PowerShell Execution

MITRE ATT&CK  
T1021.006 – PowerShell Remoting

## Description

Detects PowerShell executions that disable profiles which may indicate remote exploitation.

## Data Source

Windows Security Logs

## Relevant Event IDs

4688 – Process creation

## Detection Query

See queries/remote_powershell.kql

## Investigation Steps

1 Identify executing user  
2 Review command parameters  
3 Validate remote execution behavior

## False Positives

Automation scripts.