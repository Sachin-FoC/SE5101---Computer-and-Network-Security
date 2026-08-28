# 🔐 Software & Network Security Practical Program

Welcome to the practical repository for the **Computer and Network Security** module.

This repository contains the laboratory sheets, practical exercises, configurations, and supporting resources required to develop hands-on skills in **networking, information security, vulnerability assessment, penetration testing, network programming, and security reporting**.

The practical program is designed to progressively move from **network and security fundamentals** toward a complete **end-to-end security assessment** of a deliberately vulnerable web application.

---

## 🎯 Practical Learning Journey

The practicals follow a progressive security learning path:

```text
Network Fundamentals
        ↓
Network Topologies & Devices
        ↓
Security Lab Environment
        ↓
Network Traffic Analysis
        ↓
Network Reconnaissance
        ↓
Python Programming
        ↓
Network Programming
        ↓
Authentication & Password Security
        ↓
Web Application Security
        ↓
Web Reconnaissance
        ↓
Vulnerability Assessment
        ↓
Vulnerability Validation
        ↓
Risk Assessment
        ↓
Security Reporting
        ↓
End-to-End Security Assessment
```

By the end of the practical program, students should be able to approach a security assessment from **initial reconnaissance through vulnerability identification, validation, risk assessment, remediation, and professional reporting**.

---

# 🧪 Practical Sessions

## 1. Network Hardware & Topology Identification + CompTIA Security+

### Topics

* Identify common network hardware
* Understand common network topologies
* Introduction to fundamental cybersecurity concepts
* Introduction to CompTIA Security+ concepts
* Understand basic security terminology and principles

### Key Concepts

* Routers
* Switches
* Access points
* Firewalls
* Network interfaces
* LAN/WAN
* Star, bus, ring and mesh topologies
* CIA Triad
* Authentication and authorization
* Threats, vulnerabilities and risks

---

## 2. Cisco Packet Tracer – Network Topologies

### Topics

* Identify routers, switches, PCs, servers and access points
* Identify network cables and connections
* Build basic network topologies
* Configure basic network connectivity

### Practical Skills

* Device selection
* Physical and logical topology design
* IP addressing
* Connecting network devices
* Basic switch configuration
* Basic router configuration
* Testing connectivity

---

## 3. Security Lab & Network Fundamentals

### Topics

* Configure Kali Linux and target VMs
* Configure NAT and Host-Only networking
* Configure IP addresses
* Identify network interfaces
* Understand ports and network services

### Basic Networking Commands

```bash
ping
ip
ss
netstat
```

### Practical Skills

* Identify IP addresses
* Examine network interfaces
* Test connectivity
* Identify listening ports
* Understand network services
* Verify communication between attacker and target VMs

> **Lab Environment:** Kali Linux will be used as the security testing machine, together with a deliberately vulnerable target VM such as Metasploitable.

---

## 4. Network Traffic Analysis with Wireshark

### Topics

* Capture network traffic
* Analyze Ethernet headers
* Analyze IP headers
* Analyze TCP headers
* Understand the TCP three-way handshake
* Analyze DNS traffic
* Analyze HTTP traffic
* Follow TCP streams
* Apply Wireshark display filters

### Practical Skills

* Packet capture
* Protocol identification
* Header analysis
* Traffic filtering
* TCP stream reconstruction
* Basic network troubleshooting

---

## 5. Nmap – Network Reconnaissance

### Topics

* Host discovery
* TCP scanning
* UDP scanning
* Service and version detection
* OS detection
* Understand open, closed and filtered ports

### Practical Skills

Students will learn how to:

* Discover hosts
* Identify exposed ports
* Identify running services
* Determine service versions
* Interpret Nmap scan results
* Build a basic network reconnaissance profile

> **Important:** Scanning should only be performed against systems that are explicitly authorized for the practical exercise.

---

## 6. Python Fundamentals

### Topics

* Python syntax and programming concepts
* Variables and data types
* Conditions
* Loops
* Functions
* Modules
* File handling
* Exception handling

### Security Applications

Students will begin using Python to create simple scripts that can support security-related tasks such as:

* Input processing
* File analysis
* Data parsing
* Automation
* Basic security utilities

---

## 7. Network Programming with Python

### Topics

* TCP/IP fundamentals
* Socket programming
* TCP client/server architecture
* Build basic TCP client/server applications
* Send and receive network data
* Basic network automation

### Practical Skills

Students will develop programs that demonstrate:

```text
Client
   │
   │ TCP Connection
   ▼
Server
   │
   ├── Receive data
   ├── Process data
   └── Send response
```

Students will also explore how network communication can be automated using Python.

---

## 8. Password & Authentication Security with Python

### Topics

* Password hashing
* Salting
* Hash identification
* Dictionary attacks using deliberately provided hashes
* Password complexity
* Password security
* Account lockout
* Multi-factor authentication (MFA)

