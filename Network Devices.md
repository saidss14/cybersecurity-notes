# Network Devices

## 1. Router
A Router connects different networks and forwards data packets between them using IP addresses.

### Main Functions
- Connects different networks
- Routes internet traffic
- Assigns local IP addresses (DHCP)
- Performs NAT (Network Address Translation)

### Example
- Home Wi-Fi router connecting devices to the internet

### Works On
- Layer 3 (Network Layer)

---

## 2. Switch
A Switch connects devices within the same local network (LAN).

### Main Functions
- Transfers data between devices
- Uses MAC addresses for communication
- Reduces unnecessary traffic

### Example
- Office LAN switch

### Works On
- Layer 2 (Data Link Layer)

---

## 3. Firewall
A Firewall monitors and controls incoming and outgoing traffic based on security rules.

### Main Functions
- Blocks unauthorized access
- Filters malicious traffic
- Protects internal networks

### Types
- Hardware Firewall
- Software Firewall

### Example
- Windows Defender Firewall

### Works On
- Mainly Layer 3 and Layer 4

---

## 4. IDS (Intrusion Detection System)
An IDS monitors network traffic and detects suspicious activities or attacks.

### Main Functions
- Detects threats
- Generates alerts
- Monitors network behavior

### Example
- Snort IDS

### Important Point
- IDS only detects attacks
- It does not automatically block them

---

## 5. IPS (Intrusion Prevention System)
An IPS detects and blocks malicious traffic automatically.

### Main Functions
- Detects attacks
- Prevents intrusions
- Blocks harmful traffic

### Example
- Cisco IPS

### Important Point
- IPS can automatically stop attacks

---

## 6. Proxy Server
A Proxy Server acts as an intermediary between users and the internet.

### Main Functions
- Hides client IP addresses
- Filters web traffic
- Improves privacy
- Caches data

### Example
- Corporate proxy servers

---

## 7. VPN (Virtual Private Network)
A VPN creates a secure encrypted connection over the internet.

### Main Functions
- Encrypts internet traffic
- Protects privacy
- Hides public IP address
- Allows secure remote access

### Example
- Remote office VPN connection

### Popular VPN Protocols
- OpenVPN
- WireGuard
- IPSec

---

# Difference Between IDS and IPS

| Feature | IDS | IPS |
|---|---|---|
| Detects threats | Yes | Yes |
| Blocks attacks | No | Yes |
| Placement | Monitoring | Inline with traffic |
| Action | Alert only | Alert + Prevention |

---

# Difference Between Router and Switch

| Feature | Router | Switch |
|---|---|---|
| Connects | Different networks | Devices in same network |
| Uses | IP Address | MAC Address |
| OSI Layer | Layer 3 | Layer 2 |

---

# Quick Summary

| Device | Main Purpose |
|---|---|
| Router | Connects networks |
| Switch | Connects devices in LAN |
| Firewall | Filters traffic |
| IDS | Detects attacks |
| IPS | Prevents attacks |
| Proxy | Intermediary server |
| VPN | Secure encrypted connection |