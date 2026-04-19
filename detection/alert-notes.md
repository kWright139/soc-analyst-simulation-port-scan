# Detection Notes

## Tool Used
Wireshark (Network Protocol Analyzer)

## Detection Method
- Live packet capture on `eth0`
- Display filter applied: `icmp`

## Key Observations
- Clear identification of ICMP packets
- Visibility into source and destination IP addresses
- Ability to inspect packet structure and payload

## Analyst Insight
Filtering traffic by protocol significantly improves visibility and reduces noise, allowing analysts to focus on relevant data during investigations.