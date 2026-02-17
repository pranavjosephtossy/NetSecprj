# Background Reserach(700)
# Jithin(250)
    Nftables is the modern packet filtering framework for Linux Systems and it is the successor to iptables, ip6tables,etables and arptables. According to Red Hat Enterprise Documentation it offers a variety of improvements in performance, convenience, features and rule management by unifying packet filtering for both ipv4 and ipv6. This removes the need for having several different rule sets for various protocols and reduces the complexity.
The nftables architecture is based on tables, chains and rules. The table is the main container that holds firewall settings. A chain exists within a table, and it defines where the packets are checked and they are linked to specific points in the network flow called hooks. Some common chains are input, output and forward. Finally, rules are placed inside chains and define how traffic is handled 
Nftables also supports scripting which can have comments and variables and be loaded automatically at startup which make nftables suitable for where performance is important


# Ojal(250)
# Pranav(250)
    Endian is an a particualr service that is an evelution of traditional firewalls. It is a Unified Threat Management distro, which means it provides network security and network management solutions as a single tool. Endian was developed by an European company as a open source linux distribution. It being beased on linux was a delebrate attempt to enure compatability with as many open source devices as possible while gaining the flexibility and security of linux based devices.  
    Endian acts as the center of a networks, directing all types of traffic.(Fikri Muhammad Arifin a,*, Giva Andriana Mutiara b, Ismail c) The general topology of endian firewalls can be seen(1.1). This role as a central router is what makes if favoured among businesses and organizations. It provides a reliable layer of security while simeltaniously being able to be used as a monitiring and management tool. Endian follows zone based firewall architecture, grouping different zones with various permissions. This lets the user set specific rules of communication between other zones or zones that are classed as the same.
    It is most typically used by businesses or organizations for web-flitering, internal(Vlan) network management. and antivirus scanning. Its ability to combine all these features in one environment is what makes it so versitile 
    
## Strengts
Endian:
- `Broad and Versitile`
- `Simplicity`
## Limitations
Endian:
- `Broad but not deep`
- `Statefull firewall, resource intensive`
    