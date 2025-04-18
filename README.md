# 🛡️ Cybersecurity Portfolio

Welcome to my Cybersecurity Portfolio. This repository showcases my work in cybersecurity, focusing on incident response, security audits, system hardening, and vulnerability assessments. Each project demonstrates my experience in securing IT infrastructures and handling security breaches.

---

## 👨‍💻 About

I am pursuing a career in cybersecurity driven by a strong interest in protecting systems and data from evolving threats. I bring analytical thinking, attention to detail, and a commitment to continuous learning. With a foundation in Python, Linux, and cybersecurity tools, I am prepared to support secure, efficient environments. I value integrity, follow legal and ethical standards, and maintain professionalism through punctuality and reliability. My strengths and values align with the mission of organizations seeking trustworthy, skilled cybersecurity professionals.

---

## 🧾 Tools & Platforms

- **Tools**: Metasploit, Wireshark, Nmap, Burp Suite, Botium
- **Platforms**: Kali Linux, Windows Server, Linux

---

## 📂 Projects

### 📘 Reports

- **[dns-incident-report.pdf](Reports/dns-incident-report.pdf)**: Analysis of a DNS-based attack and recovery process.
- **[internal-it-audit-botium.pdf](Reports/internal-it-audit-botium.pdf)**: Security audit using Botium for automated testing.
- **[os-hardening-compromise-report.pdf](Reports/os-hardening-compromise-report.pdf)**: Steps taken to harden an OS after a security breach.
- **[webserver-dos-summary.pdf](Reports/webserver-dos-summary.pdf)**: Mitigation techniques for a Denial of Service attack on a web server.

### 🏅 Certifications

- **[IIT Roorkee – Advanced Cybersecurity](certifications/IIT_roorkee.jpg)**  
  Completion of Advanced Cybersecurity from IIT ROORKEE  
  ![Certification](certifications/IIT_roorkee.jpg)

---
## Lab Reports

### Recon & Enumeration Lab Report

This lab demonstrates basic reconnaissance and enumeration between two virtual machines—Ubuntu (target) and Kali Linux (attacker)—using tools like `nmap` and `apache2` in a bridged network setup.

**Environment:**
- Host OS: Windows (VirtualBox)
- Target VM: Ubuntu (Apache Web Server)
- Attacker VM: Kali Linux
- Network Mode: Bridged Adapter

**Steps:**
1. **Configure Ubuntu (Target)**
   - Check IP: `ip a`
   - Install Apache: `sudo apt install apache2`
   - Start Apache: `sudo systemctl start apache2`
   - Verify in browser: `http://<ubuntu-ip>`

2. **Configure Kali Linux (Attacker)**
   - Ping Ubuntu: `ping <ubuntu-ip>`
   - Install Nmap: `sudo apt install nmap`
   - Scan: `sudo nmap -sV <ubuntu-ip>`

**Summary:**  
Successfully performed reconnaissance and enumeration, scanned open ports, and verified the Apache web server.

📄 [Read the full report](Reports/Recon_Enumeration_Lab_Report.pdf)


## 🤝 Connect with me

Feel free to reach out if you’d like to:
- Discuss cybersecurity & learning paths
- Collaborate on a project
- Chat about tech in general!

👉 [My LinkedIn Profile](https://www.linkedin.com/in/manjeeshkv)

---

> Thanks for checking out my portfolio!
