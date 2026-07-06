# Cybersecurity Threats

## Introduction

A cybersecurity threat is any potential event, person, activity, or circumstance that can exploit a vulnerability and cause harm to an organization's information systems, networks, applications, or data.

Cyber threats continue to evolve as technology advances. Organizations must identify potential threats, assess their risks, and implement appropriate security controls to protect their information assets.

Understanding cyber threats is one of the fundamental skills required in cybersecurity, especially for careers in Governance, Risk, and Compliance (GRC), Security Operations Center (SOC), Incident Response, and Risk Management.

---

# What is a Threat?

A **Threat** is anything that has the potential to exploit a vulnerability and cause damage to an organization's assets.

A threat itself does not always result in an attack. It becomes dangerous when it successfully exploits a weakness (vulnerability).

### Example

A company uses weak passwords for employee accounts.

- Asset: Employee Email Account
- Threat: Hacker
- Vulnerability: Weak Password
- Result: Unauthorized Access

---

# Threat vs Vulnerability vs Risk

| Term | Definition |
|------|------------|
| Threat | Something that can cause harm |
| Vulnerability | A weakness that can be exploited |
| Risk | The likelihood that a threat will exploit a vulnerability |

### Example

Asset: Customer Database

Threat: Ransomware

Vulnerability: Outdated Software

Risk: Customer data may become encrypted and unavailable.

---

# Characteristics of a Cyber Threat

A cyber threat can:

- Steal sensitive information
- Damage systems
- Disrupt business operations
- Cause financial loss
- Harm an organization's reputation
- Violate legal or regulatory requirements

---

# Types of Cybersecurity Threats

## 1. Malware

Malware is malicious software designed to damage, disrupt, or gain unauthorized access to computer systems.

### Types of Malware

- Virus
- Worm
- Trojan Horse
- Spyware
- Adware
- Rootkit
- Keylogger

### Example

A user downloads a fake software installer that secretly installs spyware.

### Prevention

- Antivirus software
- Software updates
- Avoid unknown downloads
- Email filtering

---

## 2. Ransomware

Ransomware encrypts files or systems and demands payment to restore access.

### Example

An employee opens a malicious email attachment.

The ransomware encrypts the company's file server.

The attacker demands money to decrypt the files.

### Prevention

- Regular backups
- Security awareness training
- Patch management
- Endpoint protection
- Multi-Factor Authentication

---

## 3. Phishing

Phishing is a social engineering attack that tricks users into revealing sensitive information.

### Common Targets

- Passwords
- Credit card information
- Banking credentials
- Company login credentials

### Example

An employee receives an email pretending to be from Microsoft asking them to reset their password.

The employee enters their credentials on a fake website.

The attacker steals the login information.

### Prevention

- Employee awareness training
- Email filtering
- MFA
- Verify suspicious emails

---

## 4. Social Engineering

Social engineering manipulates people into performing actions that compromise security.

### Examples

- Phishing
- Pretexting
- Baiting
- Tailgating
- Shoulder Surfing

### Prevention

- Employee training
- Identity verification
- Visitor management
- Security policies

---

## 5. Insider Threat

An insider threat comes from someone within the organization.

This may include:

- Employees
- Contractors
- Vendors
- Business Partners

### Types

#### Malicious Insider

An employee intentionally steals company information.

#### Negligent Insider

An employee accidentally exposes sensitive information.

### Prevention

- Least Privilege Access
- Monitoring
- Employee Training
- Access Reviews

---

## 6. Denial-of-Service (DoS)

A DoS attack overwhelms a server or application with excessive traffic, making it unavailable.

### Example

A website receives millions of fake requests.

Legitimate users cannot access the service.

### Prevention

- Firewalls
- Rate Limiting
- Web Application Firewalls
- DDoS Protection Services

---

## 7. Distributed Denial-of-Service (DDoS)

A DDoS attack uses thousands of compromised devices (botnets) to attack a target simultaneously.

### Example

An online shopping website becomes unavailable during a large-scale DDoS attack.

### Prevention

- Cloud-based DDoS protection
- Traffic filtering
- Load balancing

---

## 8. Password Attacks

Attackers attempt to obtain passwords through various methods.

### Common Password Attacks

