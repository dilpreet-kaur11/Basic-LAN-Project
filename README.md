# Basic LAN Project in Cisco Packet Tracer

## Overview
This project demonstrates the setup of a **Basic Local Area Network (LAN)** in **Cisco Packet Tracer**. It includes multiple devices (routers, switches, and hosts) connected in a simple network topology.

## Project Details
- **Technologies Used**: Cisco Packet Tracer, TCP/IP, Networking, Switch Configuration, Router Configuration.
- **Network Components**: 
  - **Router**
  - **Switch**
  - **PCs**
  - **Cabling** (Copper Straight-through cables, etc.)

## Project Steps
1. **Open Cisco Packet Tracer**: Start a new project in Cisco Packet Tracer.
2. **Add Devices**: Drag and drop a **Router**, **Switch**, and **2-3 PCs** onto the workspace.
3. **Cable Connections**: 
   - Connect the router to the switch using a copper straight-through cable.
   - Connect the PCs to the switch using copper straight-through cables.
4. **Assign IP Addresses**:
   - Configure IP addresses for each PC on the network (e.g., PC1: `192.168.1.2`, PC2: `192.168.1.3`).
   - Set the router’s interface IP (e.g., `192.168.1.1`).
5. **Configure Router**: Use the command-line interface (CLI) of the router to configure the interfaces:
   - `Router>enable`
   - `Router#config terminal`
   - `Router(config)#interface fastEthernet 0/0`
   - `Router(config-if)#ip address 192.168.1.1 255.255.255.0`
   - `Router(config-if)#no shutdown`
6. **Test Connectivity**: 
   - Use the **ping** command from one PC to another to verify network connectivity.
   - Example: `ping 192.168.1.3` from PC1 to PC2.

## How to Use
1. Download the `.pkt` file from this repository.
2. Open it in **Cisco Packet Tracer**.
3. Follow the steps in the **Project Details** section to view and test the network setup.


