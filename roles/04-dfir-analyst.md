# 🔍 Digital Forensics & Incident Response (DFIR) Roadmap (100% Free Labs)

> **Role Overview:** DFIR Analysts investigate security breaches after an incident occurs. They perform memory forensics, disk artifact analysis, registry analysis, and malware triage to determine *how* an attacker entered, *what* they accessed, and *how* to contain the threat.

---

## 🎯 Key Competencies & Skill Matrix

```
       [ Memory Forensics ]    ──────────► ( Volatility Framework, RAM Dumps )
                 │
       [ Disk Forensics ]      ──────────► ( Autopsy, FTK Imager, E01 Images )
                 │
       [ Windows Artifacts ]   ──────────► ( Registry, Prefetch, Shimcache, Amcache )
                 │
       [ Malware Analysis ]    ──────────► ( Static & Dynamic Analysis, Ghidra, x64dbg )
```

---

## 🎓 Aligned Industry Certifications
- **GIAC Certified Forensic Analyst** (GCFA)
- **GIAC Certified Incident Handler** (GCIH)
- **Certified Computer Examiner** (CCE)
- **Blue Team Level 1 & 2** (BTL1 / BTL2)

---

## 🚀 Phase 1: Digital Forensics Fundamentals & Memory Analysis

| # | Room Name | Difficulty | Est. Time | Direct Link | Primary Skill / Learning Objective |
|---|-----------|------------|-----------|-------------|-----------------------------------|
| 1 | **Intro to Digital Forensics** | Easy | 45 mins | [Access THM](https://tryhackme.com/room/introdigitalforensics) | Chain of custody, forensic imaging, basic concepts |
| 2 | **Forensics** | Easy | 1 hr | [Access THM](https://tryhackme.com/room/forensics) | File headers, EXIF data, steganography, data carving |
| 3 | **Volatility** | Medium | 2 hrs | [Access THM](https://tryhackme.com/room/volatility) | Analyzing RAM dumps, process trees, network connections |

---

## 💾 Phase 2: Disk & Windows Forensics

| # | Room Name | Difficulty | Est. Time | Direct Link | Primary Skill / Learning Objective |
|---|-----------|------------|-----------|-------------|-----------------------------------|
| 4 | **Autopsy** | Easy/Medium | 1.5 hrs | [Access THM](https://tryhackme.com/room/autopsy2) | Disk image ingestion, keyword search, timeline analysis |
| 5 | **Windows Forensics 1** | Medium | 1.5 hrs | [Access THM](https://tryhackme.com/room/windowsforensics1) | Registry hives, SAM, SYSTEM, SOFTWARE, USB history |
| 6 | **Windows Forensics 2** | Medium | 1.5 hrs | [Access THM](https://tryhackme.com/room/windowsforensics2) | Prefetch files, Shimcache, Amcache, Jump Lists, LNK files |
| 7 | **Disk Analysis & Carving** | Medium | 1.5 hrs | [Access THM](https://tryhackme.com/room/disksurfer) | Master Boot Record (MBR), Master File Table (MFT), carving |

---

## 🦠 Phase 3: Malware Analysis & Incident Investigation

| # | Room Name | Difficulty | Est. Time | Direct Link | Primary Skill / Learning Objective |
|---|-----------|------------|-----------|-------------|-----------------------------------|
| 8 | **Intro to Malware Analysis** | Easy | 1 hr | [Access THM](https://tryhackme.com/room/malwareanalysisintro) | Static vs Dynamic analysis, hashes, VirusTotal, PEStudio |
| 9 | **RE101 - Intro to Reverse Engineering** | Medium | 2 hrs | [Access THM](https://tryhackme.com/room/re101) | Assembly language, IDA Free, Ghidra basics, disassembling binaries |
| 10 | **Redline** | Medium | 1.5 hrs | [Access THM](https://tryhackme.com/room/redline) | FireEye Redline memory collector & triage analysis |

---

## 💻 Recommended Portfolio Projects for DFIR Analysts
1. **Volatile Memory Analysis Lab Writeup:** Capture a memory sample, run Volatility plugins (`pslist`, `netscan`, `malfind`), extract malicious DLLs, and document findings.
2. **Forensic Timeline Incident Report:** Use Autopsy to reconstruct an attack timeline on a disk image, mapping out initial access, file execution, and exfiltration.
