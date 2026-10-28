Global Multi-Site Enterprise Routing & Subnetting Architecture

Overview

Welcome to the repository for my first hands-on network engineering project! As part of my 90-day deep-dive sprint into high-competency networking, this project simulates a multi-site enterprise topology connecting endpoints across different geographical regions (New York and Tokyo). It focuses on rigorous subnetting design, local IP addressing, and live router configuration from the command line.

Project Architecture & Topology

Sites: 2 Primary Remote Locations (New York & Tokyo)

Devices: Enterprise-grade Cisco Routers and End-User Workstations / Computers

Subnetting Strategy: Designed and implemented 6 distinct subnets to segment traffic, optimize broadcast domains, and mirror real-world multi-site enterprise environments.

Step-by-Step Implementation

Topology Design & Deployment:

Deployed virtual endpoints representing remote offices in New York and Tokyo.

Interconnected endpoints using appropriate physical and logical links to simulate wide-area connectivity.

IP Addressing & Subnetting:

Calculated and allocated a structured IP addressing scheme.

Successfully divided the network into 6 unique subnets to ensure proper isolation and efficient address management.

Assigned static local IP addresses and default gateways to all endpoint computers across the sites.

Live Router Configuration:

Accessed the Cisco CLI on site routers via console/direct configuration mode.

Configured interface IP addresses, enabled routing ports, and established gateway parameters.

Verified connectivity, routing tables, and inter-subnet communication through diagnostic commands (e.g., ping, show ip route).

Tools & Technologies Used

Simulation Tool: Cisco Packet Tracer

Operating System Foundation: Linux environments for script automation and documentation

Core Protocols & Concepts: IPv4 Addressing, Subnetting (VLSM/CIDR), Inter-VLAN/Inter-subnet routing, CLI Router Management.

Why This Project?

This lab moves beyond theoretical study, demonstrating practical execution of core routing and networking fundamentals required for enterprise and ISP environments. It serves as foundational evidence of my hands-on capability in network deployment and troubleshooting.

Created as part of the 90-day network engineering sprint.
