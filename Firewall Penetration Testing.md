Step 1. Locating The Firewall

           HPING OR NMAP - IT WILL GIVE A LIST OF ALLOWED SERVICES.
           
           hping3 -T -1 www.firewall.com
           
           Identify firewall ip address

Step 2. Conducting Traceroute
           
           traceroute basically provide information regarding routing path of packets.
           
Srep 3. Port scanning or enumeration:
      
           nmap -sS -T4 -p 0-1024 Firewall-ip-address
           
