Secure Small Business Network
A secure small business network designed and configured using Cisco Packet Tracer, focusing on network segmentation, traffic control, and secure communication.
Project Overview
This project demonstrates the design and configuration of a small business network using VLAN segmentation, Router-on-a-Stick, and an Extended Access Control List (ACL).
The network separates employees, servers, and guest devices into different VLANs and controls communication between them.
Network Topology
The network consists of:
Cisco 2911 Router
Cisco 2960 Switch
3 PCs
1 Server
VLAN Configuration
VLAN Name Device
VLAN 10 EMPLOYEES PC1, PC2
VLAN 20 SERVERS Server
VLAN 30 GUEST PC3
VLANs were used to separate different types of network devices and improve network organization and security.
Router-on-a-Stick
Router-on-a-Stick was configured to allow the single router interface to communicate with multiple VLANs using 802.1Q trunking.
Each VLAN was assigned its own subnet:
Employees: 192.168.10.0/24
Servers: 192.168.20.0/24
Guests: 192.168.30.0/24
ACL Security
An Extended ACL named GUEST_RESTRICTION was configured to restrict guest traffic.
The ACL prevents devices in the Guest VLAN from accessing the Server VLAN while allowing other required network communication.
Connectivity Testing
The configuration was tested using connectivity checks between devices.
Test Results
Guest PC → Server: Blocked
Guest PC → Employee PC: Allowed
These tests confirm that the ACL is controlling traffic according to the configured security requirements.
Tools & Technologies
Cisco Packet Tracer
VLANs
802.1Q Trunking
Router-on-a-Stick
Extended ACL
IPv4 Addressing
Network Segmentation
Skills Demonstrated
Network configuration
VLAN segmentation
Router configuration
Access control
Network security
Connectivity troubleshooting
Basic network testing
