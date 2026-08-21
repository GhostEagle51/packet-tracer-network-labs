# Packet Tracer Network Labs

Hands-on Cisco Packet Tracer labs covering networking fundamentals, switching, routing, network services and basic network security.

This repository was created to practice networking concepts through practical configurations and troubleshooting scenarios using Cisco Packet Tracer and Cisco IOS.

## Topics Covered

- IPv4 addressing and subnetting
- ARP and MAC address learning
- Switching
- VLANs
- Access ports
- Trunking
- Inter-VLAN Routing
- Router-on-a-Stick
- Static Routing
- Default Routing
- Spanning Tree Protocol (STP)
- EtherChannel
- LACP
- DHCP
- NAT
- PAT / NAT Overload
- Standard ACL
- Extended ACL
- Basic network troubleshooting

## Tools

- Cisco Packet Tracer
- Cisco IOS CLI
- GitHub

## Labs

- [01 - Basic LAN, ARP and MAC Address Table](./01-basic-lan-arp-mac/)
- [02 - IPv4 and Subnetting](./02-ipv4-subnetting/)
- [03 - Switching, ARP and MAC Address Table](./03-switching-arp-mac/)
- [04 - VLAN](./04-vlan/)
- [05 - Trunk](./05-trunk/)
- [06 - Inter-VLAN Routing](./06-inter-vlan-routing/)
- [07 - Static Routing](./07-static-routing/)
- [08 - Default Routing](./08-default-routing/)
- [09 - Spanning Tree Protocol (STP)](./09-stp/)
- [10 - EtherChannel](./10-etherchannel/)
- [11 - DHCP](./11-dhcp/)
- [12 - NAT and PAT](./12-nat/)
- [13 - Access Control List (ACL)](./13-acl/)
- [14 - Small Office Network](./14-small-office-network/)

## Final Lab - Small Office Network

The final lab combines several concepts from the previous labs into a single small office network.

The network contains:

- SALES VLAN
- IT VLAN
- Server VLAN
- DHCP for client devices
- Static addressing for servers
- Router-on-a-Stick
- Inter-VLAN routing
- Trunking
- Default routing
- NAT/PAT
- Internal and external networks
- Extended ACL traffic filtering

Example access policy:

```text
SALES → Internal Server = DENY
IT    → Internal Server = PERMIT
SALES → External Server = PERMIT
IT    → External Server = PERMIT
```

This lab demonstrates how multiple networking technologies can work together in a more realistic network environment.

## Repository Structure

Each lab contains:

```text
Lab Folder/
├── README.md
├── Packet Tracer .pkt file
└── topology.png
```

Each lab README includes the objective, topology, configuration steps, verification commands, connectivity tests and key concepts learned during the lab.

## Troubleshooting Experience

The labs also include practical troubleshooting scenarios encountered during configuration, including:

- Incorrect VLAN assignments
- Missing default gateways
- Trunk configuration issues
- EtherChannel negotiation problems
- DHCP address assignment issues
- Static and default route configuration
- NAT/PAT verification
- ACL interface and direction configuration

Troubleshooting these issues helped reinforce how network configurations interact with each other.

## Learning Outcome

By completing these labs, I gained practical experience configuring and troubleshooting Cisco-based networks.

The labs helped reinforce the relationship between Layer 2 switching, Layer 3 routing, network services and basic traffic filtering.

This repository will continue to serve as a practical networking reference as I continue studying network and cybersecurity technologies.
