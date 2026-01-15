# cyber-security-basics

## Understanding Cyber Security Basics & Attack Surface

---

## 📌 Introduction

Cyber Security is the practice of protecting systems, networks, applications, and data from digital attacks.  
The primary goal of cyber security is to ensure that information remains **secure, accurate, and available only to authorized users**.

This task focuses on building a strong foundation by understanding:
- CIA Triad
- Types of cyber attackers
- Attack surfaces
- OWASP Top 10
- Real-world application data flow

---

## 🔐 CIA Triad (Core Principles of Cyber Security)

### 1. Confidentiality
Confidentiality ensures that sensitive information is accessible **only to authorized users**.

**Real-world examples:**
- Online banking credentials
- WhatsApp private messages
- Medical and personal records

**Security techniques used:**
- Encryption
- Authentication (passwords, MFA)
- Access control

---

### 2. Integrity
Integrity ensures that data remains **accurate and unaltered** during storage or transmission.

**Real-world examples:**
- Bank balances not being changed illegally
- Academic marks stored correctly

**Security techniques used:**
- Hashing
- Digital signatures
- Checksums

---

### 3. Availability
Availability ensures that systems and data are **accessible whenever required**.

**Real-world examples:**
- Banking apps during transactions
- Email services running 24/7

**Threats to availability:**
- DDoS attacks
- Server failures
- Ransomware attacks

---

## 🧑‍💻 Types of Cyber Attackers

### Script Kiddies
- Beginners using ready-made tools
- Limited technical knowledge
- Attack for curiosity or fun

---

### Insiders
- Employees or trusted individuals
- Abuse legitimate access
- Difficult to detect

---

### Hacktivists
- Politically or socially motivated
- Target governments or organizations
- Aim to spread awareness or protest

---

### Nation-State Actors
- Government-sponsored attackers
- Highly skilled and well funded
- Target critical infrastructure and sensitive data

---

## 🎯 What is an Attack Surface?

An **attack surface** is the total number of points where an attacker can attempt to gain unauthorized access to a system or data.

A larger attack surface increases security risk, while a smaller one is easier to protect.

---

## 🌐 Common Attack Surfaces

### Web Applications
- Login forms
- APIs
- Databases  
**Example attacks:** SQL Injection, XSS

---

### Mobile Applications
- Insecure data storage
- Weak authentication mechanisms

---

### APIs
- Broken authentication
- Excessive data exposure

---

### Networks
- Open ports
- Weak firewall rules
- Misconfigured routers

---

### Cloud Infrastructure
- Public storage buckets
- Weak IAM policies
- Misconfigured services

---

## 🔟 OWASP Top 10

OWASP Top 10 is a list of the **most critical web application security vulnerabilities**.

Common vulnerabilities include:
- SQL Injection
- Broken Authentication
- Security Misconfiguration
- Cross-Site Scripting (XSS)
- Insecure Design

### Why OWASP Top 10 is Important:
- Industry-standard security reference
- Helps developers and security teams prioritize risks
- Reduces common security flaws in applications

---

## 📱 Mapping Daily Applications to Attack Surfaces

### Email Applications
- Phishing emails
- Malware attachments

### Messaging Applications (WhatsApp)
- Account takeover
- Malicious links

### Banking Applications
- Credential theft
- Man-in-the-Middle (MITM) attacks

---

## 🔄 Data Flow in a Typical Application

