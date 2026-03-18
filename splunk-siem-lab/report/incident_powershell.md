# SOC Incident Report

## Incident Title
Suspicious PowerShell Execution Detected

## Date
March 2026

## Detection Method
Splunk SIEM Alert Rule

## Description
Security monitoring identified multiple PowerShell execution events on a host. PowerShell is commonly used by attackers for post-exploitation activities such as lateral movement, persistence, and privilege escalation.

## Affected Host
Workstation / Server

## Log Source
Windows Event Logs (Process Creation)

## MITRE ATT&CK Mapping
- T1059.001 — PowerShell
- TA0002 — Execution

## Investigation Steps
- Analyzed process creation logs for PowerShell activity
- Identified frequency and execution patterns
- Checked for encoded or suspicious command usage
- Verified user account context

## Findings
Activity may indicate administrative usage or potential attacker execution. Further monitoring required.

## Response Actions
- Recommended enabling PowerShell logging and script block logging
- Suggested endpoint protection scan
- Continued monitoring for persistence indicators

## Severity Level
Medium