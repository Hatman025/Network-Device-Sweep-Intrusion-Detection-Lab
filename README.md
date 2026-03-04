# Network-Device-Sweep-Intrusion-Detection-Lab
A hands-on cybersecurity lab for discovering live network devices,  mapping subnets, and simulating basic intrusion detection techniques, using native Linux tools and no third-party dependencies required.


## Overview

This lab demonstrates how attackers and defenders use **ICMP ping sweeps** 
to perform network reconnaissance. It covers:

- Discovering live hosts across a subnet (.1 – .254)
- Logging and parsing ping responses to extract active IPs
- Simulating basic Intrusion Detection System (IDS) alerting
- Writing structured sweep results to output files for analysis

Built entirely in **Bash**, this project is ideal for students studying 
for CompTIA Security+, CEH, or OSCP — or anyone exploring ethical hacking 
fundamentals on Kali Linux.

---

## Features

| Feature                        | Description                                      |
|-------------------------------|--------------------------------------------------|
| 🔎 Subnet Ping Sweep           | Scans all 254 hosts in a /24 subnet              |
| 📄 Result Logging              | Saves UP/DOWN status to `sweep_results.txt`      |
| 🧠 IP Extraction               | Parses and extracts responding IP addresses      |
| 🚨 IDS Simulation              | Flags unusual response patterns as alerts        |
| 🐧 Kali Linux Native           | Uses only built-in tools (ping, grep, bash)      |




##  Project Structure

network-sweep-lab/
├── testsweep.sh          # Main ping sweep script
├── sweep_results.txt     # Output log (auto-generated)
├── ids_monitor.sh        # IDS alert simulation script
└── README.md             # Project documentation
\`\`\`

---

##  Disclaimer

> This project is intended for **educational and authorized testing purposes only**.  
> Never run network scans on systems or networks you do not own or have 
> explicit permission to test. Unauthorized scanning is illegal.

---

##  Learning Objectives

- Understand ICMP and how ping works at the network layer
- Perform host discovery using command-line tools
- Analyze network traffic patterns for anomaly detection
- Practice writing structured Bash scripts for security automation

---





-
