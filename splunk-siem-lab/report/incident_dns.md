# SOC Incident Report

## Incident Title
Suspicious DNS Communication Detected

## Date
March 2026

## Detection Method
Splunk SIEM Alert Rule

## Description
High volume DNS queries were detected between an internal host and external domains. This behavior may indicate command and control (C2) communication or malware beaconing.

## Affected Host
Internal workstation

## Log Source
Syslog / DNS Logs

## MITRE ATT&CK Mapping
- T1071.004 — DNS
- TA0011 — Command and Control

## Investigation Steps
- Identified domain names with unusually high query counts
- Correlated DNS traffic with host network activity
- Checked for known malicious domain indicators
- Monitored for data exfiltration patterns

## Findings
Traffic pattern suggests possible automated communication with external infrastructure. No confirmed data exfiltration observed.

## Response Actions
- Recommended domain blocking at firewall or DNS level
- Suggested malware scan on affected host
- Continued network monitoring

## Severity Level
Medium