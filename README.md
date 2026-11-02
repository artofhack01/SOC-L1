# SOC-L1
SOC-L1 CYBERSECURITY...

Security Operations Center (SOC)

Fundamentals, Operations, Tools & SOC Analyst Level 1

Technical Learning Documentation | Beginner to SOC L1

1. Introduction to SOC

A Security Operations Center (SOC) is a centralized team responsible for monitoring, detecting, analyzing, and responding to cybersecurity threats.

Its main objective is to protect an organization's systems, networks, endpoints, applications, and sensitive information.

Main Responsibilities:

- Security monitoring.
- Threat detection and analysis.
- Log monitoring.
- Alert investigation.
- Incident response.
- Threat hunting.
- Security reporting.

2. Important SOC Technologies and Tools

2.1 SIEM (Security Information and Event Management)

SIEM collects and analyzes logs from different sources to identify suspicious activities and generate security alerts.

Main Functions:

- Log collection.
- Event correlation.
- Alert generation.
- Threat detection.
- Security investigation.

Popular SIEM Tools:

- Splunk Enterprise Security.
- Microsoft Sentinel.
- IBM QRadar.
- Google Security Operations.

2.2 EDR (Endpoint Detection and Response)

EDR monitors endpoint devices such as computers, laptops, and servers to detect and investigate suspicious activities.

Popular EDR Tools:

- CrowdStrike Falcon.
- Microsoft Defender for Endpoint.
- SentinelOne Singularity.
- VMware Carbon Black.
- Sophos Intercept X.

2.3 XDR (Extended Detection and Response)

XDR collects and correlates security information from multiple environments, including endpoints, networks, emails, and cloud systems.

Popular XDR Tools:

- Microsoft Defender XDR.
- Palo Alto Cortex XDR.
- Trend Micro Vision One.
- CrowdStrike Falcon platform.

2.4 Firewall

A firewall monitors and controls incoming and outgoing network traffic based on predefined security rules.

Popular Firewall Solutions:

- Fortinet FortiGate.
- Palo Alto Networks.
- Cisco Secure Firewall.
- Check Point Firewall.

2.5 IDS and IPS

IDS (Intrusion Detection System): Detects suspicious network activities and generates alerts.

IPS (Intrusion Prevention System): Detects and can automatically block malicious network traffic.

Popular Tools:

- Snort.
- Suricata.
- Cisco Secure IPS.

2.6 EPP (Endpoint Protection Platform)

EPP protects endpoint devices against malware, viruses, ransomware, and other malicious activities.

Popular Solutions:

- Microsoft Defender Antivirus.
- Bitdefender GravityZone.
- Sophos Endpoint.

2.7 SOAR (Security Orchestration, Automation and Response)

SOAR automates repetitive security tasks and helps coordinate incident response.

Popular Tools:

- Palo Alto Cortex XSOAR.
- Splunk SOAR.
- IBM Security SOAR.

2.8 Network Monitoring and Packet Analysis

These tools help analysts monitor network traffic, investigate suspicious connections, and analyze packets.

Popular Tools:

- Wireshark.
- Zeek.
- tcpdump.
- NetworkMiner.

2.9 Email Security

Email security solutions protect organizations against phishing, malicious attachments, spam, and email-based attacks.

Popular Tools:

- Microsoft Defender for Office 365.
- Proofpoint.
- Mimecast.

2.10 Ticketing and Incident Management

Ticketing tools help SOC analysts document alerts, record investigation findings, track incidents, and escalate cases.

Popular Tools:

- ServiceNow.
- Jira Service Management.
- TheHive.

2.11 Vulnerability Management

These tools identify security weaknesses and vulnerabilities in systems and networks.

Popular Tools:

- Nessus.
- Qualys.
- Rapid7 InsightVM.

2.12 Threat Intelligence

Threat intelligence tools provide information about malicious IP addresses, domains, URLs, malware, and Indicators of Compromise (IOCs).

