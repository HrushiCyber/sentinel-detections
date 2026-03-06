# Suspicious OAuth Application Creation

MITRE ATT&CK  
T1528 – Steal Application Access Token

## Description

Attackers may register malicious OAuth applications to obtain persistent access.

## Data Source

Azure AD Audit Logs

## Detection Logic

Detect creation of new service principals.

## Detection Query

See queries/suspicious_oauth_app.kql

## Investigation Steps

1 Identify application owner  
2 Review permissions granted  
3 Validate admin consent activity

## False Positives

Legitimate application onboarding.