# projet-de-r-seau-bancaire

Radeon Company Ltd. – Network Design and Implementation Project
Radeon Company Ltd. is a US-owned company that deals with Banking and Insurance. The company is intending to expand its services across the African continent having the first branch to be located in Nairobi, Kenya. The company has secured a four-story building to operate within the Kenyan capital city. Therefore, the company would like to allow sourcing the knowledge from a group of final-year students from the local university to design and implement their company network. Assume you are among the students to take over this role, carefully read down the requirements then model the design and implement the network based on the company's needs. Each floor has departments as provided in the table below:

First Floor:
1. Management – 20 PCs – 4 Printers
2. Research – 20 PCs – 4 Printers
3. Human Resource – 20 PCs – 4 Printers

Second Floor:
1. Marketing – 20 PCs – 4 Printers
2. Accounting – 20 PCs – 4 Printers
3. Finance – 20 PCs – 4 Printers

Third Floor:
1. Logistics and Store – 20 PCs – 4 Printers
2. Customer Care – 20 PCs – 4 Printers
3. Guest Area – 40 PCs – 2 Printers

Fourth Floor:
1. Administration – 20 PCs – 2 Printers
2. ICT – 20 PCs – 2 Printers
3. Server Room – 2 Admin PCs – 3 Servers (DHCP, HTTP, and Email)

Requirements:
- Use a software modeling tool to visualize the network topology (Use Hierarchical Network Design).
- Software Modelling Tools: MS Visio, Visual Paradigm, or Draw.io.
- Use Cisco Packet Tracer or GNS3 for simulation.
- Use OSPF as the routing protocol.
- Each department must have a wireless network.
- Departments (except server room) will support ~60 wired and wireless users.
- Host devices must obtain IPv4 addresses automatically.
- All departments must communicate with each other.
- Create HTTP and Email servers.
- All devices should obtain IPs from DHCP server in server room.
- Configure SSH on all routers.
- Configure hostnames, passwords, banners, disable domain lookup, and encrypt passwords.
- Each department should be in a different VLAN and subnet (e.g., VLAN 10, 20, 30...).
- Use 192.168.10.0 as the base IP. Perform subnetting and determine subnet mask, usable IP range, and broadcast addresses.
- Configure all end devices with correct IP settings.
- Enable port-security with sticky MAC and violation mode as shutdown.
- Test and verify network communication.

Technologies Implemented:
1. Network topology using Cisco Packet Tracer
2. Hierarchical Network Design
3. Correct cabling
4. Basic device settings
5. VLANs and port assignments
6. Subnetting and IP addressing
7. Inter-VLAN routing (SVI)
8. DHCP Server configuration
9. SSH configuration
10. OSPF configuration
11. Port-security configuration
12. Wireless configuration
13. Host configurations
14. Network testing and verification
