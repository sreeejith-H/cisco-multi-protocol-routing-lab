# Cisco Multi-Protocol Routing Lab
### BGP • OSPF • EIGRP • Route Redistribution • Layer-3 Switching

A hands-on enterprise networking laboratory implemented using **physical Cisco networking equipment**. This project demonstrates the configuration, verification, troubleshooting, and integration of multiple dynamic routing protocols across different routing domains.

---

## 📌 Project Overview

This project simulates a multi-protocol enterprise network in which different routing domains coexist and exchange routing information through a controlled routing boundary.

The laboratory was built using physical:

- **Cisco 1841 Integrated Services Routers**
- **Cisco Catalyst C9200L-24T-4X Multilayer Switches**

The network was configured and verified through the **Cisco IOS CLI**.

The primary objective was to understand how different routing protocols operate independently and how routes can be exchanged between them using **route redistribution**.

---

## 🎯 Project Objectives

The main objectives of this lab were to:

- Configure and verify BGP
- Configure and verify OSPF
- Configure and verify EIGRP
- Establish routing protocol adjacencies
- Configure Layer-3 switching
- Configure routed interfaces
- Implement route redistribution
- Analyze routing tables
- Troubleshoot routing and connectivity problems
- Perform end-to-end connectivity testing
- Gain hands-on experience with physical Cisco equipment

---

## 🏗️ Network Architecture

The topology consists of multiple routing domains connected through Layer-3 devices.

### Routing Domains

| Routing Domain | Protocol | Purpose |
|---|---|---|
| BGP | BGP AS 1980 | External / edge routing simulation |
| Enterprise Internal | OSPF | Internal enterprise routing |
| Legacy / Separate Domain | EIGRP AS 100 | Separate Cisco routing domain |
| Redistribution Boundary | Multi-protocol L3 device | Route exchange between domains |

