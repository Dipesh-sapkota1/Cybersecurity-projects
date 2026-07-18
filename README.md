<div align="center">

# Dipesh Sapkota — Cybersecurity Portfolio

**Junior security analyst focused on blue team operations, threat detection, and incident response.**

[![Projects](https://img.shields.io/badge/Projects-1-0d1117?style=for-the-badge&labelColor=238636&color=0d1117)](.)
[![Domains](https://img.shields.io/badge/Domains-2-0d1117?style=for-the-badge&labelColor=1f6feb&color=0d1117)](.)
[![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-Referenced-0d1117?style=for-the-badge&labelColor=da3633&color=0d1117)](https://attack.mitre.org/)
[![NIST](https://img.shields.io/badge/NIST%20Frameworks-Referenced-0d1117?style=for-the-badge&labelColor=8957e5&color=0d1117)](https://www.nist.gov/cyberframework)

</div>

---

## About Me

I am a cybersecurity student building hands-on skills through home lab investigations, CTF challenges, and structured projects. My work emphasizes detection engineering, log analysis, and understanding attacker behavior at a technical level.

I document everything as if it were a real investigation — because the habit matters as much as the skill.

**Currently pursuing:** CC ISC2
**Background:** Hospitality to Cybersecurity
**Location:** Kathmandu, Nepal

---

## Career Interests

- Security Operations Center (SOC) — Tier 1 / Tier 2 Analysis
- Incident Response
- Threat Hunting
- Detection Engineering
- Digital Forensics

---

## Skills Demonstrated

| Domain | Skills |
|---|---|
| **Network Analysis** | Packet capture, traffic analysis, protocol inspection |
| **Log Analysis** | Windows Event Logs, Syslog, firewall logs, IDS alerts |
| **Threat Detection** | Signature-based and behavioral detection, alert triage |
| **OSINT** | Passive recon, IP/domain pivoting, threat intel enrichment |
| **Malware Analysis** | Static analysis, dynamic sandbox analysis |
| **Scripting** | Python, Bash (automation, parsing, IOC extraction) |
| **Reporting** | Case documentation, executive summaries, IOC tables |

---

## Tools

| Category | Tools |
|---|---|
| **SIEM & Log Management** | Splunk, Elastic Stack (ELK), Wazuh |
| **Network Analysis** | Wireshark, Zeek, Suricata, tcpdump |
| **Endpoint & Forensics** | Volatility, Autopsy, FTK Imager, Sysinternals Suite |
| **Threat Intel** | VirusTotal, AlienVault OTX, MISP, Shodan |
| **Vulnerability & Scanning** | Nmap, Nessus, OpenVAS |
| **Operating Systems** | Kali Linux, Ubuntu Server, Windows Server 2019, Windows 10 |

---

## Certifications

| Certification | Issuer | Status | Date |
|---|---|---|---|
| CC | ISC2 | `Candidate` | 31 July |

---

## Home Lab

My home lab runs on virtualization platform —  VirtualBox.

**Current setup:**

- **Attack machine:** Kali Linux laptop
- **Target machines [VM's]:** Windows 11, Ubuntu Desktop, 

The lab is designed to simulate realistic enterprise scenarios including active directory environments, web server deployments, and attacker-defender exercises.

<!-- > [Link to Lab Architecture Diagram — optional] -->

---

## Featured Projects

### 🔴 Malware Analysis / Incident Response

<table>
<tr>
<td width="60%">

#### [Emotet Epoch 4 — App Installer Phishing Investigation](./projects/emotet-epoch4-appinstaller/)

A phishing email led a victim to a spoofed Adobe installer page that abused the Windows `ms-appinstaller` protocol, dropping an Emotet Epoch 4 payload that established C2 communication and persisted via registry modification — investigated end-to-end from the original `.eml` through full packet capture analysis.

**Artifacts:** Phishing Email (.eml) · Packet Capture (.pcap) · Malicious .appinstaller/.appxbundle · IOC Table

</td>
<td width="40%" align="center">

![](https://img.shields.io/badge/-Email%20Analysis-da3633?style=flat-square)
![](https://img.shields.io/badge/-Network%20Traffic%20Analysis-da3633?style=flat-square)
![](https://img.shields.io/badge/-IOC%20Extraction-da3633?style=flat-square)
![](https://img.shields.io/badge/-Wireshark-da3633?style=flat-square)

**Status:** `Complete`

</td>
</tr>
</table>


<!-- ## Writeups
---

| Title | Platform | Category | Link |
|---|---|---|---|
| [Writeup Title] | TryHackMe / HTB / PicoCTF | [SOC / Forensics / Web] | [Link] |
| [Writeup Title] | [Platform] | [Category] | [Link] | -->

---

## Frameworks & Standards Applied

| Framework | Applied In |
|---|---|
| [MITRE ATT&CK](https://attack.mitre.org/) | Emotet Epoch 4 — App Installer Phishing Investigation |
<!-- | [NIST Cybersecurity Framework (CSF)](https://www.nist.gov/cyberframework) | [Project name(s)] |
| [NIST SP 800-61 Rev. 2](https://csrc.nist.gov/publications/detail/sp/800-61/rev-2/final) — Incident Handling | Emotet Epoch 4 — App Installer Phishing Investigation |
| [OWASP](https://owasp.org) | [Project name(s)] |
| [CIS Controls v8](https://www.cisecurity.org/controls/) | [Project name(s)] | -->

---

## Repository Structure

```
portfolio/
├── README.md                  ← You are here
├── projects/
│   └── emotet-epoch4-appinstaller/
│       ├── README.md          ← Project overview
│       ├── report.md          ← Full technical report
│       └── screenshots/
| 
    
```

> Start with any project's `README.md` before opening the technical documents.

---

## How to Navigate This Repo

Every project directory contains its own `README.md` that explains:
- What the project is and why it was built
- The scenario or context (company, threat, environment)
- The framework or methodology applied
- A guide to reading the files in that directory

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dipesh-sapkota-740b5612b/)

---

<div align="center">

*All projects documented here were conducted in isolated lab environments for educational purposes.*

</div>
