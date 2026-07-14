Many beginners want to learn cybersecurity, ethical hacking, web security, Linux, reverse engineering, malware analysis, blue team, and CTFs, but they do not know where to start.

The biggest mistake is jumping straight into random tools without understanding the basics. Cybersecurity is not just about tools. You need networking, Linux, programming, web fundamentals, operating systems, and a lot of practice.

This thread is a curated list of free and legal resources that can help beginners build a strong foundation step by step.


1. Web Security / Bug Bounty

Web security is one of the best areas for beginners because you can practice legally using labs. You will learn how websites break, how vulnerabilities happen, and how to test safely.

PortSwigger Web Security Academy
https://portswigger.net/web-security

One of the best free web security platforms. It has high-quality lessons and hands-on labs for real web vulnerabilities.

Topics covered:

    SQL Injection
    Cross-Site Scripting
    Authentication bugs
    Access control flaws
    SSRF
    File upload vulnerabilities
    Business logic bugs
    JWT attacks
    CSRF
    Clickjacking
    Web cache poisoning


Why it is useful:
PortSwigger teaches the vulnerability, explains the theory, then gives you a lab to practice legally.

OWASP Top 10
https://owasp.org/www-project-top-ten/

The OWASP Top 10 is one of the most important documents for web security beginners. It explains the most common web application security risks.

Good for learning:

    Broken access control
    Cryptographic failures
    Injection
    Insecure design
    Security misconfiguration
    Vulnerable components
    Authentication failures


OWASP Juice Shop
https://owasp.org/www-project-juice-shop/

A deliberately vulnerable web application made for training. You can run it locally and practice in a safe environment.

Good for:

    Web hacking practice
    OWASP Top 10
    Beginner and advanced challenges
    Safe legal testing


HackerOne Hacktivity
https://hackerone.com/hacktivity

A public list of disclosed vulnerability reports. Very useful to understand how real bug bounty reports are written.

Good for:

    Reading real reports
    Learning impact explanation
    Understanding report structure
    Seeing real-world examples


Bugcrowd University
https://www.bugcrowd.com/hackers/bugcrowd-university/

Free learning material for bug bounty beginners.

Good for:

    Bug bounty methodology
    Recon basics
    Web vulnerability basics
    Responsible disclosure



2. Linux / Networking Basics

Before learning hacking, you need to understand how systems communicate. Networking and Linux are core skills.

OverTheWire Bandit
https://overthewire.org/wargames/bandit/

One of the best beginner resources for learning Linux through practical challenges.

You will practice:

    SSH
    File permissions
    Directories
    Commands
    Pipes
    Grep
    Find
    Cron basics
    Basic privilege concepts


Professor Messer Network+
https://www.professormesser.com/network-plus/n10-009/n10-009-video/n10-009-training-course/

Free networking videos that explain the fundamentals clearly.

Important topics:

    TCP/IP
    DNS
    DHCP
    Ports
    Protocols
    Routing
    Switching
    Subnetting
    Firewalls
    VPNs


Cisco Networking Basics
https://skillsforall.com/course/networking-basics

Beginner-friendly networking course from Cisco.

Good for:

    Network devices
    IP addressing
    Network communication
    Basic troubleshooting


Wireshark Documentation
https://www.wireshark.org/docs/

Wireshark is one of the most important tools for understanding network traffic.

Learn:

    Packets
    TCP handshakes
    DNS traffic
    HTTP traffic
    TLS basics
    Filters
    Packet analysis


Linux Journey
https://linuxjourney.com/

Easy Linux lessons for beginners.

Good for:

    Terminal basics
    File system
    Processes
    Permissions
    Users and groups
    System logs



3. CTF / Practice Platforms

CTFs are one of the best ways to practice safely. They give you legal environments designed for learning.

TryHackMe
https://tryhackme.com/

Very beginner-friendly platform with guided rooms.

Good for:

    Linux basics
    Web security
    Networking
    Blue team
    Red team basics
    Intro to pentesting


Hack The Box Academy
https://academy.hackthebox.com/

Structured modules for cybersecurity learning.

Good for:

    Linux fundamentals
    Web requests
    Active Directory
    Windows fundamentals
    Penetration testing
    Privilege escalation


picoCTF
https://picoctf.org/

Great CTF platform for beginners.

Categories:

    General skills
    Cryptography
    Web exploitation
    Forensics
    Reverse engineering
    Binary exploitation


Root-Me
https://www.root-me.org/

Large challenge platform with many categories.

Good for:

    Web client
    Web server
    Cryptography
    Forensics
    Programming
    App scripting
    Reversing


pwn.college
https://pwn.college/

