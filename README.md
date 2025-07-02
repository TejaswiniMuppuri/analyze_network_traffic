**Network Traffic Analysis Report**

**Overview**
This report presents the analysis results of a network traffic capture conducted using Wireshark. The focus is on identifying active protocols, participating devices, and noteworthy network behavior observed within the 192.168.1.0/24 subnet over a 1-minute capture duration.

**Key Findings**

**Primary Protocols Detected:**

TCP

UDP

ARP

DNS

ICMP

mDNS (Multicast DNS)

**Detected Devices:**

192.168.1.1 (Default Gateway)

192.168.1.100 (Host)

192.168.1.105 (Host)

224.0.0.251 (mDNS Multicast)

255.255.255.255 (Broadcast)

ff02::1 (IPv6 All-Nodes Multicast)

**Notable Activities:**

DNS Queries to external resolvers (e.g., 8.8.8.8, 1.1.1.1)

ARP Requests/Replies for MAC address resolution

Multicast DNS (mDNS) service discovery traffic

ICMP Echo Requests/Replies (Ping operations)

TCP SYN/SYN-ACK handshake attempts to external IPs

DHCP Discovery and Offer messages for IP address assignment

**Usage**
Refer to the report.md file for a full breakdown of packet-level insights, timestamps, and communication patterns. This includes protocol hierarchies, port usage statistics, and communication flows between devices.

