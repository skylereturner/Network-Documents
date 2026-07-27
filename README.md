# Physical network topology:  
Physical network topology is attached to the repository titled HomeNetwork.pdf
# Logical network topology:  
Logical network topology is attached to the repository titled HomeNetwork.pdf
# IP addressing and subnet documentation:
The home network internal IP address subnet is 192.168.1.0/24. All of the devices on the network connects to the router being 192.168.1.1/24 to get an automatic IP address using the dhcp server running on the router. Every device except Computer number 1 and the server has a wireless connection to the router. The router also is the primary dns server to all devices in the network
# Network device inventory:
The only network device currently in the private network is the router acting as a wireless router, wired router and mini switch. The device is acting as the default gateway to all access devices on the network
# Servers and network services, if applicable:
The network has one server with the IP address of 192.168.1.20/24. Currently the IP services being ran on the network is DCHP which hands out Ip addresses for the devices connected and DNS which is also on the router that is using google dns which is 8.8.8.8
# Relevant device configuration information:
The router is completely configured and managed by isp So, there is no relvant device configuration information that I know of because I do not have access to the routers management page
# A description of the method used to store login credentials securely:
The password used to log into the network is stored on the router as plaintext. To authenticate user on the network the router combines the SSID and the network password and encrypts that information multiple times. If the device trying to connect to the network matches the same encrypted password that is on the router the device is authenticated and able to connect.

# IP Table:
|Device|IP address|Connection Type|
|------|----------|---------------|
|phone 1:|DHCP|    Wireless|
|Phone 2|DHCP|Wireless|
|Phone 3|DHCP|Wireless|
|Phone 4|DHCP|Wireless|
|Phone 5:|DHCP|Wireless|
|Computer 1|DHCP|Wireless|
|Computer 2|DHCP|Wireless|
|Laptop 1|DHCP|Wireless|
|Laptop 2|DHCP|Wireless|
|Router|192.168.1.1|Wired/wireless|
|Server|192.168.1.20|wired|
|Printer|192.168.1.10|Wireless| 


Revision history:
Document completed on 7/25/2026
Attached logic and physical topology 7/26/2026
No other changes have been made to the document
References to any related files or diagrams
Network topology has been attached to the reporitory with the title of HomeNetwork.pdf
