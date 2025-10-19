# medusa-bruteforce-lab
Simulated SSH brute force attack using Medusa with detection via Snort IDS and AlienVault OSSIM correlation.

# Simulating SSH Brute Force Attack with Medusa and Snort IDS

**Duration:** Feb 2025 – Mar 2025  

This project demonstrates how to simulate and detect an SSH brute-force attack using Medusa, Snort IDS, and AlienVault OSSIM.

## Lab Setup
- **Attacker:** Kali Linux running Medusa  
- **Target:** Ubuntu Server (SSH service)  
- **Detection:** Snort IDS integrated with AlienVault OSSIM SIEM  
- **Monitoring:** Network traffic captured and correlated through OSSIM

<img width="1536" height="1024" alt="lab_diagram" src="https://github.com/user-attachments/assets/0d63f13a-3a4a-4e64-a915-51635a1af58b" />


## Objective
To simulate an SSH brute-force scenario and validate intrusion detection capabilities using Snort and OSSIM correlation.

## Tools Used
- Medusa (Brute Force Attack Tool)  
- Snort IDS  
- AlienVault OSSIM  
- Wireshark (for packet capture and analysis)

## Outcome
Snort successfully detected SSH brute-force attempts and generated alerts, which were correlated in OSSIM for incident tracking.

