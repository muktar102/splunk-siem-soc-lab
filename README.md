Splunk SIEM SOC Monitoring Lab
Project Overview
This project demonstrates the implementation of a Security Information and Event Management (SIEM) solution using Splunk Enterprise to detect, analyze, and respond to simulated cyber security threats.
The lab focuses on real-world SOC Analyst use-cases such as brute force attacks, port scanning, command-and-control communication, suspicious PowerShell activity, and abnormal network traffic patterns.
Using the BOTS v3 dataset, multiple detection queries, dashboards, alerts, and incident reports were developed to simulate enterprise security monitoring operations.

Objectives
	•	Implement SIEM monitoring using Splunk
	•	Detect common attack techniques
	•	Create SOC dashboards for threat visibility
	•	Configure automated alert rules
	•	Perform incident analysis and reporting
	•	Map detections to MITRE ATT&CK Framework

Tools & Technologies
	•	Splunk Enterprise (SIEM)
	•	BOTS v3 Security Dataset
	•	SPL (Search Processing Language)
	•	MITRE ATT&CK Framework


Detection Use Cases Implemented
✅ Brute Force Login Detection
Detects repeated failed login attempts from Windows Security Logs.
✅ Port Scanning Detection
Identifies hosts scanning multiple ports indicating reconnaissance activity.
✅ Suspicious PowerShell Execution
Monitors abnormal PowerShell activity which may indicate malware execution or lateral movement.
✅ Suspicious DNS / Command & Control Detection
Detects abnormal DNS queries and possible communication with malicious domains.
✅ High Volume Network Communication
Identifies unusual traffic spikes between internal systems.

SOC Monitoring Dashboard
A centralized SOC dashboard was built to visualize:
	•	Failed login attempts
	•	Port scanning sources
	•	DNS suspicious domains
	•	PowerShell execution trends
	•	High volume network traffic
This dashboard enables real-time threat visibility and faster security investigations.

Alert Rules Configured
Automated Splunk alert rules were created for:
	•	Brute force login attempts
	•	Port scanning activity
	•	Suspicious DNS communication
	•	Possible Command & Control traffic
	•	Abnormal PowerShell execution
Alerts were configured to trigger when suspicious thresholds were exceeded.

MITRE ATT&CK Mapping
Detection 
MITRE Technique
Brute Force
T1110 – Brute Force
Port Scan
T1046 – Network Service Discovery
PowerShell Abuse
T1059.001 – PowerShell
DNS C2 Communication
T1071.004 – DNS Protocol
Data Exfiltration / Traffic Spike
T1041 – Exfiltration Over C2 Channel

Incident Response Reports
Simulated incident reports were created following SOC investigation procedures including:
	•	Alert validation
	•	Log analysis
	•	Threat assessment
	•	Containment recommendations
	•	Security improvement suggestions

Project Structure
splunk-siem-lab/
│
├── README.md
├── dataset/ (reference link only)
├── logs/
├── queries/
├── dashboard/
├── screenshots/
└── report/


Skills Demonstrated
	•	SIEM Implementation
	•	Log Analysis & Threat Detection
	•	SPL Query Development
	•	SOC Dashboard Design
	•	Alert Engineering
	•	Incident Response Simulation
	•	MITRE ATT&CK Mapping
	•	Cyber Security Investigation

Author
Ahmed Muktar 
SOC Analyst | Cyber Security 

