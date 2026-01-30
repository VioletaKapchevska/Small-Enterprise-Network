# Small-Enterprise-Network

This project is a simulation of a small office network with 4 departments: HR, Sales, IT and Guest WI-FI. 
It includes:
- Vlan configuration;
- DHCP;
- NAT;
- OSPF;
- ACL rules;
Network topology:
Router1(R1) - Inter-VLAN routing, NAT to access the internet, default gateway for all VLANs;
Router2(R2) - Optional brach router with OSPF configuration;
Switch1(S1) and Switch2(S2) - VLAN separation, trunk ports connected to router1(R1);
Print Server connected to VLAN 10(HR), accessible only by HR and Sales;
PCs - located in different VLANs;
Wireless AP - connected to Guest VLAN , internet-only access;

<img width="898" height="700" alt="network-topology" src="https://github.com/user-attachments/assets/9fe1b898-3011-4690-ba4f-edb9ded60984" />
