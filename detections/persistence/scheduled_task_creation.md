# Scheduled Task Persistence

MITRE ATT&CK  
T1053 – Scheduled Task

## Description

Detects creation of scheduled tasks which attackers may use for persistence.

## Data Source

Windows Security Logs

## Relevant Event IDs

4698 – Scheduled task created

## Detection Query

See queries/scheduled_task_creation.kql

## Investigation Steps

1 Identify task creator  
2 Review task command  
3 Validate legitimacy

## False Positives

Administrative scheduled jobs.