### Practical Skills

Students will explore:

* Secure password storage
* Hashing versus encryption
* Salted password hashes
* Password strength
* Authentication weaknesses
* Basic defensive authentication mechanisms

> **Safety:** Password-cracking exercises must use only hashes deliberately provided for the laboratory exercise. Do not use real credentials or unauthorized password data.

---

## 9. Web Application Security – DVWA / OWASP Juice Shop

### Topics

* Web application fundamentals
* HTTP fundamentals
* OWASP Top 10 introduction
* Burp Suite basics
* SQL Injection
* Cross-Site Scripting (XSS)
* Authentication vulnerabilities
* Session vulnerabilities

### Practical Environment

Students will perform controlled security testing using deliberately vulnerable applications such as:

* **DVWA (Damn Vulnerable Web Application)**
* **OWASP Juice Shop**

### Practical Skills

* Intercept HTTP requests
* Modify requests
* Analyze responses
* Identify common web vulnerabilities
* Understand vulnerability impact

---

## 10. Web Application Reconnaissance

### Topics

* Identify application technologies
* Identify application endpoints
* Discover directories
* Discover parameters
* Identify APIs
* Analyze HTTP requests and responses
* Identify potential attack surfaces

### Reconnaissance Process

```text
Target Application
        ↓
Technology Identification
        ↓
Endpoint Discovery
        ↓
Directory Discovery
        ↓
Parameter Discovery
        ↓
API Identification
        ↓
Attack Surface Mapping
```

The objective is to understand the application before attempting vulnerability assessment.

---

## 11. Vulnerability Assessment – Buggy Web Application

### Topics

* Assess a deliberately vulnerable web application
* Test authentication
* Test authorization
* Test input validation
* Test session management
* Identify vulnerabilities
* Document findings
* Collect supporting evidence

### Assessment Areas

Students will investigate areas such as:

* Authentication
* Authorization
* Input validation
* Session management
* Access control
* File handling
* Application logic

The emphasis is on **systematic vulnerability identification and documentation**.

---

## 12. Vulnerability Validation & Exploitation

### Topics

* Safely validate identified vulnerabilities
* SQL Injection
* XSS
* IDOR
* File upload vulnerabilities
* Other common web application vulnerabilities
* Understand vulnerability impact
* Recommend basic mitigations

### Validation Process

```text
Potential Vulnerability
          ↓
      Verification
          ↓
      Controlled Test
          ↓
    Collect Evidence
          ↓
    Determine Impact
          ↓
    Recommend Fix
```

Students will perform validation only within the authorized laboratory environment.

---

## 13. Risk Assessment & Prioritization

### Topics

* Assess vulnerability severity
* Assess business impact
* Introduction to CVSS
* Classify risks
* Prioritize vulnerabilities for remediation

### Risk Categories

| Severity    | Description                             |
| ----------- | --------------------------------------- |
| 🔴 Critical | Immediate and potentially severe impact |
| 🟠 High     | Significant security impact             |
| 🟡 Medium   | Moderate security impact                |
| 🟢 Low      | Limited security impact                 |

Students will learn to move beyond simply identifying vulnerabilities and determine **which vulnerabilities should be addressed first and why**.

---

## 14. Security Reporting & Remediation

### Topics

* Prepare a professional vulnerability assessment report
* Document findings
* Present evidence
* Explain vulnerability impact
* Assign severity
* Provide remediation recommendations
* Present findings to a technical team

### Typical Finding Structure

```text
Finding
   ↓
Description
   ↓
Affected Component
   ↓
Evidence
   ↓
Impact
   ↓
Severity
   ↓
CVSS
   ↓
Remediation
   ↓
References
```

The objective is to develop the ability to communicate technical security findings clearly to both **technical and non-technical stakeholders**.

---

# 15. End-to-End Web Application Security Assessment

The final practical integrates the skills developed throughout the module into a simulated real-world security engagement.

### Assessment Workflow

```text
┌──────────────────────────────┐
│        Target Application    │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│       Reconnaissance         │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│   Attack Surface Mapping     │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│   Vulnerability Discovery    │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│   Vulnerability Validation   │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│      Risk Assessment         │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│     Remediation Planning     │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│     Security Report          │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│     Final Presentation       │
└──────────────────────────────┘
```

### Final Deliverables

Students will produce:

1. Reconnaissance results
2. Attack surface documentation
3. Vulnerability findings
4. Evidence/screenshots
5. Severity and risk assessment
6. CVSS-based prioritization
7. Remediation recommendations
8. Professional security assessment report
9. Final presentation

The final exercise simulates a **real-world security assessment engagement** in a controlled academic environment.

---

# 🛠️ Tools & Technologies

The practical program may use the following tools and technologies:

