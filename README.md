# Web Security Labs

Hands-on notes from teaching myself penetration testing and security fundamentals — mostly in a home lab using Kali Linux, Metasploitable2, and DVWA, along with practice on TryHackMe, Hacker101, and other CTF platforms.

I document what I learn as I go so I understand why something works, rather than only memorising the commands.

## What's here

### Metasploitable Lab — Full Attack Walkthrough

Scanned, enumerated, and exploited Metasploitable2, a deliberately vulnerable virtual machine designed for security practice.

1. **Reconnaissance** — used Nmap to identify open ports and running services
2. **Exploitation** — used the known vsftpd 2.3.4 backdoor to gain shell access
3. **Troubleshooting** — documented the difference between failed and successful exploitation attempts
4. **Post-exploitation** — explored basic file and system access after gaining a shell
5. **Loot** — retrieved a sample password hash file from the training machine for hash-format study

All testing was carried out in an isolated home lab against intentionally vulnerable systems.

### SQL Injection — DVWA

Basic authentication bypass payloads and notes on how poorly handled user input can manipulate database queries.

### XSS — DVWA

Practice with basic script injection and notes on why input validation and output encoding are important.

### Nmap — Quick Reference

A collection of Nmap commands that I regularly use for port scanning, service detection, and basic enumeration.

### CTF Practice

- **Hacker101 CTF** — beginner web security challenges, including notes on the vulnerabilities I identified and how I approached them
- **NINEBYTE CTF 2026** — challenges involving cryptography, digital forensics, corrupted file analysis, hidden data extraction, and image and audio analysis
- **TryHackMe** — an ongoing record of rooms covering web application security, common vulnerabilities, penetration testing, and Linux fundamentals

## Why I'm Doing This

I am working to build a practical understanding of both offensive and defensive security.

Learning how attacks work helps me understand the evidence they leave behind, such as suspicious log entries, unusual authentication activity, or unexpected network traffic. This is one of the reasons I am particularly interested in SOC and blue-team roles.

## Current Status

- Google Cybersecurity Professional Certificate
- NINEBYTE CTF 2026 Certificate
- TryHackMe Jr Penetration Tester path — in progress
- Continuing to add new labs and CTF practice

## Tools Used Across These Labs

- Kali Linux
- Nmap
- Metasploit Framework
- DVWA
- Burp Suite
- Wireshark
