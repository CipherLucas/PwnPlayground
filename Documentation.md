# 🖥️ Lucas' Cybersecurity Home Lab

## ⚠️ DISCLAIMER:
Everything that I am doing in this lab is solely for educational purposes ONLY. I do not support some of the labs that I have have taken on, some of these labs simulate what real threat actors do. Everything that I have done is isolated on a private VLAN and the firewall is configured to block outgoing traffic so nothing can be out of scope. 

<br />

## 📜 Purpose
The purpose of my home lab is to create a secure, hands-on environment to learn and apply cybersecurity skills. It serves to:

- Simulate real-world attack and defense scenarios.
- Practice penetration testing, incident response, and digital forensics.
- Enhance my ability to configure and secure systems and networks.

## 🏗️ Lab Setup Overview
My lab leverages VMware Workstation to manage multiple virtual machines (VMs) on a powerful host system. The setup includes network segmentation to simulate real-world internal and external environments.

### Host System Specs
- **CPU**: Intel i9-10900K
- **GPU**: NVIDIA 3070 Ti
- **RAM**: 32GB
- **Storage**: 6TB

### Hypervisor
- **VMware Workstation Pro**: Chosen for its robust virtualization capabilities and ease of managing complex lab setups.

### Networking
- **Bridged Networking**: Simulates external connections.
- **NAT Configuration**: Internal networking for isolated communications.
- **Firewall Integration**: Virtual IPFire machine to filter and monitor traffic.

## 🖼️ Lab Network Diagram
Visualizing the Setup  

![Lab Network Diagram](https://github.com/CipherLucas/PwnPlayground/blob/main/PwnPlayground.drawio.png) 

## 🖥️ Machines in Use

| Machine              | Purpose                                                                      |
|----------------------|------------------------------------------------------------------------------|
| **Kali Purple**       | Ethical hacking, incident response, and purple teaming.                      |
| **Metasploitable 2**  | Vulnerable machine for exploitation and vulnerability analysis.              |
| **IPFire**            | Virtual firewall to filter and monitor network traffic.                       |
| **Windows Server 2012** | Simulates Active Directory for privilege escalation and forensics.           |
| **Windows 7**         | Legacy machine for exploit testing and forensic tasks.                       |
| **SEED Ubuntu**       | Focused on web application security and cryptographic exercises.             |
| **Ghost Spectre Win11** | Used to test various RATTING Tools. Use since Windows defender is disabled |
## 🔬 Projects Conducted

### 1. Penetration Testing
- Conducted vulnerability scans and generated detailed reports using **Nessus**.
- Exploited vulnerabilities on **Metasploitable 2** with **Metasploit** to simulate attacker methodologies.

### 2. Phishing Analysis
- Analyzed email headers using **Email Header Tools** to detect spoofing and phishing attempts.
- Used **BlackEye** and **Ngrok** to set up phishing sites in a controlled environment, testing phishing techniques ethically.

### 3. Traffic Filtering and Monitoring
- Configured **IPFire** to filter network traffic, implementing and testing intrusion detection rules.
- Captured and analyzed traffic with **Wireshark** to identify malicious patterns.

### 4. Forensic Investigations
- Used **Windows 7** and **Windows Server 2012** for forensic analysis of simulated incidents.
- Investigated registry changes and recovered deleted files to trace activity.

### 5. Web Application Security
- Performed **XSS** and **SQL Injection** attacks on **SEED Ubuntu** to test application vulnerabilities.
- Hardened the web server and application as part of the remediation process.

## 🔧 Tools Used

- **Nessus**: For vulnerability scanning and reporting.
- **Metasploit**: For exploiting vulnerabilities and testing system defenses.
- **Wireshark**: For traffic capture and analysis.
- **BlackEye**: For phishing site simulation in a secure lab.
- **Ngrok**: Local hosting of phishing sites for research purposes.
- **ANY.RUN**: Phishing email and URL sandboxing.

## 🌟 Key Outcomes

- Gained practical experience with penetration testing, from reconnaissance to exploitation.
- Developed advanced skills in phishing detection and site analysis.
- Configured firewalls and monitored traffic to simulate intrusion detection systems.
- Enhanced forensics and incident response capabilities in a controlled environment.
