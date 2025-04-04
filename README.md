# Enterprise Branch Network – Packet Tracer Project

## 👨‍💻 Created by: Shahin Akbari

## 🌐 Network Overview
This project simulates a multi-branch enterprise network using Cisco Packet Tracer. It includes:
- Multiple VLANs across 4 networks (192.168.10.0/24 to 192.168.40.0/24)
- OSPF Multi-Area
- NAT to Internet
- DHCP Server
- Syslog Logging
- SNMP Monitoring
- NTP Time Synchronization

## 📦 Topology Highlights
- Core, Branch, and Layer 3 Switches
- Internet Router with NAT and Public IP
- Central Syslog/NTP/SNMP server in VLAN10

## ⚙️ Technologies Used
- Routing: OSPF (multi-area)
- NAT: PAT (overload) on the edge router
- Syslog: Logs sent to `192.168.10.250`
- NTP: All devices synced to central server
- SNMP: Enabled on all routers/switches (community: `public`)

## 📁 Files Included
- `Enterprise_Branch_Network_2025.pkt` – Cisco Packet Tracer file
- `README.md` – This documentation

## 📬 Contact
Created by Shahin Akbari  
Email: akbarishahin@gmail.com  
