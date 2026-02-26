# Jithin()

# Ojal()
To implement pfSense as the firewall consisted of first completing the initial setup wizard and configuring the LAN and WAN interfaces to match the virtual lab environment similar to lab0. The WAN interface was assigned the static address 192.168.10.1/24 while the LAN interface was configured as 192.168.20.1/24, providing a controlled internal network for testing. Once the target VM was assigned 192.168.20.10, the pfSense web interface became the central point for rule creation, management and verification. 
Rules were added on the LAN interface to demonstrate pfSense's filtering bheaviour. ICMP block rule was first applied to prevent pinging from TVM to the firewall, confirming pfSense correctly enforced protocol-level restrictions. Then an allow rule was placed above it to show top-down rule processing mode which then restored ICMP. 
traffic-policy behavior was tested by switching between default-allow and default-deny conigurations, demonstrating how pfsense can restrict or permit outbound traffic with minute changes. logging was enabled on selected rules, providing clear evidence of allowed and blocked packets. 

# Pranav()
Implementing nftable as the firewall invovled creating a clean structure and applyimng tsrgets rules. I defined an inet table and an input chain. For port filering i allowed http while blocking ssh to demonstrate selective access.
ICMP rules were configured to test protocol level control and how the firewall diffrentiates between traffic types.
Traffic policy testing was also implemented by configuring the firewall with default-allow and default-deny. This showcased how nftables enforced broad security policies. Finally logging rules were implemted to capture traffic that was allowed and denied. This structures approach that each rule set could be evaluated independently and accurately