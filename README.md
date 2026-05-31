# CyberSecurity_Task_1
# Task Name
Scan your Local Network for Open Ports
# Objectives
The objective of this task was to learn basic network reconnaissance and identify open ports on a local system using Nmap.
# Tools Used
Nmap
Zenmap
Windows Command Prompt
# Procedure
Insalled Nmap and Zenmap on windows
Found the local IP Address using the ipconfig command
Identified the local IP
Performed a regular scan  using Zenmap
Performed TCP SYN Scan using the command : nmap -sS (local ip address here)
Observed open TCP ports and related services
Saved the scan results in HTML format
Took screenshot of the scan output
# Open Ports Found
135/tcp open  msrpc
139/tcp open  netbios-ssn
445/tcp open  microsoft-ds
# Explanation of TCP SYN Scan
A TCP SYN scan is a ype of port scanning technique used by Nmap to identify open TCP ports. it sends a SYNC packet to the target port and checks the response without completing the full TCP handshake, making the scan fast and efficient.
# POtential Security Risks
Open ports may expose network services to attackers
SMB-Realted ports like 139 ans 445 cna be targeted if systems are unpatched
Unnecessary open services can increase network vulnerability
# Key Concepts Learned
Port Scanning
TCP SYN Scan
Open Ports
Network Reconnaissance
Service Detection
Basic Network Security
