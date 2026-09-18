# Networkwalks Week 2 – Penetration Testing

## 📌 Project Overview

This repository documents my Week 2 practical work completed as part of my Cybersecurity Internship at Networkwalks.

The practical work focused on two important phases of penetration testing:

1. Footprinting & Reconnaissance
2. Network Scanning & Discovery

The objective was to understand how security professionals collect information, analyze network details, identify live hosts, and document their findings within an authorized scope.

## 🎯 Objectives

- Understand the fundamentals of footprinting and reconnaissance
- Perform basic domain and DNS information gathering
- Identify web technologies and security mechanisms
- Understand network configuration and subnet information
- Discover live hosts within an authorized local network
- Identify IP and MAC address information
- Perform network scanning using Zenmap/Nmap
- Document practical observations and evidence

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| WHOIS | Domain registration and information gathering |
| WhatWeb | Web technology fingerprinting |
| nslookup | DNS information and name resolution |
| cURL | HTTP header inspection |
| Wafw00f | Web Application Firewall detection |
| DNSRecon | DNS enumeration and record discovery |
| ipconfig | Local network configuration |
| ARP | IP-to-MAC address mapping |
| Zenmap / Nmap | Network scanning and host discovery |
| Windows CMD | Network troubleshooting and information gathering
# 🔎 Phase 1 – Footprinting & Reconnaissance

Footprinting and reconnaissance were performed to understand the publicly observable information associated with the authorized target.

### Activities Performed

- WHOIS information gathering
- Website technology fingerprinting using WhatWeb
- DNS lookup using nslookup
- HTTP header inspection using cURL
- WAF detection using Wafw00f
- DNS enumeration using DNSRecon

### Key Learning

I learned how different reconnaissance tools provide different types of information and how their outputs can be interpreted during the initial phase of a penetration testing workflow.

# 🌐 Phase 2 – Network Scanning & Discovery

Network scanning was performed on the authorized local network to identify active hosts and understand basic network relationships.

### Activities Performed

- Checked local IP configuration using `ipconfig`
- Identified the local subnet
- Performed Ping Scan using Zenmap
- Identified live hosts
- Checked IP-to-MAC address mappings using `arp -a`
- Generated a network topology using Zenmap

### Scan Result

**Network:** `10.155.34.0/24`

**Live Hosts Identified:** 2

The practical scan identified two active hosts within the authorized local network.

> Note: Detailed IP and MAC address information is not published here to avoid exposing network-specific information publicly.

# 📚 Key Learning Outcomes

Through this practical, I gained hands-on exposure to:

- Footprinting and reconnaissance
- DNS enumeration
- Web technology identification
- WAF detection
- Network configuration analysis
- Host discovery
- IP and MAC address mapping
- Network scanning with Zenmap/Nmap
- Network topology visualization
- Security documentation and evidence collection

# 📸 Evidence

The repository contains selected screenshots and documentation from the practical activities.

Sensitive network information has been redacted where necessary before public sharing.

# 📄 Project Documentation

The detailed penetration testing report covering the Week 2 activities is included in this repository.

**Modules Covered:**

- W2-PM1 – Footprinting & Reconnaissance
- W2-PM5 – Network Scanning with Zenmap

# ⚠️ Disclaimer

All activities documented in this repository were performed for authorized educational and internship purposes.

No unauthorized access, exploitation, or attack against systems was performed.

The network scanning activity was conducted only within the authorized local network scope.

## 👩‍💻 Author

**Sahana S**
Cybersecurity Student  
Cybersecurity Internship – Networkwalks


## 🔐 Cybersecurity Focus

**SOC Operations | Network Security | Penetration Testing | Red Team Practices | Security Monitoring**
