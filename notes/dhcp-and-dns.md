# DHCP Network Lab

## Objective
Configure a network where IP addresses are assigned automatically using DHCP.

## Devices Used
- 1 Router
- 1 Switch
- 2 PCs

## Topology
PCs ---- Switch ---- Router

## Router Configuration
- DHCP pool created for 192.168.1.0/24
- Default gateway set to 192.168.1.1
- DNS set to 8.8.8.8

## PC Configuration
- Set to DHCP mode (automatic IP)

## Result
- PCs received IP automatically from router
- Successful ping to router and between PCs

## Key Learning
- DHCP assigns IP automatically
- Router can act as DHCP server
- Default gateway is required for communication outside local network
