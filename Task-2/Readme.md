# Task 02 - Network Scanning & Service Identification

## Objective

To create an authorized local target lab using Kali Linux and Metasploitable 2, verify connectivity, identify the target IP address, and perform basic Nmap scanning to identify open ports and running services.

## Lab Environment

- Attacker/Scanning Machine: Kali Linux
- Target Machine: Metasploitable 2
- Tool Used: Nmap

## Tasks Performed

- Identified the IP addresses of Kali Linux and Metasploitable 2
- Verified connectivity between Kali Linux and Metasploitable 2 using `ping`
- Performed a basic Nmap host and port scan
- Identified open ports and running services
- Performed service and version detection using Nmap `-sV`

## Lab Details

- Kali Linux IP: `192.168.134.128`
- Metasploitable 2 IP: `192.168.134.129`

## Commands Used

```bash
ping -c 4 192.168.134.129
