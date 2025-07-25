# Configuring Network Addressing and Internet Connections

## Key Concepts
*	Understand IPv4 and IPv6 addressing schemes and differences
*	Configure static and dynamic (DHCP) IP addressing
*	Understand subnetting basics and subnet masks
*	Explain the function of DNS and how it resolves names to IPs
*	Describe NAT and PAT for IP address translation
*	Understand Internet connection types (DSL, cable, fiber, satellite, cellular)
*	Configure wireless network security protocols (WEP, WPA, WPA2, WPA3)

## Homelab

1. Open Command Prompt (Window) or Terminal (Mac/Linux)
2. Run the following command:
   * Windows: ```ipconfig /all```
   * Mac/Linux: ```ifconfig``` or ```ip a```
3. Identify the following:
   * IPv4 Address
   * Subnet Mask
   * Default Gateway
   * DNS Server
4. Take a screenshot and label each part.

## Alternate Lab

In Windows:
1. Go to **Network and Sharing Center** &rarr; **Change adapter settings**
2. Right click your network adapter &rarr; Properties &rarr; IPv4
3. Select "Use the following IP address" and enter:
   * IP: ```192.168.1.100```
   * Subnet: ```255.255.255.0```
   * Gateway: ```192.168.1.1```
   * DNS: ```8.8.8.8```
4. Apply settings and test with:
   * ```ping google.com```
   * ```ping 8.8.8.8```
5. Revert to DHCP and observe the IP change

## Alternate Lab 2

1. Oppen command Prompt
2. Use ```nslookup google.com```
3. Observe the IP address returned
4. try other domains like ```amazon.com```,```cnn.com```
5. Change your DNS to Cloudflare (```1.1.1.1```) or Google (```8.8.8.8```) and observe differences

### Lab Journal 
* What did you observe?
* What did you learn?
* What questions do you still have?
