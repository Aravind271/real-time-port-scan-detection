# Real-Time Port Scan Detection and Automated Response Framework

## Overview
This project implements a lightweight Network Intrusion Detection System (NIDS)
to detect port scanning behavior using log-based network traffic analysis and
automated response mechanisms.

## Motivation
Port scanning is a common reconnaissance technique used before cyber attacks.
This project aims to detect such behavior in real time and automatically block
malicious sources.

## System Architecture
- Traffic capture: Libpcap
- Detection engine: Python
- Response: Linux iptables
- Visualization: Splunk SIEM

## Detection Techniques
- TCP SYN scan detection
- Connect scan detection
- Slow-rate scan detection
- Rule-based threshold analysis

## Automated Response
- Dynamic firewall rule insertion
- IP blocking based on detection confidence

## Tools & Technologies
Python, Linux, Libpcap, iptables, Splunk, TCP/IP

## Future Work
- Extend to general network behavior monitoring
- Add anomaly-based detection
- Performance evaluation under high traffic
