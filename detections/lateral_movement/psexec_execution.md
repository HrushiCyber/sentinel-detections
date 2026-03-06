# PsExec Lateral Movement

MITRE ATT&CK  
T1021.002 – SMB/Windows Admin Shares

## Description

Detects execution of PsExec tool which is commonly used for lateral movement.

## Data Source

Windows Security Logs

## Relevant Event IDs

4688 – Process creation

## Detection Query

See queries/psexec_execution.kql

## Investigation Steps

1 Identify executing account  
2 Verify remote host accessed  
3 Investigate administrative activity

## False Positives

System administrators using PsExec legitimately.