# 🔍 Free TryHackMe DFIR Labs – Memory Forensics, Artifacts & Incident Investigation Practice

A curated list of **free TryHackMe rooms** focused entirely on **Digital Forensics and Incident Response (DFIR)** training. Ideal for **Digital Forensics Analysts**, **Incident Responders**, and **Malware Investigators**, these hands-on labs cover core skills like **volatile memory analysis**, **disk forensics**, **Windows artifact investigation**, and **malware reverse engineering**.

---

## 🚀 Why This List?

Whether you're a beginner or preparing for certifications like:

- GIAC Certified Forensic Analyst (GCFA)
- GIAC Certified Incident Handler (GCIH)
- Blue Team Level 1 & 2 (BTL1 / BTL2)
- Certified Computer Examiner (CCE)

...these labs will help you develop skills in:

- ✅ Forensic acquisition & chain of custody principles  
- ✅ Volatile RAM extraction & analysis (Volatility 3)  
- ✅ File carving & metadata extraction (Autopsy & FTK)  
- ✅ Windows Registry forensics (SAM, SYSTEM, SOFTWARE hives)  
- ✅ Program execution artifacts (Prefetch, Shimcache, Amcache, LNK)  
- ✅ Static & dynamic malware triage (VirusTotal, PEStudio, Ghidra)

---

# 📚 TryHackMe DFIR Room List (Free)

> 🆓 These rooms are **100% free** at the time of writing and updated regularly.

---

| Icon | Title | Subtitle | Link |
|:---:|---|---|:---:|
| 🔬 | **Intro to Digital Forensics** | Chain of custody, forensic imaging & legal investigation basics | [🔗 Visit](https://tryhackme.com/room/introdigitalforensics) |
| 🗃️ | **Forensics** | File headers, magic bytes, EXIF metadata & steganography | [🔗 Visit](https://tryhackme.com/room/forensics) |
| 🧠 | **Volatility** | RAM dump extraction, process trees & network socket recovery | [🔗 Visit](https://tryhackme.com/room/volatility) |
| 🔎 | **Autopsy** | Disk image ingestion, keyword search & timeline reconstruction | [🔗 Visit](https://tryhackme.com/room/autopsy) |
| 🪟 | **Windows Forensics 1** | Registry hives, SAM, SYSTEM, SOFTWARE, USB device history | [🔗 Visit](https://tryhackme.com/room/windowsforensics1) |
| 🗂️ | **Windows Forensics 2** | Prefetch files, Shimcache, Amcache, Jump Lists & Shellbags | [🔗 Visit](https://tryhackme.com/room/windowsforensics2) |
| 💾 | **Forensic Imaging** | Bit-by-bit imaging, MBR/GPT parsing, Master File Table (MFT) | [🔗 Visit](https://tryhackme.com/room/forensicimaging) |
| 🦠 | **Intro to Malware Analysis** | Static vs Dynamic analysis, file hashing, strings & VirusTotal | [🔗 Visit](https://tryhackme.com/room/intromalwareanalysis) |
| ⚙️ | **RE101 - Intro to Reverse Eng** | Assembly language, x86 architecture & Ghidra disassembly | [🔗 Visit](https://tryhackme.com/room/re101) |
| 🚨 | **Redline** | FireEye Redline memory collector & compromise assessment | [🔗 Visit](https://tryhackme.com/room/redline) |

---

## 💼 Recommended Hands-on Portfolio Projects
1. **Memory Forensics Case Report:** Analyze a memory image using Volatility 3 plugins (`windows.pstree`, `windows.malfind`), extract the malicious payload, and write a forensic report.
2. **Post-Mortem Disk Investigation:** Use Autopsy to reconstruct the exact timeline of a ransomware execution on a disk image using our [Incident Report Template](../templates/incident-report-template.md).
