# Account Creation Detection

MITRE ATT&CK  
T1136 – Create Account

## Description

Attackers may create new accounts to maintain persistence and access compromised systems.

## Data Source

Windows Security Logs

## Relevant Event IDs

4720 – User account created

## Detection Logic

Detect newly created user accounts.

## Detection Query

See queries/account_created.kql

## Investigation Steps

1 Identify account creator  
2 Validate reason for account creation  
3 Check privileges assigned to account

## False Positives

Authorized administrative user creation.