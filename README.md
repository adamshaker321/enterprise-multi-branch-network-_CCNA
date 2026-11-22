# Enterprise Multi-Branch Network Design & Implementation
<img width="1919" height="1017" alt="network" src="https://github.com/user-attachments/assets/eeeb21a3-9a24-43b6-afcd-1e93eae298c3" />

## Project Overview

This project demonstrates the design and implementation of a multi-branch enterprise network using Cisco Packet Tracer.

The network connects multiple departments across different branches through an ISP infrastructure, providing structured network segmentation, dynamic routing, centralized network services, and controlled communication between network segments.

## Network Architecture

The project includes:

- Multiple enterprise branches.
- Department-based VLAN segmentation:
  - VLAN 10 – Sales
  - VLAN 20 – HR
  - VLAN 30 – Accounting
  - VLAN 40 – IT
- Layer 3 switching for Inter-VLAN Routing.
- Dedicated server infrastructure (VLAN 50).
- WAN connectivity through an ISP network.

## Technologies Implemented

| Technology | Implementation |
|---|---|
| VLANs | Departmental Network Segmentation |
| Inter-VLAN Routing | Layer 3 Switches |
| OSPF | Dynamic Routing |
| Trunking | 802.1Q |
| DHCP | Automatic IP Allocation |
| DNS | Domain Name Resolution |
| HTTP | Web Server |
| ACLs | Traffic Filtering |
| VTY | Remote Device Management |
| Redundancy | Backup Network Links |
| WAN / ISP | Multi-Branch Connectivity |

## Network Topology

See the screenshots directory for the complete network topology and configuration details.

## Connectivity Testing

The network was tested to verify:

- Communication between different VLANs.
- Inter-branch connectivity.
- OSPF routing operation.
- DHCP address allocation.
- DNS resolution and HTTP accessibility.
- ACL traffic filtering.
- Network connectivity and redundancy.

## Tools Used

- Cisco Packet Tracer
- Cisco IOS CLI

## Project File

The complete Cisco Packet Tracer project file (.pkt) is included in this repository.

---

**Project Type:** Practical Networking Project  
**Focus:** Enterprise Networking | Network Infrastructure | CCNA 200-301
