# Network-Traffic-Visibility-and-Protocol-Analysis-Using-Zeek
A cybersecurity lab project demonstrating network traffic monitoring, protocol analysis, and log investigation using Zeek Network Security Monitor.

## Overview

This project demonstrates the use of Zeek Network Security Monitor to capture and analyze network traffic in a Kali Linux environment. The objective was to gain visibility into network communications by investigating DNS, connection, and SSL/TLS logs generated from normal web browsing activity.

---

## Objectives

- Configure and deploy Zeek
- Capture live network traffic
- Analyze DNS, connection, and SSL/TLS logs
- Understand network visibility and monitoring concepts

---

## Tools Used

- Zeek
- Kali Linux
- Firefox
- GitHub

---

## Lab Architecture

User Traffic
     ↓
    Zeek
     ↓
 ┌─────────┬─────────┬─────────┐
 │ dns.log │ conn.log│ ssl.log │
 └─────────┴─────────┴─────────┘
     ↓
  Analysis

---

## Methodology

1. Installed and configured Zeek.
2. Monitored the active network interface.
3. Generated traffic through web browsing.
4. Collected Zeek logs.
5. Analyzed DNS, connection, and SSL/TLS activity.

---

## Log Analysis

### DNS Analysis

- Identified queried domains
- Observed DNS record types
- Examined domain resolution activity

### Connection Analysis

- Analyzed source and destination communications
- Reviewed protocols and port usage
- Investigated network connection patterns

### SSL/TLS Analysis

- Examined encrypted communications
- Reviewed server names and TLS information

---

## Key Findings

- Successfully captured network traffic using Zeek
- Observed DNS requests to commonly used websites
- Identified active TCP and UDP connections
- Monitored encrypted HTTPS communications
- Demonstrated protocol-level visibility into network activity

---

## Skills Demonstrated

- Network Traffic Analysis
- Network Security Monitoring
- Zeek Log Analysis
- DNS Investigation
- Protocol Analysis
- Linux Administration

---

## Future Improvements

- Integrate Zeek with Splunk
- Create custom detection rules
- Develop threat-hunting use cases

---

## Conclusion

This project demonstrates how Zeek can be used to monitor and analyze network communications. The generated logs provide valuable visibility into network activity and support security monitoring and investigation workflows.
