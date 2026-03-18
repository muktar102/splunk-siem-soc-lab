{\rtf1\ansi\ansicpg1252\cocoartf2821
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\froman\fcharset0 Times-Bold;\f1\froman\fcharset0 Times-Roman;\f2\fnil\fcharset0 AppleColorEmoji;
\f3\fmodern\fcharset0 Courier;\f4\fnil\fcharset0 Menlo-Regular;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;\red109\green109\blue109;}
{\*\expandedcolortbl;;\cssrgb\c0\c0\c0;\cssrgb\c50196\c50196\c50196;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid101\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid2}
{\list\listtemplateid3\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid201\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid3}
{\list\listtemplateid4\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid301\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid4}
{\list\listtemplateid5\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid401\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid5}
{\list\listtemplateid6\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid501\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid6}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}{\listoverride\listid3\listoverridecount0\ls3}{\listoverride\listid4\listoverridecount0\ls4}{\listoverride\listid5\listoverridecount0\ls5}{\listoverride\listid6\listoverridecount0\ls6}}
\margl1440\margr1440\vieww29200\viewh18400\viewkind0
\deftab720
\pard\pardeftab720\sa321\partightenfactor0

\f0\b\fs48 \cf0 \expnd0\expndtw0\kerning0
Splunk SIEM SOC Monitoring Lab\

\fs36 Project Overview\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 This project demonstrates the implementation of a 
\f0\b Security Information and Event Management (SIEM)
\f1\b0  solution using 
\f0\b Splunk Enterprise
\f1\b0  to detect, analyze, and respond to simulated cyber security threats.\
The lab focuses on real-world 
\f0\b SOC Analyst use-cases
\f1\b0  such as brute force attacks, port scanning, command-and-control communication, suspicious PowerShell activity, and abnormal network traffic patterns.\
Using the 
\f0\b BOTS v3 dataset
\f1\b0 , multiple detection queries, dashboards, alerts, and incident reports were developed to simulate enterprise security monitoring operations.\
\pard\pardeftab720\partightenfactor0
\cf3 \
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 Objectives\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa240\partightenfactor0
\ls1\ilvl0
\f1\b0\fs24 \cf0 \kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Implement SIEM monitoring using Splunk\
\ls1\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Detect common attack techniques\
\ls1\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Create SOC dashboards for threat visibility\
\ls1\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Configure automated alert rules\
\ls1\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Perform incident analysis and reporting\
\ls1\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Map detections to 
\f0\b MITRE ATT&CK Framework
\f1\b0 \
\pard\pardeftab720\partightenfactor0
\cf3 \
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 Tools & Technologies\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa240\partightenfactor0
\ls2\ilvl0
\f1\b0\fs24 \cf0 \kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Splunk Enterprise (SIEM)\
\ls2\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
BOTS v3 Security Dataset\
\ls2\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
SPL (Search Processing Language)\
\ls2\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
MITRE ATT&CK Framework\
\
\pard\pardeftab720\partightenfactor0
\cf3 \
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 Detection Use Cases Implemented\
\pard\pardeftab720\sa280\partightenfactor0

\f2\b0\fs28 \cf0 \uc0\u9989 
\f0\b  Brute Force Login Detection\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 Detects repeated failed login attempts from Windows Security Logs.\
\pard\pardeftab720\sa280\partightenfactor0

\f2\fs28 \cf0 \uc0\u9989 
\f0\b  Port Scanning Detection\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 Identifies hosts scanning multiple ports indicating reconnaissance activity.\
\pard\pardeftab720\sa280\partightenfactor0

\f2\fs28 \cf0 \uc0\u9989 
\f0\b  Suspicious PowerShell Execution\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 Monitors abnormal PowerShell activity which may indicate malware execution or lateral movement.\
\pard\pardeftab720\sa280\partightenfactor0

\f2\fs28 \cf0 \uc0\u9989 
\f0\b  Suspicious DNS / Command & Control Detection\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 Detects abnormal DNS queries and possible communication with malicious domains.\
\pard\pardeftab720\sa280\partightenfactor0

\f2\fs28 \cf0 \uc0\u9989 
\f0\b  High Volume Network Communication\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 Identifies unusual traffic spikes between internal systems.\
\pard\pardeftab720\partightenfactor0
\cf3 \
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 SOC Monitoring Dashboard\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 A centralized SOC dashboard was built to visualize:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa240\partightenfactor0
\ls3\ilvl0\cf0 \kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Failed login attempts\
\ls3\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Port scanning sources\
\ls3\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
DNS suspicious domains\
\ls3\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
PowerShell execution trends\
\ls3\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
High volume network traffic\
\pard\pardeftab720\sa240\partightenfactor0
\cf0 This dashboard enables 
\f0\b real-time threat visibility and faster security investigations.
\f1\b0 \
\pard\pardeftab720\partightenfactor0
\cf3 \
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 Alert Rules Configured\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 Automated Splunk alert rules were created for:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa240\partightenfactor0
\ls4\ilvl0\cf0 \kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Brute force login attempts\
\ls4\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Port scanning activity\
\ls4\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Suspicious DNS communication\
\ls4\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Possible Command & Control traffic\
\ls4\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Abnormal PowerShell execution\
\pard\pardeftab720\sa240\partightenfactor0
\cf0 Alerts were configured to trigger when suspicious thresholds were exceeded.\
\pard\pardeftab720\partightenfactor0
\cf3 \
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 MITRE ATT&CK Mapping\

