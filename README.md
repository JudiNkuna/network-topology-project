# network-topology-project
Networks Project-Designing functional topologies (Star,Extended-star,Ring,Mesh,Bus and Hybrid)
## Project Overview
This project demonstrates the design, simulation, and configuration of various network topologies using Cisco Packet Tracer. The project includes five core topologies and one hybrid topology with dual-stack IPv4/IPv6 configuration.

**Student Name:** RJ Nkuna 
**Student ID:** 31978150

1.Bus Topology

Design: Linear network with central backbone cable

##Devices:

-4x PC-PT

-1x Hub-PT

-Copperstraight through cable

### Configuration Steps
1. Physical connections completed
2. IP addresses assigned
3. Connectivity tested


2.Mesh Topology

##Devices
-4x PC-PT
-4x Switch-PT
-Copper cross  over cable

### Configuration Steps
1. Physical connections completed
2. IP addresses assigned
3. Connectivity tested

3.Star Topology

Devices

-4x PC-PT
-1x Switch-PT
-copper straight through

### Configuration Steps
1. Physical connections completed
2. IP addresses assigned
3. Connectivity tested


4.Ring Topology

-Devices 
-7x PC-PT
-7x Switch
-copper straoght through
-copper cross over

Network Behaviour:
-Logical Topology: STP(spanning tree protocol)
-Physical Topology:7 switches in a ring configuration
STP denoted by the orange dot,prevents network loops and provises

### Configuration Steps
1. Physical connections completed
2. IP addresses assigned
3. Connectivity tested

5.Extended Star Topology
-Devices
-3x Switch
-6x PC-PT
-copper straight through

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


