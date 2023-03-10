# Cisco ASA 5506-X Firewall Configuration on a 3-Tier Campus LAN Architecture

![image](https://github.com/ascotlan/Cisco-ASA-5506-X-Firewall-Configuration-on-a-3-Tier-Campus-LAN-Architecture/blob/main/topology.png)

## Abstract

In this packet tracer project, I was able to implement a firewall using the Cisco ASA 5506-X appliance. This is a continuation from a previous project titled as [“Cisco Meraki Centralized WLC on a 3-Tier Campus LAN Architecture”](https://github.com/ascotlan/Cisco-Meraki-Centralized-WLC-on-a-3-Tier-Campus-LAN-Architecture). Security levels were configured on the inside and outside interface on the firewall. I then successfully configured dynamic routes to/from the inside interface on the firewall using the OSPF routing protocol. A static default route to the outside was configured on the firewall. A network object was implemented to represent the inside network. That object was used to create address translation to the outside interface using PAT. ACLs were implemented to manage the flow of key traffic.
