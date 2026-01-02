
🔍 Vulnerability Scan Analysis (Summary)

A vulnerability assessment was conducted on multiple hosts in the internal network using **Tenable Nessus**. The scan identified a wide range of security issues across different systems, with varying severity levels.

 📌 Key Findings

* **Total Hosts Scanned:** 5
* **Most Affected Host:** `192.168.86.131`
* **Critical Issues Detected:** Legacy services, outdated software, weak cryptographic configurations, and known backdoors.
* **High-Risk Vulnerabilities:**

  * Apache Tomcat Ghostcat (CVE-2020-1938)
  * Deprecated SSL/TLS versions (SSLv2, SSLv3, TLS 1.0)
  * Weak SSH and SSL cipher suites
  * Bind shell and default credentials exposure

 🛑 Major Security Concerns

* End-of-Life operating systems and services
* Unencrypted services such as **Telnet, FTP, VNC**
* Weak encryption algorithms vulnerable to **DROWN, POODLE, SWEET32, Logjam**
* Misconfigured services (NFS, SMB, DNS, Apache Tomcat)

 ✅ Less Affected Hosts

* `192.168.86.1`, `192.168.86.254` showed mostly **informational findings**
* `192.168.86.2` and `192.168.86.133` had **medium-level vulnerabilities** related to DNS, SSL certificates, and software DoS issues

 🔧 Recommendations

* Upgrade or remove **end-of-life systems**
* Disable unused and insecure services
* Enforce strong encryption and secure protocols
* Apply latest security patches and configurations
* Regular vulnerability scanning and monitoring

---

📄 **Tool Used:** Tenable Nessus
📅 **Scan Date:** 02 January 2026
