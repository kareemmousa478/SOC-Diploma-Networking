# IP Addressing

## Overview

VLSM was used throughout the network to allocate IP addresses based on the requirements of each network.

Default classful /8, /16, and /24 networks were avoided.

## Subnetting

The topology uses different subnet sizes including:

| Prefix | Purpose |
|---|---|
| /26 | Larger LAN segment |
| /28 | Smaller LAN segment |
| /29 | VLAN/LAN segments |
| /30 | Point-to-point router links |

## Point-to-Point Links

/30 subnets were used for router-to-router connections because they provide a suitable address space for point-to-point links.

## VLSM Benefit

VLSM allows different networks to use different subnet sizes instead of assigning the same subnet size to every network.

This helps use IPv4 address space more efficiently.
