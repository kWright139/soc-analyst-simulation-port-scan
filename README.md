# SOC Analyst Simulation: Port Scan Investigation

## Overview
This project simulates a Security Operations Center (SOC) analyst investigating a potential reconnaissance attack in a controlled lab environment. A port scan was conducted from an attacker machine, and alerts/logs were analyzed using Security Onion.

## Tools Used
- Security Onion
- Kali Linux
- Nmap
- Zeek
- Suricata

## Lab Environment
- Attacker: Kali Linux (192.168.1.10)
- Target: Ubuntu VM (192.168.1.20)
- Monitoring: Security Onion

## Scenario Summary
An Nmap TCP SYN scan was launched from the attacker machine targeting the victim system. Security Onion detected suspicious activity and generated alerts, which were investigated to determine intent and impact.

## Skills Demonstrated
- Alert triage
- Network traffic analysis
- Log analysis (Zeek & Suricata)
- Incident timeline creation
- IOC identification
- Security documentation

## Key Findings
- Source IP: 192.168.1.10
- Destination IP: 192.168.1.20
- Activity: TCP SYN scan (reconnaissance)
- Detection: Suricata alert + Zeek connection logs
- Conclusion: Malicious scanning behavior consistent with pre-attack reconnaissance

## Project Structure
soc-analyst-simulation-port-scan/
├── README.md
├── scenario/
├── investigation/
├── evidence/
├── detection/
└── lessons-learned.md


## 🧠 Conclusion
This activity represents early-stage reconnaissance often used by attackers to identify open ports and services. Proper detection and response at this stage can prevent further exploitation.

---