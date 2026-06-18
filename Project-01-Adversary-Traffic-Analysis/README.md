# Detection and Analysis of Simulated Adversary Activity

## Objective

Simulate attacker activity against a vulnerable Linux host and analyze the resulting traffic from a defensive perspective.

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

## Activities Performed

- Network reconnaissance
- Service enumeration
- Credential validation using Hydra
- FTP authentication
- File retrieval
- Packet analysis using Wireshark

## Key Findings

- Weak FTP credentials were present.
- Multiple vulnerable services were exposed.
- Reconnaissance and authentication traffic were visible in packet captures.
- File transfer activity could be observed and analyzed from the blue-team perspective.
