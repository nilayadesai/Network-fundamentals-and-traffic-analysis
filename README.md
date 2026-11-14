# Ethernet Communication Investigation & Traffic Analysis

A hands-on investigation of Ethernet communication and TCP/IP protocols using Linux (Ubuntu) and Wireshark.

## Overview

This project focuses on understanding how devices communicate over an Ethernet network and how different network protocols handle data transmission.

The practical work involves Linux network diagnostics, packet capturing, and analysing ARP, ICMP, TCP, and UDP traffic using Wireshark.

## Tech Stack

- **Operating System:** Ubuntu Linux
- **Network Analysis:** Wireshark
- **Networking:** Ethernet (IEEE 802.3), TCP/IP
- **Protocols:** ARP, ICMP, TCP, UDP
- **Tools:** Linux Terminal, iproute2, ping, ss

## Objectives

- Understand Ethernet frame structure and TCP/IP architecture.
- Explore Linux network interfaces and IP configuration.
- Study MAC and IPv4 addressing.
- Perform network diagnostics using Linux commands.
- Capture and analyse network packets using Wireshark.
- Understand the working of ARP, ICMP, TCP, and UDP protocols.

## Practical Activities

| Activity | Description | Wireshark Filter |
|----------|-------------|------------------|
| ARP Analysis | Captured ARP Requests and Replies | `arp` |
| ICMP Analysis | Analysed Echo Request and Echo Reply packets | `icmp` |
| TCP Analysis | Observed TCP Three-Way Handshake and data transfer | `tcp` |
| UDP Analysis | Analysed UDP datagrams and header fields | `udp` |

## Linux Commands Used

| Command | Purpose |
|---------|---------|
| `ip addr` | Display network interfaces and IP addresses |
| `ip route` | Display routing table |
| `arp -a` | View ARP cache |
| `hostname -I` | Display assigned IP addresses |
| `ping -c 4 <IP>` | Test network connectivity |
| `ss -tulnp` | Display active and listening sockets |
| `netstat -tuln` | Display listening network ports |

## Key Observations

- Identified network interfaces and their MAC/IP addresses.
- Observed ARP-based IP-to-MAC address resolution.
- Verified network connectivity through ICMP.
- Analysed TCP Three-Way Handshake (SYN, SYN-ACK, ACK).
- Observed UDP communication without connection establishment.
- Inspected packet headers, source/destination addresses, ports, and protocol fields.

