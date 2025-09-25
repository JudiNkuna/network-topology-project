# network-topology-project
Networks Project-Designing functional topologies (Star,Ring,Mesh,Bus and Hybrid)
## Project Overview
This project demonstrates the design, simulation, and configuration of various network topologies using Cisco Packet Tracer. The project includes five core topologies and one hybrid topology with dual-stack IPv4/IPv6 configuration.

**Student Name:** RJ Nkuna 
**Student ID:** 31978150

1.Bus Topology

Design: Linear network with central backbone cable

Devices:

4x PC-PT

1x Hub-PT

Copperstraight through cable

IP Addressing:

Device	IPv4 Address	IPv6 Address
PC0	192.168.1.2/24	2001:db8:1::0/64
PC1	192.168.1.3/24	2001:db8:1::1/64
PC2	192.168.1.4/24	2001:db8:1::2/64
PC3	192.168.1.5/24	2001:db8:1::3/64

### Configuration Steps
1. Physical connections completed
2. IP addresses assigned
3. Connectivity tested
Screenshot and Verification:
<img width="1366" height="768" alt="Screenshot (64)" src="https://github.com/user-attachments/assets/2e784326-fd9f-466f-b75b-d2494c08e94b" />

<img width="1366" height="768" alt="Screenshot (74)" src="https://github.com/user-attachments/assets/5c099c09-95fd-442c-9228-d0d01ab19d49" />



2.Mesh Topology

Devices
4x PC-PT
4x Switch-PT
Copper cross  over cable

IP Addressing:

Device	IPv4 Address	IPv6 Address
PC0	192.168.1.10/24	2001:DB8:1::10/64
PC1	192.168.1.11/24	2001:DB8:1::11/64
PC2	192.168.1.12/24	2001:DB8:1::12/64
PC3	192.168.1.12/24	2001:DB8:1::13/64

### Configuration Steps
1. Physical connections completed
2. IP addresses assigned
3. Connectivity tested

screenshot and verification:
<img width="1366" height="768" alt="Screenshot (67)" src="https://github.com/user-attachments/assets/4c095e89-05b2-4c67-bd10-48129e5228ac" />

<img width="1366" height="768" alt="Screenshot (70)" src="https://github.com/user-attachments/assets/2f2d480c-d0fc-4640-b470-8dc457efce1a" />

3.Star Topology

Devices

4x PC-PT
1x Switch-PT
copper straight through

IP Addressing:
Device	IPv4 Address	IPv6 Address
PC0	192.168.1.2/24	2001:DB8:1::2/64
PC1	192.168.1.3/24	2001:DB8:1::3/64
PC2	192.168.1.4/24	2001:DB8:1::4/64
PC3	192.168.1.5/24	2001:DB8:1::5/64

### Configuration Steps
1. Physical connections completed
2. IP addresses assigned
3. Connectivity tested

screenshot and verification:
<img width="1366" height="768" alt="Screenshot (59)" src="https://github.com/user-attachments/assets/4347244b-bfb7-41f0-8fc8-8d9c8ed387be" />

<img width="1366" height="768" alt="Screenshot (60)" src="https://github.com/user-attachments/assets/f5ba560d-2f6c-46c2-a070-396d342b8245" />


4.Ring Topology

Devices 
7x PC-PT
7x Switch
copper straoght through
copper cross over

Network Behaviour:
-Logical Topology: STP(spanning tree protocol)
-Physical Topology:7 switches in a ring configuration
STP denoted by the orange dot,prevents network loops and provises

IP Addressing:
Device	IPv4 Address	IPv6 Address
PC0	192.168.1.10/24	2001:DB8:1::0/64
PC1	192.168.1.11/24	2001:DB8:1::1/64
PC2	192.168.1.12/24	2001:DB8:1::2/64
PC3	192.168.1.13/24	2001:DB8:1::3/64
PC0	192.168.1.14/24	2001:DB8:1::4/64
PC1	192.168.1.15/24	2001:DB8:1::5/64
PC2	192.168.1.16/24	2001:DB8:1::6/64
### Configuration Steps
1. Physical connections completed
2. IP addresses assigned
3. Connectivity tested

screenshots and verification:
<img width="1366" height="768" alt="Screenshot (76)" src="https://github.com/user-attachments/assets/cba933db-5e59-4b1c-9af1-308404870b4b" />

<img width="1366" height="768" alt="Screenshot (77)" src="https://github.com/user-attachments/assets/3ca19058-a8dd-4346-a960-fd2fd3dfba9f" />

5.Extended Star Topology
Devices


screenshot and Verification:
<img width="1366" height="768" alt="Screenshot (71)" src="https://github.com/user-attachments/assets/30273f98-ae4e-4549-aeae-5ae90bf14928" />
<img width="1366" height="768" alt="Screenshot (72)" src="https://github.com/user-attachments/assets/9b04833f-98e3-441f-beb8-8c2d5b5adc92" />

