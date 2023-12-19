# Lab-View-Captured-Traffic-in-Wireshark

**Objectives**

Part 1: Download and Install Wireshark

Part 2: Capture and Analyze ARP Data in Wireshark
* Start and stop data capture of ping traffic to remote hosts.
* Locate the IPv4 and MAC address information in captured PDUs.
* Analyze the content of the ARP messages exchanged between devices on the LAN.

Part 3: View the ARP cache entries on the PC

* Access the Windows Command Prompt.
* Use the Windows arp command to view the local ARP table cache on the PC.

Background / Scenario
Address Resolution Protocol (ARP) is used by TCP/IP to map a Layer 3 IPv4 address to a Layer 2 MAC address. When an Ethernet frame is transmitted on the network, it must have a destination MAC address. To dynamically discover the MAC address of a known destination, the source device broadcasts an ARP request on the local network. The device that is configured with the destination IPv4 address responds to the request with an ARP reply and the MAC address is recorded in the ARP cache.

Every device on the LAN maintains its own ARP cache. The ARP cache is a small area in RAM that holds the ARP responses. Viewing an ARP cache on a PC displays the IPv4 address and the MAC address of each device on the LAN with which the PC has exchanged ARP messages.

Wireshark is a software protocol analyzer, or "packet sniffer" application, used for network troubleshooting, analysis, software and protocol development, and education. As data streams travel back and forth over the network, the sniffer "captures" each protocol data unit (PDU) and can decode and analyze its content according to the appropriate protocol specifications.

Wireshark is a useful tool for anyone working with networks and can be used with most labs in the Cisco courses for data analysis and troubleshooting. This lab provides instructions for downloading and installing Wireshark, although it may already be installed. In this lab, you will use Wireshark to capture ARP exchanges on the local network.

Required Resources
* 1 PC (Windows 10)
* internet access
* Additional PC(s) on a local-area network (LAN) will be used to reply to ping requests. If no additional PCs are on the LAN, the default gateway address will be used to reply to the ping requests.

https://github.com/arren-a/Lab-View-Captured-Traffic-in-Wireshark/wiki
