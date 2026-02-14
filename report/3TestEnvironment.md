# Test Environment(300)

    The test environment was set up in a virtual environment, virtualbox. This offers a controlled and repetable environment. Using virtualization allows for easy configuration and setup. The snapshot ability helps restore vms if the need arises

    The network topology follows a simple three point structure with an attacker virtual machine, a firewall virtual machine and a target virtual machine. The firewall is placed in between the target virtual machine and attacker virtual machine acting as a gateway through which all trafic pass to and from the target virtual machine. This placement allows for the filtering and procecessing of packets by the firewal and also showcases a realistic implemntation of the firewalls in which they are places between the network and outside sources.

    The attacker virtual machine was placed on a seperate subnet from the target virtual machine. `192.168.10.0/24` vs `192.168.20.0/24`. The firewall is configured with interfaces, LAN interface for the target virtual machine and internal netwrok, and WAN interface for the attacker. This ensures an accurate real world example of outside actor trying to "hack" the target virtual machine

    The attacker virtual machine is linux, which was picked for it extensive suite of penetration testing tools. The target virtual machine is a ubuntu server virtual machine. The firewall virtual machine runs the three selected firewalls: Endian Firewall Community Edition, OJAL and JITHIN. The firewalls are evaluated independently on the same topology, within the same environment.

# Jithin()
# Ojal()
# Pranav()