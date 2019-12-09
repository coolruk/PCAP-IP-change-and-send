# PCAP-IP-change-and-send

This program is useful utility for administrator.

In my other program is normally generating network traffic from PCAP files. But we need to change the IP addresses of both source and destination in order to adjust the traffic in a different infrastructure. I normally use this program to reproduce network traffic which caused a false-positive alert or turned out to be a real attack in order to test IDS/IPS/SIEM rule set. This function is in Suricata detection system and very useful to verify the rule before apply it to live production.

Also I added to replay network traffic according to the time frame of traffic. This will help to reproduce the network traffic precisely. 

-Prerequisite
1. Wireshark
2. Npcap 0.992
