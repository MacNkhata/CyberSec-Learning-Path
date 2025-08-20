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
