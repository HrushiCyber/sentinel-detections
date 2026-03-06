# Rare User Agent Detection

MITRE ATT&CK  
T1078 – Valid Accounts

## Description

Attackers may authenticate using unusual user agents or scripts.

## Data Source

Azure AD Sign-in Logs

## Detection Logic

Detect rare or uncommon user agents.

## Detection Query

See queries/rare_user_agent.kql

## Investigation Steps

1 Identify user agent  
2 Check user activity  
3 Validate authentication source

## False Positives

New applications accessing tenant.