Popular Resources:

- VirusTotal.
- AbuseIPDB.
- MISP.
- AlienVault OTX.

### 1\. True Positive Indicators

* Malicious IP/Domain: Connection to a known malicious IP or domain.

* Unusual Activity Time: Accessing sensitive data at unusual hours (e.g., 3 AM).

* Privilege Escalation: Unauthorized attempts to gain higher privileges.

* Data Exfiltration: Large amounts of data uploaded to external storage.

* Failed Logins Followed by Success: Multiple failed login attempts followed by successful login.

### 2\. Common False Positives

* Automated Scans: Legitimate system scans triggering port scan alerts.

* Admin Activity: Normal admin actions flagged as suspicious.

* Poor SIEM Rules: Low detection thresholds generating unnecessary alerts.

* Benign Software: Legitimate software flagged by EDR.

* Scheduled Tasks: Normal scheduled tasks appearing as unusual processes.


3. SOC Team Structure and Responsibilities

A SOC team consists of different professionals who work together to protect an organization's digital environment.

Role| Main Responsibility
CISO| Overall security strategy
SOC Manager| Manages SOC operations
SOC L1 Analyst| Initial alert monitoring and investigation
SOC L2 Analyst| Detailed incident investigation
SOC L3 Analyst| Advanced threat hunting and analysis
Security Engineer| Manages security infrastructure
Detection Engineer| Develops detection rules
IR Team| Handles security incidents

SOC L1 Analyst Responsibilities:

- Monitor security alerts.
- Review SIEM alerts.
- Perform initial investigations.
- Analyze relevant logs.
- Identify suspicious activities.
- Document findings.
- Escalate potential incidents to L2.

Critical Mistakes to Avoid as a SOC L1 Analyst

- Ignoring Alerts: Never ignore an alert just because it appears harmless.
- Poor Documentation: Always record investigation findings in the incident ticket.
- Missing Evidence: Collect relevant logs and supporting information.
- Failure to Escalate: Escalate suspicious incidents according to organizational procedures.

Key Principle: If it isn't documented, there is no reliable record of the investigation.

4. The Three Main Pillars of SOC

An effective SOC operates through three major pillars:

1. People: Security professionals responsible for protecting the organization.
2. Process: Rules, procedures, and workflows followed during security investigations.
3. Technology: Tools used for monitoring, detection, investigation, and response.

Five Ws Framework

SOC analysts use the Five Ws to understand security incidents.

- What: What happened?
- When: When did it happen?
- Where: Where did it happen?
- Who: Who was involved?
- Why: Why did it happen?

This framework helps analysts investigate incidents and prepare accurate reports.

5. Importance of Logs in Cybersecurity

Logs are records of activities generated by systems, applications, servers, and network devices.

Important Types of Logs:

- Firewall Logs.
- Windows Event Logs.
- Linux System Logs.
- Authentication Logs.
- Network Logs.
- Application Logs.
- Endpoint Logs.

Why Are Logs Important?

They help SOC analysts investigate suspicious activities, identify unauthorized access, understand attack patterns, and collect evidence.

Tools for Log Analysis:

- Splunk.
- Elastic Stack (ELK).
- Graylog.
- Microsoft Sentinel.

6. MSSP (Managed Security Service Provider)

An MSSP is a third-party company that provides cybersecurity services to other organizations.

Companies that cannot maintain their own SOC can outsource security operations to an MSSP.

Main Services:

- Security monitoring.
- Threat detection.
- SIEM management.
- Incident response support.
- Vulnerability monitoring.
- Security reporting.

7. Human Beings as an Attack Vector

Human beings are important targets for cybercriminals because attackers often manipulate people instead of directly attacking technical systems.

7.1 Social Engineering

Social engineering involves manipulating people into revealing confidential information or performing unsafe actions.

Common Techniques:

