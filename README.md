# Network Walks – Week 1: Kali Linux Lab Setup

## Overview
This project documents my Week 1 cybersecurity internship lab setup. The objective was to prepare a Kali Linux virtual machine for cybersecurity learning and practical exercises.

## Tools Used
- Oracle VirtualBox
- Kali Linux
- Windows host operating system

## Lab Configuration
- Configured a VirtualBox NAT Network named `NetworkWalks`
- Configured the network subnet as `10.0.0.0/24`
- Connected the Kali Linux virtual machine to the NAT Network
- Configured a shared folder between the Windows host and Kali Linux
- Enabled VirtualBox clipboard and drag-and-drop settings

## Problem I faced
  Problem: Kali Linux showed an active eth0 interface but no IPv4 address.
  Solution: I reviewed the VirtualBox NAT Network and DHCP settings to troubleshoot the network configuration.
  What I learned: How VirtualBox networking, IP addressing and DHCP work together.

## Evidence
A screenshot of the lab setup is included in this repository as evidence of the work completed.

## Learning Outcomes
- Practiced configuring a virtual machine for cybersecurity training
- Learned the difference between NAT and NAT Network in VirtualBox
- Practiced configuring virtual networking and shared folders
- Gained practical experience preparing a Kali Linux lab environment

## Next Steps
- Verify the Kali Linux IP address and internet connectivity
- Test clipboard and shared-folder access
- Continue with the upcoming cybersecurity lab activities

**Program:** Network Walks Cybersecurity Internship  
**Task:** Week 1 – VirtualBox and Kali Linux Lab Setup



<img width="1917" height="1040" alt="Screenshot 2026-10-28 132707" src="https://github.com/user-attachments/assets/b6c5a3dd-e99c-44fb-8a9e-d07b2bdb598d" />

kali-linux-lab-setup.png.

