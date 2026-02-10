# Wireshark-Traffic-Analysis
Network traffic capture, analysis, and reporting using Wireshark
# Wireshark Traffic Analysis Project

## Objective
To capture and analyze live network traffic and identify normal and suspicious activity.

## Tools Used
- Wireshark

## Environment
- Network Interface: Wi-Fi
- Operating System: Windows
- Capture Duration: 5–10 minutes

## Methodology
- Captured live network traffic using Wireshark
- Applied protocol-based filters (TCP, DNS, ICMP)
- Analyzed traffic behavior and packet patterns

## Observations
### Normal Traffic
- DNS queries for domain name resolution
- TCP 3-way handshake during web access

### Suspicious Traffic
- Excessive ICMP Echo Requests from a single source IP
- Possible indication of ping flood activity

## Impact
Abnormal traffic may cause network slowdown and resource exhaustion.

## Recommendations
- Block suspicious IP addresses
- Apply ICMP rate limiting
- Continuous network monitoring

## Conclusion
The project demonstrates basic SOC-level traffic monitoring and analysis skills.