- Building trust.
- Creating urgency.
- Emotional manipulation.
- Impersonation.

7.2 Phishing

Phishing is a cyberattack in which attackers use fake emails, messages, or websites to steal sensitive information.

Examples:

- Fake login pages.
- Fraudulent links.
- Suspicious email attachments.
- Fake banking notifications.

7.3 Other Human-Focused Attacks

- Malware Downloads: Tricking users into downloading malicious files.
- Deepfake Attacks: Using fake audio or videos to impersonate people.
- Impersonation: Pretending to be trusted individuals.
- Keylogging: Recording keyboard inputs to steal information.
- Credential Theft: Stealing usernames and passwords.
- Physical Attacks: Gaining unauthorized physical access to devices or workplaces.

8. PhishTank – Phishing Detection

Website: https://phishtank.org/

PhishTank is a community-based platform used to check and investigate reported phishing URLs.

Main Uses:

- Checking suspicious URLs.
- Identifying reported phishing websites.
- Supporting phishing investigations.

9. How to Defend Against Cyberattacks

9.1 Mitigation

Mitigation means reducing the possibility or impact of cyberattacks.

Important Methods:

- Use strong and unique passwords.
- Enable Multi-Factor Authentication (MFA).
- Avoid suspicious links and attachments.
- Keep software updated.
- Follow security policies.
- Apply least-privilege access.

9.2 Detection

Detection means identifying suspicious activities as early as possible.

Important Solutions:

- Anti-phishing solutions.
- Antivirus software.
- EDR solutions.
- SIEM solutions.
- Network monitoring tools.

9.3 Zero Trust Security

Zero Trust follows the principle:

Never Trust, Always Verify.

Important Principles:

- Verify every access request.
- Authenticate users and devices.
- Apply least-privilege access.
- Continuously monitor activities.
- Use strict access controls.

9.4 Security Awareness Training

Employees should receive regular training about:

- Phishing attacks.
- Social engineering.
- Password security.
- MFA.
- Suspicious links.
- Reporting security incidents.

10. Important SOC Abbreviations

Abbreviation| Full Form
SOC| Security Operations Center
SIEM| Security Information and Event Management
EDR| Endpoint Detection and Response
XDR| Extended Detection and Response
IDS| Intrusion Detection System
IPS| Intrusion Prevention System
EPP| Endpoint Protection Platform
SOAR| Security Orchestration, Automation and Response
CISO| Chief Information Security Officer
IR| Incident Response
MSSP| Managed Security Service Provider
CSIRT| Computer Security Incident Response Team
CERT| Computer Emergency Response Team
MFA| Multi-Factor Authentication
IOC| Indicator of Compromise
IOA| Indicator of Attack
IP| Internet Protocol
DNS| Domain Name System
VPN| Virtual Private Network
URL| Uniform Resource Locator
HTTP| Hypertext Transfer Protocol
HTTPS| Hypertext Transfer Protocol Secure
OS| Operating System
IT| Information Technology
AV| Antivirus

11. Conclusion

A Security Operations Center plays an important role in protecting organizations against cybersecurity threats.

A successful SOC depends on three main pillars: People, Process, and Technology.

SOC L1 analysts are responsible for monitoring alerts, analyzing logs, performing initial investigations, documenting findings, and escalating suspicious incidents.

Understanding tools such as Splunk, CrowdStrike Falcon, Microsoft Sentinel, Wireshark, ServiceNow, and other security solutions is important for developing practical SOC skills.

Cybersecurity also requires awareness of human-focused attacks such as phishing, social engineering, and credential theft.

The ultimate goal of a SOC is to detect, investigate, and respond to security threats effectively.

---

Documentation Focus: SOC Fundamentals, SOC L1 Responsibilities, SIEM, Splunk, EDR, XDR, Security Tools, Log Analysis, Ticketing Systems, MSSP, Incident Response, Human Attack Vectors, and Security Awareness.
