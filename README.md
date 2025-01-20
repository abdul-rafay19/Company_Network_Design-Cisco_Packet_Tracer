# Company-Network-Design-Cisco-Packet-Tracer
This project outlines the network infrastructure design for a company with two branches located in different states and a central server in another state. The design incorporates advanced networking techniques for efficient communication, scalability, and security.

## Group Members
- Abdul Rafay (233679) (Project Lead)
- Tayyab Abbas (233681)
- Muhammad Awais (233680)
- Arslan Dilawar (233515)

## Table of Contents
1. [Introduction](#introduction)
2. [Network Design](#network-design)
   - [Topology Diagram](#topology-diagram)
   - [Justification of Topology](#justification-of-topology)
3. [Configuration Details](#configuration-details)
   - [VLAN Configuration](#vlan-configuration)
   - [InterVLAN Routing](#intervlan-routing)
   - [DHCP Configuration](#dhcp-configuration)
   - [RIP Protocol](#rip-protocol)
   - [Firewalls](#firewalls)
4. [Routing Optimization](#routing-optimization)
5. [Testing and Validation](#testing-and-validation)
   - [Functional Testing](#functional-testing)
   - [Simulation](#simulation)
6. [Conclusion](#conclusion)

## Introduction
This project presents a detailed design of a network for a company with two branch offices and a central server, focusing on ensuring efficient communication, scalability, and security. The network includes VLANs, inter-VLAN routing, DHCP, DNS, HTTP services, and uses RIP for dynamic routing.

## Network Design
### Topology Diagram
A comprehensive topology diagram illustrates the network's structure, showcasing the connections between branches and the central server.

### Justification of Topology
The chosen topology supports efficient communication and centralized management. It includes VLANs for each department, dynamic routing through RIP, and firewalls for security.

## Configuration Details
### VLAN Configuration
VLANs are configured for each department to improve network performance and isolate traffic.

### InterVLAN Routing
InterVLAN routing is set up using sub-interfaces on central routers, enabling communication between different VLANs.

### DHCP Configuration
DHCP servers are configured to dynamically allocate IP addresses, simplifying network management.

### RIP Protocol
RIP is employed to dynamically share routing information between the branches and the central server.

### Firewalls
Firewalls are implemented on DHCP and HTTP servers to restrict unauthorized access.

## Routing Optimization
RIP is used for its simplicity and effectiveness in smaller networks, ensuring updated routing information across the network.

## Testing and Validation
### Functional Testing
Tests include DHCP functionality, inter-VLAN communication, WLAN connectivity, and DNS/HTTP services.

### Simulation
Simulations for HTTP, DNS, and ICMP validate network performance and reliability.

## Conclusion
The project successfully demonstrates the design and implementation of a robust network infrastructure, with recommendations for future improvements like OSPF and intrusion detection systems.

