# 🛡️ Security Operations Center (SOC) & Security Analyst Roadmap (100% Free Labs)

> **Role Overview:** A SOC Security Analyst is the frontline defender of an organization. Responsible for monitoring security alerts, triaging incidents, analyzing network logs, and mitigating cyber threats before they escalate into full breaches.

---

## 🎯 Key Competencies & Skill Matrix

```
       [ Log & Event Analysis ] ──────────► ( Splunk, ELK, Windows Event Logs )
                 │
       [ Network Forensics ]    ──────────► ( Wireshark, TCPDump, Zeek )
                 │
       [ Endpoint Monitoring ]  ──────────► ( Sysmon, EDR, Defender )
                 │
       [ Incident Triage ]      ──────────► ( Phishing, Malware Analysis, Snort )
```

---

## 🎓 Aligned Industry Certifications
- **CompTIA Security+** (SY0-701)
- **CompTIA CySA+** (CS0-003)
- **Blue Team Level 1** (BTL1)
- **Microsoft SC-200** (Security Operations Analyst)
- **Certified SOC Analyst** (CSA)

---

## 🚀 Phase 1: Fundamentals & Environment Setup

Build your core understanding of networking, Linux/Windows operating systems, and defensive security.

| # | Room Name | Difficulty | Est. Time | Direct Link | Primary Skill / Learning Objective |
|---|-----------|------------|-----------|-------------|-----------------------------------|
| 1 | **OpenVPN Setup** | Info | 15 mins | [Access THM](https://tryhackme.com/room/openvpn) | Connect your terminal to TryHackMe attack boxes |
| 2 | **Welcome to TryHackMe** | Info | 10 mins | [Access THM](https://tryhackme.com/room/welcometthm) | Platform navigation & lab machine interaction |
| 3 | **Intro to Cyber Security** | Easy | 30 mins | [Access THM](https://tryhackme.com/room/introtocybersecurity) | Red vs Blue team concepts & security fundamentals |
| 4 | **Principles of Security** | Easy | 45 mins | [Access THM](https://tryhackme.com/room/principlesofsecurity) | CIA Triad, Security Controls, & Defense in Depth |
| 5 | **Linux Fundamentals 1** | Easy | 45 mins | [Access THM](https://tryhackme.com/room/linuxfundamentalspart1) | Basic Linux CLI navigation & file management |
| 6 | **Windows Fundamentals 1** | Easy | 45 mins | [Access THM](https://tryhackme.com/room/windowsfundamentals1) | Windows OS architecture, Control Panel, & GUI |

---

## 🔍 Phase 2: SIEM, Log Analysis & Detection Tools

Master the primary tools used in real-world Security Operations Centers.

| # | Room Name | Difficulty | Est. Time | Direct Link | Primary Skill / Learning Objective |
|---|-----------|------------|-----------|-------------|-----------------------------------|
| 7 | **Intro to SIEM** | Easy | 45 mins | [Access THM](https://tryhackme.com/room/introtosiem) | Concepts of SIEM, log collection, dashboards & alerts |
| 8 | **Splunk: Basics** | Easy | 1 hr | [Access THM](https://tryhackme.com/room/splunk101) | Searching logs, SPL queries, and filtering security events |
| 9 | **Wireshark: The Basics** | Easy | 1 hr | [Access THM](https://tryhackme.com/room/wiresharkthebasics) | Packet capture analysis, PCAP filter rules, & HTTP/DNS inspect |
| 10 | **Snort** | Medium | 1.5 hrs | [Access THM](https://tryhackme.com/room/snort) | IDS/IPS rule writing, network signature matching |
| 11 | **Zeek** | Medium | 1.5 hrs | [Access THM](https://tryhackme.com/room/zeekbro) | Network monitoring framework & log analysis |
| 12 | **Windows Event Logs** | Easy | 1 hr | [Access THM](https://tryhackme.com/room/windowsevents) | Investigating Event IDs 4624, 4625, 7045, & PowerShell logs |
| 13 | **Sysmon** | Medium | 1 hr | [Access THM](https://tryhackme.com/room/sysmon) | System Monitor log telemetry, process creation, & network connections |

---

## 🚨 Phase 3: Incident Response & Phishing Triage

Learn how to handle real security incidents, triage suspicious emails, and detect malware execution.

| # | Room Name | Difficulty | Est. Time | Direct Link | Primary Skill / Learning Objective |
|---|-----------|------------|-----------|-------------|-----------------------------------|
| 14 | **Phishing Emails 101** | Easy | 45 mins | [Access THM](https://tryhackme.com/room/phishingemails101) | Email header analysis, SPF/DKIM/DMARC, attachment analysis |
| 15 | **Incident Response Methodology** | Easy | 45 mins | [Access THM](https://tryhackme.com/room/incidentresponsemethodology) | PICERL framework (Preparation, Identification, Containment...) |
| 16 | **Investigat3d** | Medium | 1.5 hrs | [Access THM](https://tryhackme.com/room/investigat3d) | Hands-on Windows triage, compromised machine investigation |
| 17 | **Blueprint** | Medium | 1 hr | [Access THM](https://tryhackme.com/room/blueprint) | Blue team defenses, hardening, and network security audit |
| 18 | **Base64** | Easy | 30 mins | [Access THM](https://tryhackme.com/room/base64) | Decoding obfuscated malware payloads & PowerShell commands |

---

## 💻 Recommended Portfolio Projects for SOC Analyst
1. **Splunk Lab Writeup & Dashboards:** Create a GitHub writeup demonstrating how you queried Splunk logs to detect a brute-force SSH/RDP attack.
2. **Wireshark PCAP Analysis Report:** Analyze a malicious PCAP file, document IOCs (IP addresses, domain names, hashes), and map the attacker actions to MITRE ATT&CK. (Use template from [`templates/incident-report-template.md`](../templates/incident-report-template.md)).
