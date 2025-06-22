# Networking-Lab-Project
A collection of Cisco Packet Tracer labs covering VLANs, OSPF, static routing, DHCP, ACLs, and more. Built as part of my networking and cybersecurity studies to demonstrate practical CCNA-level skills.


# 🚀 Comprehensive Cisco Networking Portfolio – VLANs, OSPF, ACLs, NAT, DHCP, PPP/CHAP

This repository showcases a complete, scenario-based enterprise networking portfolio built using Cisco Packet Tracer. These labs were designed and completed as part of my hands-on learning in network engineering and cybersecurity. Each scenario builds upon the previous, covering a progressive set of Cisco networking technologies.

---

## 📂 Scenario Summary

### 🧩 Scenario 4 – Internal Network with OSPF and ACLs
- Deployed a multi-router network using **OSPF** as the routing protocol
- Configured VLANs across Latur and Udgir campuses
- Implemented **inter-VLAN routing**, ACLs to control traffic between VLANs, and port security
- Default route advertised from the gateway (Barshi)
- Configured OSPF with wildcard masks, loopback interfaces, and passive-interface command
- Verified end-to-end connectivity, ACL rules, and port-level restrictions

---

### 🧩 Scenario 5-P – Core Routing and ACL Enforcement
- Built a 3-router network with OSPF routing and static route to ISP
- VLANXXX, VLANYYY, VLANZZZ configured with inter-VLAN routing
- Applied **complex ACLs** to enforce HTTP-only access, restrict ICMP and Telnet between VLANs
- Used sticky MACs and port security on access interfaces
- Configured Telnet with restricted access from authorized VLANs only

---

### 🧩 Scenario 5-C – NAT Implementation and Subnet Translation
- Implemented **NAT overloading** using three sub-pools for public IPs
- Devices in VLANs routed through NAT to simulate real-world ISP interaction
- Traffic translation verified using `show ip nat translations`
- Ensured internal IP privacy and controlled public exposure

---

### 🧩 Scenario 5-D – DHCP Automation
- Configured **centralized DHCP** from core router
- Used DHCP helper addresses to forward client requests across VLANs
- Configured pools for each VLAN and reserved IPs using exclusions
- Fully automated IP address assignment

---

### 🧩 Scenario 6-P – Enterprise Design with NAT, DHCP, ACLs & OSPF
- Rebuilt previous topology to match a real-world enterprise layout
- Integrated **OSPF**, **NAT**, **DHCP**, and **ACLs**
- Ensured redundancy and scalability
- Refined access control between VLANs, allowing asymmetric ping rules
- Demonstrated VLAN-level NAT mapping

---

### 🧩 Scenario 6-C – PPP and CHAP Authentication
- Enabled **PPP encapsulation** on serial link to ISP
- Configured **CHAP authentication** for secure router-to-ISP communication
- Validated successful handshake using debug commands
- Hardened WAN-facing interfaces with authentication and encapsulation

---

## 🧪 Skills Demonstrated
- Subnetting, VLANs, and Inter-VLAN Routing  
- OSPF Dynamic Routing (single-area)  
- NAT (PAT using pools) and public/private IP assignment  
- Centralized DHCP with helper-address  
- ACL enforcement (Telnet, ICMP, HTTP filtering)  
- Port Security using sticky MAC, protect mode  
- PPP encapsulation with CHAP authentication  
- Use of Cisco IOS troubleshooting and verification commands

---

## 🌐 Custom Scenario 7 – "Enterprise + Cloud-Edge Secure Network"

### ✨ Overview
This original scenario builds on all previous scenarios and simulates a hybrid enterprise setup with a small cloud-edge segment for future expansion.

### 🔧 Configuration Highlights
- 4 routers (3 internal + 1 ISP/cloud edge)
- Two switches across departments: R&D, Finance, Public
- VL
