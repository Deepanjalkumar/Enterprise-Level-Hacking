Step 1. Locating The Firewall

           HPING OR NMAP - IT WILL GIVE A LIST OF ALLOWED SERVICES.
           
           hping3 -T -1 www.firewall.com
           
           Identify firewall ip address

Step 2. Conducting Traceroute
           
           traceroute basically provide information regarding routing path of packets.
           
Step 3. Port scanning or enumeration:
      
           nmap -sS -sV -T4 -p 0-1024 Firewall-ip-address
           
Step 4. Banner grabbing of firewall:

           telnet 192.168.0.1  22
           
           nc -v 192.168.0.1
           
           dmitry -b 192.168.0.1
           
           curl -s -| 192.168.0.1 | grep -e "Server"
           
           nmap -sV --script=banner 192.168.0.0.1
           
           nmap -Pn -p 80 -sV --script=banner 192.168.0.1
           
           
