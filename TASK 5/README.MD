# Capstone Project: Vulnerability Assessment & Incident Response

## 📌 Project Overview
This project was completed as part of the **Apex Planet** (Task 5) internship. It simulates a real-world scenario where a server (Metasploitable 2) is assessed for vulnerabilities, exploited by an attacker (Kali Linux), and defended by a Security Analyst through Incident Response protocols.

## 🛠️ Tools Used
- **Attacker OS:** Kali Linux
- **Target OS:** Metasploitable 2
- **Scanner:** Nmap, Nikto
- **Exploitation:** Metasploit Framework
- **Monitoring:** Wireshark
- **Defense/IR:** Linux IPTables, Process Management

## 🚀 Methodology
1. **Reconnaissance:** Scanning the network to find active hosts and open ports.
2. **Vulnerability Assessment:** Identifying high-risk services (VSFTPD 2.3.4).
3. **Exploitation:** Gaining root access via a known backdoor.
4. **Incident Response:** 
   - **Detection:** Analyzing port 6200 traffic in Wireshark.
   - **Containment:** Blocking the attacker IP via Firewall.
   - **Eradication:** Killing malicious processes and stopping services.

## 📊 Key Findings
- **Vulnerability:** VSFTPD v2.3.4 Backdoor (CVE-2011-2523)
- **Risk:** Critical (Root Level Access)
- **Status:** Remedied through service termination and IP blocking.

## 📁 Project Deliverables
- [Full PDF Report](./Reports/Capstone_Project_Report.pdf)
- [Project Presentation Video](INSERT_YOUR_YOUTUBE_OR_DRIVE_LINK_HERE)

## 👤 Author
- **Your Name**
- [Your LinkedIn Profile Link]
