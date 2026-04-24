# Cybersecurity Lab - IDS & IPS using Suricata

## 📌 Overview
This project demonstrates the design and implementation of Intrusion Detection System (IDS) and Intrusion Prevention System (IPS) using Suricata. It focuses on real-time threat detection, prevention, and network security analysis.

## 🎯 Objectives
- Understand IDS vs IPS concepts
- Implement detection rules
- Perform real-time threat mitigation
- Analyze network logs and attacks

## 🛠️ Tools & Technologies
- Kali Linux
- Suricata
- iptables (NFQUEUE)
- arpspoof

## ⚙️ Features
- ICMP reconnaissance detection
- SYN Flood (DoS) attack detection
- Inline IPS configuration
- ARP spoofing detection (MITM attack)
- Log analysis using Suricata logs

## 🧪 Implementation Steps
1. Install and configure Suricata
2. Enable promiscuous mode
3. Add custom detection rules
4. Integrate NFQUEUE using iptables
5. Simulate attacks (ICMP, SYN Flood, ARP Spoofing)
6. Analyze logs from `/var/log/suricata/fast.log`

## 📊 Key Findings
- IDS provides monitoring and alerts
- IPS actively blocks malicious traffic
- Real-time detection improves network security
- Proper rule tuning reduces false positives

## 🔒 Recommendations
- Deploy IPS in critical systems
- Strengthen Layer 2 security (DAI, DHCP Snooping)
- Regularly update detection rules

## 📁 Author
Muhammad Usama Bilal

## 📚 Instructor
Muhammad Saad
