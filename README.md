# Hybrid IDS & Honeypot System Using AI

This repository presents a graduation project in cybersecurity that combines
a Honeypot system with an Intrusion Detection System (IDS) enhanced by
Artificial Intelligence for detecting and analyzing cyber attacks.

# Project Objective
The main goal of this project is to design and implement a hybrid security
architecture capable of:
- Detecting network-based attacks
- Analyzing attacker behavior
- Improving detection accuracy using AI

# System Architecture
The system consists of three main environments:

- Attacker Machine: Kali Linux
- Victim Machine: Ubuntu running Cowrie Honeypot
- Detection & Analysis Machine: Ubuntu Server running Suricata IDS and AI


# Attack Flow:
Kali Linux → Cowrie Honeypot → Suricata IDS → AI Analysis

# Technologies Used
- Cowrie SSH Honeypot
- Suricata IDS
- Ubuntu Server 24.04 LTS
- Kali Linux
- Python
- VMware

 # Implemented Attacks
- SSH Brute-force attack using Hydra
- Network scanning and intrusion attempts

 # Logs & Analysis
- Cowrie logs (JSON)
- Suricata alerts (eve.json)
- AI-based anomaly detection (Isolation Forest)

# Project Status
- Cowrie Honeypot:  Implemented
- Suricata IDS:  In progress
- AI Analysis: 🔄 Planned
