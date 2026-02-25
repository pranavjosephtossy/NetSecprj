# Jithin()
# Ojal()

# Pranav()
Implementing nftable as the firewall invovled creating a clean structure and applyimng tsrgets rules. I defined an inet table and an input chain. For port filering i allowed http while blocking ssh to demonstrate selective access.
ICMP rules were configured to test protocol level control and how the firewall diffrentiates between traffic types.
Traffic policy testing was also implemented by configuring the firewall with default-allow and default-deny. This showcased how nftables enforced broad security policies. Finally logging rules were implemted to capture traffic that was allowed and denied. This structures approach that each rule set could be evaluated independently and accurately