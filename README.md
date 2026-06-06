# School Network Design And Implementation

A secure, highly scalable, and optimized campus network infrastructure designed and simulated using **Cisco Packet Tracer**. This project implements enterprise-grade architectures including dynamic routing protocols, efficient IP allocation matrices, border internet routing, and tight localized switch port security boundaries.

---

## 🚀 Key Features & Architectural Modules

* **Network Segmentation (VLANs):** Divides the school infrastructure into isolated logical broadcast domains per department to separate sensitive administrative traffic from baseline student and guest access points.
* **Variable Length Subnet Masking (VLSM):** Implements an efficient IP addressing scheme across the entire infrastructure to maximize IPv4 allocation utility and completely minimize address waste.
* **Dynamic Inter-Router Routing (OSPF):** Configures Open Shortest Path First (OSPF) dynamic routing across regional routers, establishing automated path determination, rapid convergence, and effortless network scalability.
* **Internet Edge & NAT Translation:** Simulates external internet boundaries using Network Address Translation (NAT) to securely mask internal private addresses behind a public internet gateway IP.
* **Multi-Tier Security Infrastructure:**
  * **Access Control Lists (ACLs):** Enforces strict traffic filtering policies at the layer-3 boundary to block unauthorized zones from communicating with sensitive subnets.
  * **Switch Port Security:** Locks down hardware access at the switches by limiting MAC address registration, instantly disabling a port if an foreign device attempts to connect.
* **Centralized Network Services:** Fully integrates core infrastructure servers handling dynamic host address assignments (DHCP), domain naming systems (DNS), dedicated local HTTP web hosting, and a campus-wide Email communication network.
* **Integrated Campus WLAN:** Deploys wireless access points mapping securely to localized subnets for continuous mobile laptop and smart device integration.

---

## 🛠️ Hardware & Protocols Simulated

* **Core Equipment:** Cisco Routers, Catalyst Layer 2 Switches, and Wireless Access Points.
* **End Nodes:** Departmental PCs, Network Printers, and Central Application Servers.
* **Core Protocols:** IPv4 Address Allocations, VLSM, OSPF, NAT, 802.1Q VLAN trunking, DHCP, DNS, HTTP, SMTP/POP3, and Port Security matrices.

---

## 💻 Tech Stack & Tools

* **Simulation Environment:** Cisco Packet Tracer (v8.0 or higher recommended)
* **Design Strategy:** Layered Hierarchical Network Architecture

---

## 🛠️ How to Open and Run the Simulation

### Prerequisites
* You must have **Cisco Packet Tracer** installed on your desktop.

### Execution Instructions
1. **Clone this project repository to your local system:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/School-Network-Design-And-Implementation.git](https://github.com/YOUR_USERNAME/School-Network-Design-And-Implementation.git)
   cd School-Network-Design-And-Implementation
