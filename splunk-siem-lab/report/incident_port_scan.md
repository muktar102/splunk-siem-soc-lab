# SOC Incident Report

## Incident Title
Network Port Scanning Activity Detected

## Date
March 2026

## Detection Method
Splunk SIEM Alert Rule

## Description
Unusual network activity was detected where a single source IP attempted connections to multiple destination ports across internal systems. This behavior is consistent with reconnaissance or port scanning activity.

## Affected Systems
Multiple internal hosts

## Log Source
Network Logs (Firewall / Syslog)

## MITRE ATT&CK Mapping
- T1046 — Network Service Discovery
- TA0007 — Discovery

## Investigation Steps
- Reviewed Splunk alert triggered for high number of destination ports
- Identified source IP responsible for scanning activity
- Analyzed communication pattern across network services
- Checked for follow-up exploitation attempts

## Findings
Activity indicates possible attacker reconnaissance phase. No successful exploitation observed.

## Response Actions
- Recommended blocking suspicious source IP
- Increased monitoring on targeted hosts
- Suggested vulnerability scanning and patch verification

## Severity Level
Medium