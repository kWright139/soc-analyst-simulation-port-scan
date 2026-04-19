# Scenario Description

## Objective
Simulate and investigate a reconnaissance attack using a TCP SYN port scan.

## Environment Setup
- Kali Linux used as the attacker machine
- Ubuntu VM used as the target
- Security Onion used for monitoring and detection

## Attack Execution
The following command was executed on Kali Linux:
nmap -sS 192.168.1.20

## Expected Behavior
- Multiple connection attempts to various ports
- Minimal handshake completion (SYN packets)
- Detection by IDS/IPS tools

## Detection Sources
- Suricata alerts
- Zeek connection logs

## Analyst Goal
Identify:
- Source of attack
- Type of activity
- Targeted ports
- Potential risk level