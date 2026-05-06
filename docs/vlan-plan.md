# VLAN Plan

This network is segmented into multiple VLANs to improve security and performance.

## VLAN Details

| VLAN ID | Name        | Purpose              |
|--------|------------|--------------------|
| 10     | Users       | Employee devices    |
| 20     | Management  | Admin systems       |
| 30     | Servers     | Server resources    |

## Design Logic

- VLANs reduce broadcast traffic
- Improves security by isolating departments
- Enables inter-VLAN routing via Router (R1)

## Routing Method

Router-on-a-Stick (RoAS) is used for inter-VLAN communication.