Excellent for low-level security and systems.

Good for:

    Linux internals
    Program behavior
    Memory
    Exploitation basics
    Reverse engineering
    Binary security


VulnHub
https://www.vulnhub.com/

Download vulnerable virtual machines and practice offline.

Good for:

    Lab building
    Enumeration
    Privilege escalation
    CTF-style practice


Hack The Box Labs
https://www.hackthebox.com/

More challenging than beginner platforms, but very useful after learning the basics.

Good for:

    Realistic pentesting practice
    Machines
    Challenges
    Skill development



4. Reverse Engineering

Reverse engineering helps you understand how programs work internally. Start with legal practice files, crackmes, CTF binaries, and your own compiled programs.

Ghidra
https://ghidra-sre.org/

Free reverse engineering framework.

Useful for:

    Static analysis
    Decompilation
    Strings
    Functions
    Imports
    Control flow
    Cross references


x64dbg
https://x64dbg.com/

Free Windows debugger.

Useful for:

    Breakpoints
    Registers
    Memory analysis
    Runtime behavior
    Step-by-step debugging


OpenSecurityTraining2
https://ost2.fyi/

One of the best free resources for low-level security, reverse engineering, and computer architecture.

Good for:

    x86/x64
    Assembly
    Operating systems
    Exploitation concepts
    Reverse engineering fundamentals


Crackmes.one
https://crackmes.one/

Legal reverse engineering practice binaries made for learning.

Good for:

    Beginner reversing
    Password checks
    Anti-debugging basics
    Keygen-style practice in a legal environment


PE-bear
https://github.com/hasherezade/pe-bear

Tool for viewing Windows PE file structure.

Useful for:

    Headers
    Sections
    Imports
    Exports
    File structure


Detect It Easy
https://github.com/horsicq/Detect-It-Easy

Tool for detecting file type, compiler, packer, and binary information.

Good for:

    Checking executable type
    Identifying packers
    Initial binary analysis


Beginner Reverse Engineering Workflow

1. Check file type
2. Look at strings
3. Check imports
4. Open in Ghidra
5. Let auto-analysis finish
6. Rename important functions
7. Follow cross references
8. Debug only when static analysis is not enough
9. Take notes
10. Practice on legal samples only


5. Blue Team / DFIR

Blue team is about defense, detection, investigation, and response. It is a very important side of cybersecurity.

CyberDefenders
https://cyberdefenders.org/

Hands-on blue team labs.

Good for:

    Incident response
    Forensics
    Malware analysis
    Log analysis
    SOC practice


LetsDefend
https://letsdefend.io/

SOC training platform.

Good for:

    Alert triage
    Phishing analysis
    SIEM practice
    Incident handling


Malware Traffic Analysis
https://www.malware-traffic-analysis.net/

Great resource for learning network traffic analysis.

Good for:

    PCAP analysis
    Malware traffic
    Wireshark practice
    Indicators of compromise


Security Blue Team
https://www.securityblue.team/

Blue team learning and certification resources.

Good for:

    Defensive security
    SOC basics
    Practical blue team skills


DFIR Report
https://thedfirreport.com/

Real-world incident reports and attack analysis.

Good for:

    Reading real investigations
    Understanding attacker behavior
    Learning detection ideas
    Improving defensive mindset



6. Malware Analysis / Safe Labs

Malware analysis should always be done in a safe, isolated lab. Never run unknown files on your main computer.

REMnux
https://remnux.org/

Linux toolkit for malware analysis.

Good for:

    Static malware analysis
    Network analysis
    Document analysis
    Reverse engineering support


Flare VM
https://github.com/mandiant/flare-vm

Windows malware analysis and reverse engineering environment.

Good for:

    Debugging
    Static analysis
    Dynamic analysis
    Reverse engineering tools


ANY.RUN Blog
https://any.run/cybersecurity-blog/

Good articles about malware behavior and analysis.

Good for:

    Malware trends
    Behavior analysis
    Threat research
    Learning from examples


Malware Unicorn Reverse Engineering 101
https://malwareunicorn.org/workshops/re101.html

Free reverse engineering and malware analysis workshop.

Good for:

    Assembly basics
    Debugging
    Malware analysis introduction
    Beginner reversing


Practical Malware Analysis Labs
https://github.com/mikesiko/PracticalMalwareAnalysis-Labs

Labs related to malware analysis learning.

Important:
Only use these in an isolated lab environment.

Safe Lab Tips

    Use a virtual machine
    Disable shared clipboard
    Disable shared folders
    Take snapshots
    Do not use personal accounts
    Do not connect sensitive devices
    Keep samples isolated
    Never analyze unknown files on your main system



