# Network-Scanning-with-Scapy
A beginner-friendly cybersecurity project demonstrating how to perform ICMP ping-based network scanning using Python and Scapy. This project explores packet crafting, protocol layering, and raw socket communication to determine host availability at the network layer.

## 📌 Overview

This project demonstrates how to use **Scapy** to perform basic network scanning by sending ICMP echo requests (ping packets) to determine whether a host is online or offline.

Unlike high-level HTTP requests, this project operates at the network layer by crafting and sending raw packets.

This makes it a foundational cybersecurity exercise in:

- Packet construction
- Network protocol layering
- Raw socket communication
- Host discovery techniques

---

## 🧠 What This Project Demonstrates

- How ICMP ping works under the hood
- How to build IP and ICMP packets manually
- How to send and receive packets programmatically
- How operating system permissions affect low-level networking
- Basic exception handling for network tools

---

## ✅ Requirements

To run this project locally, you will need:

- Python 3.8+
- Jupyter Notebook or Jupyter Lab
- Scapy (`pip install scapy`)
- Administrator/root privileges
- Npcap (Windows users only)

### ⚠ Windows Users

Install **Npcap** and enable:

✔ Install Npcap in WinPcap API-compatible Mode

Without Npcap, Scapy cannot send raw packets.

---

## ⚙ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/network-scanning-with-scapy.git
cd network-scanning-with-scapy
