 Technologies Implemented
    1. Design Tool: Utilize Cisco Packet Tracer for designing and implementing the network solution.
    2. Hierarchical Design: Implement a hierarchical model that incorporates redundancy for enhanced network resilience.
    3. ISPs: Establish connectivity to an Airtel ISP Router within the network infrastructure.
    4. WLC: Ensure that each department is equipped with a Wireless Access Point (WAP) to provide WiFi access to employees, corporate users, external auditors, and guests, all centrally managed by a Wireless LAN Controller (WLC).
    5. VoIP: Deploy IP phones in each department to support Voice over IP (VoIP) communication.
    6. VLAN: Maintain VLANs with the following IDs: 10 for LAN, 50 for WLAN, and 99 for VoIP across the entire network.
    7. EtherChannel: Implement the Link Aggregation Control Protocol (LACP) for EtherChannel configuration, enhancing link aggregation efficiency.
    8. STP PortFast and BPDUguard: Configure Spanning Tree Protocol (STP) PortFast and BPDUguard to expedite port transitions from blocking to forwarding states.
    9. Subnetting: Utilize subnetting techniques to allocate the appropriate number of IP addresses to each network group.
    10. Basic Settings: Configure fundamental device settings, including hostnames, and console passwords, enable passwords, banner messages, password encryption, and disable IP domain lookup.
    11. Inter-VLAN Routing: Enable devices in all departments to communicate with one another by configuring the respective multilayer switch for inter-VLAN routing.
    12. Core Switch: Assign IP addresses to Multilayer switches to enable both routing and switching functionalities.
    13. DHCP Server: Ensure that all devices in the network (excluding IP phones) obtain IP addresses dynamically from Active Directory (AD) servers located at the server farm site.
    14. Cisco 2811 Router: Deploy a Cisco Catalyst 2811 router capable of supporting telephony services.
    15. HSRP: Implement high-availability router protocols such as HSRP to achieve redundancy, load balancing, and failover capabilities.
    16. Static Addressing: Allocate static IP addresses to devices located in the server room.
    17. Telephony Service: Configure Voice over IP (VoIP) on the WAN router and assign dial numbers in the format (3...).
    18. Routing Protocol: Utilize Open Shortest Path First (OSPF) as the routing protocol to advertise routes on the firewall, routers, and multilayer switches.
    19. Standard ACL for SSH: Establish a simple standard Access Control List (ACL) on the VTY line to permit remote administrative tasks via SSH only for the Senior Network Security Engineer PC.
    20. Cisco ASA Firewall: Configure default static routes, basic settings, security levels, zones, and policies on the Cisco ASA Firewall to define access control and resource utilization within the network.
    21. Final Testing: Conduct thorough testing to verify proper communication and ensure that all configured elements function as intended.
