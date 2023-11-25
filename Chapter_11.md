
# Chapter 11

## The Binary Number System
- The binary number system consists of ones (1s) and zeros (0s), representing electrical energy or its absence.
- To convert binary to decimal, insert the decimal value for each bit represented by a one, then add these values together.

## Dotted Decimal Notation
- IPv4 addresses are displayed in decimal form as dotted decimal notation, with each octet separated by a period.

## Subnetting
- Subnetting divides a network into subnetworks or subnets.
- Subnetting expands the network portion of an IP address by borrowing bits from the host portion.
- A subnet mask identifies the network and host portions of an IP address.
- Addresses with all zeros or ones in the host portion are not assignable.
- Variable-length subnet mask (VLSM) creates additional subnets from a subnet.
- Fixed-length subnet mask (FLSM) has equal-sized subnets.
- Subnetting enhances security and reduces network traffic by isolating broadcasts.

## Network Segmenting Devices
- Bridges and switches (layer 2 devices) filter frames based on MAC addresses.
- Switches segment wired networks and can create VLANs.
- Routers (layer 3 devices) filter frames based on IP addresses.
- Routers connect different network switches and make decisions based on source and destination IP addresses.
- Routers reduce collision domains by not forwarding broadcasts.
- Router metrics determine the best route based on factors like throughput, reliability, packet loss, latency, and hops.
- Routing protocols include Interior Gateway Protocol (IGP) and Exterior Gateway Protocol (EGP).
- RIP, EIGRP, and multilayer switches are various routing solutions.
- ASICs in switches expand function.

## Virtual LAN (VLAN)
- VLANs connect workstations on separate or the same network segments.
- VLANs can be created statically or dynamically.
- IEEE 802.1Q standard describes VLAN technology.
- Spanning Tree Protocol corrects switch loops.

## Classless Inter-Domain Routing (CIDR)
- CIDR identifies the network portion of an IP address with a slash (/) symbol followed by the network prefix length.
- The network prefix length ranges from 0 to 32.

## Link Aggregation
- Link aggregation parallels two or more network cables to increase bandwidth and provide redundancy.
