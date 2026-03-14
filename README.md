# Active-Directory-Splunk-Brute-Force-Lab
Cybersecurity home lab simulating an RDP brute force attack against Windows 10 machine and detecting it using Splunk SIEM

## Lab Environment

4 Virtual Machines were used:

- Splunk Server
- Windows Server 2022 (Active Directory)
- Windows 10 victim machine
- Kali Linux attacker machine

## Attack Simulation

A brute-force attack was executed from Kali Linux using Crowbar against Windows 10 machine through RDP

## Detection
Splunk ingested Windows security logs and detected multiple failed login attempts

Event ID:
4625 - Failed Logon Attempt

## Key Learning Outcomes
- Building small Active-Directory environment (creating users, assigning roles)
- Simulating attacker behavior
- Using Splunk SIEM for log analysis
- Dectecting vruce-force attacks

## Screenshots
