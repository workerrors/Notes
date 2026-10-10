Cheatsheet:

 
OSI model: (Used wireshark to further understand the OSI model.)
layer 1, physical - Cables, fiber, and signal itself

layer 2, data link - frame, mac address, extended unique identifier (EUI-48, EUI64), switch

layer 3, network - IP address, router, packet

layer 4, transport - TCP segment, UDP datagram

layer 5, session - control protocols, tunneling protocols

layer 6, presentation - application encryption/decryption (SSL, TLS)

layer 7, application - your eyes


#######


Wireshark, used to capture and inspect network traffic


#######


Cyberchef, used to encrypt/decrypt data


#######


Nmap, used to scan ports and discover network services/devices


scan types, example commands:


ARP scan - sudo nmap -PR -sn 10.200.6.0/24


ICMP Echo Scan - sudo nmap -PE -sn 10.200.6.0/24


ICMP Timestamp Scan - sudo nmap -PP -sn 10.200.6.0/24


ICMP Address Mask Scan - sudo nmap -PM -sn 10.200.6.0/24


TCP SYN Ping Scan -  	sudo nmap -PS22,80,443 -sn 10.200.6.0/30


TCP ACK Ping Scan - sudo nmap -PA22,80,443 -sn 10.200.6.0/30


UDP Ping Scan - sudo nmap -PU53,161,162 -sn 10.200.6.0/30


Options:

-n: no DNS lookup


-R: reverse-DNS lookup for all hosts


-sn: host discovery only







