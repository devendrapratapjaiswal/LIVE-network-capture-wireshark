# Task 5 – Capture and Analyze Network Traffic Using Wireshark

This repository contains the complete work for **Task 5** of my Cybersecurity Internship at **ElevateLabs**.  
The goal of this task was to capture live network traffic using **Wireshark**, analyze the protocols, and understand packet-level communication.

---

## Objective

- Capture live traffic on my local machine.
- Analyze and identify various protocol types (at least 3).
- Export the packet capture as a `.pcapng` file.
- Document the findings and packet details through screenshots and report.

---

## Tools Used

| Tool      | Purpose                                  |
|-----------|------------------------------------------|
| Wireshark | Packet capturing and protocol analysis   |
| Ethernet  | Used as the active network interface     |
| Kali Linux | Host OS for performing the analysis     |

---

## Protocols Identified

| Protocol | Description                                  | Screenshot                                     |
|----------|----------------------------------------------|------------------------------------------------|
| **DNS**  | Used to resolve domain names to IP addresses | `dns-protocol-packet-detail.png`              |
| **NBNS** | NetBIOS Name Service for IP-hostname mapping | `nbns-packet-ip-idenfication.png`             |
| **ARP**  | Address Resolution Protocol (MAC/IP link)    | `packet-detail-arp-stream.png`                |
| **UDP**  | Connectionless data transport protocol       | `packet-udp-stream-in-yaml.png`               |
| **TCP**  | Connection-oriented data transfer protocol   | `packet-tcp-stream-in-yaml-format.png`        |


