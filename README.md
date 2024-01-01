# Network Design for Multi-Branch Organization

## Project Summary
This project involves designing and implementing a network for a company with one headquarters in Riyadh and two branches in Jeddah and Dammam. The aim is to enable effective communication and resource sharing across all locations with a focus on security, efficiency, and scalability.

## High-Level Organization Description
- **Headquarters (Riyadh)**: Comprises four departments (IT, HR, Finance, Sales) and a server room, each department equipped with PCs and printers.
- **Branches (Jeddah and Dammam)**: Each branch consists of a single department (Sales) with necessary computing resources.

## Network Features
- **VLAN Implementation**: Each department is assigned its own VLAN to segregate the network and improve security and performance.
- **Dynamic IP Addressing**: A DHCP server dynamically assigns IP addresses to devices, simplifying management and connectivity.
- **Multilayer Switching**: Interconnection of VLANs through a multilayer switch, allowing communication across different network segments.
- **Router Configuration**: Establishing connectivity between the headquarters and branches, ensuring seamless communication across locations.

## Devices Used
- **End Devices**: PCs and printers.
- **Intermediate Devices**: Routers, switches, and a multilayer switch.

## Configuration Steps
- **VLANs**: Set up and assign unique VLAN IDs and interfaces.
- **Routing**: Enable IP routing on the multilayer switch for inter-VLAN traffic.
- **VLAN Trunking**: Configure trunking to carry traffic from multiple VLANs between switches.
- **Access Ports**: Assign VLANs to access ports for end devices communication.
- **Router Connectivity**: Establish physical and logical connections between routers and the multilayer switch, employing Routing Information Protocol (RIP) for routing.

## Network Benefits
- **Effective Communication**: Ensures smooth and secure communication between different departments and branch locations.
- **Centralized Control**: Central management with the multilayer switch acting as a hub in the headquarters.
- **Scalability**: Easy to add or modify the network components as the organization grows.

## Conclusion
Our network design prioritizes security, efficiency, and ease of management while providing a scalable solution for the company's communication needs across its various departments and locations.

