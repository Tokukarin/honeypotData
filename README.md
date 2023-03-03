## Timestamps and IPs of bots/hackers that try to access my server.
### The data in the json file is stored in this format:
#### Most important parts:
dest_port       - The Destination Port (ssh is changed to another port and mapped via NAT to 22 externally).   
protocol        - Protocol   
src_ip          - The IPs of the script kiddies, If you read this, feel free to DDoS them.   
timestamp       - Will be used for elasticsearch/grafana to visualize the data later on.   
#### Note to self: create Grafana Dashboard for the data.
