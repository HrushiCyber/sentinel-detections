# Suspicious Service Creation

MITRE ATT&CK  
T1543.003 – Create or Modify System Process

## Description

Attackers can create Windows services to maintain persistence on compromised systems.

## Data Source

Windows Security Logs

## Relevant Event IDs

7045 – New service installed

## Detection Logic

Monitor creation of new services.

## Detection Query

See queries/service_creation.kql

## Investigation Steps

1 Identify service executable path  
2 Verify service creator account  
3 Analyze service behavior and persistence mechanism

## False Positives

Legitimate software installation.