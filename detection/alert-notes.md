# Detection Notes

## Suricata Alerts
- Alert Type: Port Scan Detection
- Signature: ET SCAN Nmap SYN Scan

## Zeek Logs
- Multiple connection attempts recorded
- High volume of connections from single source IP

## Detection Summary
Both Suricata and Zeek provided strong indicators of scanning behavior. Correlation between tools confirmed malicious intent.

## Analyst Notes
Cross-referencing alerts with logs improves confidence in detection and reduces false positives.