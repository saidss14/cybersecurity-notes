===============================
NETWORK TRAFFIC ANALYSIS
===============================

INTRODUCTION
-------------
Network Traffic Analysis (NTA) means monitoring and analyzing the data moving through a network. It helps security analysts and network engineers understand how devices communicate and identify suspicious or unusual activity.

It is mainly used for:
- Cybersecurity
- Troubleshooting network issues
- Monitoring traffic
- Investigating attacks
- Understanding network communication

--------------------------------------------------

1. PCAP (Packet Capture)
-------------------------

PCAP stands for Packet Capture.

It is a file format used to store captured network packets so they can be analyzed later.

A PCAP file contains:
- Source IP Address
- Destination IP Address
- Protocol Information
- Packet Data
- Timestamps

Common file extensions:
- .pcap
- .pcapng

PCAP files are commonly analyzed using tools like Wireshark and tcpdump.

Uses of PCAP:
- Investigating cyber attacks
- Malware analysis
- Troubleshooting network problems
- Monitoring network activity

Advantages:
- Provides detailed packet-level information
- Useful for deep traffic analysis
- Helpful during forensic investigations

Disadvantages:
- PCAP files can become very large
- Requires more storage space

--------------------------------------------------

2. FLOW LOGS
------------

Flow logs store metadata about network communication instead of full packet contents.

They provide a summary of traffic between devices.

Flow logs usually contain:
- Source IP Address
- Destination IP Address
- Source Port
- Destination Port
- Protocol
- Number of packets
- Amount of transferred data

Examples:
- NetFlow
- IPFIX
- VPC Flow Logs

Advantages:
- Smaller in size compared to PCAP
- Faster to analyze
- Useful for monitoring large networks

Disadvantages:
- Does not contain full packet data
- Limited visibility compared to PCAP

--------------------------------------------------

PCAP vs FLOW LOGS
-----------------

PCAP:
- Stores complete packet data
- Useful for detailed investigations
- Requires more storage

FLOW LOGS:
- Stores traffic summaries
- Useful for monitoring network activity
- Requires less storage

--------------------------------------------------

3. WIRESHARK
------------

Wireshark is a graphical network protocol analyzer used to capture and inspect network traffic.

It is one of the most popular tools for packet analysis.

Features:
- Live packet capturing
- Packet filtering
- Protocol analysis
- Stream following
- Exporting PCAP files

Common Filters:
ip.addr == 192.168.1.1
tcp.port == 80
http
dns

Uses:
- Detecting suspicious traffic
- Troubleshooting network issues
- Learning network protocols
- Analyzing malware communication

Advantages:
- Easy-to-use graphical interface
- Detailed packet inspection
- Supports many network protocols

Disadvantages:
- Uses more system resources
- Large captures may slow down analysis

--------------------------------------------------

4. TCPDUMP
----------

tcpdump is a command-line packet capture tool mainly used in Linux systems.

It captures and displays packets directly from the terminal.

Basic Commands:

Capture packets:
sudo tcpdump

Capture packets on a specific interface:
sudo tcpdump -i eth0

Save packets into a PCAP file:
sudo tcpdump -w capture.pcap

Read packets from a PCAP file:
sudo tcpdump -r capture.pcap

Filter traffic by port:
sudo tcpdump port 80

Advantages:
- Lightweight and fast
- Useful on remote servers
- Works well without a graphical interface

Disadvantages:
- Command-line based
- Can be difficult for beginners

--------------------------------------------------

WIRESHARK vs TCPDUMP
--------------------

WIRESHARK:
- Graphical Interface
- Beginner friendly
- Better visualization of packets

TCPDUMP:
- Command-line based
- Lightweight
- Better for quick captures on servers

--------------------------------------------------

COMMON NETWORK PROTOCOLS
------------------------

HTTP  - Used for web communication
HTTPS - Secure web communication
DNS   - Converts domain names into IP addresses
TCP   - Reliable communication protocol
UDP   - Faster communication protocol
ICMP  - Used for network diagnostics
FTP   - File transfer protocol
SSH   - Secure remote access

--------------------------------------------------

IMPORTANCE OF NETWORK TRAFFIC ANALYSIS
--------------------------------------

Network Traffic Analysis helps organizations:
- Detect cyber attacks
- Monitor suspicious activity
- Troubleshoot connectivity issues
- Investigate security incidents
- Understand how devices communicate

--------------------------------------------------

SIMPLE WORKFLOW
---------------

Network Traffic
       ↓
Packet Capture
       ↓
Store as PCAP
       ↓
Analyze using Wireshark or tcpdump
       ↓
Detect Issues or Threats

--------------------------------------------------

CONCLUSION
----------

Network Traffic Analysis is an important part of cybersecurity and networking.

Important concepts include:
- PCAP for storing packet captures
- Flow Logs for traffic summaries
- Wireshark for graphical packet analysis
- tcpdump for command-line packet capture

These tools help security analysts monitor traffic, investigate incidents, and identify threats effectively.