| Area                   | Tools / Technologies                   |
| ---------------------- | -------------------------------------- |
| Virtualization         | VirtualBox / VMware                    |
| Security Testing OS    | Kali Linux                             |
| Vulnerable Targets     | Metasploitable, DVWA, OWASP Juice Shop |
| Networking Simulation  | Cisco Packet Tracer                    |
| Traffic Analysis       | Wireshark                              |
| Network Reconnaissance | Nmap                                   |
| Web Testing            | Burp Suite                             |
| Programming            | Python                                 |
| Web Security           | DVWA / OWASP Juice Shop                |
| Risk Assessment        | CVSS                                   |
| Security Standards     | OWASP / CompTIA Security+ concepts     |

---

# ⚠️ Responsible Security Testing

All practical exercises in this repository are intended for **authorized educational environments only**.

Students must:

* Test only systems provided or explicitly authorized for the practical.
* Use deliberately vulnerable machines and applications for exploitation exercises.
* Never scan or attack public systems without explicit authorization.
* Never use real user credentials or sensitive information.
* Never perform attacks against university infrastructure or third-party systems.
* Keep vulnerable virtual machines isolated from networks where necessary.
* Follow the instructions provided in each laboratory sheet.

> **The skills learned in this module must be applied responsibly and ethically.**

---

# 📚 Practical Progression

|  # | Practical                                  | Main Focus                         |
| -: | ------------------------------------------ | ---------------------------------- |
| 01 | Network Hardware & Topology Identification | Networking & Security Fundamentals |
| 02 | Cisco Packet Tracer                        | Network Topologies                 |
| 03 | Security Lab & Network Fundamentals        | Virtual Labs & Networking          |
| 04 | Wireshark                                  | Network Traffic Analysis           |
| 05 | Nmap                                       | Network Reconnaissance             |
| 06 | Python Fundamentals                        | Programming                        |
| 07 | Network Programming with Python            | Socket Programming                 |
| 08 | Password & Authentication Security         | Authentication Security            |
| 09 | DVWA / OWASP Juice Shop                    | Web Application Security           |
| 10 | Web Application Reconnaissance             | Attack Surface Discovery           |
| 11 | Vulnerability Assessment                   | Vulnerability Identification       |
| 12 | Vulnerability Validation                   | Controlled Exploitation            |
| 13 | Risk Assessment                            | CVSS & Prioritization              |
| 14 | Security Reporting                         | Reporting & Remediation            |
| 15 | End-to-End Assessment                      | Complete Security Engagement       |

---

# 🎓 Expected Outcome

After completing the practical program, students should be able to:

* Understand fundamental computer and network security concepts.
* Identify and analyze common network infrastructure.
* Configure a controlled security laboratory.
* Analyze network traffic using Wireshark.
* Perform authorized network reconnaissance using Nmap.
* Develop basic security-related Python programs.
* Build network applications using Python sockets.
* Understand password and authentication security.
* Perform controlled web application security testing.
* Conduct web application reconnaissance.
* Identify and validate common vulnerabilities.
* Assess vulnerability severity and business impact.
* Prioritize vulnerabilities using CVSS concepts.
* Recommend appropriate security mitigations.
* Produce professional vulnerability assessment reports.
* Present security findings to a technical audience.
* Conduct an end-to-end security assessment in a controlled environment.

---

## 📁 Repository Structure

A recommended repository structure is:

```text
computer-and-network-security/
│
├── README.md
│
├── Lab-01-Network-Hardware-and-Security/
├── Lab-02-Cisco-Packet-Tracer/
├── Lab-03-Security-Lab-Network-Fundamentals/
├── Lab-04-Wireshark/
├── Lab-05-Nmap/
├── Lab-06-Python-Fundamentals/
├── Lab-07-Python-Network-Programming/
├── Lab-08-Password-Authentication-Security/
├── Lab-09-Web-Application-Security/
├── Lab-10-Web-Reconnaissance/
├── Lab-11-Vulnerability-Assessment/
├── Lab-12-Vulnerability-Validation/
├── Lab-13-Risk-Assessment/
├── Lab-14-Security-Reporting/
│
└── Lab-15-End-to-End-Security-Assessment/
```

Each laboratory directory can contain the corresponding **lab sheet, source code, configuration files, datasets, screenshots/evidence requirements, and submission instructions** where applicable.

---

# 🔐 From Fundamentals to Security Assessment

This practical program is structured to develop security skills progressively:

> **Understand the network → observe the network → discover the network → program for the network → assess applications → identify vulnerabilities → validate vulnerabilities → assess risk → remediate → report.**

The final goal is not simply to learn individual security tools, but to develop a **structured security assessment mindset** that can be applied to real-world security problems.

---

### Computer & Network Security

**Software Engineering / Faculty of Computing**

*For academic and authorized security testing purposes only.*
