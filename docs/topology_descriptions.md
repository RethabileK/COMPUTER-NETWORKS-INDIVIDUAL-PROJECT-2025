# Network Topology Descriptions

## 1. Introduction
This document provides an overview of the network topologies designed and simulated in Cisco Packet Tracer. Each topology demonstrates different networking concepts including IPv4 and IPv6 addressing and the hypbrid topology represent VLAN segmentation, DHCP, DNS, HTTP server integration, basic security, while the wireless mesh network represent wireless connectivity.

---

## 2. Topology 1 – Bus Topology
**Description:**  
The bus topology consists of a three connected switches, each connected to 2 PCs . All communication passes through the switches representing a single shared backbone. This shows how collisions happen in legacy networks.
This setup demonstrates efficient LAN design and device management.

**Devices Used:**
- 3 × Cisco 2960-24TT Switches 
- 6 × PCs  

**Key Configurations:**
- IPv4 Network : 192.168.1.0/29  
- IPv6 Network : 2001:DB8:ACAD:1::/125
- Each PC configured with static IP.

---

## 3. Topology 2 – Mesh Topology
**Description:**  
All the PCs are interconnected with each other. I used switches to show the connection between the PCs.

**Devices Used:**
- 6 × Cisco 2960-24TT Switches
- 6 × PCs  

**Key Configurations:**
- IPv4 Network : 192.168.1.0/29  
- IPv6 Network : 2001:DB8:ACAD:1::/125
- Each PC configured with static IP.

---

## 4. Topology 3 – Star Topology
**Description:**  
The star topology consists of a central switch connecting multiple PCs, all  communication passes through the switch. This topology shows efficient LAN design and device management.

**Devices Used:**
- 1 × Cisco 2960-24TT Switches 
- 6 × PCs   

**Key Configurations:**
- IPv4 Network : 192.168.1.0/29  
- IPv6 Network : 2001:DB8:ACAD:1::/125
- Each PC configured with static IP.

---

## 5. Topology 4 – Ring Topology
**Description:**  
The PCs in ring topology are connected in a circular path using switches. Data moves in one direction.

**Devices Used:**
- 6 × Cisco 2960-24TT Switches
- 6 × PCs

**Key Configurations:**
- IPv4 Network : 192.168.1.0/29  
- IPv6 Network : 2001:DB8:ACAD:1::/125
- Each PC configured with static IP.

---

## 6. Topology 5 – Extended Star topology
**Description:**  
The extended star topology is a hierarchical version of the star topology where multiple switches are connected to the central switch and they connect to several PCs.

**Devices Used:**
- 5 × Cisco 2960-24TT Switches
- 12 × PCs

**Key Configurations:**
- IPv4 Network : 192.168.1.0/28  
- IPv6 Network : 2001:DB8:ACAD:1::/124
- Each PC configured with static IP.

---
## 7. Topology 6 – Hybrid topology
**Description:**  
This topology combines the extended star and the ring topology using VLAN segmentation, a server and basic security.

**Devices Used:**
- 7 × Cisco 2960-24TT Switches
- 10 × PCs
- 1 × Cisco 3560-24PS Multilayer switch
- 1 × Server 

**Key Configurations:** 
- VLAN10 : 192.168.10.0/29 and 2001:DB8:10::0/64
- VLAN20 : 192.168.20.0/29 and 2001:DB8:20::0/64
- VLAN30 : 192.168.30.0/29 and 2001:DB8:30::0/64
- VLAN40 : 192.168.40.0/29 and 2001:DB8:40::0/64
- VLAN99 : 192.168.99.1/29 and 2001:DB8:99::0/64
- Each PC configured with static IP.
- Multilayer Switch security( with a password)

---
## 8. Topology 7 – Wireless Mesh topology
**Description:**  
This topology shows a wireless mesh network 3 Root Access Points that have diffent SSID and WPA2-PSK Pass Phrase and end devices connected wirelessly through any the Access Points. There was no device on Cisco Packet Tracer that i could find to represent the true wireless mesh since the devices cannot communicate without connecting the APs to the switch.

**Devices Used:**
- 1 × Cisco 2960-24TT Switches
- 2 × Tablets
- 2 × Laptops
- 3 × Smartphones
- 3 × Access Points
- 1 × Server
- 1 × 5505 Firewall
- 1 × Cloud
- 1 × Cell Tower

**Key Configurations:** 
- SSID: LAN 1, LAN 2, LAN 3  
- Security: WPA2-PSK (Passphrase: Rethabile1, Rethabile2, Rethabile 3)
- IPv4 Network : 192.168.1.0/28  
- IPv6 Network : 2001:DB8:1::0/124

---

## 8. Topology .pkt
The document for the topologies can be found under the topologies folder.

