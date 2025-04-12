# Cybersecurity_Home_Lab_v1
Home Cybersecurity Lab built in Cisco Packet Tracer featuring RIP routing, DHCP, and ASA firewall for internal/external network segmentation.

## Summary

This project allowed me to test and demonstrate my networking skills using Cisco Packet Tracer. I independently selected and configured the equipment, connected all devices, and built a fully functional internal and external network separated by a Cisco ASA firewall. 

Key features include:
- Dynamic routing with RIP v2
- DHCP services on both networks
- Successful end-to-end connectivity testing
- Network segmentation for security using firewall zones

This lab simulates the foundation of a real-world secure enterprise environment and serves as a platform for further cybersecurity exploration, including ACLs, DMZs, and attack simulation.

## Getting Started

To run this lab:
1. Download the `.pkt` file from this repo
2. Open it in Cisco Packet Tracer
3. Power on the devices (especially ASA, which takes longer to boot)
4. Use the Command Prompt on the PCs to test connectivity


## Topology Diagram:
[ External PC ]──┐
                 │
              [ Router ]
                 │
          [ ASA Firewall ]
                 │
             [ Switch ]
              /      \
     [ Internal PC ] [ Server ]

## Tools:
Cisco Packet Tracer
Cisco ISR4321 Router
Cisco ASA 5506 Firewall
Cisco 2960 Switch
PC-PT Hosts
Server-PT

