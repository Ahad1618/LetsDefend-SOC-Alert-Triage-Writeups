# LetsDefend SOC Alert Triage Writeups

This repository contains a collection of detailed SOC (Security Operations Center) alert triage reports completed on the [LetsDefend](https://letsdefend.io) platform. LetsDefend provides a realistic SOC environment with integrated EDR, SIEM, logs, and threat intelligence, allowing hands-on experience with real-world scenarios.

## Contents

Each alert write-up includes:

- **Alert context and summary**
- **Investigation process and tool outputs**
- **Extracted artifacts and IoCs**
- **Triage answers and conclusions**

## Covered Categories

- **Malware Analysis**
  - Tools used: [Anyrun](https://any.run), [VirusTotal](https://virustotal.com), [Cuckoo Sandbox](https://cuckoosandbox.org), [MalwareBazaar](https://bazaar.abuse.ch)
  - Static and dynamic analysis using: `oletools`, `strings`, `exiftool`, etc.

- **Cyber Threat Intelligence (CTI)**  
  - IOC extraction and enrichment from sandbox and threat feeds

- **Phishing Detection**
  - Email headers, links, attachments, and payload analysis

- **Web Attack Detection**
  - Identifying and analyzing:
    - Local File Inclusion (LFI)
    - SQL Injection (SQLi)
    - Cross-Site Scripting (XSS)
    - Command Injection
    - Directory Traversal

## Tools & Techniques Used

- **EDR/SIEM Log Analysis**
- **Malware Sandboxing**
- **Kali Linux-based static analysis**
- **Threat intelligence lookups**
- **Manual alert triage workflow**

## Purpose

This repository serves as:

- A **personal portfolio** to showcase practical SOC experience
- A **learning resource** for aspiring SOC analysts, blue teamers, and cybersecurity students
- A **reference** for detection and investigation workflows

