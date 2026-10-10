# ⚔️ Penetration Tester & Ethical Hacker Roadmap (100% Free Labs)

> **Role Overview:** A Penetration Tester (Ethical Hacker) identifies security vulnerabilities in networks, web applications, and systems before malicious attackers exploit them. This role requires deep knowledge of offensive techniques, enumeration, vulnerability exploitation, and privilege escalation.

---

## 🎯 Key Competencies & Skill Matrix

```
       [ Recon & Scanning ]    ──────────► ( Nmap, Rustscan, GoBuster )
                 │
       [ Web App Security ]    ──────────► ( Burp Suite, OWASP Top 10, SQLi, XSS )
                 │
       [ System Exploitation ] ──────────► ( Metasploit, Searchsploit, Custom Exploits )
                 │
       [ Privilege Escalation ]──────────► ( LinPEAS, WinPEAS, SUID, Sudo rules )
```

---

## 🎓 Aligned Industry Certifications
- **eJPT** (eLearnSecurity Junior Penetration Tester)
- **PNPT** (Practical Network Penetration Tester)
- **CompTIA PenTest+** (PT0-002)
- **OSCP** (Offensive Security Certified Professional)
- **CEH** (Certified Ethical Hacker)

---

## 🚀 Phase 1: Offensive Security Fundamentals & Networking

Master foundational networking tools and essential command-line scanning techniques.

| # | Room Name | Difficulty | Est. Time | Direct Link | Primary Skill / Learning Objective |
|---|-----------|------------|-----------|-------------|-----------------------------------|
| 1 | **Starting Off in Cybersecurity** | Info | 20 mins | [Access THM](https://tryhackme.com/room/startingoffincsecurity) | Overview of ethical hacking paths & methodologies |
| 2 | **Nmap** | Easy | 1 hr | [Access THM](https://tryhackme.com/room/nmap) | Network scanning, port discovery, script engine (NSE) |
| 3 | **Further Nmap** | Medium | 1 hr | [Access THM](https://tryhackme.com/room/furthernmap) | Advanced scan flags, stealth scanning, evasion techniques |
| 4 | **Subdomain Enumeration** | Easy | 45 mins | [Access THM](https://tryhackme.com/room/subdomainenumeration) | Sublist3r, OSINT DNS enumeration, virtual host discovery |
| 5 | **Network Services** | Easy | 1.5 hrs | [Access THM](https://tryhackme.com/room/networkservices) | Enumerating SMB, Telnet, FTP services |
| 6 | **Network Services 2** | Easy | 1.5 hrs | [Access THM](https://tryhackme.com/room/networkservices2) | Enumerating & exploiting NFS, SMTP, MySQL |

---

## 🌐 Phase 2: Web Application Security (OWASP Top 10)

Learn how web applications are attacked and exploited using industry-standard proxies and tools.

| # | Room Name | Difficulty | Est. Time | Direct Link | Primary Skill / Learning Objective |
|---|-----------|------------|-----------|-------------|-----------------------------------|
| 7 | **Burp Suite: The Basics** | Easy | 1 hr | [Access THM](https://tryhackme.com/room/burpsuitebasics) | Intercepting proxy, request modification, Repeater |
| 8 | **Burp Suite: Repeater** | Easy | 45 mins | [Access THM](https://tryhackme.com/room/burpsuiterepeater) | Manual HTTP request manipulation & parameter fuzzing |
| 9 | **OWASP Top 10** | Easy | 3 hrs | [Access THM](https://tryhackme.com/room/owasptop10) | Hands-on walkthrough of the 10 most critical web vulns |
| 10 | **SQL Injection** | Easy | 1.5 hrs | [Access THM](https://tryhackme.com/room/sqlinjection) | In-band, blind, and error-based SQLi techniques |
| 11 | **Cross-Site Scripting (XSS)** | Easy | 1.5 hrs | [Access THM](https://tryhackme.com/room/xssgi) | Stored, Reflected, and DOM-based XSS exploitation |
| 12 | **Upload Vulnerabilities** | Medium | 2 hrs | [Access THM](https://tryhackme.com/room/uploadvulns) | Bypassing file upload restrictions for Remote Code Execution (RCE) |

---

## 💥 Phase 3: Exploitation Frameworks & Privilege Escalation

Gain initial shell access and escalate privileges on Linux and Windows targets.

| # | Room Name | Difficulty | Est. Time | Direct Link | Primary Skill / Learning Objective |
|---|-----------|------------|-----------|-------------|-----------------------------------|
| 13 | **Metasploit: Introduction** | Easy | 1 hr | [Access THM](https://tryhackme.com/room/metasploitintro) | Msfconsole, modules, payloads, listening & handling shells |
| 14 | **Linux Privilege Escalation** | Easy/Medium | 2 hrs | [Access THM](https://tryhackme.com/room/linprivesc) | SUID binaries, cron jobs, sudo misconfigurations, capabilities |
| 15 | **Windows Privilege Escalation** | Medium | 2 hrs | [Access THM](https://tryhackme.com/room/windowsprivilegeescalation) | Unquoted service paths, token manipulation, automated scripts |
| 16 | **Ignite** | Easy CTF | 1 hr | [Access THM](https://tryhackme.com/room/ignite) | Real-world Fuel CMS vulnerability exploitation to root |
| 17 | **Pickle Rick** | Easy CTF | 1 hr | [Access THM](https://tryhackme.com/room/picklerick) | Rick and Morty themed web enumeration & privilege escalation |
| 18 | **Brooklyn 99** | Easy CTF | 45 mins | [Access THM](https://tryhackme.com/room/brooklyn99) | Beginner friendly CTF with steganography, SSH bruteforce & sudo |

---

## 💻 Recommended Portfolio Projects for PenTesters
1. **CTF Writeup Repository:** Write clean markdown writeups for rooms like *Pickle Rick*, *Ignite*, or *OWASP Top 10* using the template in [`templates/thm-lab-writeup-template.md`](../templates/thm-lab-writeup-template.md).
2. **Professional Penetration Testing Report:** Create a mock pentest executive report summarizing web application vulnerabilities, impact scores (CVSS), and mitigation advice using [`templates/pentest-report-template.md`](../templates/pentest-report-template.md).
