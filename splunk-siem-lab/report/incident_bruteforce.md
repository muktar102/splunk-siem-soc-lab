# SOC Incident Report

## Incident Title
Brute Force Login Attempt Detected

## Date
March 2026

## Detection Method
Splunk SIEM Alert Rule

## Description
Multiple failed login attempts were detected from a single source indicating a possible brute force attack against internal systems.

## Affected Host
SEPM Server

## Log Source
Windows Security Logs (EventCode 4625)

## MITRE ATT&CK Mapping
- T1110 — Brute Force
- TA0006 — Credential Access

## Investigation Steps
- Verified alert in Splunk dashboard
- Analyzed failed login patterns
- Identified source host generating multiple authentication failures
- Checked for successful login attempts after failures

## Findings
No successful compromise observed.

## Response Actions
- Recommended account lockout policy
- Suggested monitoring source IP

## Severity Level
Medium