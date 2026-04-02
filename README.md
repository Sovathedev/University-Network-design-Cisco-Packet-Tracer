# University-Network-design-Cisco-Packet-Tracer

## 📖 Overview
This project simulates a university network architecture using the Cisco Packet Tracer simulation. The design is based on the Cisco three-layer model, balancing the need for connectivity in academic/administrative operations and security.

## 🛠️ Key Technologies & Protocols
Architecture: Cisco 3-Layer Model (Core, Distribution, Access).
Routing & High Availability: OSPF (dynamic routing), HSRP (gateway redundancy).
Switching & Segmentation: VLANs, VTP, STP, EtherChannel.
Security: Cisco ASA 5506-X Firewalls, Access Control Lists (ACLs), Port Security.
Services: DHCP, DNS, FTP, Web, and VoIP (Cisco 2811).

## 📊 Performance & Evaluation
The network was  tested under three scenarios: Normal, High-load, and Failover.
Normal Condition: Operated with optimal efficiency, maintaining 0-4ms latency and 0% packet loss.
High-Load Condition: While FTP throughput decreased by ~41% (from 1.33 Mbps to 0.79 Mbps), critical services like VoIP and internal email remained  functional.
Failover Recover: Perform good fault tolerance with a convergence time of  5 seconds when one Distribution switch fail , proving the effectiveness of the HSRP protocol.

## 🚀 How to Run
Step 1: Install Cisco Packet Tracer following instruction in install/.
Step 2: Open University.pkt.
Step 3: Check the config/ folder for specific CLI commands used on the Catalyst switches and ASA firewalls.