- Brute Force
- Dictionary Attack
- Credential Stuffing
- Password Spraying

### Prevention

- Strong Password Policies
- MFA
- Password Managers
- Account Lockout Policies

---

## 9. SQL Injection

SQL Injection occurs when attackers insert malicious SQL code into an application's input fields.

### Example

A vulnerable login page allows attackers to bypass authentication.

### Prevention

- Parameterized Queries
- Input Validation
- Secure Coding Practices
- Web Application Firewall

---

## 10. Cross-Site Scripting (XSS)

XSS allows attackers to inject malicious JavaScript into web pages.

### Example

An attacker injects a malicious script into a comment section.

Visitors who open the page execute the script unknowingly.

### Prevention

- Input Validation
- Output Encoding
- Content Security Policy (CSP)

---

## 11. Man-in-the-Middle (MitM)

A Man-in-the-Middle attack occurs when an attacker intercepts communication between two parties.

### Example

A user connects to an unsecured public Wi-Fi network.

An attacker captures login credentials.

### Prevention

- HTTPS
- VPN
- Encryption
- Secure Wi-Fi

---

## 12. Zero-Day Attack

A Zero-Day attack exploits a software vulnerability before the vendor releases a security patch.

### Prevention

- Patch Management
- Threat Intelligence
- Endpoint Detection and Response (EDR)

---

# Common Threat Actors

| Threat Actor | Description |
|--------------|-------------|
| Cybercriminals | Steal money or sensitive information |
| Nation-State Actors | Conduct cyber espionage or sabotage |
| Insider Threats | Employees or contractors |
| Hacktivists | Attack for political or social reasons |
| Terrorist Organizations | Disrupt critical infrastructure |
| Script Kiddies | Inexperienced attackers using existing tools |

---

# Threats Mapped to the CIA Triad

| Threat | Confidentiality | Integrity | Availability |
|----------|----------------|-----------|--------------|
| Phishing | ✅ | ❌ | ❌ |
| Malware | ✅ | ✅ | ✅ |
| Ransomware | ❌ | ✅ | ✅ |
| SQL Injection | ✅ | ✅ | ❌ |
| DDoS | ❌ | ❌ | ✅ |
| Insider Threat | ✅ | ✅ | ✅ |

---

# Real-World Scenario

## Organization

ABC Hospital

### Asset

Patient Database

### Threat

Ransomware

### Vulnerability

Unpatched Operating System

### Impact

- Medical records become inaccessible.
- Hospital operations are disrupted.
- Financial losses occur.
- Patient trust decreases.

### Security Controls

- Daily backups
- Patch management
- Endpoint Detection and Response (EDR)
- Security awareness training
- Network segmentation

---

# Why Understanding Threats is Important

Organizations identify threats to:

- Protect sensitive information
- Reduce cybersecurity risks
- Improve business continuity
- Support compliance
- Build effective security controls
- Prevent financial losses

---

# Interview Questions

## 1. What is a cybersecurity threat?

A cybersecurity threat is anything that has the potential to exploit a vulnerability and cause harm to information systems or data.

---

## 2. What is the difference between a Threat and a Vulnerability?

A threat is something capable of causing harm.

A vulnerability is a weakness that allows the threat to succeed.

---

## 3. What is the difference between DoS and DDoS?

A DoS attack uses a single source to overwhelm a target.

A DDoS attack uses multiple compromised systems (botnets) to attack simultaneously.

---

## 4. What is Ransomware?

Ransomware is malicious software that encrypts files and demands payment for their recovery.

---

## 5. What is Phishing?

Phishing is a social engineering attack that tricks users into revealing sensitive information through fake emails, websites, or messages.

---

## Summary

Cybersecurity threats are constantly evolving and can target people, processes, and technology. Understanding different types of threats—such as malware, ransomware, phishing, insider threats, SQL injection, and DDoS attacks—helps organizations implement effective security controls and reduce risk. A solid understanding of cyber threats is essential for professionals working in GRC, SOC, Incident Response, Risk Management, and Information Security.

---

# References

1. NIST Cybersecurity Framework (CSF)
2. NIST SP 800-53
3. ISO/IEC 27001:2022
4. CIS Controls v8
5. OWASP Top 10
6. MITRE ATT&CK Framework
