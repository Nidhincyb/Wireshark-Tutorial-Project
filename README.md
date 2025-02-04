# Wireshark-Tutorial-Project
Wireshark is a powerful, open-source tool used for network protocol analysis. This project is designed to serve as a comprehensive guide and tutorial on how to use Wireshark effectively for packet capturing, network troubleshooting, and protocol analysis.

## Tools & Technologies
Wireshark: Network protocol analyzer for packet capturing and analysis.
Operating Systems: Windows, macOS, Linux.
Protocols Covered: HTTP, TCP/IP, UDP, DNS, ICMP, ARP, and more.

## Using Wireshark for Network Analysis

### Step 1: Starting a Packet Capture
Select Network Interface: When you open Wireshark, select the interface you want to capture traffic from (e.g., Wi-Fi, Ethernet).
Start Capture: Click on the interface to begin capturing packets. You will see network packets being displayed in real-time.

### Step 2: Applying Filters
Wireshark allows you to filter captured traffic to make your analysis more manageable. Here are some common filters:

Display Filters:

To view only HTTP traffic: http
To capture traffic from a specific IP: ip.addr == 192.168.1.10
To see DNS traffic: dns

Capture Filters:

To capture only UDP traffic: udp
To capture traffic from a specific port: port 80

### Step 3: Analyzing Protocols
Wireshark allows you to inspect the protocols within each captured packet. For example:

TCP Handshake: You can view the three-way handshake (SYN, SYN-ACK, ACK) to troubleshoot connection issues.
HTTP Requests: Examine HTTP request and response headers to troubleshoot web application behavior.
DNS Queries: Troubleshoot DNS resolution issues by looking at DNS query packets and responses.

### Step 4: Saving and Sharing Captures
Wireshark allows you to save captured packets as .pcap files, which can be shared with other team members or analyzed later.
