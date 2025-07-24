# Comparing Local Networking Hardware

## Key Concepts
* Understand the purpose of networking devices (switch, router, hub, modem, firewall, access point)
* Differentiate between wireless standards (802.11 a/b/g/n/ac/ax)
* Identify Ethernet cable types and connectors (Cat5e, Cat6, RJ-45)
* Understand the function of patch panels, punch-down tools, and wiring standards (T568A/B)
* Describe functions of network interface cards (NICs)
* Explain basic network topologies (star, mesh, bus)

## Homelab

1. Create two or more VMs (Windows/Linux)
2. Set network adapters to "Internal Network" mode to allow VMs to communicate privately
3. Use ping command to check connectivity
4. Use ipconfig or ifconfig to see network configurations
5. Use a VM running pfSense (Free Open Source Firewall / Router Software) or a Linux VM configured with routing rules
6. Connect other VMs to the router and test routing/firewall functions

## Alternative Lab

### Analyze Network Traffic with Wireshark

1. Start Wireshark on one VM or host machine
2. Fiter traffic for protocols like ARP, DHCP, DNS
3. identify source/destination IPs and protocols
4. Observe DHCP discover/offer process, ARP requests, DNS queries
