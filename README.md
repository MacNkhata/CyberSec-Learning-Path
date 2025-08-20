# CyberSec-Learning-Path
A repository to track my learning journey as I start my journey into the world of cyber security

# 🛠️ Cybersecurity Home Lab

This repository documents my journey in building a cybersecurity home lab to practice both offensive (Red Team) and defensive (Blue Team) skills. The goal is to simulate a real-world enterprise environment for penetration testing, monitoring, and incident response.

## 🚀 Lab Objectives

- Practice penetration testing (network, web apps, Active Directory).

-  Learn Active Directory attacks & defenses.

-  Configure and manage a firewall (pfSense).

-  Deploy and use a SIEM (Wazuh/ELK) for log monitoring & alerting.

-  Build a portfolio of attack/defense write-ups.

## 🏗️ Lab Topology
```Java 
Kali Linux (Attacker) ---> pfSense Firewall ---> Windows Server 2022 (AD DC)
                                            ├─> Windows 10 (Workstation)
                                            ├─> Ubuntu Server (Wazuh SIEM)
                                            └─> DVWA / Juice Shop (Vulnerable Apps)
```
- 🔴 Kali Linux – Attacker machine (Nmap, Metasploit, Burp Suite, etc.)
- 🟦 Windows Server 2022 – Active Directory Domain Controller
- 🟦 Windows 10 – Domain-joined workstation
- 🟨 pfSense – Firewall/router
- 🟩 Ubuntu Server (Wazuh/ELK) – SIEM for log collection & monitoring
- 🟪 DVWA / Juice Shop – Intentionally vulnerable apps

## ⚡ Tools & Technologies

- Offense: Nmap, Burp Suite, Metasploit, Hydra

- Defense: Wazuh SIEM, Splunk Free, Wireshark, Zeek

- Infrastructure: VMware/VirtualBox, pfSense, Ubuntu Server

- Targets: Windows AD, DVWA, Juice Shop, Metasploitable

## 📖 Progress & Writeups

I’ll be documenting:

- 📝 Attack walkthroughs (e.g., exploiting DVWA, AD enumeration)

- 📊 Blue Team detection (SIEM alerts, log queries)

- 📂 Reports & dashboards

Follow my journey on [LinkedIn](https://www.linkedin.com/in/macdonald-nkhata-8aab1025a/) & [Twitter/X](https://x.com/Mac_Nkhata)

##🔖 Tags

#CyberSecurity #Pentesting #BlueTeam #RedTeam #SIEM #LearnInPublic
