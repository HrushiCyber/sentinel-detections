# Suspicious Scheduled Task Creation

MITRE ATT&CK  
T1053 – Scheduled Task

## Description

Attackers create scheduled tasks to execute malware periodically.

## Data Source

Windows Security Logs

## Relevant Event IDs

4698 – Scheduled task created

## Detection Logic

Detect scheduled task creation events.

## Detection Query

See queries/suspicious_scheduled_task.kql

## Investigation Steps

1 Review task command and executable  
2 Verify user creating task  
3 Check for persistence patterns

## False Positives

Legitimate automated tasks.