
# Chapter 10

## IPv4 Addressing
- Two types of IP addressing schemes: IPv4 and IPv6.
- IPv4 uses four octets, separated by periods, to uniquely identify each host.
- The first octet's decimal number identifies the IP class (Class A: 1–127, Class B: 128–191, Class C: 192–223).
- Reserved/private IP address ranges: 10.0.0.0 to 10.255.255.255, 172.16.0.0 to 172.31.255.255, 192.168.0.0 to 192.168.255.255.
- Network Address Translation (NAT) allows multiple workstations to share an Internet connection.

## Domain Name System (DNS)
- DNS matches host and domain names to IP addresses.
- A Fully Qualified Domain Name (FQDN) includes a host name and domain name.
- DNS is hierarchical: top-level domains, second-level domains, subdomains.
- A hosts file resolves computer names to IP addresses when DNS is unavailable.
- WINS matches IP addresses to NetBIOS names.

## IP, TCP, and UDP
- Common protocols in TCP/IP suite: IP, TCP, UDP.
- UDP frame format: source port, destination port, message length, checksum.
- TCP header includes sequence number for data reassembly.

## Assigning IP Addresses
- Static IP assignment: manually entered per host.
- Dynamic IP assignment: automatically issued, typically at boot.
- Dynamic Host Configuration Protocol (DHCP) dynamically assigns IP addresses.
- DHCP sets a lease period for IP address assignments.
- Automatic Private IP Addressing (APIPA) issues temporary IP addresses in DHCP server failure cases.

## TCP/IP Ports and Sockets
- A port number creates a virtual connection between two TCP/IP computers.
- A socket combines a port number with an IP address.

## IPv6 Addressing
- IPv6 is a classless scheme, not requiring a subnet mask.
- Advantages of IPv6: larger address pool, better security, quality of service, reduced broadcasts.
- IPv6 uses eight 16-bit hexadecimal sets; no subnet mask needed.
- EUI-64 identifier serves like a MAC address.
- Global address: public address, administered by IANA.
- Link-local addresses (start with FE80) are not routable.
- Unique-local addresses (begin with FD00) are routable within a private network.
- A network adapter can have multiple IPv6 addresses.

## Types of IPv6 Addresses
- Unicast address: delivers packets to a single network address.
- Multicast address: delivers packets to multiple addresses.
- Anycast address: delivers packets to the nearest interface, mainly for routers.
- Loopback addresses: IPv4 is 127.0.0.1, IPv6 is ::1.

## IPv6 Transition Technologies
- 6to4 addresses (start with 2002:) support IPv6/IPv4 communication on IPv4 networks.
- ISATAP supports IPv6 tunneling over IPv4 networks.
- Teredo tunnels incoming IPv6 traffic through an IPv4 firewall.

## Broadcast and Multicast Addresses
- LLMNR protocol uses both IPv4 and IPv6 for name resolution via multicast.

## IPv6 Lifetimes
- Valid lifetime: typically a week.
- Preferred lifetime: a day.
