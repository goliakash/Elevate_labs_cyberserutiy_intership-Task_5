# Elevate_labs_cyberserutiy_intership-Task_5

# Task 5 – Capture and Analyze Network Traffic Using Wireshark

## 🎯 Objective
The goal of this task was to capture live network packets using **Wireshark** and analyze them to identify basic protocols (DNS, HTTP, TCP) and their traffic characteristics.

---

## 🛠 Tools Used
- **Wireshark** (Network Protocol Analyzer)  
- **Operating System**: [Your OS, e.g., Kali Linux/Windows]  

---

## 📌 Methodology
1. Installed Wireshark and started capture on the active interface.  
2. Generated traffic by browsing websites and using ping commands.  
3. Stopped capture after 1–2 minutes.  
4. Applied filters (`dns`, `http`, `tcp`) to analyze specific protocols.  
5. Saved capture as `wireshark_capture.pcap`.  
6. Exported screenshots for documentation.  

---

## 🔎 Findings

### a) DNS (Domain Name System)
- Captured multiple DNS queries and responses.  
- Example: Query for `contile.services.mozilla.com`.  
- Demonstrates how domain names are resolved into IP addresses.  

📸 Screenshot:  
![DNS Screenshot](wireshark_1.png)

---

### b) HTTP (Hypertext Transfer Protocol)
- Observed HTTP GET requests and responses.  
- Example: `GET /success.txt?ipv4 HTTP/1.1` → Response: `200 OK`.  
- Confirms successful client-server communication.  

📸 Screenshot:  
![HTTP Screenshot](wireshark_2.png)

---

### c) TCP (Transmission Control Protocol)
- Captured the **TCP 3-way handshake** (SYN, SYN-ACK, ACK).  
- Example: Connection to `34.160.144.191` on port 443 (HTTPS).  
- TLS handshake packets were also seen, showing encrypted traffic.  

📸 Screenshot:  
![TCP Screenshot](wireshark_3.png)

---

## ✅ Conclusion
Through this task, I learned:  
- How to capture live packets with Wireshark.  
- How to apply filters for specific protocol analysis.  
- How DNS, HTTP, and TCP function in real network traffic.  

This exercise improved my skills in packet analysis and basic network troubleshooting.  

---