\itap1\trowd \taflags0 \trgaph108\trleft-108 \trbrdrt\brdrnil \trbrdrl\brdrnil \trbrdrr\brdrnil 
\clvertalc \clshdrawnil \clwWidth3044\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx4320
\clvertalc \clshdrawnil \clwWidth3699\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx8640
\pard\intbl\itap1\pardeftab720\qc\partightenfactor0

\fs24 \cf0 Detection \cell 
\pard\intbl\itap1\pardeftab720\qc\partightenfactor0
\cf0 MITRE Technique\cell \row

\itap1\trowd \taflags0 \trgaph108\trleft-108 \trbrdrl\brdrnil \trbrdrr\brdrnil 
\clvertalc \clshdrawnil \clwWidth3044\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx4320
\clvertalc \clshdrawnil \clwWidth3699\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx8640
\pard\intbl\itap1\pardeftab720\partightenfactor0

\f1\b0 \cf0 Brute Force\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 T1110 \'96 Brute Force\cell \row

\itap1\trowd \taflags0 \trgaph108\trleft-108 \trbrdrl\brdrnil \trbrdrr\brdrnil 
\clvertalc \clshdrawnil \clwWidth3044\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx4320
\clvertalc \clshdrawnil \clwWidth3699\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx8640
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 Port Scan\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 T1046 \'96 Network Service Discovery\cell \row

\itap1\trowd \taflags0 \trgaph108\trleft-108 \trbrdrl\brdrnil \trbrdrr\brdrnil 
\clvertalc \clshdrawnil \clwWidth3044\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx4320
\clvertalc \clshdrawnil \clwWidth3699\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx8640
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 PowerShell Abuse\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 T1059.001 \'96 PowerShell\cell \row

\itap1\trowd \taflags0 \trgaph108\trleft-108 \trbrdrl\brdrnil \trbrdrr\brdrnil 
\clvertalc \clshdrawnil \clwWidth3044\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx4320
\clvertalc \clshdrawnil \clwWidth3699\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx8640
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 DNS C2 Communication\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 T1071.004 \'96 DNS Protocol\cell \row

\itap1\trowd \taflags0 \trgaph108\trleft-108 \trbrdrl\brdrnil \trbrdrt\brdrnil \trbrdrr\brdrnil 
\clvertalc \clshdrawnil \clwWidth3044\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx4320
\clvertalc \clshdrawnil \clwWidth3699\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx8640
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 Data Exfiltration / Traffic Spike\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 T1041 \'96 Exfiltration Over C2 Channel\cell \lastrow\row
\pard\pardeftab720\partightenfactor0
\cf3 \
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 Incident Response Reports\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 Simulated incident reports were created following SOC investigation procedures including:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa240\partightenfactor0
\ls5\ilvl0\cf0 \kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Alert validation\
\ls5\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Log analysis\
\ls5\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Threat assessment\
\ls5\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Containment recommendations\
\ls5\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Security improvement suggestions\
\pard\pardeftab720\partightenfactor0
\cf3 \
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 Project Structure\
\pard\pardeftab720\partightenfactor0

\f3\b0\fs26 \cf0 splunk-siem-lab/\

\f4 \uc0\u9474 
\f3 \

\f4 \uc0\u9500 \u9472 \u9472 
\f3  README.md\

\f4 \uc0\u9500 \u9472 \u9472 
\f3  dataset/ (reference link only)\

\f4 \uc0\u9500 \u9472 \u9472 
\f3  logs/\

\f4 \uc0\u9500 \u9472 \u9472 
\f3  queries/\

\f4 \uc0\u9500 \u9472 \u9472 
\f3  dashboard/\

\f4 \uc0\u9500 \u9472 \u9472 
\f3  screenshots/\

\f4 \uc0\u9492 \u9472 \u9472 
\f3  report/\
\pard\pardeftab720\partightenfactor0

\f1\fs24 \cf3 \
\
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 Skills Demonstrated\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa240\partightenfactor0
\ls6\ilvl0
\f1\b0\fs24 \cf0 \kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
SIEM Implementation\
\ls6\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Log Analysis & Threat Detection\
\ls6\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
SPL Query Development\
\ls6\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
SOC Dashboard Design\
\ls6\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Alert Engineering\
\ls6\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Incident Response Simulation\
\ls6\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
MITRE ATT&CK Mapping\
\ls6\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Cyber Security Investigation\
\pard\pardeftab720\partightenfactor0
\cf3 \
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 Author\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 Ahmed Muktar\uc0\u8232 Aspiring SOC Analyst | Cyber Security Enthusiast\
\pard\pardeftab720\partightenfactor0
\cf3 \
}