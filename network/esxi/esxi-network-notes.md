# ESXi Network Notes

Initial notes for homelab ESXi networking.

- Management network on VLAN 10
- vSwitch0 used for management

## Assumptions

- ESXi management network must remain reachable from admin workstation
- Management traffic is not routed between VLANs
- Changes to vSwitch0 should be done during maintenance window

