# 🏥 Hospital Network Design – Cisco Packet Tracer Project

This project showcases a complete hospital network setup designed and configured using **Cisco Packet Tracer**, simulating real-world enterprise-level infrastructure tailored for medical environments.

## 📌 Objective

To build a secure, scalable, and efficient network for a hospital environment with segmented VLANs, routing protocols, DHCP services, secure remote access, and internet connectivity using NAT and ACLs.

---

## 🛠️ Tools & Technologies

- Cisco Packet Tracer
- Cisco Routers and Layer 3 Switches
- CLI Configuration (no GUI shortcuts)
- Protocols: OSPF, DHCP, NAT, ACL, IPsec VPN
- Security: SSH, Port Security

---

## 🧠 Key Features

- ✅ **VLANs** for different departments (ICU, OPD, Labs, Admin, Pharmacy, etc.)
- ✅ **Inter-VLAN routing** via Layer 3 switches
- ✅ **OSPF** dynamic routing protocol across all routers
- ✅ **DHCP** configuration for IP auto-assignment per VLAN
- ✅ **NAT & ACL** to control internet access and secure internal resources
- ✅ **IPsec VPN** tunnel for secure remote access between branches or data centers
- ✅ **SSH** access to all core devices for secure remote administration
- ✅ **Port Security** enabled with sticky MAC & shutdown violation mode

---

## 🧪 Testing Done

- `Ping` and `Traceroute` across VLANs and between remote sites
- Verified DHCP lease assignment
- Access restriction using extended ACLs
- VPN tunnel functionality check with simulated secure communication

---

## 📂 Project Structure

```bash
📁 Hospital-Network
├── Hospital_Network.pkt         # Main Packet Tracer topology file
├── README.md                    # Project overview and documentation
└── configs/                     # (Optional) Folder with device configs
