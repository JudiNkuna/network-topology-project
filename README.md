# network-topology-project
Networks Project-Designing functional topologies (Star,Extended-star,Ring,Mesh,Bus and Hybrid)
## Project Overview
This project demonstrates the design, simulation, and configuration of various network topologies using Cisco Packet Tracer. The project includes five core topologies and one hybrid topology with dual-stack IPv4/IPv6 configuration.

**Student Name:** RJ Nkuna 
**Student ID:** 31978150

 Implemented Topologies
1. BusTopology
File: bus-topology.pkt
Description:
Linear network architecture where all devices share a single communication backbone.

Key Features:

Single backbone cable

Terminators at both ends

Simple cost-effective design

6.Hybrid Topology
-2X routers
-6x Switches
-12x PC's
-3x Servers
-copper straight cable
VLANS 10: Computers
VLAN30: Servers
##Topology Characteristics
Mesh Component:
Implementation: Dual routers with interconnected links
Redundancy: Multiple paths between routers and distribution switches
Benefit: High availability and fault tolerance

Star Compon:ent
Implementation: Access switches connecting end devices to distribution switches
Devices: PCs and servers connect to access switches in star formation
Benefit: Easy troubleshooting and centralized management

Bus Component:
Implementation: Distribution switches connected via trunk link
Data Flow: Shared backbone between distribution layers
Benefit: Simplified inter-switch communication

Ring Component:
Implementation: Spanning Tree Protocol creates logical ring for redundancy
Loop Prevention: STP prevents broadcast storms
Benefit: Automatic failover and path redundancy


