# 🏥 Hospital Network Design in Cisco Packet Tracer

## 📌 Overview
This project demonstrates the design and implementation of a **realistic hospital network infrastructure** using Cisco Packet Tracer.

The network simulates a real-world healthcare environment including:
- Multiple departments
- Secure segmentation
- Wireless infrastructure
- VoIP communication
- Server and DMZ zones

---

## 🧠 Key Concepts
- VLAN segmentation
- Inter-VLAN routing
- OSPF routing protocol
- HSRP redundancy
- DHCP & IP planning
- Cisco ASA Firewall (DMZ)
- Wireless networking
- VoIP integration

---

# 🛠️ Network Design & Implementation Process

---

## 🔹 1. Network Topology Design

Initial layout of the hospital network showing hierarchical structure and device distribution.

<img width="1866" height="733" alt="1slika" src="https://github.com/user-attachments/assets/e8bb1aef-5072-483a-a185-e0f7167054d6" />

---

## 🔹 2. Full Network Architecture

Complete enterprise-level topology including:
- Core switches
- Access layer
- Firewall
- WAN and Cloud
- Server infrastructure

<img width="2017" height="1101" alt="Screenshot 2026-03-29 221243" src="https://github.com/user-attachments/assets/12d69939-e855-41e2-9076-5d62fcada1f2" />

---

## 🔹 3. Basic Device Configuration

Initial configuration applied to all devices:
- Hostnames
- Console passwords
- Enable password
- SSH setup
- Banner messages

<img width="1440" height="530" alt="3slika" src="https://github.com/user-attachments/assets/c959f748-2139-4d53-9032-aec04f95b2fd" />

---

## 🔹 4. VLAN Configuration & Trunking

Implementation of VLAN segmentation:
- VLAN 10 → LAN
- VLAN 50 → WLAN
- VLAN 99 → VoIP

Includes trunk ports and access port assignments.

<img width="1145" height="734" alt="4slika" src="https://github.com/user-attachments/assets/e0628031-e972-40c1-9c74-b539f1cd58e3" />

---

## 🔹 5. IP Addressing & Subnetting

Network planning including:
- Subnets
- Gateway addresses
- Broadcast ranges

<img width="1064" height="625" alt="5slika" src="https://github.com/user-attachments/assets/71c1eb4e-4f08-4b71-b145-4f5704e4fcb2" />

---

## 🔹 6. Server Configuration (Static IP)

Configuration of servers inside DMZ:
- Static IP assignment
- DNS configuration
- Default gateway setup

<img width="1145" height="586" alt="6slika" src="https://github.com/user-attachments/assets/b491db6a-8ff4-4de2-9282-55cf64c6cfec" />

---

## 🔹 7. DHCP Configuration

Dynamic IP assignment for clients:
- DHCP pools
- Gateway setup
- DNS integration

<img width="900" height="690" alt="7slika" src="https://github.com/user-attachments/assets/c9bd5654-a0e3-499f-b145-9a3bf3bae211" />

---

## 🔹 8. Wireless Network (WLAN)

Multiple wireless networks configured:
- Employee network
- Guest network
- Corporate network

<img width="898" height="269" alt="8slika" src="https://github.com/user-attachments/assets/6ddcb470-3b75-48a4-ab29-0b2b2ef30139" />

---

## 🔹 9. VoIP Configuration

IP Telephony setup enabling communication across departments.

<img width="896" height="733" alt="9slika" src="https://github.com/user-attachments/assets/97ea1659-acb0-41c6-abb1-6ade3203c4fb" />

---

## 🌐 Addressing Plan

| Network | Address Range |
|--------|--------------|
| WLAN   | 10.10.0.0/16 |
| LAN    | 192.168.0.0/20 |
| Voice  | 172.16.0.0/20 |
| DMZ    | 10.20.20.0/26 |
| Public | 197.200.100.0 |

---

## ⚙️ Technologies Used
- Cisco Packet Tracer
- VLANs & Trunking
- Layer 2 & Layer 3 Switching
- OSPF
- HSRP
- DHCP / DNS
- Cisco ASA Firewall
- VoIP
- Wireless LAN

---

## ▶️ How to Run
1. Open Cisco Packet Tracer
2. Load:
