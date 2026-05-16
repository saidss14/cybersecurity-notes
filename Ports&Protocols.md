# Ports and Protocols

## What is a Port?
A **port** is a communication endpoint used by network-enabled devices to identify and manage different services or applications, allowing data to reach the correct application on the device.


# What is a Protocol?
A **protocol** is a set of rules that defines how data is transmitted and communicated between devices over a network.

### Examples:
- HTTP
- HTTPS
- FTP
- SSH
- DNS


# Difference Between Port and Protocol

| Port | Protocol |
|---|---|
| Identifies a service/application | Defines communication rules |
| Numerical value | Set of communication standards |
| Example: 80, 443 | Example: HTTP, TCP |


# Common Ports and Protocols

| Port | Protocol | Service |
|---|---|---|
| 20/21 | FTP | File Transfer |
| 22 | SSH | Secure Remote Login |
| 23 | Telnet | Remote Login |
| 25 | SMTP | Sending Emails |
| 53 | DNS | Domain Name Resolution |
| 67/68 | DHCP | Automatic IP Assignment |
| 80 | HTTP | Websites |
| 110 | POP3 | Receiving Emails |
| 123 | NTP | Time Synchronization |
| 143 | IMAP | Email Access |
| 161 | SNMP | Network Management |
| 389 | LDAP | Directory Services |
| 443 | HTTPS | Secure Websites |
| 445 | SMB | File Sharing |
| 3389 | RDP | Remote Desktop |


# Types of Ports

## Well-Known Ports
- Range: 0–1023
- Used by common services

## Registered Ports
- Range: 1024–49151
- Used by applications

## Dynamic/Private Ports
- Range: 49152–65535
- Temporary ports used by devices


# Common Protocols

## TCP
- Connection-oriented
- Reliable communication

## UDP
- Faster but less reliable
- Used in streaming and gaming


# Example
When you open a secure website:
- HTTPS protocol is used
- Port 443 handles the communication
