# cybersecurity-home-lab

## Overview
This project documents the setup of a small cybersecurity home lab using virtual machines. The goal was to simulate common network activity and observe how security logs capture suspicious behavior.

## Lab Setup
- VirtualBox
- Windows 10 virtual machine
- Ubuntu Linux virtual machine
- NAT Network for isolated communication

## What I Did
- Configured virtual machines to communicate securely
- Troubleshot network and IP address issues
- Simulated basic attack activity inside the lab
- Viewed and analyzed security logs

## Simulated Activities

### Network Scan
From the Ubuntu machine, I ran a network scan against the Windows machine using Nmap to simulate reconnaissance activity.

## Authentication Failures
- Generated failed login attempts on Windows
- Reviewed Windows Security Event logs
- Reviewed Linux authentication logs

## Evidence
### Screenshots in the screenshots folder show:
- IP configuration on both systems
- Successful network communication 
- Nmap scan results
- Windows firewall logs showing blocked connections

## Lessons Learned
- Learned how NAT networks work with VirtualBox
- Learned how to enable and read Windows firewall logs
- How to identify suspicious activity in logs
- That security logging must be enabled to detect attacks
- Learned how to detect port scans with Nmap
- How to document technical work clearly

## Next Steps
- Add centralized log collection with Splunk or Wazuh
- Create alerts for suspicious activity
- Add more simulated attacks

**Example Command:**
```bash
nmap -sS 10.0.2.7
Cybersecurity home lab demonstrating basic attack simulation and log analysis using Windows and Linux virtual machines.

