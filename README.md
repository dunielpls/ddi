# ddi
A DNS, DHCP and IPAM (DDI) solution based on a combination of PowerDNS
Authoritative, ISC Kea and NetBox.

# Installation
TODO

# Features
DNS:
- Create reverse DNS zones from NetBox prefixes.
- Create regular DNS zones from NetBox - custom model.
- Enable Dynamic DNS updates from NetBox prefixes.

DHCP:
- Define DHCP subnets from NetBox prefixes.
- Define DHCP pools from NetBox IP ranges.
- Modify DHCP options from NetBox IP ranges and IP addresses.
- Create DHCP reservations from NetBox IP addresses.

IPAM:
- Populate NetBox with IP addresses based on active DHCP leases.
- Filter and display various models based on their presence and status in the
DHCP server.

# Planned features
- Full redundancy.
- High availability.
- More flexibility with regards to databases.
- ...

# Topology
This diagram shows the basic topology and data flow:

![topology-light](doc/images/topology-light.png#gh-light-mode-only)![topology-dark](doc/images/topology-dark.png#gh-dark-mode-only)

# Architecture
TODO

# License
MIT

