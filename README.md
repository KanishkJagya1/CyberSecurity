# Capture The Flag (CTF) Handbook
Author: Kanishk Jagya  
GitHub: [github.com/KanishkJagya1](https://github.com/KanishkJagya1)

## Table of Contents
1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
    - [What is CTF?](#what-is-ctf)
    - [Types of CTF Challenges](#types-of-ctf-challenges)
    - [Setting Up Your Environment](#setting-up-your-environment)
3. [CTF Topics](#ctf-topics)
    - [Web Exploitation](#web-exploitation)
        - [SQL Injection](#sql-injection)
        - [Cross-Site Scripting (XSS)](#cross-site-scripting-xss)
        - [Cross-Site Request Forgery (CSRF)](#cross-site-request-forgery-csrf)
        - [Server-Side Request Forgery (SSRF)](#server-side-request-forgery-ssrf)
        - [Prototype Pollution](#prototype-pollution)
        - [Broken Access Control](#broken-access-control)
    - [Cryptography](#cryptography)
        - [Classical Ciphers](#classical-ciphers)
        - [Modern Cryptography](#modern-cryptography)
        - [Hash Functions](#hash-functions)
    - [Reverse Engineering](#reverse-engineering)
        - [Disassembly](#disassembly)
        - [Decompilation](#decompilation)
        - [Debugging](#debugging)
    - [Forensics](#forensics)
        - [File Carving](#file-carving)
        - [Memory Forensics](#memory-forensics)
        - [Network Forensics](#network-forensics)
    - [Binary Exploitation](#binary-exploitation)
        - [Buffer Overflow](#buffer-overflow)
        - [Format String Exploits](#format-string-exploits)
        - [Return-Oriented Programming (ROP)](#return-oriented-programming-rop)
    - [Miscellaneous](#miscellaneous)
        - [Steganography](#steganography)
        - [OSINT](#osint)
4. [Tools and Resources](#tools-and-resources)
    - [Common Tools](#common-tools)
    - [Online Resources](#online-resources)
5. [Practice Challenges](#practice-challenges)
6. [Conclusion](#conclusion)

## Introduction
Welcome to the Capture The Flag (CTF) Handbook! This repository provides a comprehensive guide to getting started with CTF competitions, understanding various topics, and utilizing essential tools. Whether you're a beginner or an experienced player, this handbook will help you enhance your skills and prepare for CTF challenges.

## Getting Started

### What is CTF?
Capture The Flag (CTF) is a type of cybersecurity competition where participants solve security-related challenges to find "flags." These flags are hidden pieces of data that prove a particular vulnerability or skill has been exploited. CTF competitions are often used to educate and train individuals in various cybersecurity domains.

### Types of CTF Challenges
1. **Jeopardy-style**: Participants solve individual tasks from various categories to earn points. The team or individual with the most points at the end wins.
2. **Attack-Defend**: Teams defend their own services while trying to attack and exploit the services of other teams. This type focuses on both offense and defense skills.
3. **Mixed**: A combination of Jeopardy-style and Attack-Defend challenges.

### Setting Up Your Environment
- **Virtual Machines**: Use VMs to safely run and test potentially malicious code.
- **Development Tools**: Install text editors, debuggers, and other essential tools.
- **Networking Tools**: Set up tools like Wireshark, Nmap, and Burp Suite for network analysis.

## CTF Topics

### Web Exploitation

    - SQL Injection
    SQL Injection involves manipulating SQL queries through input fields to gain unauthorized access or retrieve hidden data. This vulnerability occurs when user inputs are not properly sanitized before being included in SQL queries.

    - Cross-Site Scripting (XSS)
    XSS allows attackers to inject malicious scripts into web pages viewed by other users. There are three main types: Stored, Reflected, and DOM-based XSS.

    - Cross-Site Request Forgery (CSRF)
    CSRF tricks a user into performing actions they didn't intend to, by exploiting their authenticated session on a web application.

    - Server-Side Request Forgery (SSRF)
    SSRF allows an attacker to make requests from the server to internal resources. This can lead to accessing sensitive internal services.

    - Prototype Pollution
    Prototype Pollution involves injecting properties into JavaScript object prototypes, affecting all objects that inherit from that prototype. This can manipulate application behavior and lead to security issues.

    - Broken Access Control
    Broken Access Control occurs when an application does not properly enforce permissions, allowing unauthorized access to resources.

### Cryptography

    - Classical Ciphers
    Classical ciphers include basic encryption techniques like Caesar cipher, Vigenère cipher, and substitution ciphers.

    - Modern Cryptography
    Modern cryptography involves advanced algorithms such as AES, RSA, and ECC, focusing on secure data encryption and decryption.

    - Hash Functions
    Hash functions convert input data into fixed-size strings. Common hash functions include MD5, SHA-1, and SHA-256.

### Reverse Engineering

    - Disassembly
    Disassembly involves converting machine code into assembly code to understand the program's functionality.

    - Decompilation
    Decompilation is the process of converting compiled code back into high-level code to analyze its logic.

    - Debugging
    Debugging is the practice of running a program step-by-step to identify and fix bugs or vulnerabilities.

### Forensics

    - File Carving
    File Carving is the process of extracting files from unallocated disk space or memory dumps.

    - Memory Forensics
    Memory Forensics involves analyzing volatile memory to uncover hidden or running processes, injected code, and more.

    - Network Forensics
    Network Forensics focuses on capturing and analyzing network traffic to identify malicious activities.

### Binary Exploitation

    - Buffer Overflow
    Buffer Overflow occurs when data exceeds the allocated buffer memory, leading to arbitrary code execution.

    - Format String Exploits
    Format String Exploits involve manipulating format string functions to read or write arbitrary memory.

    - Return-Oriented Programming (ROP)
    ROP is an advanced exploitation technique that uses existing code snippets to execute arbitrary code.

### Miscellaneous

    - Steganography
    Steganography involves hiding data within other files, such as images or audio, without altering the carrier file's appearance.

    - OSINT
    Open Source Intelligence (OSINT) involves gathering information from publicly available sources to support security assessments.

## Tools and Resources

### Common Tools
- **Burp Suite**: For web vulnerability scanning and exploitation.
- **Wireshark**: For network traffic analysis.
- **Ghidra**: A reverse engineering tool for decompiling and analyzing binaries.
- **John the Ripper**: A powerful password cracking tool.
- **Metasploit**: A penetration testing framework.

### Online Resources
- **CTF101**: Comprehensive CTF guides and tutorials.
- **OverTheWire**: Wargames for practicing various security skills.
- **Hack The Box**: A platform to practice penetration testing on real-world challenges.

## Practice Challenges
Engage in practice challenges from platforms like CTF101, OverTheWire, and Hack The Box to hone your skills.

## Conclusion
This CTF Handbook serves as a comprehensive guide to understanding and tackling various CTF challenges. By exploring different topics and utilizing essential tools, you can enhance your cybersecurity skills and prepare for competitive CTF events. Happy hacking!