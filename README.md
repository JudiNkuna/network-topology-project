# network-topology-project
Networks Project-Designing functional topologies (Star,Extended-star,Ring,Mesh,Bus and Hybrid)
## Project Overview
This project demonstrates the design, simulation, and configuration of various network topologies using Cisco Packet Tracer. The project includes five core topologies and one hybrid topology with dual-stack IPv4/IPv6 configuration.

**Student Name:** RJ Nkuna 
**Student ID:** 31978150

 Implemented Topologies
1. Bus Topology
File: BusTopology.pkt

Description:
Linear network architecture where all devices share a single communication backbone.

Key Features:

Single backbone cable

Terminators at both ends

Simple cost-effective design

2. Mesh Topology
File: MeshTopology1.pkt

Description:
Fully interconnected network providing redundant paths and high reliability.

Key Features:

Point-to-point connections between all devices

Maximum redundancy

High cabling complexity

3. Ring Topology
File: RingTopology1.pkt

Description:
Circular network where each device connects to exactly two neighbors.

Key Features:

Unidirectional or bidirectional data flow

Token passing mechanism

Deterministic performance

4. Star Topology
File: StarTopology.pkt

Description:
Centralized network with all devices connected to a central hub/switch.

Key Features:

Centralized management

Single point of failure (central device)

Easy to expand

5. Extended Star Topology
File: ExtendedStar1.pkt

Description:
Hierarchical star topology with multiple layers of central devices.

Key Features:

Scalable hierarchical design

Multiple central points

Enterprise-level architecture

6. Hybrid Topology
File:  HybridTopology.pkt

 Description: A combination of two or more topologies.
 
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


