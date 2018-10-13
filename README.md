# ambergambit  
Project: Nemesis - Rabid Wireless Access Point that attacks malicious clients connecting to it (they have to break WEP to connect)
* sysctl - TCP/IP stack hardening  
* arpwatch - Monitor static ARP entries  
* iptables - NAT Masquerade, ARP broadcasts, DNS leaks  
* ebtables - Filter bridged connections  
* hostapd - Wireless Access Point  
* wpa_supplicant - use WEP encryption, expect only malicious clients  
* udev - MAC Spoofing  
* gkismet / giskismet - Wireless scanner w/GPS  
* gpsd - gps daemon  
* sql db - Store kismet data  
* ettercap - Man-in-the-Middle Framework: ARP Poisoning, ICMP Redirection, DHCP Spoofing, Port Stealing, Characters Injection, SSH1 MITM  
* wireshark / tshark - Network Sniff Layer 2 (Data Link Layer) and Layer 3 (Network Layer)  
* honeyd - Virtual Host Honeypot  
* msfvenom -  
* metasploit -  
* evilginx - Man-in-the-Middle Session Hijacking Framework  
* snort - IPS / IDS  
* ntopng - Network Statistics (what are these malicious clients trying to do?)  

# sysctl  
https://wiki.archlinux.org/index.php/sysctl#TCP.2FIP_stack_hardening  
`net.ipv4.icmp_echo_ignore_all = 1`  


# udev  
MAC Spoofing on device hotplug  


# ebtables  
Layer 2 filtering  


# iptables  
Layer 3 filtering  
NAT Masquerade  


# hostapd  


# wpa_supplicant  


# gkismet / giskismet  
https://www.kismetwireless.net/  
https://github.com/internetofdongs/IoD-Screwdriver  


# gpsd  
https://piratefache.ch/mapping-wifi-networks-on-google-maps/  


# sqlite3  


# google earth  


# wireshark / tshark  


# ettercap - ARP Poisoning  
https://medium.com/secjuice/man-in-the-middle-attack-using-arp-spoofing-fa13af4f4633  
https://github.com/Ettercap/ettercap  


# honeyd  
https://wiki.archlinux.org/index.php/honeyd  


# msfvenom  


# metasploit  


# evilginx  
https://github.com/kgretzky/evilginx2  


# snort - IPS / IDS


# ntopng  

