# Create-STP-Packets

You must use these commands with scapy

sendp(Ether(dst="01:80:c2:00:00:00")/LLC()/STP(), iface=“eth0”, count=10000)

https://scapy.readthedocs.io/en/latest/index.html
