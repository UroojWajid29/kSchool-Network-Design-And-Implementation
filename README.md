# School Security and Surveillance Network

A secure, scalable, and automated campus network infrastructure designed and simulated using **Cisco Packet Tracer**. This project integrates traditional enterprise network segmentation and centralized web/email services alongside an **Internet of Things (IoT) security automation matrix** to mimic a modern smart-school campus.

---

## 🚀 Key Features & Configurations

* **Network Segmentation via VLANs:** Divides the school infrastructure into isolated logical broadcast domains (e.g., Administration, Faculty, Students, and IoT Systems) to optimize traffic and enhance organizational security.
* **Inter-VLAN Routing:** Configured a core layer router (Router-on-a-Stick setup) to allow authorized, secure cross-communication between distinct subnet departments.
* **Centralized Network Services:**
  * **DHCP Server:** Dynamically assigns IP addresses, subnet masks, default gateways, and DNS server attributes to endpoint nodes.
  * **DNS Server:** Resolves user-friendly web names into exact IP destinations.
  * **HTTP Web Server:** Hosts a customized virtual campus internal web portal.
  * **Email Server:** Establishes cross-department communication channels utilizing SMTP and POP3 protocol configurations.
* **Smart IoT Security Automation:** Features a live motion sensor linked directly to a network siren/alarm. When unauthorized motion is tripped, the ecosystem autonomously activates the campus alarm system.
* **Integrated Wireless LAN (WLAN):** Employs wireless access points to deliver secure local data access to mobile student and faculty devices across campus boundaries.

---

## 🛠️ Hardware & Devices Simulated

* **Networking Equipment:** Cisco Routers and Catalyst Layer 2 Switches.
* **End Devices:** Desktop PCs, Laptop Workstations, and Multi-Functional Network Printers.
* **Central Servers:** Unified Generic Servers running DNS, DHCP, HTTP, and EMAIL services concurrently.
* **IoT Components:** Motion Detection Sensors, Smart Registration Gateways, and Networked Alarm Sirens.

---

## 💻 Tech Stack & Tools

* **Simulation Software:** Cisco Packet Tracer (v8.0 or higher recommended)
* **Core Protocols:** IPv4 Addressing, VLAN (802.1Q), DHCP, DNS, HTTP, SMTP, POP3, and IEEE 802.11 (Wi-Fi).

---

## 🛠️ How to Open and Run the Simulation

### Prerequisites
* You must have **Cisco Packet Tracer** installed on your system.

### Running the File
1. **Clone this repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/School-Security-Surveillance-Network.git](https://github.com/YOUR_USERNAME/School-Security-Surveillance-Network.git)
   cd School-Security-Surveillance-Network
