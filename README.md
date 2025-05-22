# 🌐 Project Funkytown Network & System Project

A university networking project simulating the complete IP addressing and infrastructure setup for the digital development of Funkytown. The goal is to plan and design a scalable, segmented, and efficient network that supports companies and datacenters across the city.

---

## 📋 Project Overview

The municipality of **Funkytown** supports digital infrastructure growth. The company **eXia** took the opportunity to build and manage a connected network infrastructure, interconnecting multiple enterprise sites, a library, the datacenter **Digiplex**, and integrating IPv6 tunneling.

---

## 🧱 Structure

The project includes:

- IP addressing plans (IPv4 / IPv6)
- VLSM/CIDR-based segmentation
- Interconnection between enterprise networks and the ISP DSLAM
- IPv6-over-IPv4 tunneling for dual-stack connectivity
- VLANs across multiple organizations and a datacenter
- NAT and network management strategies

---

## 🗂 Deliverables

- **📄 Addressing Plan**: Private and public IP allocation for all sites using VLSM
- **📡 VLAN Setup**: Logical separation across departments and management networks
- **🛰️ ISP Topology**: Mesh network including Google and the ISP DSLAM
- **🔁 IPv6 Tunnel**: From eXia to Digiplex using 6in4 tunneling
- **🧠 Definitions & Concepts**: CIDR, NAT, VLAN, Broadcast, Subnetting, etc.

---

## 🗺️ Key Components

### 🌐 IPv4 Addressing

- Used VLSM to allocate:
  - **/28** for small enterprise segments
  - **/25, /26, /27** for larger VLANs
  - Reserved private address ranges based on RFC1918

### 🌍 IPv6 Implementation

- **eXia**: `2001:db8:2000::/64`
- **Datacenter**: `2001:db8:1000::/64`
- IPv6-over-IPv4 tunnel established for routing across non-native IPv6 routers

### 🧮 Tools & Planning

- All address assignments and topology validated with **Packet Tracer**
- Network configuration designed to support:
  - Scalability
  - Efficient routing
  - Centralized management via Meraki server
