# Detection and Analysis of Simulated Adversary Activity

## Objective

Simulate attacker activity against a vulnerable Linux host and analyze the resulting network traffic from a defensive perspective.

## Lab Environment

### Red Team
- Kali Linux
- IP: 192.168.56.102

### Victim
- Metasploitable 2
- IP: 192.168.56.101

### Blue Team
- Ubuntu Linux
- IP: 192.168.56.103
- Wireshark
- Wazuh

## What I Did

1. Verified connectivity between systems.
2. Performed service enumeration using Nmap.
3. Identified exposed services on the target.
4. Used Hydra to validate FTP credentials.
5. Authenticated to the FTP service.
6. Enumerated files on the target system.
7. Retrieved a file from the target host.
8. Captured and analyzed network traffic using Wireshark.
9. Investigated attacker activity from a blue-team perspective.

## Key Findings

- Weak FTP credentials were present.
- Multiple vulnerable services were exposed.
- Reconnaissance activity was visible in packet captures.
- FTP authentication activity was captured and analyzed.
- File transfer activity could be reconstructed from network traffic.

## Skills Demonstrated

- Virtualization
- Linux Administration
- Nmap
- Hydra
- FTP
- Wireshark
- Packet Analysis
- Network Reconnaissance
- Technical Documentation

## Technologies Used

- Oracle VirtualBox
- Kali Linux
- Ubuntu Linux
- Metasploitable 2
- Wireshark
- Wazuh
- Nmap
- Hydra
