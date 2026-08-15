# IPv4 and Subnetting Lab

## Objective

The goal of this lab is to understand how devices communicate across different IPv4 subnets and how a router and default gateway enable communication between separate networks.

## Topology

- 2 PCs
- 2 Cisco switches
- 1 router
- 2 different IPv4 subnets

## IP Addressing

| Device | IP Address | Subnet Mask | Default Gateway |
|---|---|---|---|
| PC0 | 192.168.1.10 | 255.255.255.0 | 192.168.1.1 |
| Router G0/0 | 192.168.1.1 | 255.255.255.0 | - |
| Router G0/1 | 192.168.2.1 | 255.255.255.0 | - |
| PC1 | 192.168.2.20 | 255.255.255.0 | 192.168.2.1 |

## Connectivity Test

Without a default gateway, communication between the two different subnets failed.

After configuring the router interfaces and default gateways, PC0 successfully communicated with PC1.

```bash
ping 192.168.2.20
```
## What I Learned
- How IPv4 subnets separate networks
- How a subnet mask identifies the local network
- Why devices in different subnets require a router
- The purpose of a default gateway
- How a router forwards packets between different networks
- How to configure router interfaces in Cisco Packet Tracer

