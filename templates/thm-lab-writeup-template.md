# 📝 TryHackMe Writeup: [Room Name]

**Author:** [Your Name / GitHub Handle]  
**Date:** [YYYY-MM-DD]  
**Category:** [Blue Team / Red Team / Web Security / DFIR / SOC]  
**Difficulty:** [Easy / Medium / Hard]  
**Room Link:** [https://tryhackme.com/room/...](https://tryhackme.com/room/...)

---

## 🎯 Executive Summary
Briefly summarize what this room covers, what key tools were used, and the main learning outcomes.

---

## 🛠️ Tools Used
- Tool 1 (e.g., `Nmap`, `Wireshark`, `Splunk`)
- Tool 2
- Tool 3

---

## 🏁 Step-by-Step Walkthrough

### Task 1: [Task Title]
Explanation of what needed to be achieved in this task.

```bash
# Terminal command used
nmap -sV -sC -p- <TARGET_IP>
```

#### Key Findings / Observations:
- Finding 1: Open ports identified (e.g., Port 80, Port 22)
- Finding 2: Vulnerable service version detected

---

### Task 2: [Task Title / Exploitation / Analysis]
Detailed breakdown of how the challenge was solved. Include screenshots or code snippets where relevant.

```python
# Code snippet or query used
SELECT * FROM users WHERE username = 'admin' OR '1'='1';
```

---

## 🔐 Flags Captured
- **Flag 1 (User Flag):** `THM{example_user_flag_here}`
- **Flag 2 (Root/System Flag):** `THM{example_root_flag_here}`

---

## 💡 Key Takeaways & Defense Advice
- **Root Cause:** How could this vulnerability/incident have been prevented?
- **Remediation Steps:**
  1. Step 1: Update software to latest version.
  2. Step 2: Implement least-privilege IAM policies.
  3. Step 3: Enforce strong password requirements and MFA.
