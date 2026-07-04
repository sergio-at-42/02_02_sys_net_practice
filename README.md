*This project has been created as part of the 42 curriculum by sbeldjao*

---

# Net_Practice
### Your very first own server.

---

## Description  
NetPractice is a hands-on networking project featuring 10 progressive levels that teach essential computer networking fundamentals. Through interactive problem-solving, you'll master TCP/IP addressing, subnet masks, default gateways, routing, and OSI layers by troubleshooting and configuring non-functioning network diagrams. This browser-based training provides practical experience in network administration, preparing you for real-world system administration and networking challenges.   

## Instructions  
- download the file attached to the activity’s page.  
- extract the files into any folder of your choice.  
- run the run.sh file. This shell script will launch a web server and open your preferred web browser to the dedicated page. 
- if you prefer open the page manually, go to : **http://localhost:49242** 

## Resources  
### IP address
An **IP (Internet Protocol) address** is a unique numerical identifier assigned to a device on a network. It allows devices to communicate by identifying both the sender and the destination of data. IP addresses are used to route information across local networks and the Internet. They can be either IPv4 (32-bit) or IPv6 (128-bit), depending on the version of the Internet Protocol.  

### subnet mask
A **subnet mask** is a value used with an IP address to separate the network portion from the host portion of the address. It determines whether two devices belong to the same local network or must communicate through a router. In IPv4, a subnet mask is a 32-bit value, commonly written in dotted-decimal notation (for example, 255.255.255.0). It is also commonly represented using CIDR notation, such as /24.  

### default gateway
A **default gateway** is the network device, usually a **router**, that forwards traffic from a local network to other networks, such as the Internet. It is the destination used when a device needs to communicate with an IP address outside its own subnet. The default gateway is identified by its IP address and must be on the same local network as the device. Without a valid default gateway, communication is limited to the local subnet.  

### routers
A **router** is a network device that forwards data packets between different IP networks. It examines the destination IP address of each packet and selects the best path based on its routing table. Routers enable communication between separate networks, such as local networks and the Internet. They can use **static routes** or **dynamic routing protocols** to determine the most efficient path for network traffic.  

### switches
A **network switch** is a device that connects multiple devices within the same local area network (LAN). It forwards Ethernet frames only to the destination device by using **MAC addresses**, reducing unnecessary network traffic. Unlike a hub, a switch sends data only to the intended recipient. Modern switches can also support advanced features such as **VLANs**, **Quality of Service (QoS)**, and **Power over Ethernet (PoE)**.  

### OSI layers
+----------------------------------+  
| 7. Application                   |  
+----------------------------------+  
| 6. Presentation                  |  
+----------------------------------+  
| 5. Session                       |  
+----------------------------------+  
| 4. Transport                     |  
+----------------------------------+  
| 3. Network                       |  
+----------------------------------+  
| 2. Data Link                     |  
+----------------------------------+  
| 1. Physical                      |  
+----------------------------------+  

