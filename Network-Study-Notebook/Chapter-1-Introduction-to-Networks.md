# Chapter 1 – Introduction to Networks

**CompTIA Network+ (N10-009) – Personal Study Notes**  
Beast Mode Experiment 2026 – 3-week full focus on Network

## 1. What is a Network?
- Two or more connected devices that share resources (data, applications, printers).
- Hosts communicate using binary data (packets).

## 2. Local Area Network (LAN)
- Connects devices within a small geographic area (home, office, single building).
- High speed and low latency.

## Latency
- Round-trip time for a packet to travel from source to destination and back.
- Measured in milliseconds (ms).
- Low latency = fast and responsive network.
- High latency = performance problems.
- Example: `ping 8.8.8.8` → 15 ms (good) vs 250 ms (bad).

## Workgroup
- Group of devices in the same network segment.
- No central security or trust relationship.
- Each device manages its own users, passwords, and shared resources.
- Common in home/small office networks.
- Low security: manual authentication, easy lateral movement if compromised.

## Common Network Components

### Workstation
- High-performance computer for demanding tasks.
- Multiple CPUs, large RAM, and powerful GPU.
- Used by security analysts, developers, video editors, etc.
- Acts as a client in the network.

### CPU (Central Processing Unit)
- The brain of the computer. Executes instructions and calculations.
- Workstations often use multi-core CPUs.

### Server
- Powerful computer or software that provides specialized services to clients.
- Dedicated and more reliable than normal workstations.

### Common Server Types
- **File Server**: Stores and shares files and folders.
- **Mail Server**: Sends, receives, and stores emails (e.g. Gmail).
- **Print Server**: Manages print jobs for network printers.
- **Web Server**: Hosts websites and web applications.
- **Application Server**: Runs business applications.
- **Proxy Server**: Acts as intermediary for security and performance.
- **Fax / Telephony Server**: Handles fax or VoIP calls.

### Host
- Any device with an IP address that can communicate using TCP/IP.
- Broad term: workstations, servers, laptops, smartphones, printers, IoT devices, etc.

### TCP/IP
- Standard protocol suite of the Internet and most modern networks.
- **TCP** = reliable, ordered data delivery.
- **IP** = addressing and routing of packets.

## Network Types

### PAN (Personal Area Network)
- Smallest network. Connects personal devices in short range (Bluetooth, USB, Ethernet).

### CAN (Campus Area Network)
- Covers a university or corporate campus. Interconnects multiple LANs with Wi-Fi for roaming.

### MAN (Metropolitan Area Network)
- Covers a city or campus. Connects multiple buildings (“concentrated WAN”).

### WAN (Wide Area Network)
- Covers large geographic areas. Connects multiple LANs using routers. Slower and more expensive.

### Internet
- Largest distributed WAN. Connects millions of networks via routers.

### SAN (Storage Area Network)
- Dedicated high-speed network for storage only. Used in data centers (Fibre Channel / FCoE).

### SD-WAN (Software-Defined WAN)
- Modern flexible WAN. Manages multiple connections with software for real-time optimization.

### MPLS (Multi-Protocol Label Switching)
- Advanced routing for WANs. Provides prioritization, redundancy and flexibility.

## Network Architecture

### Peer-to-Peer (P2P)
- All devices are equal. Each can act as client and server.
- Low security. Only for small networks.

### Client-Server
- Dedicated server manages security and resources.
- Clients only request services. Server never used as workstation.
- High security and scalability.

## Physical Network Topologies

### Bus Topology
- All devices on a single cable. Outdated, single point of failure.

### Point-to-Point
- Direct link between two devices.

### Hub-and-Spoke (Star Topology)
- All devices connect to a central switch. Most common today.

### Mesh Topology
- Every device connects to every other. High redundancy, expensive.

### Spine-and-Leaf Topology
- Modern data center design. Leaf switches connect servers, Spine switches connect leaves. Excellent for east-west traffic.

### Three-Tiered Model
- Access Layer → Distribution Layer → Core Layer.

### Traffic Flows
- **North-South**: Traffic to/from Internet or external.
- **East-West**: Server-to-server inside the data center.

## Key Concepts
- **Network Backbone**: Main high-speed path.
- **Network Segments**: Divided parts for performance/security.
- **Virtual Networking**: VLANs, VXLAN, SDN.
- **Selecting Topology**: Balance cost, scalability and redundancy.

---

**Status:** Chapter 1 Completed  
**Next:** Chapter 2 + TryHackMe Network Fundamentals
