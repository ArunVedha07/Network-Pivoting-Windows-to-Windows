# Pivoting and Lateral Movement using SOCKS Proxy

## Overview
This repository documents a network pivoting and lateral movement exercise conducted using the Metasploit Framework and a SOCKS proxy. The assessment demonstrates how an initially compromised system can be leveraged to access and exploit additional systems within an internal network using proxy-based scanning and exploitation techniques, all within a controlled lab environment.

## Summary of Actions

- Gained initial access to the first system and established a Meterpreter session
- Configured internal routing using Metasploit’s autoroute module
- Deployed a SOCKS proxy to enable external terminal access to the internal network
- Performed internal network scanning using proxychains and Nmap
- Identified an exposed SMB service on a secondary system
- Successfully exploited the second system using the MS17-010 (EternalBlue) vulnerability

---

## Repository Structure

- /report — Pivoting and lateral movement assessment report
- /screenshots — Evidence of pivot setup, scanning, and exploitation
- /notes — Commands and configuration details used during the exercise

---

## Tools & Technologies

- Kali Linux
- Windows systems (primary and cloned targets)
- Metasploit Framework
- SOCKS proxy
- Proxychains
- Nmap

---
