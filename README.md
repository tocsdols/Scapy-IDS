## 🎯 Objective

The objective of this project is to build a basic Intrusion Detection System (IDS) capable of detecting suspicious network activity by monitoring TCP SYN packet behavior in real time.

The project focuses on identifying potential port scanning attempts by analyzing repeated connection requests from the same IP address within a specified time window.

## 🧠 Skills Learned

- Network traffic analysis
- Packet sniffing with Scapy
- TCP/IP and SYN packet understanding
- Basic intrusion detection concepts
- Python scripting for cybersecurity
- Real-time threat monitoring
- Logging and alert generation
- Working with packet-level network data

## 🛠 Tools Used

- Python 3
- Scapy
- Npcap (Windows packet capture support)
- Command Prompt / Terminal
- VS Code (or preferred code editor)
- Git & GitHub

## 📌 Steps Used

1. Installed Python and Scapy for packet analysis.
2. Configured packet capture support using Npcap (Windows).
3. Created a packet sniffing script using Scapy.
4. Filtered TCP packets with SYN flags enabled.
5. Stored and tracked source IP addresses sending SYN packets.
6. Implemented detection logic for repeated SYN requests within 60 seconds.
7. Generated alerts when suspicious activity exceeded the threshold.
8. Logged intrusion attempts into `scan_log.txt`.
9. Tested the IDS in a controlled environment.
10. Documented the project and uploaded it to GitHub.

## 🎥 Project Demo

Watch the full project walkthrough and live demonstration here:

[YouTube Demo Link](https://www.youtube.com/watch?v=yJuEgMhqsNk)



## 📸 Screenshots
**Real-time network sniffing**


ref 1 - Linux terminal
<img width="1190" height="594" alt="Pasted Graphic" src="https://github.com/user-attachments/assets/948d809b-b52e-4527-ad75-0a098422e59c" />

ref 2 - MacOS terminal
<img width="583" height="383" alt="Configuration" src="https://github.com/user-attachments/assets/860a608f-d15b-49af-93eb-25af270eed21" />



**Port scan detection via TCP SYN pattern**

ref 3 
<img width="655" height="417" alt="Pasted Graphic 5" src="https://github.com/user-attachments/assets/060a6cbb-6b78-49af-93f2-1751d3bbf013" />



**Log file terminal output**

Alerts are logged to scan_log.txt for auditing

ref 4
<img width="689" height="437" alt="Pasted Graphic 6" src="https://github.com/user-attachments/assets/cdce6d42-143f-4629-8611-50355a265205" />







**Samuel — Aspiring SOC Analyst & Cybersecurity Enthusiast**


