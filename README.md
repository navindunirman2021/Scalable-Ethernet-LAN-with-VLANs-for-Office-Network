**Project Overview:**
In this project, I was tasked with designing and implementing a scalable Ethernet LAN network with Virtual Local Area Networks (VLANs) to enhance network performance, security, and redundancy for an office building with multiple floors. The goal was to logically segment the network into two distinct VLANs—Network-A and Network-B—while ensuring inter-floor communication and high availability.

**Key Responsibilities and Achievements:**

**Network Design:**
Designed a multi-floor office network with three switches, ensuring each floor was equipped with 24-port Cisco 2960 series switches. The network was divided into two distinct VLANs (Network-A and Network-B), optimizing traffic and improving security by segmenting different departments or network roles.

**VLAN Configuration:**
Configured VLANs across the switches with Network-A using VLAN ID 10 and Network-B using VLAN ID 20. Ports 1–10 on each switch were assigned to Network-A, and ports 11–15 were assigned to Network-B, allowing efficient traffic management and isolation.

**Inter-Switch Connectivity:**
Established redundancy and fault tolerance by configuring trunk links between the switches on different floors. Ensured that in case of a switch failure, communication would still be possible between the other floors.

**IP Addressing and Device Configuration:**
Assigned and configured IP addresses for all devices in the network (PCs and switches) according to the design, ensuring seamless communication within the same network (VLAN) across multiple floors.

**Fault Tolerance:**
Implemented a fault tolerance strategy by ensuring that if one of the switches failed (e.g., Floor-02-SW), PCs on other floors (Floor-1 and Floor-3) could still communicate. This was achieved through redundant trunk links and strategic switch configuration.

**Testing and Validation:**
Conducted extensive testing to ensure that all PCs could successfully communicate within the same VLAN across different floors. Verified that the network was resilient, and PC communication persisted even during potential switch outages.

**Technologies Used:
**
Cisco Packet Tracer for network simulation and configuration.

Cisco 2960 Series Switches for VLAN setup and inter-switch communication.

Ethernet LAN configuration for interconnecting switches and PCs.
