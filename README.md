Penetration-Testing
Penetration testing on Metasploitable2 - Cyber Security &amp; Ethical Hacking Intern
Full Penetration Testing & Red Team Simulation

Cybersecurity & Ethical Hacking Internship - Maincrafts Technology 

Overview

This is a complete penetration test done on Metasploitable2 as part of an internship project.

All testing was performed in a VirtualBox lab environment. No real-world systems or external networks were targeted.

Target Environment
Target Machine - Metasploitable2 
Attacker Machine - Kali Linux 
Network - VirtualBox Host-Only Adapter

 Penetration Testing Phases
1. Reconnaissance: Nmap -sn, arp-scan, netdiscover 
2. Scanning & Enumeration:  Nmap -sV, Nmap -A, Nikto 
3. Exploitation: SSH, DVWA, SQL Injection, XSS 
4. Privilege Escalation:  sudo -l, sudo su, find -perm -4000
5. Post-Exploitation:  cat /etc/shadow, ls /root, ps aux
6. Reporting: Full professional report with screenshots 

Vulnerabilities Found
PT6-001: Default SSH Credentials - Critical - Exploited 
PT6-002: SQL Injection — DVWA - Critical - Exploited 
PT6-003: XSS Reflected — DVWA - High - Exploited 
PT6-004: Sudo Misconfiguration (ALL) ALL - Critical - Exploited 
PT6-005: Outdated Kernel Linux 2.6.24 (2008) - Critical - Confirmed 
PT6-006: /etc/shadow Accessible After Escalation - High - Exploited 
PT6-007: SUID Binaries Exposed - High - Confirmed 
PT6-008: Insecure Services Running (22 open ports) - Medium - Confirmed 
PT6-009: Web Server Misconfigurations — Nikto - Medium - Confirmed 

Total: 9 vulnerabilities — 4 Critical, 3 High, 2 Medium  
Time to Root: under 5 minutes from initial access

Repository Structure
