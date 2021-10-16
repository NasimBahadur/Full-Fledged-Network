# Full-Fledged-Network
In this project, I designed a full-fledged network for an organization with multiple subnets using CISCO packet tracer. Here, I used 3 different types of IP addresses. Configured the whole network in such a way that IP for the hosts of different networks will be automatically assigned by a single DHCP server.

# Installation 
To run the "design.pkt" file, at first, you have to create an account in https://www.netacad.com/ and install the 'CISCO PACKET TRACER' software.

# Design Description
We have to build a complete model of a complex network by discovering the interconnectivity of the system and subnetworks that will reflect the INTERNATIONAL APOLLO University’s structure and facilities within the network will include the bellow’s features:
1. The web page of the university will reflect International Apollo University’s web page.
2. DNS server is installed to locate webserver - meaning people will browse University’s web site with the following address: http://www.apollointernational.edu
3. Among the hosts, we make sure that wireless links to the networks are available.
4. University’s full network has covered its six campuses with six routers, connectivity between routers are mesh (complex).
5. Connectivity between all the hosts is established.

While designing, we have kept in mind that for future expansion/growth, we should have enough facilities. As it was compulsory for us to incorporate wireless devices along with wired hosts in the LAN, we followed this instruction. In the physical design, we have a server room where all the servers are positioned in one LAN segment. Making our routing system more efficient, we configured the router with some extra features:
1. Configured the whole network in such a way that IP for the hosts of different campuses will be automatically assigned by a single DHCP server.
2. Network addresses were used from 3 different classes.
3. Subnets are incorporated into our system.

# Tools
Cisco packet tracer 8.0.0
1. Router: PT-Router
2. Switch: 2960-24TT
3. Wireless device: AccessPoint-PT
4. End devices: PC-PT, Server-PT, Laptop-PT, TabletPC-PT, SMARTPHONE-PT
5. Cable: Copper Straight-through, Serial DCE & Automatically choose connection type (for configuring wireless network system through AccessPoint-PT)

# Design
1. Services: DHCP, DNS, Web
2. DHCP server IP: 192.168.10.129 (static)
3. A single DHCP server is used.
4. Web server IP: 192.168.10.131 (static)
5. DNS server IP: 192.168.10.130 (static)
6. Dynamic routing algorithm (using OSPF protocol)
7. Incorporated subnetting into 3 different types of class IP Address

# Physical diagram
![Screenshot from 2021-10-16 21-47-01](https://user-images.githubusercontent.com/43060004/137594227-53fe1e81-0b7c-4840-8e0e-f579a1eecff6.png)

# Testing
Successfully ping for most of the case

![Screenshot from 2021-10-16 21-54-16](https://user-images.githubusercontent.com/43060004/137594229-46d40c62-77c8-46e2-acb2-3b3ac6ebcf6c.png)

Any devices can access the University website by entering http://www.apollointernational.edu

![Screenshot from 2021-10-16 21-59-32](https://user-images.githubusercontent.com/43060004/137594230-faabf6d1-c885-43d0-89e7-90b69b5e03e8.png)

