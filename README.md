# VLAN Network Topology – Packet Tracer Lab

## 📘 Overview
This project simulates a VLAN-based network topology using Cisco Packet Tracer. It demonstrates network segmentation, trunking, and inter-VLAN routing across multiple devices.

## 🖥️ Topology Summary
- **Router**: 2901 MERCY WANJUGU
- **Switches**: 2 Layer 2 switches
- **End Devices**: 6 PCs, 6 Laptops, 6 Servers
- **Connections**: 
  - Router Gig0/0 ↔ Switch A
  - Router Gig0/1 ↔ Switch B
  - End devices connected via Fa0/x ports

## 🧠 VLAN Configuration
| VLAN | Purpose        | Devices on Switch A | Devices on Switch B |
|------|----------------|---------------------|---------------------|
| 10   | Staff PCs      | PC0, PC1            | PC2, PC3            |
| 20   | Laptops        | Laptop0, Laptop1    | Laptop2, Laptop3    |
| 30   | Servers        | Server0, Server1    | Server2, Server3    |

## 🌐 IP Addressing Plan
| VLAN | Subnet         | Gateway IP       |
|------|----------------|------------------|
| 10   | 192.168.10.0/24 | 192.168.10.1     |
| 20   | 192.168.20.0/24 | 192.168.20.1     |
| 30   | 192.168.30.0/24 | 192.168.30.1     |

## 🔧 Configuration Highlights
- VLANs created and assigned to switch ports
- Trunk links configured between switches and router
- Router-on-a-stick setup for inter-VLAN routing
- Ping tests performed to verify connectivity

## 📸 Screenshots
Include labeled topology diagrams and ping results here.

## 👩‍💻 Author
**Mercy Wanjugu**  
Software Engineering Student @ USIU-A  
GitHub: [@mercywanjugu](https://github.com/mercywanjugu)

