Step 1. Locating The Firewall

           HPING OR NMAP - IT WILL GIVE A LIST OF ALLOWED SERVICES.
           
           hping3 -T -1 www.firewall.com
           
           Identify firewall ip address
           
           nmap --script=firewalk --traceroute 10.10.10.10.

Step 2. Conducting Traceroute
           
           traceroute basically provide information regarding routing path of packets.
           
Step 3. Port scanning or enumeration:
      
           nmap -sS -sV -T4 -p 0-1024 Firewall-ip-address
           
Step 4. Banner grabbing of firewall:

           telnet 192.168.0.1  22
           
           nc -nvv 192.168.0.1  80
           
           dmitry -b 192.168.0.1
           
           curl -s -| 192.168.0.1 | grep -e "Server"
           
           nmap -sV --script=banner 192.168.0.0.1
           
           nmap -Pn -p 80 -sV --script=banner 192.168.0.1
        
Step 5. Access control enumeration:

           nmap -sA 10.10.10.1
           
Step 6. Identify firewall architecture:

Step 7. Firewall policy:
                      
           Testing firewall policy: Sourve ip/port, Destination ip/port, and zone that you wish to test.
           
           Test web policy: Policy that you wish to test
           
           other values: url, authenticated user and time & day

Step 6. Firewalking:
 
Step 7. Port redirection

Step 8. Http tunneling:

Step 7. Firewall vulnerabilities           
