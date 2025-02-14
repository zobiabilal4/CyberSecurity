# CyberSecurity Repository

Welcome to the **CyberSecurity Repository**! This repository is dedicated to understanding cybersecurity threats, vulnerabilities, and exploitation techniques, with a special focus on **Information Security**.

## 🔐 What is Cyber Security?
Cybersecurity is the practice of protecting systems, networks, and programs from digital attacks. These attacks typically aim to access, modify, or destroy sensitive information, extort money from users, or disrupt normal business operations. **Information Security**, a subset of cybersecurity, specifically focuses on protecting data from unauthorized access, breaches, and leaks.

### 📌 Key Areas of Information Security:
- **Confidentiality**: Ensuring that information is accessible only to those authorized to have access.
- **Integrity**: Maintaining the accuracy and reliability of data.
- **Availability**: Ensuring that information and systems are available when needed.
- **Authentication**: Verifying the identity of users accessing a system.
- **Non-Repudiation**: Preventing denial of actions performed by a user.

---

## 📂 Repository Structure
```
CyberSecurity-Toolkit/
├── Vulnerabilities/
│   ├── BSDSF21A026_ASSIGNMENT1.pdf  # Discussion on HTML Injection, XSS, and SQL Injection
├── Exploits/
│   ├── sudo_exploit_CVE-2019-14287  # Privilege escalation vulnerability in sudo
│   ├── shellshock_exploit_CVE-2014-6271  # Remote code execution via Bash
│   ├── dirtyCOW_exploit_CVE-2016-5195  # Race condition vulnerability in Linux
├── Learning-Resources/
│   ├── Information_Security.pdf  # Detailed overview of InfoSec concepts
│   ├── Ethical_Hacking.pdf  # Guides on penetration testing methodologies
│   ├── Network_Security.pdf  # Notes and resources for network security
├── README.md  # Overview of the repository
```

## 🔎 Types of Vulnerabilities & Exploitation Techniques
This repository contains detailed discussions on various security vulnerabilities and how they can be exploited.

### 📌 BSDSF21A026_ASSIGNMENT1 (Common Web Vulnerabilities)
- **HTML Injection**: Injecting malicious HTML code into web pages.
- **Cross-Site Scripting (XSS)**: Injecting scripts into web applications to steal information or manipulate users.
- **SQL Injection**: Exploiting vulnerabilities in SQL queries to access unauthorized database information.

### 📌 System Exploits
#### **Task 1: Exploiting the sudo Vulnerability (CVE-2019-14287)**
- **Description**: A privilege escalation vulnerability in sudo (before v1.8.28).
- **Impact**: Allows a user to execute commands as root, bypassing sudoers restrictions.
- **Exploit Methodology**: Modifying the sudoers file to execute commands as an unintended user.

#### **Task 2: Exploiting the ShellShock Vulnerability (CVE-2014-6271)**
- **Description**: A critical vulnerability in Bash (versions 1.0.3 to 4.3.0).
- **Impact**: Enables attackers to execute arbitrary commands via crafted environment variables.
- **Exploit Methodology**: Injecting malicious function definitions into Bash shell commands.

#### **Task 3: Exploiting the DirtyCOW Vulnerability (CVE-2016-5195)**
- **Description**: A race condition vulnerability in Linux Kernel (up to v2.6.22).
- **Impact**: Allows an unprivileged user to modify read-only memory mappings and escalate privileges.
- **Exploit Methodology**: Manipulating memory mapping to gain unauthorized write access.

---

## 🚀 Getting Started
1. Clone the repository:
   ```sh
   git clone https://github.com/zobiabilal4/CyberSecurity.git
   ```
2. Navigate into the directory:
   ```sh
   cd CyberSecurity
   ```
3. Explore the different vulnerabilities and exploits!

## 🎯 Contributing
We welcome contributions! If you have a script, tool, or guide to add, follow these steps:
1. Fork the repository.
2. Create a new branch.
3. Add your contributions.
4. Submit a pull request.

## 📜 License
This repository is for educational purposes only. Use responsibly and ethically. 🚀
