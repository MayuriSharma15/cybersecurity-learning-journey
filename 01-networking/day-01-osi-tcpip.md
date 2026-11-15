# Day 1: OSI and TCP/IP Model

## OSI model (7 layers, top to bottom)
7 Application (HTTP, DNS, SMTP) | 6 Presentation (TLS, encoding) | 5 Session | 4 Transport (TCP, UDP, ports) | 3 Network (IP, routers) | 2 Data Link (MAC, switches) | 1 Physical (cables, Wi-Fi)

## TCP/IP model (4 layers)
Application | Transport | Internet | Network Access

## Key points
- Switch works at Layer 2 (MAC addresses). Router works at Layer 3 (IP addresses). Firewalls filter at Layers 3-7.
- TCP is reliable and connection-based (3-way handshake: SYN, SYN-ACK, ACK). UDP is fast and connectionless (DNS, streaming).
- Port = which service on a host (80 HTTP, 443 HTTPS, 22 SSH, 53 DNS, 3389 RDP).

## Why it matters for a SOC analyst
Alerts are written in terms of IPs, ports and protocols. Many SYNs to many ports from one IP looks like a port scan.

## Lab
Commands run: ipconfig /all, ping, tracert, nslookup, netstat -ano
Findings: (write your own observations here)
