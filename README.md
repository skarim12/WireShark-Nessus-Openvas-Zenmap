# Active Reconnaissance & Vulnerability Enumeration Lab

## Overview
This lab demonstrates the active reconnaissance phase of a penetration test using industry-standard security tools. The objective was to identify live hosts, enumerate services, analyze network traffic, and discover vulnerabilities through network and vulnerability scanning.

## Objectives
- Discover live hosts on target networks
- Identify open ports and running services
- Detect operating systems and software versions
- Capture and analyze scan traffic with Wireshark
- Perform vulnerability assessments using Nessus and OpenVAS
- Compare multiple Nmap scan techniques

## Tools Used
- Zenmap (Nmap GUI)
- Nmap
- Wireshark
- Nessus Essentials
- OpenVAS (Greenbone)
- Kali Linux

## Techniques Performed

### Host Discovery
- ICMP Ping Scan (-sn)
- Network mapping
- Reverse DNS lookups
- Host identification

### Port Scanning
- TCP SYN Scan (-sS)
- TCP Connect Scan
- ACK Scan (-sA)
- UDP Scan (-sU)
- Aggressive Scan (-A)
- Version Detection (-sV)
- OS Detection (-O)
- Traceroute
- Timing Templates (-T4/-T5)

### Packet Analysis
Captured network traffic using Wireshark to analyze:
- TCP three-way handshake
- SYN, SYN/ACK, ACK, and RST packets
- UDP communication
- Source and destination IP addresses
- TCP/UDP headers
- Packet payloads

### Vulnerability Assessment
Performed vulnerability scans using:
- Nessus Essentials
- OpenVAS (Greenbone)

Identified:
- High, Medium, Low, and Informational findings
- CVSS scores
- Service vulnerabilities
- Security misconfigurations
- Recommended remediations

## Skills Demonstrated
- Active Reconnaissance
- Network Enumeration
- Port Scanning
- Service Enumeration
- Operating System Fingerprinting
- Packet Analysis
- Vulnerability Assessment
- Network Traffic Analysis
- Security Tool Configuration
- Cybersecurity Documentation

## Key Takeaways
This project provided practical experience with the reconnaissance phase of penetration testing by combining network scanning, packet analysis, and vulnerability assessment. Using Zenmap, Nmap, Wireshark, Nessus, and OpenVAS, I identified hosts, analyzed network communications, discovered vulnerabilities, and documented security findings. These exercises strengthened my understanding of how attackers enumerate networks and how defenders can detect and mitigate reconnaissance activity.
