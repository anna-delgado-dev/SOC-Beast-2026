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
- **Print Server**: Manages and queues print jobs for network printers.
- **Web Server**: Hosts websites and web applications (e.g. Apache, Nginx).
- **Application Server**: Runs business applications.
- **Proxy Server**: Acts as intermediary for security and performance.
- **Fax / Telephony Server**: Handles fax or VoIP calls.

### Host
- Any device with an IP address that can communicate using TCP/IP.
- Broad term: includes workstations, servers, laptops, smartphones, printers, IoT devices, etc.

### TCP/IP
- Standard protocol suite of the Internet and most modern networks.
- **TCP** = reliable, ordered data delivery (connection-oriented).
- **IP** = addressing and routing of packets.
- Used by every host with an IP address.

## Network Types

### PAN (Personal Area Network)
- Smallest network type. Connects personal devices in short range.
- Technologies: Bluetooth, USB, Ethernet.

### CAN (Campus Area Network)
- Covers a university or corporate campus. Interconnects multiple LANs.
- Usually includes Wi-Fi for roaming users.

### MAN (Metropolitan Area Network)
- Covers a city or campus. Connects multiple buildings.
- Usually provided by a carrier (“concentrated WAN”).

### WAN (Wide Area Network)
- Covers large geographic areas. Connects multiple LANs using routers and carrier links.
- Slower and more expensive than LAN/MAN.

### Internet
- Largest distributed WAN in the world. Connects millions of networks via routers.

### SAN (Storage Area Network)
- Dedicated high-speed network for storage traffic only.
- Connects servers to centralized storage arrays.
- Used mainly in data centers.
- Main protocols: Fibre Channel (FC) or FCoE.

### SD-WAN (Software-Defined WAN)
- Modern flexible WAN technology.
- Manages multiple connection types (MPLS, LTE, broadband) with software.
- Allows real-time optimization.

### MPLS (Multi-Protocol Label Switching)
- Advanced routing technology for WANs.
- Provides high performance, traffic prioritization, redundancy, and flexibility.

## Network Architecture

### Peer-to-Peer (P2P)
- All devices are equal – no central authority.
- Each device can act as both client and server.
- Low security. Only suitable for small networks (< 10-20 users).

### Client-Server
- Dedicated server manages the network, security, and resources.
- Clients only request services.
- Server is never used as a normal workstation.
- High security and scalability. Used in most professional environments.

## Physical Network Topologies

### Bus Topology
- All devices on a single cable. Simple but outdated. Single point of failure.

### Point-to-Point
- Direct connection between two devices. Common in WAN links.

### Hub-and-Spoke (Star Topology)
- All devices connect to a central switch. Most common in modern LANs.

### Mesh Topology
- Every device connects to every other. High redundancy, very expensive.
- Partial mesh is more common.

### Spine-and-Leaf Topology
- Modern data center design.
- Leaf switches connect to servers and endpoints.
- Spine switches connect only to leaf switches.
- Excellent for east-west traffic and scalability.

### Three-Tiered Hierarchical Model
- **Access Layer**: Connects end-user devices.
- **Distribution Layer**: Aggregates traffic and applies policies.
- **Core Layer**: High-speed backbone between distribution layers.

### Traffic Flows
- **North-South Traffic**: Traffic entering or leaving the network (to Internet, cloud, external users).
- **East-West Traffic**: Server-to-server traffic inside the data center.

## Key Concepts
- **Network Backbone**: Main high-speed path between network segments.
- **Network Segments**: Parts of the network separated for performance or security.
- **Virtual Networking**: VLANs, VXLAN, SDN (software-defined networks).
- **Selecting the Right Topology**: Balance between cost, scalability, and redundancy (Star for small offices, Spine-and-Leaf for large data centers).

---

**Status:** Chapter 1 Completed  
**Next:** Chapter 2 + TryHackMe Network Fundamentals
