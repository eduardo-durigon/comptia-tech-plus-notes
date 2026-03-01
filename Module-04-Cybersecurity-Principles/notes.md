# Module 04: Cybersecurity Principles 🔐

---

## 📌 Overview

This module introduces the foundational principles of cybersecurity, including security models, authentication methods, malware types, firewalls, patch management, and security best practices.

---

# 4.1 🔐 What Is Security?

Security is the practice of controlling access to important systems, data, and resources.

It protects:
- Devices
- Networks
- Applications
- Data
- Physical equipment

---

# 🛡 The CIA Triad

A core cybersecurity model:

## 1️⃣ Confidentiality
Keeping information private and protected from unauthorized access.

Examples:
- Encryption
- Access controls
- Password protection

---

## 2️⃣ Integrity
Ensuring data has not been altered or tampered with.

Tools:
- Hashing (MD5, SHA)
- Digital signatures

If even one character changes, the hash value changes.

---

## 3️⃣ Availability
Ensuring systems and data are accessible when needed.

Threats:
- Denial of Service (DoS) attacks
- System failures

Solutions:
- Backups
- Redundancy
- Data centers

---

## 🔏 Non-Repudiation

Ensures someone cannot deny performing an action.

Examples:
- Digital signatures
- Logged transactions

---

# 🏛 NIST Cybersecurity Framework

The NIST framework helps organizations manage cybersecurity risks.

### 5 Core Functions:
1. Identify – Understand risks and assets  
2. Protect – Implement safeguards  
3. Detect – Monitor for threats  
4. Respond – Take action against incidents  
5. Recover – Restore systems and data  

---

# 🔐 Authentication & Authorization

## Authentication
Proving who you are.

### Types:
- Something you know (password)
- Something you have (token, phone)
- Something you are (biometrics)

---

## Biometric Authentication
- Fingerprint
- Retina scan
- Iris scan

Downsides:
- Privacy concerns
- False positives/negatives

---

## 2FA & MFA
- 2FA → Two-Factor Authentication  
- MFA → Multi-Factor Authentication  

Adds extra security beyond passwords.

---

## SSO (Single Sign-On)

Login once, access multiple systems.

Pros:
- Convenient
- Faster login process

Cons:
- If compromised, attacker gains access to everything

---

## Authorization

Determines what actions a user is allowed to perform.

Common permissions:
- Read
- Write (Modify)
- Execute
- Delete

---

## Least Privilege

Users should only have the minimum access required to perform their job.

---

## Implicit Deny

If there is no rule allowing access → access is automatically denied.

---

# 🔍 AAA Model

- Authentication
- Authorization
- Accounting

Accounting tracks:
- Logins
- User actions
- System changes

---

# 🦠 Malware & Threats

## Malware
Malicious software designed to damage systems or steal information.

Types include:
- Virus
- Worm
- Trojan
- Ransomware
- Spyware
- Logic bomb

---

## Virus
- Spreads when executed
- Requires user interaction
- Can corrupt files or systems

---

## Worm
- Spreads automatically over networks
- No user interaction needed
- Copies itself between computers

---

## Ransomware
- Locks computer or encrypts files
- Demands payment for access

---

## Spyware
- Monitors user activity
- May include keyloggers
- Often generates pop-up ads

---

# 🎯 Social Engineering Attacks

## Phishing
Fraudulent emails designed to steal credentials.

## Spear Phishing
Targeted phishing aimed at a specific individual.

## Smishing
Phishing via text messages.

## Shoulder Surfing
Watching someone type passwords or PINs.

## Tailgating
Following an authorized person into a restricted area.

---

# 🛡 Security Tools in Practice

## Defense in Depth
Layered security approach across the network.

Examples:
- Firewalls
- Antivirus
- Access controls
- Network segmentation

---

## Separation of Duties
Splitting responsibilities between individuals to reduce insider threats.

---

## Network Segmentation
Restricting access between different areas of a network.

---

## Geofencing
Setting virtual geographic boundaries.
If a device leaves the boundary → alert triggered.

---

# 🔥 Firewalls

A firewall filters traffic based on rules.

Rules may include:
- Source
- Destination
- Port
- Protocol

---

## Types of Firewalls

### Hardware Firewall
- Protects entire network
- Installed at network edge

### Software Firewall
- Installed on individual devices

### Web Application Firewall (WAF)
- Protects web applications
- Filters HTTP traffic

---

# 🦠 Antivirus Software

Detects and stops malware.

Detection methods:
- Signature-based (known threats)
- Heuristic analysis (behavior-based)

Features:
- Real-time scanning
- Quarantine infected files
- Scheduled scans

Keep antivirus updated regularly.

---

# 🧩 Patch Management & Updates

## Patch Management
Process of:
1. Checking for updates
2. Testing updates
3. Deploying updates

---

## Zero-Day Attacks
Exploits vulnerabilities before patches are available.

---

# 🔒 Physical Security Controls

- Equipment locks
- USB port locks
- Boot restrictions from USB

Computers have:
- Physical value
- Data value

Both must be protected.

---

# 💼 Careers in Cybersecurity

- Cybersecurity Analyst
- Penetration Tester
- Cybersecurity Engineer

Cybersecurity engineers design and build digital defenses for systems and data.

---

# 📝 Summary

In this module, I learned:
- The CIA Triad
- Authentication & authorization
- Malware types and social engineering
- Firewalls and antivirus systems
- Patch management and zero-day threats
- Physical and network security controls

---

⭐ End of Module 04
