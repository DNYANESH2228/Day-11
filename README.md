# Day-11
Cybersecurity-Internship
# Day 11 – Network Services

## 1. Network Service and Port
SSH runs on Port 22. It allows secure remote login to another system.

## 2. Connection to Port Scanning
Using Nmap (Day 9), we can scan a system to discover open ports. 
If Port 22 is open, it means the SSH service is running.

Example:
nmap -p 22 <IP>

## 3. Firewall Control
A firewall can block or allow access to SSH.

Example rule:
Allow SSH from trusted IP
Block SSH from unknown networks.

## 4. Concept Learned
I learned that network services listen on specific ports and attackers often scan these ports to identify potential vulnerabilities.
