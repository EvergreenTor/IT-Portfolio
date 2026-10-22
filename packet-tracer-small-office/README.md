# Small Office Network Simulation — Cisco Packet Tracer

## 1. Project Overview
<!-- What does this project simulate, and why did I build it? -->
The goal of this project is to simulate a small-office network using Cisco Packet Tracer. The project focuses on configuring network devices, establishing connectivity between end devices, and practicing basic networking and troubleshooting skills. 

## 2. Objectives
<!-- What skills or concepts did I want to practice? -->
- Configure Static IPv4 addresses 
- Configure DHCP to assign IP addresses automatically 
- Test connectivity between devices using Ping
- Configure a Cisco Router and Switch
- Practice IPv4 Subnetting and routing between subnets

## 3. Network Topology / Architecture
<!-- Add a Mermaid diagram or screenshot of the network architecture. -->

## 4. Tools & Technologies
<!-- List the software, devices, protocols, and technologies used. -->
- Cisco Packet Tracer

## 5. Configuration / Implementation
<!-- Describe the main setup steps and important configurations. -->
The network initially consisted of two PCs connected to a switch. I configured static IPv4 addresses on both PCs and used ping to verify connectivity between them.

I then added a router to serve as the network's default gateway, providing a path for traffic to reach other IP networks when appropriate routing and upstream connectivity are configured.

Next, I configured DHCP on the router to assign IPv4 addresses automatically and added two more end devices to the network. These devices obtained their IP configuration through DHCP.

This implementation provided hands-on practice with static IPv4 addressing, DHCP configuration, default gateways, and basic network connectivity testing.
## 6. Testing & Verification
<!-- What tests did I run? What were the results? -->
I performed multiple ping tests to verify connectivity between devices in the network.

- PC-to-PC connectivity: Tested communication between PCs connected to the switch.

- PC-to-router connectivity: Tested whether each PC could reach the router's LAN interface, which serves as its default gateway.

- Routing considerations: Although the current lab focuses on the local network, a correctly configured router can route traffic between different IP subnets when appropriate routes and interface configurations are in place. Internet connectivity would require an upstream connection and additional configuration.

These tests helped verify local network connectivity and the role of the router as a gateway to other networks.

## 7. Troubleshooting & Challenges
<!-- What went wrong? How did I investigate, identify, and resolve it? -->

## 8. What I Learned
<!-- What technical knowledge or practical skills did I gain? -->
This project helped me become more familiar with Cisco Packet Tracer and its capabilities for simulating small networks. I practiced configuring static IPv4 addresses, setting up DHCP on a router, and testing connectivity with ping.

I also gained practical troubleshooting experience by investigating DHCP configuration issues and APIPA addresses. When I configured static IPv4 addresses, I learned that devices on the same local network need compatible IP addresses and subnet masks to communicate directly. Incorrect addressing or subnet configuration can cause ping tests to fail.

Finally, I practiced basic Cisco IOS commands to configure the router's IPv4 interface address and DHCP service. This project strengthened my understanding of IP addressing, DHCP, network connectivity, and basic troubleshooting.
## 9. Future Improvements
<!-- What would I like to add, improve, or practice next? -->

Future improvements to this project include adding a second IP subnet and configuring routing to test communication between devices on different subnets.

VLAN configuration and network segmentation will be explored in a separate, more advanced project. That project will simulate an organization with multiple departments and demonstrate how VLANs can logically separate network traffic.
