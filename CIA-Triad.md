# CIA Triad

## Introduction

The CIA Triad is one of the most fundamental concepts in cybersecurity. It serves as a model for developing security policies, procedures, and controls that protect information systems and data.

CIA stands for:

- Confidentiality
- Integrity
- Availability

These three principles help organizations secure sensitive information and maintain trust in their systems. Most cybersecurity controls and security frameworks are designed to support one or more aspects of the CIA Triad.

---

# 1. Confidentiality

## Definition

Confidentiality ensures that information is accessible only to authorized individuals, systems, or processes. It prevents unauthorized disclosure of sensitive information.

The primary goal of confidentiality is to protect data from being viewed, copied, or stolen by unauthorized users.

---

## Examples

- Online banking credentials
- Personal identification information (PII)
- Medical records
- Company financial reports
- Government classified information

---

## Methods Used to Achieve Confidentiality

### Access Control

Access control restricts access to resources based on user permissions.

Examples:

- User accounts
- Role-Based Access Control (RBAC)
- Least Privilege Principle

### Authentication

Authentication verifies the identity of users.

Examples:

- Passwords
- PINs
- Biometrics
- Multi-Factor Authentication (MFA)

### Encryption

Encryption converts readable data into an unreadable format.

Examples:

- AES
- RSA
- TLS/SSL

### Data Classification

Organizations classify information based on sensitivity levels.

Examples:

- Public
- Internal
- Confidential
- Restricted

---

## Threats to Confidentiality

### Phishing Attacks

Attackers trick users into revealing sensitive information.

### Insider Threats

Employees may intentionally or accidentally expose confidential data.

### Data Breaches

Unauthorized individuals gain access to sensitive databases.

### Malware

Malicious software can steal credentials and confidential information.

---

## Real-World Example

A hospital stores patient records in a database.

Confidentiality is maintained through:

- User authentication
- Encryption
- Restricted access for medical staff

Unauthorized users should not be able to view patient records.

---

# 2. Integrity

## Definition

Integrity ensures that data remains accurate, complete, and trustworthy throughout its lifecycle.

Data should not be modified, deleted, or corrupted by unauthorized individuals.

---

## Importance of Integrity

Without integrity:

- Data becomes unreliable
- Business decisions may be incorrect
- Financial losses may occur
- Trust in systems decreases

---

## Methods Used to Achieve Integrity

### Hashing

Hashing generates a unique value for data.

Examples:

- MD5
- SHA-1
- SHA-256

If the data changes, the hash value changes.

### Digital Signatures

Digital signatures verify the authenticity and integrity of data.

Commonly used in:

- Secure emails
- Software distribution
- Digital certificates

### Checksums

Checksums detect accidental changes in data.

### Version Control

Tracks changes made to files and documents.

Examples:

- Git
- GitHub

---

## Threats to Integrity

### Malware

Malware can alter or corrupt files.

### Unauthorized Modifications

Attackers may modify records or configurations.

### SQL Injection

Attackers manipulate database information.

### Human Error

Users may accidentally delete or modify important data.

---

## Real-World Example

An online banking system records money transfers.

Integrity ensures:

- Transaction amounts are correct
- Account balances are accurate
- Records are not altered by attackers

---

# 3. Availability

## Definition

Availability ensures that systems, applications, and data are accessible whenever authorized users need them.

Even if data is secure and accurate, it is useless if users cannot access it.

---

## Importance of Availability

Organizations rely on continuous access to:

- Websites
- Databases
- Email systems
- Cloud services
- Business applications

Downtime can result in:

- Financial loss
- Productivity loss
- Reputation damage

---

## Methods Used to Achieve Availability

### Backups

Data backups allow recovery after failures.

Types:

- Full Backup
- Incremental Backup
- Differential Backup

### Redundancy

Multiple systems perform the same function.

Examples:

- Redundant servers
- RAID storage
- Multiple internet connections

### Disaster Recovery Plans

Procedures for restoring operations after disasters.

### Load Balancing

Traffic is distributed across multiple servers.

### Uninterruptible Power Supply (UPS)

Provides temporary power during outages.

---

## Threats to Availability

### DDoS Attacks

Attackers flood systems with traffic, making services unavailable.

### Hardware Failures

Storage devices and servers can fail unexpectedly.

### Natural Disasters

Floods, earthquakes, and fires can disrupt operations.

### Power Outages

Loss of power can make systems inaccessible.

---

## Real-World Example

An e-commerce website experiences heavy traffic during a sale.

Availability is maintained through:

- Load balancing
- Cloud scaling
- Backup servers

Customers can continue shopping without interruption.

---

# Relationship Between the Three Principles

The CIA Triad works together to provide comprehensive security.

| Principle | Focus | Example |
|------------|---------|---------|
| Confidentiality | Prevent unauthorized access | Encryption |
| Integrity | Prevent unauthorized modification | Hashing |
| Availability | Ensure access when needed | Backups |

---

# CIA Triad in Daily Life

## ATM Machine

### Confidentiality
PIN numbers are protected.

### Integrity
Transaction amounts remain accurate.

### Availability
ATM services remain accessible.

---

## Online Banking

### Confidentiality
Account information is protected.

### Integrity
Transactions cannot be altered.

### Availability
Banking services are available 24/7.

---

# Importance of CIA Triad in Cybersecurity

The CIA Triad helps organizations:

- Design secure systems
- Protect sensitive information
- Meet compliance requirements
- Reduce cybersecurity risks
- Build customer trust

Many security frameworks and standards are based on CIA principles, including:

- ISO 27001
- NIST Cybersecurity Framework
- CIS Controls

---

# Key Takeaways

- CIA stands for Confidentiality, Integrity, and Availability.
- Confidentiality protects information from unauthorized access.
- Integrity ensures information remains accurate and trustworthy.
- Availability ensures systems and data remain accessible.
- The CIA Triad is the foundation of modern cybersecurity.
- Most security controls support one or more aspects of the CIA Triad.