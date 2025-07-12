# 📡 Packet Sniffer using Scapy

A simple yet powerful Python-based packet sniffer built with [Scapy](https://scapy.net/). This tool captures live network traffic and analyzes IP packets, providing insights such as source/destination IPs, ports, protocols, and payload sizes.

---

## 🚀 Features

* Captures live network packets
* Extracts and displays:

  * Source & Destination IP
  * Protocol Type (TCP, UDP, ICMP, Others)
  * Source & Destination Port (if applicable)
  * Payload Length
* Real-time console output
* Lightweight and easy to use

---

## 🧠 How It Works

This script uses the `scapy.all.sniff()` function to capture packets in real-time. For each packet:

* It checks if it contains an IP layer.
* If present, it extracts:

  * IP addresses
  * Protocol type
  * Ports (for TCP/UDP)
  * Payload size

Sample output:

```
----------------------------------------------------------------------
Source IP      : 20.42.65.91
Destination IP : 10.75.251.142
Protocol        : TCP
Source Port     : 443
Destination Port: 51207
Payload Length  : 32 bytes
```

---

## 🛠 Requirements

* Python 3.x
* Scapy

Install Scapy using pip:

```bash
pip install scapy
```

> ⚠️ **Note**: You may need to run the script with administrator/root privileges for packet sniffing.

---

## 📁 Usage

### Step 1: Clone the repository

```bash
git clone (https://github.com/AnshikaAsthana/CodeAlpha_Task1/blob/main/Basic%20Network%20Sniffer)
```

### Step 2: Run the script

```bash
sudo python3 sniffer.py
```

Press `Ctrl + C` to stop sniffing.

---

## 📄 File Structure

```
packet-sniffer/
│
├── sniffer.py         # Main packet sniffer script
└── README.md           # This file
```

---

## 👩‍💻 Created By

**Anshika Raj**
Feel free to connect and contribute!

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

Let me know if you'd like to add a logo, license file, or contribution guidelines!
