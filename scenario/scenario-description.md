# Scenario Description

## Objective
Simulate and investigate network activity from a Security Operations Center (SOC) analyst perspective by capturing and analyzing live traffic.

## Environment
- Platform: VMware Workstation Pro
- OS: Kali Linux (pre-built VM)
- Network Mode: NAT
- Tools Used:
  - Wireshark
  - Ping (ICMP traffic generation)

## Activity Performed
A continuous ICMP ping was sent from the Kali Linux system to an external host (8.8.8.8) to generate observable network traffic.

Command used:
ping 8.8.8.8

## Detection Method
Wireshark was used to capture live network traffic on interface `eth0`. A display filter (`icmp`) was applied to isolate relevant packets.

## Analyst Goal
- Capture live network traffic
- Filter relevant packets
- Identify source and destination
- Analyze packet structure and behavior