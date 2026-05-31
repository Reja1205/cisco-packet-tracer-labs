
# Basic LAN Lab

## Objective
Create a simple LAN using 2 PCs and 1 switch and test connectivity.

## Devices Used
- 2 PCs
- 1 Switch

## Topology
PC1 ---- Switch ---- PC2

## IP Configuration
PC1:
- IP: 192.168.1.10
- Subnet: 255.255.255.0

PC2:
- IP: 192.168.1.11
- Subnet: 255.255.255.0

## Testing
- Used ping from PC1 to PC2
- Result: Successful communication

## Key Learning
- Devices in same subnet can communicate via switch
- Switch works at Layer 2 (MAC address)
- No router needed for same network