7. Programming for Security

Programming helps you automate tasks, understand vulnerabilities, read code, and build your own tools.

Python Official Tutorial
https://docs.python.org/3/tutorial/

Python is great for beginners and security automation.

Useful for:

    Scripting
    Automation
    Parsing logs
    Working with APIs
    Writing simple tools


Automate the Boring Stuff with Python
https://automatetheboringstuff.com/

Beginner-friendly Python book.

Good for:

    File automation
    Web scraping basics
    Working with data
    Practical scripting


C Programming Tutorial
https://www.learn-c.org/

C is important if you want to understand memory and low-level security.

Good for:

    Pointers
    Memory
    Buffers
    Compilation
    Executables


The Rust Book
https://doc.rust-lang.org/book/

Rust is useful for systems programming and secure tooling.

Good for:

    Memory safety
    Systems programming
    Modern security tools


JavaScript.info
https://javascript.info/

JavaScript is very important for web security.

Good for:

    XSS understanding
    Frontend behavior
    Browser security
    DOM manipulation



8. Suggested Beginner Roadmap

If you are completely new, this is a clean path to follow.

Stage 1: Fundamentals

    Learn basic networking
    Learn Linux terminal
    Learn how websites work
    Learn basic Python
    Learn HTTP requests and responses


Resources:
https://linuxjourney.com/
https://overthewire.org/wargames/bandit/
https://www.professormesser.com/
https://docs.python.org/3/tutorial/

Stage 2: Web Security

    Study OWASP Top 10
    Practice PortSwigger labs
    Run OWASP Juice Shop
    Read disclosed reports


Resources:
https://owasp.org/www-project-top-ten/
https://portswigger.net/web-security
https://owasp.org/www-project-juice-shop/
https://hackerone.com/hacktivity

Stage 3: CTF Practice

    Start with beginner CTFs
    Learn basic enumeration
    Practice simple web challenges
    Practice Linux privilege concepts


Resources:
https://tryhackme.com/
https://picoctf.org/
https://www.root-me.org/

Stage 4: Reverse Engineering

    Learn assembly basics
    Learn how executables work
    Use Ghidra
    Use x64dbg
    Practice on crackmes and CTF binaries


Resources:
https://ghidra-sre.org/
https://x64dbg.com/
https://ost2.fyi/
https://crackmes.one/

Stage 5: Blue Team

    Learn logs
    Learn Wireshark
    Analyze PCAPs
    Practice incident response labs
    Read real DFIR reports


Resources:
https://cyberdefenders.org/
https://letsdefend.io/
https://www.malware-traffic-analysis.net/
https://thedfirreport.com/

Stage 6: Build Projects
Some beginner project ideas:

    Simple port scanner
    Log parser
    Password strength checker
    HTTP header analyzer
    Small vulnerable web app for local practice
    Notes from every lab you complete
    Personal cybersecurity blog
    Packet analysis writeups



9. Beginner Mistakes to Avoid

    Learning tools before fundamentals
    Copying commands without understanding them
    Testing random websites without permission
    Ignoring networking
    Ignoring Linux
    Not taking notes
    Jumping into malware without a lab
    Running unknown files on your main PC
    Trying advanced topics too early
    Not practicing consistently



10. Recommended Weekly Study Plan

Week 1: Linux Basics
Practice OverTheWire Bandit and basic terminal commands.

Week 2: Networking
Learn TCP/IP, DNS, HTTP, ports, and protocols.

Week 3: Python Basics
Learn variables, loops, files, requests, and basic automation.

Week 4: Web Security Basics
Study OWASP Top 10 and start PortSwigger labs.

Week 5: CTF Practice
Start TryHackMe, picoCTF, or Root-Me beginner challenges.

Week 6: Reverse Engineering Basics
Install Ghidra and x64dbg. Practice with simple legal crackmes.

Week 7: Blue Team Basics
Use Wireshark, analyze PCAPs, and try CyberDefenders labs.

Week 8: Build a Small Project
Create a script, write a lab report, or document what you learned.


Important Legal Note

Only practice on:

    Systems you own
    CTF platforms
    Legal labs
    Vulnerable machines made for training
    Bug bounty programs where you have permission
    Local environments you created yourself


Do not test random websites, accounts, services, servers, or applications without authorization.

Cybersecurity skills should be used for learning, defense, research, and ethical work.


Final Advice

Cybersecurity takes time. Do not rush the process. Build your foundation first, practice legally, take notes, and try to understand why things work instead of only copying commands.

The best path is:

Learn basics → Practice labs → Take notes → Build projects → Read real reports → Repeat

If you know more free legal resources, don't shy to share it with us!
