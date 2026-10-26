# UptoSkills-VAPT-Assessment-Nmap
Authorized VAPT assessment project for UptoSkills. Includes reconnaissance, Nmap scanning results, vulnerability analysis, findings, and security recommendations documented during the cybersecurity internship.
UptoSkills VAPT Assessment - Nmap
Overview
This repository contains the Nmap-based reconnaissance and network assessment conducted as part of an authorized Vulnerability Assessment and Penetration Testing (VAPT) activity.

The objective was to identify active hosts, discover open ports, detect services, perform basic enumeration, and document security observations using Nmap.

Tool Used
Nmap 7.95
Kali Linux
Activities Performed
Host Discovery
Ping Sweep (-sn)
Live Host Identification
Port Scanning
Default TCP Scan
SYN Scan (-sS)
Specific Port Scan (-p)
Top 1000 Port Scan
Full Port Scan (-p-)
Service Enumeration
Service Version Detection (-sV)
Default Script Scan (-sC)
Aggressive Scan (-A)
Network Analysis
Traceroute
Multi-host Scanning
Subnet Enumeration
UDP Analysis
DNS (53)
DHCP (67/68)
NTP (123)
SNMP (161/162)
OpenVPN (1194)
Reporting
Normal Output (-oN)
XML Output (-oX)
Key Findings
Open TCP Ports
80/tcp (HTTP)
443/tcp (HTTPS)
8080/tcp (HTTP Proxy)
8443/tcp (HTTPS Alternate)
Service Detection
Cloudflare Proxy Services Identified
Multiple Web-facing Services Accessible
OS Detection
Nmap generated multiple operating system fingerprints; however, results were inconclusive due to filtering and Cloudflare protection.

Vulnerability Checks
Using Nmap NSE vulnerability scripts:

No DOM-based XSS detected
No Stored XSS detected
No CSRF issues detected
No critical vulnerabilities identified through NSE scripts
Recommendations
Keep all web services updated.
Regularly review firewall rules.
Harden exposed services and alternate ports.
Conduct application-level testing for:
SQL Injection
Authentication Issues
Access Control Weaknesses
Remote Code Execution
Continuously monitor exposed services.
Disclaimer
This assessment was conducted only within the scope of authorized security testing. All activities were performed for educational and security assessment purposes and in accordance with applicable authorization requirements.

Author
Aharnish Dhaw Kumar

Cybersecurity Intern | VAPT | Penetration Testing | Network Security
