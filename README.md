# Network Port Scanning using Nmap

## Objective
To identify open or filtered ports in a local network using Nmap.

## Tools Used
- Nmap

## Steps Performed
1. Installed Nmap
2. Identified local IP range (192.168.1.0/24)
3. Performed scan using:
   nmap -sS 192.168.1.0/24
4. Saved output to result.txt
5. Analyzed scan results

## Results
The Nmap scan detected multiple active hosts in the local network.
However, all scanned ports were in a filtered state, indicating that a firewall is blocking incoming connections.
No open ports were found, which suggests the network is secure.

## Conclusion
The network is protected by a firewall, and no open ports were detected.

## Author
sujan
