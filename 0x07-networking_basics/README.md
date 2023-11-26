Networking Basics Project
Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

OSI Model
What it is
How many layers it has
How it is organized
What is a LAN
Typical usage
Typical geographical size
What is a WAN
Typical usage
Typical geographical size
What is the Internet
What is an IP address
What are the 2 types of IP address
What is localhost
What is a subnet
Why IPv6 was created
TCP/UDP
What are the 2 mainly used data transfer protocols for IP (transfer level on the OSI schema)
What is the main difference between TCP and UDP
What is a port
Memorize SSH, HTTP, and HTTPS port numbers
What tool/protocol is often used to check if a device is connected to a network
Tasks
0. OSI Model
What is the OSI model?
Set of specifications that network hardware manufacturers must respect
The OSI model is a conceptual model that characterizes the communication functions of a telecommunication system without regard to their underlying internal structure and technology
The OSI model is a model that characterizes the communication functions of a telecommunication system with a strong regard for their underlying internal structure and technology
How is the OSI model organized?
Alphabetically
From the lowest to the highest level
Randomly
1. Types of Network
What type of network a computer in local is connected to?
Internet
WAN
LAN
What type of network could connect an office in one building to another office in a building a few streets away?
Internet
WAN
LAN
What network do you use when you browse www.google.com from your smartphone (not connected to the WiFi)?
Internet
WAN
LAN
2. MAC and IP Address
What is a MAC address?
The name of a network interface
The unique identifier of a network interface
A network interface
What is an IP address?
Is to devices connected to a network what postal address is to houses
The unique identifier of a network interface
Is a number that network devices use to connect to networks
3. UDP and TCP
Which statement is correct for the TCP box:
It is a protocol that is transferring data in a slow way but surely
It is a protocol that is transferring data in a fast way and might lose data along in the process
Which statement is correct for the UDP box:
It is a protocol that is transferring data in a slow way but surely
It is a protocol that is transferring data in a fast way and might lose data along in the process
Which statement is correct for the TCP worker:
Have you received boxes x, y, z?
May I increase the rate at which I am sending you boxes?
4. TCP and UDP Ports
Write a Bash script that displays listening ports:

That only shows listening sockets
That shows the PID and name of the program to which each socket belongs
5. Is the Host on the Network
The Internet Control Message Protocol (ICMP) is a protocol in the Internet protocol suite. It is used by network devices to check if other network devices are available on the network. The command ping uses ICMP to make sure that a network device remains online or to troubleshoot issues on the network.

Write a Bash script that pings an IP address passed as an argument.