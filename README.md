# TP Réseau - Université Euromed de Fès (UEMF)

## 🌐 Network Simulation Project

This repository contains the files for a **Travaux Pratiques (TP) Réseau** (Networking Lab) project, likely completed as part of the curriculum at the **Université Euromed de Fès (UEMF)**, specifically within the **École d'Ingénierie Digitale et d'Intelligence Artificielle (EIDIA)** or a related program [1] [2].

The project is a network simulation designed and configured using **Cisco Packet Tracer**, a powerful network simulation tool that allows for the creation, configuration, and testing of network topologies and protocols [3].

---

## 🎯 Project Objective

The primary goal of this lab exercise was to design and implement a functional network infrastructure. This typically involves:

1.  **Topology Design:** Creating a logical and physical network map.
2.  **Device Configuration:** Configuring network devices (routers, switches, end devices) with necessary parameters.
3.  **Protocol Implementation:** Setting up essential networking protocols (e.g., static/dynamic routing, VLANs, DHCP, DNS).
4.  **Connectivity Testing:** Verifying end-to-end connectivity and service functionality.

**NOTE:** The specific objectives of this TP (e.g., implementing OSPF, configuring a specific number of VLANs, setting up a particular server service) are contained within the `.pkt` file and should be detailed in the **Configuration Details** section below.

---

## 🛠️ Prerequisites

To open and interact with this project, you must have **Cisco Packet Tracer** installed on your system.

*   **Software:** [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer)
*   **Project File:** `tp_reseau_uemf.pkt`

---

## 🚀 Usage

1.  **Download:** Clone this repository to your local machine.
2.  **Open:** Launch Cisco Packet Tracer.
3.  **Load:** Open the file `tp_reseau_uemf.pkt` from the cloned directory.
4.  **Explore:** Examine the network topology in the workspace.
5.  **Verify:** Use the simulation and real-time modes to test connectivity (e.g., `ping`, `tracert`) and verify the configuration of all devices (e.g., `show running-config` on CLI).

---

## ⚙️ Configuration Details (To be completed by the user)

This section should be updated with the specific details of the network configuration implemented in the `tp_reseau_uemf.pkt` file.

### 1. Network Topology Summary

| Component | Quantity | Description |
| :--- | :--- | :--- |
| **Routers** | [e.g., 2] | [e.g., Cisco 4321, configured for inter-VLAN routing] |
| **Switches** | [e.g., 3] | [e.g., Cisco 2960, configured with multiple VLANs] |
| **End Devices** | [e.g., 10] | [e.g., PCs, Laptops, Servers] |
| **Services** | [e.g., 2] | [e.g., DHCP Server, Web Server] |

### 2. IP Addressing Scheme

| Network/VLAN | Subnet Address | Subnet Mask | Gateway | Purpose |
| :--- | :--- | :--- | :--- | :--- |
| **VLAN 10 (Admin)** | `192.168.10.0` | `255.255.255.0` | `192.168.10.1` | Administration staff |
| **VLAN 20 (Students)** | `192.168.20.0` | `255.255.255.0` | `192.168.20.1` | Student workstations |
| **WAN Link** | `10.0.0.0` | `255.255.255.252` | N/A | Link between R1 and R2 |

### 3. Protocols Implemented

| Protocol | Devices | Configuration Summary |
| :--- | :--- | :--- |
| **Routing** | [e.g., R1, R2] | [e.g., OSPF Area 0, Static Routes to ISP] |
| **VLANs** | [e.g., SW1, SW2] | [e.g., VLANs 10, 20, 99 (Management)] |
| **DHCP** | [e.g., Server] | [e.g., DHCP pool configured for VLAN 10 and 20] |
| **Security** | [e.g., R1] | [e.g., Basic ACLs implemented] |


## ⚖️ License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
