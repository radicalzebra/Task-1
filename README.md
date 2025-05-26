Hello, My name is <b>Arshad Faiyaz<b> , this is my implementation of <b>Task-1<b>

Steps:
1.Started my VM instance running kali
2.Installed nmap via nmap.org
3.Found my IP range using ifconfig command which gave me my instance IP & netmask
4.Used command <b>nmap -sS -A -oN portscan 192.168.x.x/24<b> to perform a TCP SYN scan
5.Scanned all hosts within the IP range
6.Found SSH running on port 22 and DNS running on port 63
7.Found other info such as the Operating System of the host IP and MAC (using -A flag) and saved the output to a file (using -oN flag)
8.Potential Security Risks found are <b>DNS cache Poisoning<b> & <b>DNS Tunneling<b>
9.Used <b>Wireshark<b> to analyse the packets 


Thank you 😎
