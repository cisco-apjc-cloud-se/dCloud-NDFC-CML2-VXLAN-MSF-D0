# dCloud-NDFC-CML2-VXLAN-MSF-D0

dCloud Custom Demo for NDFC/CML2 
Pre-built VXLAN Multi-Site Fabric Day 0
- 2 DC sites built using Nexus 9300v
  - DC1 - 4 Leaves, 2 Spines, 2 Anycast BGWs, 4 Ubuntu hosts
  - DC2 - 2 vPC BGWs, 2 Ubuntu hosts
- Ubuntu hosts are connected using LACP port-channels
- WAN (N9Kv) router for VRF-lite peering
- Fabrics are pre-configured with DHCP enabled for POAP but NO SWITCHES have been claimed

![Alt text](image.png)