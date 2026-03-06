# Privileged Group Membership Change

MITRE ATT&CK  
T1098 – Account Manipulation

## Description

Attackers may add accounts to privileged groups such as Administrators or Domain Admins.

## Data Source

Windows Security Logs

## Relevant Event IDs

4728 – Member added to security-enabled global group  
4732 – Member added to local group

## Detection Logic

Detect addition of users to privileged groups.

## Detection Query

See queries/group_membership_change.kql

## Investigation Steps

1 Identify added account  
2 Confirm request legitimacy  
3 Check for other suspicious activity

## False Positives

Authorized privilege escalation by administrators.