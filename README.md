# Computer Network Architecture and Design Project

## About
Architecting and Configuring a multi-room College Campus network using Cisco Packet Tracer, based on custom requirements. <br>
- Tools used: ![Cisco](https://img.shields.io/badge/cisco-%23049fd9.svg?style=for-the-badge&logo=cisco&logoColor=%23000000)  Packet Tracer 

Author: Sandra

## Objective
Demonstrate end-to-end network engineering to build a multi-segment enterprise campus network. Utilising Cisco Packet Tracer to configure custom subnetting scheme requirements, implement IP addressing and static routes using Cisco CLI on different hardware interfaces, testing and troubleshooting design. Enabling seamless inter-network communication.

## 1. Network Topology Planning & IP Scheme Design
Each workroom of the campus network was configured to satisfy specified requirements. Each room was equipped with 12 computers. Rooms were logically separated with subnets to create distinct boundaries, with different switch and router topologies. Assigning a dedicated Network ID for each space allowed for a clean, segmented and scalable IP schema across the campus. 

- Using Cisco Packet Tracer to build specified topologies:

  - Example Workroom 1 Topology:

<img src="https://github.com/SandyLdn/LANconfig/blob/c048776a174cb7e6fc060884878d927878d10750/LanConfigWorkRoom1Topology-Screenshot.png" width="40%">

  - Example Workroom 2 Topology, with different subnets created:

<img src="https://github.com/SandyLdn/LANconfig/blob/689a5829f0b86da692ca43f0364f015feb27da73/2-LanConfigWorkRoom2Topology-Screenshot.png" width="50%">

## 2. Testing Network Connectivity With Ping 
After connecting devices to appropriate ports, it was time to test connectivity over the network.

- Using ping command to test communication between devices, on Workroom 1 network:

Success!

<img src="https://github.com/SandyLdn/LANconfig/blob/ea3362f54508741ee951576c399e6abdfeaf251e/3-LanConfPingTest-Screenshot.png" width="60%">

- Using ping command to test connectivity between devices on different subnets, on Workroom 2 network:

 Success!

<img src="https://github.com/SandyLdn/LANconfig/blob/fb8624d79699fcba67bbf64b5710aab68924fa3a/4-LanCongPing2-Screenshot.png" width="60%">

## 3. Connecting 2 Isolated Networks Together
In this phase of the project introduced a new network segment, between Workroom 1 and Workroom 2 routers. Static routes were assigned between the 2 routers to allow connectivity between all computers. 

 - Creating a new network between router 1 of Workroom 1 and router 2 of Workroom 2:

<img src="https://github.com/SandyLdn/LANconfig/blob/329ec68837c9b41769118ee26df21ed1fa540bd6/5-LanConfR1R2connect-Screenshot.png" width ="60%">

 
## 4. Testing Connectivity Devices in Separate Networks & Subnets:

Finally, the infrastructure was rigorously tested, using the ping command tool, to ensure that all devices were reachable; between networks and between subnets.

 Success!

<img src="https://github.com/SandyLdn/LANconfig/blob/1793fd177d8ea45dea956fb6e63c12bd8e5d01cf/6-LanConfW1toW2ping-Screenshot.png" width="60%">

- Testing if devices can communicate across Workroom 2's subnets:

Success!

<img src="https://github.com/SandyLdn/LANconfig/blob/73379fb8cac95bd70482bc20c2ced93ddaccf44e/7-LanConfW2SubnetPing-Screenshot.png" width="60%">

## 5. Key Learnings
- Network architecture and design using networking tools, such as Cisco Packet Tracer
- IP address planning and segmenting. Ensuring that IP addresses are not wasted and networks are appropriately sized and scalable, utilising appropriate subnet masks
- Programmed static routes, determining next-hop forwarding, allowing isolated routers to send data packets to other networks
- Enhanced CLI skills, specifically setting-up and configuring devices and networks, using the Cisco command-line
- Practising testing and troubleshooting the network, as I go. Systematically using ping to trace connections and identify issues, ensuring efficient data transit, between different spaces and devices on the campus network
- Understanding how physical and logical networks interact, such as switches and routers coordinate with logical concepts such as subnets, to create an effective enterprise network
