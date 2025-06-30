# Wireshark Traffic Analysis Report

**Protocols Identified:**
1. DNS – used for domain name resolution (UDP port 53)
2. HTTP – used for web browsing (TCP port 80)
3. TCP – general protocol for reliable data transfer

**Details:**
- Captured packets showed several DNS queries when websites were visited.
- HTTP packets revealed GET and POST requests to external servers.
- TCP packets included 3-way handshakes (SYN, SYN-ACK, ACK).
- ICMP packets observed during `ping` tests.

**Tools Used:**
- Wireshark (interface: Ethernet)
- Filtered using: `http`, `dns`, `tcp`


