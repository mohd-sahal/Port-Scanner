# Port Scanner 🔍

A beginner-level Python-based Port Scanner using Scapy.  
This tool allows you to scan multiple ports on a given IP address to check which ports are open.

## Features
- Accepts user input for host IP and ports
- Uses SYN scan via Scapy
- Displays open ports

## 💡 What I Learned

- Basics of **port scanning** and how TCP SYN packets work in scanning.
- How to use **Scapy** for low-level network operations in Python.
- Regular expressions to **validate IP addresses**.
- Taking and processing user input in Python.
- How to gracefully handle **exceptions** (like invalid input or runtime errors).


---

## 📦 Packages Used

| Package | Purpose |
|--------|---------|
| `scapy` | For crafting and sending TCP SYN packets and sniffing responses. |
| `re`    | For validating the IP address format using regular expressions. |
| `sys` / `try-except` | For error handling and clean exits. *(built-in)
