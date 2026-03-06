# Impossible Travel Login

MITRE ATT&CK  
T1078 – Valid Accounts

## Description

Detects logins from geographically distant locations within a short timeframe.

## Data Source

Azure AD Sign-in Logs

## Detection Logic

Identify users logging in from multiple distant locations.

## Detection Query

See queries/impossible_travel.kql

## Investigation Steps

1 Identify user login locations  
2 Validate VPN usage  
3 Investigate potential credential compromise

## False Positives

VPN connections or traveling employees.