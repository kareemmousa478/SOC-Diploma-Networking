# Connectivity Verification

The network was tested after configuration to verify that the required services and routing protocols were functioning correctly.

## Tests Performed

### End-to-End Connectivity

Ping tests were performed between different network segments.

### DHCP

DHCP clients were verified to ensure they automatically received valid IP configuration.

### SSH

SSH remote access was tested from a client PC.

### DNS

DNS name resolution was tested using the configured domain name.

### HTTP

The web server was accessed using the domain name rather than directly using its IP address.

### VLANs

VLAN configuration and connectivity between devices within the same VLAN were verified.

### Routing

Routing tables and OSPF neighbor relationships were checked using Cisco IOS commands.

## Useful Verification Commands

```text
show ip interface brief
show ip route
show ip ospf neighbor
show vlan brief
ping
traceroute
