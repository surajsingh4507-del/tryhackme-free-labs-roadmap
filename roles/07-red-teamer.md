# 🔴 Red Teamer & Advanced Adversary Simulation Roadmap (100% Free Labs)

> **Role Overview:** Red Teamers perform covert, multi-stage adversary simulations against enterprise networks. They simulate Advanced Persistent Threats (APTs), bypass defensive security controls, compromise Active Directory environments, and execute post-exploitation activities.

---

## 🎯 Key Competencies & Skill Matrix

```
       [ Active Directory Attacks ] ──► ( Kerberoasting, AS-REP Roasting, BloodHound )
                 │
       [ Evasion & Stealth ]        ──► ( AV/EDR Bypass, Obfuscation, Living off the Land )
                 │
       [ Command & Control (C2) ]   ──► ( Mythic, Sliver, Covenant, Beaconing )
                 │
       [ Lateral Movement ]         ──► ( PsExec, WMI, WinRM, Pass-the-Hash )
```

---

## 🎓 Aligned Industry Certifications
- **Certified Red Team Operator** (CRTO)
- **Offensive Security Certified Expert** (OSCE / OSED / OSEP)
- **GIAC Exploit Researcher and Advanced Penetration Tester** (GXPN)

---

## 🚀 Phase 1: Active Directory Basics & Attack Vectors

| # | Room Name | Difficulty | Est. Time | Direct Link | Primary Skill / Learning Objective |
|---|-----------|------------|-----------|-------------|-----------------------------------|
| 1 | **Active Directory Basics** | Easy | 1 hr | [Access THM](https://tryhackme.com/room/activedirectorybasics) | Domain Controllers, LDAP, Kerberos authentication, GPOs |
| 2 | **Attacking Active Directory** | Medium | 2 hrs | [Access THM](https://tryhackme.com/room/attacktivedirectory) | Impacket, Kerberoasting, AS-REP Roasting, BloodHound |
| 3 | **Post Exploitation Basics** | Easy | 1 hr | [Access THM](https://tryhackme.com/room/postexploitationbasics) | Hash dumping, credential harvesting, persistence creation |

---

## 🎭 Phase 2: Red Team Operations & C2 Infrastructure

| # | Room Name | Difficulty | Est. Time | Direct Link | Primary Skill / Learning Objective |
|---|-----------|------------|-----------|-------------|-----------------------------------|
| 4 | **Red Team Intro** | Easy | 1 hr | [Access THM](https://tryhackme.com/room/redteamintro) | Engagement scoping, OPSEC, Red Team vs Pen Testing |
| 5 | **Red Team Recon** | Medium | 1.5 hrs | [Access THM](https://tryhackme.com/room/redteamrecon) | Stealthy reconnaissance, domain fronting, infrastructure setup |
| 6 | **Intro to C2** | Medium | 1.5 hrs | [Access THM](https://tryhackme.com/room/c2intro) | Command & Control frameworks, listeners, implants, stagers |

---

## ⚡ Phase 3: Evasion & Post-Exploitation

| # | Room Name | Difficulty | Est. Time | Direct Link | Primary Skill / Learning Objective |
|---|-----------|------------|-----------|-------------|-----------------------------------|
| 7 | **Bypassing AV** | Medium | 2 hrs | [Access THM](https://tryhackme.com/room/bypassingav) | Payload encoding, shellcode execution, obfuscation |
| 8 | **Living Off the Land (LOLBAS)** | Medium | 1.5 hrs | [Access THM](https://tryhackme.com/room/lolbas) | Exploiting native Windows binaries (Certutil, PowerShell, MSBuild) |
| 9 | **Lateral Movement** | Medium | 2 hrs | [Access THM](https://tryhackme.com/room/lateralmovement) | Pass-the-Hash, Pass-the-Ticket, WinRM, WMI execution |

---

## 💻 Recommended Portfolio Projects for Red Teamers
1. **Active Directory Attack & Defense Lab:** Set up a local AD domain, simulate Kerberoasting and BloodHound path discovery, and document defensive mitigation steps.
2. **Obfuscation & Payload Generation Suite:** Create a custom PowerShell/C# stager script with base64/XOR obfuscation and test against Defender.
