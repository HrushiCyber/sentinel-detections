# Multiple Failed Login Attempts

MITRE ATT&CK  
T1110 – Brute Force

## Description

Detect multiple failed login attempts which may indicate password guessing.

## Data Source

Azure AD Sign-in Logs

## Detection Logic

Detect users with many failed login attempts.

## Detection Query

See queries/multiple_failed_logins.kql

## Investigation Steps

1 Identify attacking IP  
2 Check targeted accounts  
3 Investigate brute force attempts

## False Positives

Users entering incorrect passwords.