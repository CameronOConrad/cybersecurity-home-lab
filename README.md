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

**Example Command:**
```bash
nmap -sS 10.0.2.7
Cybersecurity home lab demonstrating basic attack simulation and log analysis using Windows and Linux virtual machines.
