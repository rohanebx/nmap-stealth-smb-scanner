
# Nmap Stealth SMB Scanner

A Python script that uses Nmap with advanced IDS/IPS evasion techniques to stealthily scan SMB and RPC ports (135, 137, 138, 139, 445) on a target system. For ethical use in penetration testing labs or red teaming with permission.

## ⚙️ Features

- Checks if Nmap is installed
- Stealth SYN scan (`-sS`)
- Packet fragmentation (`-f`)
- MAC spoofing and decoys
- Custom data and scan delay
- Targets Windows SMB/RPC ports

## 🛠️ Requirements

- Python 3
- Nmap

## 🚀 Usage

```bash
python3 smb-stealth-scan.py
