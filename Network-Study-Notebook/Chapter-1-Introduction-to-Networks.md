# Day 4 – Network+ Focus (26 March 2026)

**Study Block 1** – CompTIA Network+ Chapter 1: Introduction to Networks  
**Time spent**: ~4 hours (2 hours lectura + apuntes + ejercicio)

### Progress
- Completado **Chapter 1** entero.
- Tomados apuntes claros y organizados de todo el capítulo.
- Entendido conceptos clave: componentes de red, tipos de redes, arquitecturas y topologías.

### Chapter 1 – Apuntes Resumidos (Clean Version)

**1. What is a Network?**  
- Two or more connected devices that share resources (data, applications, printers).  
- Hosts communicate using binary data (packets).

**2. Local Area Network (LAN)**  
- Connects devices within a small geographic area (home, office, single building).  
- High speed and low latency.

**Latency**  
- Round-trip time for a packet to travel from source to destination and back.  
- Measured in milliseconds (ms).  
- Low latency = fast network | High latency = performance problems.

**Workgroup**  
- Group of devices in the same network segment with no central security.  
- Each device manages its own users and resources. Low security.

**Common Network Components**

**Workstation**  
- High-performance computer (multiple CPUs, large RAM, powerful GPU).  
- Used by security analysts, developers, etc. Acts as client.

**CPU**  
- The brain of the computer. Executes instructions and calculations.

**Server**  
- Powerful dedicated computer/software that provides services to clients.

**Common Server Types**  
- File Server (stores/shares files)  
- Mail Server (emails)  
- Print Server (printing jobs)  
- Web Server (websites)  
- Application Server (business apps)  
- Proxy Server (security & performance)  
- Fax/Telephony Server (fax or VoIP)

**Host**  
- Any device with an IP address using TCP/IP (workstations, servers, phones, printers, IoT…).

**TCP/IP**  
- Standard protocol suite of modern networks.  
- TCP = reliable data delivery | IP = addressing and routing.

**Network Types**  
- **PAN**: Smallest (personal devices, Bluetooth/USB).  
- **CAN**: Campus (university/corporate buildings).  
- **MAN**: City level (concentrated WAN).  
- **WAN**: Large areas, uses routers, slower/expensive.  
- **Internet**: Largest distributed WAN.  
- **SAN**: Dedicated storage network for data centers (Fibre Channel).  
- **SD-WAN**: Flexible modern WAN with software control.  
- **MPLS**: Advanced routing with prioritization and redundancy.

**Network Architecture**  
- **Peer-to-Peer (P2P)**: All devices equal, low security, only small networks.  
- **Client-Server**: Dedicated server manages security and resources. High security and scalability.

**Physical Network Topologies**  
- **Bus**: Single cable – outdated, single point of failure.  
- **Point-to-Point**: Direct link between two devices.  
- **Star (Hub-and-Spoke)**: Most common – all connect to central switch.  
- **Mesh**: Every device connected to every other – high redundancy, expensive.  
- **Spine-and-Leaf**: Modern data center (Leaf → servers, Spine → leaves). Excellent for east-west traffic.

**Three-Tiered Model**  
- Access Layer → Distribution Layer → Core Layer.

**Traffic Flows**  
- **North-South**: Traffic to/from Internet or external.  
- **East-West**: Server-to-server inside the data center.

**Key Concepts**  
- Network Backbone: Main high-speed path.  
- Network Segments: Divided parts for performance/security.  
- Virtual Networking: VLANs, VXLAN, SDN.  
- Selecting Topology: Balance cost vs scalability vs redundancy.

### Network Study Notebook
→ [Network-Study-Notebook](./Network-Study-Notebook/)  
→ [Chapter 1 – Introduction to Networks](./Network-Study-Notebook/Chapter-1-Introduction-to-Networks.md)

**Personal Reflection**  
Hoy terminé el primer capítulo completo. Los conceptos más importantes (Client-Server vs P2P, Spine-and-Leaf, North-South vs East-West traffic) ya están claros. Los apuntes quedan limpios y listos para repasar y mostrar en portfolio.

**Status**: Chapter 1 ✅ Completed  
**Tomorrow**: Review notes + start Chapter 2 + TryHackMe Network Fundamentals

**Total study time today**: ~4 hours (planned 6 hours)
