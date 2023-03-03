# Honeypot Data

## Timestamps and IPs of bots/hackers that try to access my server.

### The data in the json file is stored in this format:

action		- What the hacker tries to do.   
data		- Short description of everything.    
dest_ip		- The IP to which the services are bound.   
dest_port	- The Port of the protocol (ssh is changed to another port and mapped via NAT to 22 externally).   
protocol	- Protocol   
src_ip		- The IP of the script kiddie, If you read this, feel free to DDoS.   
src_port	-   
timestamp	- Will be used for elasticsearch/grafana to visualize the data later on.   
