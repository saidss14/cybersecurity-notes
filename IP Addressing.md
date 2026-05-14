# Day 2 — IP Addressing (IPv4, IPv6, Subnetting)

## What is IP Addressing?
An IP address is a unique identifier assigned to a device connected to a network.

Types of IP addresses:
- IPv4
- IPv6


# IPv4

## Features
- 32-bit address
- Decimal format
- 4 octets

Example:
```bash
192.168.1.1
```

### IPv4 Classes

| Class | Range | Usage |
|---|---|---|
| A | 1–126 | Large networks |
| B | 128–191 | Medium networks |
| C | 192–223 | Small networks |


# Private IP Ranges

| Range |
|---|
| 10.0.0.0 – 10.255.255.255 |
| 172.16.0.0 – 172.31.255.255 |
| 192.168.0.0 – 192.168.255.255 |


# IPv6

## Features
- 128-bit address
- Hexadecimal format
- Larger address space
- Better security support

Example:
```bash
2001:db8::ff00:42:8329
```



# Subnetting

Subnetting divides a large network into smaller subnets.

## Benefits
- Better security
- Efficient IP usage
- Reduced congestion

### CIDR Examples

| CIDR | Hosts |
|---|---|
| /24 | 254 |
| /25 | 126 |
| /26 | 62 |


# Useful Commands

## Check IP Address

### Windows
```bash
ipconfig
```

### Linux
```bash
ip addr
```

## Ping Test
```bash
ping google.com
```

# Cybersecurity Importance

IP addressing helps in:
- Network scanning
- Packet analysis
- Firewall configuration
- Traffic monitoring

Tools:
- Wireshark
- Nmap
- Tcpdump

# Quick Revision

| Topic | Key Point |
|---|---|
| IPv4 | 32-bit |
| IPv6 | 128-bit |
| Subnetting | Dividing networks |
| CIDR | Slash notation |