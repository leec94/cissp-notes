# Chapter 11: Secure Network Architecture and Components
## Notes
- WPA3: 
  - types: 
    - WPA3-ENT
    - WPA3-PER
- simultaneous authentication of equals (SAE): used by WPA3-PER
- storage area network (SAN): solutions 
- internet small computer systems interfae (iSCSI): storage technology that works at layer 3, sending block level access commands to network based storage devices 
- Fiber Channel over IP (FCIP): encapsulated within IP, at layer 3 (network) 
- virtual extensible local area network (VxLAN): encapsulates VLAN mgmt traffic sends across subnets to geographically separated locations 
- Fiber Channel over Ethernet (FCoE): can be used by SAN to function over ethernet, using switches, host based adapters, NICs and cabling
- Fiber Channel
- address resolution protocol (ARP): used to resolve IP addresses into MAC addresses, layer 2 protocol
- ARP cache: used to cache IP address and MAC address translations (layer 2 and 3)
- store-and-forward switching: receives and stores the entire frame in a buffer before forwarding, for better error checking and data integrity
- cut-through switching: forwards a frame as soon as it reads the destination address. for low latency 
- 