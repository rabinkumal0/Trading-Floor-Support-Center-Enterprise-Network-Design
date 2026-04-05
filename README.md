# Trading-Floor-Support-Center-Enterprise-Network-Documentation
📡 Enterprise Network Design – Trading Floor Support Center
📖 Overview

This project demonstrates the design and implementation of a scalable and redundant enterprise network for a 3-floor organization with 600 users using Cisco Packet Tracer.

🏗️ Network Architecture
3-Tier Design: Core, Distribution, Access
Dual core routers for ISP connectivity
Multilayer switches for inter-VLAN routing
Access switches for department-level connectivity


🧩 VLANs & Departments
VLAN 10 – Sales & Marketing
VLAN 20 – HR & Logistics
VLAN 30 – Finance & Accounts
VLAN 40 – Admin & PR
VLAN 50 – ICT
VLAN 60 – Server Room


⚙️ Technologies Used
VLANs & Trunking
Inter-VLAN Routing (SVI)
OSPF (Dynamic Routing)
HSRP (Gateway Redundancy)
DHCP (IP Addressing)
NAT/PAT (Internet Access)
SSH (Secure Remote Access)
Port Security
Wireless Networking (WPA2)


🔁 Key Features
Redundant network design (dual routers & links)
High availability using HSRP
Automated IP assignment via DHCP
Secure remote device management using SSH
Internet access with NAT/PAT
Department-wise network segmentation using VLANs


🧪 Verification
Inter-VLAN communication successful
OSPF neighbors established
HSRP failover tested
DHCP working across all VLANs
Internet connectivity verified
SSH access tested


🛠️ Tools
Cisco Packet Tracer


📂 Files Included
Network topology screenshots
Packet Tracer (.pkt) file
Project documentation (PDF)
