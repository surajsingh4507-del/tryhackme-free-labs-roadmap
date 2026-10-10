# 🚨 Security Incident Triage & Response Report

**Incident ID:** INC-2026-001  
**Severity:** [ Critical | High | Medium | Low ]  
**Lead Analyst:** [Your Name]  
**Date of Incident:** [YYYY-MM-DD]  
**Status:** [ Closed / Under Monitoring / Mitigated ]

---

## 1. Executive Summary
Provide a high-level summary of the security incident, affected systems, root cause, and immediate containment measures taken.

---

## 2. Incident Timeline (UTC)

| Time | Event / Alert Source | Description |
|------|----------------------|-------------|
| 10:15:00 | SIEM (Splunk) | High volume of failed SSH login attempts detected from IP `192.168.1.150` |
| 10:18:22 | Sysmon Event 4624 | Successful RDP authentication under account `admin_local` |
| 10:22:10 | EDR Alert | Suspicious PowerShell command executed with `-EncodedCommand` flag |
| 10:25:00 | Network Firewall | Outbound connection initiated to known C2 IP `185.220.101.5` |
| 10:30:00 | SOC Analyst | Host `WS-FINANCE-04` isolated from network |

---

## 3. Indicators of Compromise (IOCs)

### 🌐 Network IOCs
- **Malicious IP Addresses:** `185.220.101.5`
- **C2 Domains:** `update-check-service.com`
- **User Agent:** `Mozilla/5.0 (Windows NT 10.0; Win64; x64) CustomC2/1.0`

### 💻 Endpoint IOCs
- **Host Affected:** `WS-FINANCE-04` (`10.0.4.45`)
- **File Hashes (SHA-256):** `e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855`
- **Persistence Mechanism:** Scheduled Task named `WindowsSecurityHealthCheck`

---

## 4. MITRE ATT&CK Mapping

- **Initial Access:** Valid Accounts (T1078)
- **Execution:** Command and Scripting Interpreter: PowerShell (T1059.001)
- **Persistence:** Scheduled Task/Job (T1053.005)
- **Command and Control:** Application Layer Protocol: Web Protocols (T1071.001)

---

## 5. Containment & Remediation Actions

1. Host Isolation: Removed `WS-FINANCE-04` from network VLAN.
2. Credential Reset: Rotated passwords for compromised account `admin_local` and enforced MFA.
3. C2 Blocking: Blacklisted `185.220.101.5` and `update-check-service.com` at perimeter firewall.
4. Persistence Removal: Terminated malicious process PID 4108 and deleted scheduled task.

---

## 6. Lessons Learned & Recommendations
- Enforce Account Lockout Policies after 5 failed login attempts.
- Restrict PowerShell execution policy via GPO (`Restricted` or `AllSigned`).
- Implement EDR auto-containment rules for encoded PowerShell payloads.
